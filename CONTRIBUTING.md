# Steps to Contribute

Thank you for your interest in contributing! Here’s a simple guide to help you get started.

## 1. Fork the Repository

- Click the **Fork** button at the top right of the repository page.
- This creates a copy of the repository under your GitHub account.

## 2. Clone Your Fork

- Clone your forked repository to your local machine:
  ```bash
  git clone https://github.com/YOUR-USERNAME/OpenSource_Launchpad.git
  cd OpenSource_Launchpad
  ```

## 3. Set Upstream Remote

- Add the original repository as a remote to keep your fork updated:
  ```bash
  git remote add upstream https://github.com/sayeegosavi/OpenSource_Launchpad.git
  ```

## 4. Create a New Branch

- Create a branch for your changes:
  ```bash
  git checkout -b issue-NUMBER-small-info
  ```

## 5. Make Your Changes

- Make the necessary changes or additions to the codebase.
- Follow any existing code style and conventions.

## 6. Commit Your Changes

- Stage and commit your changes with a clear message:
  ```bash
  git add .
  git commit -m "Add: brief description of your changes"
  ```

## 7. Keep Your Branch Updated

- Before pushing, pull the latest changes from the upstream `main` branch:
  ```bash
  git pull upstream main
  ```

## 8. Push to Your Fork

- Push your branch to your forked repository:
  ```bash
  git push origin feature/your-feature-name
  ```

## 9. Open a Pull Request (PR)

- Go to your fork on GitHub and click **Compare & pull request**.
- Provide a clear title and description of your changes.
- Submit the pull request to the original repository’s `main` branch.

## 10. Review and Iterate

- Maintainers will review your PR and may request changes.
- Make any requested updates and push them to the same branch—your PR will update automatically.

---

### Additional Notes

- Ensure your changes don’t break existing functionality.
- If the project has a `CONTRIBUTING.md` file, please read it for specific guidelines.
- Be respectful and constructive in all communications.

Thank you for contributing! 🎉
