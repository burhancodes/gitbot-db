# GitHub Release Bot Database
---

This repository holds a JSON file (`repos.json`) used by the GitHub Release Bot to track and announce new releases for various repositories. The bot posts updates about releases categorized into different topics like Android, Linux, Windows, macOS, and miscellaneous projects.

## How to Contribute

We welcome contributions to expand the list of repositories! If you have a repository or know one that should be tracked, follow the instructions below to add it.

### Contribution Guidelines

1. **Fork the repository**:
   - Click the "Fork" button in the top-right corner of this repository to create a copy in your GitHub account.

2. **Clone your forked repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/gitbot-db.git
   cd gitbot-db
   ```

3. **Edit the `repos.json` file**:
   - Open the `repos.json` file located in the root directory of the project.
   - Add your repository link under the relevant category. The available categories are:
     - `android`
     - `magisk-xposed`
     - `linux`
     - `windows`
     - `misc`

   The format for adding a new repository is:
   ```json
   "category": [
     "owner/repo_name",
     "owner/another_repo"
   ]
   ```

   For example:
   ```json
   "linux": [
     "yourgithubusername/yourlinuxrepo"
   ]
   ```

4. **Submit a Pull Request (PR)**:
   - Commit your changes and push them to your forked repository:
     ```bash
     git add repos.json
     git commit -m "Added repo to linux category"
     git push origin main
     ```

   - Go to your forked repository on GitHub and click the "Pull Request" button.
   - Submit your pull request to this repository with a brief description of the changes.

## Why Your Contribution Matters

By contributing repositories, you're helping grow a valuable resource for users and developers who want to stay updated on new releases in various categories. The bot uses this list to notify specific communities (e.g., Android, Linux, Windows, etc.) about updates that they care about, making open-source contributions more visible and accessible.

Your contribution supports:
- **Open-source engagement**: Keep communities informed of the latest features and fixes.
- **Community collaboration**: Share and discover new projects across github and let every know about it.

Thank you for helping make this project better!

---
