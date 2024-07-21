# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


### I. **General Guidelines**

1. **Frequent Commits and Pulls:**
   - Commit changes frequently and pull updates regularly to avoid conflicts.

2. **Clear Commit Messages:**
   - Write clear, descriptive commit messages that explain the purpose of the change.

3. **Regular Merges:**
   - Merge feature branches into `develop` or `main` frequently to avoid long-lived branches.

4. **Handle Merge Conflicts Carefully:**
   - Resolve conflicts carefully to ensure that code is not unintentionally broken.

5. **Backup and Security:**
   - Ensure sensitive information (like API keys) is not committed to the repository. Use environment variables or secrets management tools.

6. **Branch Protection Rules:**
   - Configure branch protection rules in GitHub to require reviews before merging and enforce status checks.


### **Guidelines for Pull Requests**

1. **Clear and Descriptive Titles:**
   - Use a descriptive title that summarizes the purpose of the PR.

2. **Detailed Description:**
   - Provide a thorough description of what changes were made, why they were made, and how to test them.

3. **Keep PRs Small:**
   - Make pull requests small and focused on a single task or feature. This makes them easier to review and less likely to introduce conflicts.

4. **Add Context and References:**
   - Link to relevant issues or tasks that the PR addresses. This helps reviewers understand the context and importance of the changes.

5. **Request Reviews Early:**
   - Request reviews as soon as possible to get feedback early and avoid delays in the development process.

6. **Address Feedback Promptly:**
   - Act on feedback quickly and update the PR accordingly. Communicate any challenges or questions you have during the review process.

7. **Test Thoroughly:**
   - Ensure that changes are thoroughly tested before submitting the PR. Include automated tests if possible.

8. **Follow Contribution Guidelines:**
   - Adhere to the project’s contribution guidelines and coding standards. Check for any specific PR guidelines outlined in the repository.

9. **Use Branch Protection Rules:**
   - Configure branch protection rules to enforce required reviews, status checks, and other quality controls before merging.

10. **Close or Archive Old PRs:**
    - Close or archive pull requests that are no longer relevant or have become stale.


### **Example Pull Request Workflow**

1. **Branch Creation:** Create a feature branch and work on it.
2. **Push Changes:** Push changes to GitHub.
3. **Open PR:** Open a pull request against the target branch.
4. **Review:** Team members review the PR, provide feedback, and suggest changes.
5. **Update:** Make changes based on feedback and push updates to the branch.
6. **Approval:** Once approved, merge the PR into the target branch.
7. **Close PR:** Close the PR and delete the feature branch if no longer needed.