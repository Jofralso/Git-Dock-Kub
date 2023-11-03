# GitHub Learning Exercises - 10 Challenges

Welcome to the "Exercises" section of the GitHub learning repository. In this document, you'll find a series of hands-on exercises to practice and reinforce your GitHub skills. Each exercise includes both an explanation and a solution to help you understand and apply the concepts.

Feel free to explore the exercises in any order you prefer.

## Exercise 1: Creating and Cloning a Repository

**Explanation:**
- Creating a new GitHub repository allows you to store your code and collaborate with others.
- Cloning a repository means copying it to your local machine for editing.

**Solution:**
1. Create a new repository on GitHub with a README file.
2. Clone the repository to your local machine using `git clone <repository_url>`.
3. Make a change to the README file, commit the change, and push it to the repository on GitHub.

## Exercise 2: Branching and Merging

**Explanation:**
- Branches allow you to work on different features or bug fixes in isolation.
- Merging combines changes from one branch into another.

**Solution:**
1. Create a new branch using `git branch <branch-name>`.
2. Switch to the new branch with `git checkout <branch-name>`.
3. Make some changes in the new branch and commit them.
4. Switch back to the main branch with `git checkout main`.
5. Merge the changes from the new branch into the main branch with `git merge <branch-name>`.

## Exercise 3: Collaborative Workflow with Pull Requests

**Explanation:**
- Pull requests (PRs) enable collaboration by proposing changes and discussing them before merging.
- Collaborators review and approve PRs.

**Solution:**
1. Create a new repository or use an existing one.
2. Add a collaborator to your repository on GitHub.
3. Create a new branch for a feature or bug fix.
4. Make changes in your branch and push them.
5. Open a pull request from your branch to the main branch.
6. Collaborators review and merge the pull request.

## Exercise 4: Managing Issues

**Explanation:**
- Issues are used to track tasks, enhancements, and bugs.
- You can use labels, milestones, and assignees to organize and prioritize issues.

**Solution:**
1. Create a new issue in your repository on GitHub.
2. Provide a title, description, and assign labels, milestones, and assignees.
3. Close the issue with a reference to the commit that resolves it.

## Exercise 5: Forking and Contributing to Open Source

**Explanation:**
- Forking allows you to copy an open-source repository to your account.
- Contributing to open source involves making changes and submitting pull requests.

**Solution:**
1. Find an open-source project on GitHub.
2. Fork the repository to your account.
3. Clone your fork to your local machine.
4. Make a contribution (e.g., fixing a bug or adding a feature).
5. Commit and push your changes.
6. Create a pull request to the original repository.

## Exercise 6: Project Boards

**Explanation:**
- Project boards help you organize and prioritize work.
- You can use columns and automation to manage tasks.

**Solution:**
1. Create a project board for a GitHub repository.
2. Add issues to the project board and categorize them using columns.
3. Use automation to move issues through different stages.

## Exercise 7: Creating and Applying .gitignore

**Explanation:**
- A `.gitignore` file specifies files and directories that Git should ignore.
- It helps keep unneeded files out of the repository.

**Solution:**
1. Create a `.gitignore` file for your project.
2. Define rules in the `.gitignore` file to exclude specific files or directories.

## Exercise 8: Branch Protection Rules

**Explanation:**
- Branch protection rules enhance the security of your repository.
- They prevent direct pushes to specific branches.

**Solution:**
1. Open your repository on GitHub.
2. Go to the "Settings" tab.
3. Select "Branches" in the left sidebar.
4. Add a branch protection rule for the main branch.
5. Specify required status checks, reviews, or restrictions.
6. Test the protection rules by attempting to push changes directly to the protected branch.

## Exercise 9: GitHub Actions - Continuous Integration

**Explanation:**
- GitHub Actions automates workflows such as testing, building, and deployment.
- Continuous Integration (CI) runs tests automatically on code changes.

**Solution:**
1. Create a GitHub Actions workflow in your repository.
2. Configure the workflow to run tests on every push to the repository.
3. Define the testing steps and use GitHub-hosted runners or self-hosted runners.

## Exercise 10: GitHub Pages - Hosting a Website

**Explanation:**
- GitHub Pages allows you to host static websites from your repositories.
- You can use a `docs` folder or a dedicated `gh-pages` branch.

**Solution:**
1. Create a simple HTML webpage or use an existing one.
2. Push the webpage content to your repository.
3. Configure GitHub Pages to publish from the `docs` folder or the `gh-pages` branch.
4. Access your hosted website at `https://username.github.io/repository-name`.

Congratulations! You've completed all 10 GitHub exercises. These exercises have given you hands-on experience with various GitHub features and workflows, making you more proficient in using GitHub for version control, collaboration, and automation.
