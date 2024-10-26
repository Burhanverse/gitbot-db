# GitHub Repo Tracker Database
---

This repository holds a JSON file (`repos.json`) used by the GitHub Release Bot to track and announce new releases for various repositories. The bot posts updates about releases categorized into different topics like Android, Linux, Windows, macOS, and miscellaneous projects.

### Contribution

1. **Fork the repository**:
   - Click the "Fork" button in the top-right corner of this repository to create a copy in your GitHub account.

2. **Edit the `repos.json` file**:
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
     
---
