### Exercise 1: Create a Repository and Branch

#### Task:
1. Create a new GitHub repository named "Collaboration-Exercise."
2. Clone the repository to your local machine.
3. Create a new branch named "feature/add-intro-page."
4. Add an introduction page (HTML and CSS) to the project.
5. Stage, commit, and push the changes to your branch.
6. Create a pull request for your branch on GitHub.

#### Solution:
```bash
# Terminal commands for students to execute
git clone <repository_url>
cd Collaboration-Exercise
git checkout -b feature/add-intro-page
# Add and modify files (index.html, styles.css)
git add .
git commit -m "Add introduction page"
git push origin feature/add-intro-page
# Create a pull request on GitHub
```

---

### Exercise 2: Code Conflicts

#### Task:
1. Create a new branch named "feature/add-footer."
2. Add a footer section to the project.
3. Meanwhile, another student creates a branch "feature/add-header" and adds a header section.
4. Both students try to merge their branches into the main branch.
5. Resolve the conflicts.

#### Solution:
```bash
# Student 1: Terminal commands
git checkout -b feature/add-footer
# Add and modify files (footer.html, styles.css)
git add .
git commit -m "Add footer"
git push origin feature/add-footer

# Student 2: Terminal commands
git checkout -b feature/add-header
# Add and modify files (header.html, styles.css)
git add .
git commit -m "Add header"
git push origin feature/add-header

# Conflicts occur when merging
# Resolve conflicts, commit changes, and push again
```

---

### Exercise 3: Code Review and Discussion

#### Task:
1. Fork the "Collaboration-Exercise" repository.
2. Clone your forked repository locally.
3. Create a new branch named "feature/add-navigation."
4. Add a navigation menu to the project.
5. Create a pull request and ask for a code review.
6. Another student reviews the code and suggests changes.
7. Address the comments and update the pull request.

#### Solution:
```bash
# Terminal commands for students to execute
# Fork the repository on GitHub
# Clone the forked repository locally
git clone <your_forked_repository_url>
cd Collaboration-Exercise
git checkout -b feature/add-navigation
# Add and modify files (navigation.html, styles.css)
git add .
git commit -m "Add navigation"
git push origin feature/add-navigation
# Create a pull request on GitHub
# Discuss and address code review comments
# Update the existing commit and force-push (use with caution)
```

---

### Exercise 4: Collaboration on the Same Branch

#### Task:
1. Clone the "Collaboration-Exercise" repository.
2. Create a new branch named "feature/add-sidebar."
3. Meanwhile, another student wants to collaborate on the same branch.
4. Encourage the second student to create a new branch for their changes.
5. Both students should push their changes to GitHub.

#### Solution:
```bash
# Student 1: Terminal commands
git clone <repository_url>
cd Collaboration-Exercise
git checkout -b feature/add-sidebar
# Add and modify files (sidebar.html, styles.css)
git add .
git commit -m "Add sidebar"
git push origin feature/add-sidebar

# Student 2: Terminal commands
git checkout -b feature/modify-sidebar  # Create a new branch
# Add and modify files (sidebar.html, styles.css)
git add .
git commit -m "Modify sidebar"
git push origin feature/modify-sidebar
```

---

### Exercise 5: Sync with the Main Branch

#### Task:
1. Clone the "Collaboration-Exercise" repository.
2. Create a new branch named "feature/add-contact-page."
3. Periodically, sync your local repository with the main branch to get the latest changes.

#### Solution:
```bash
# Terminal commands for students to execute
git clone <repository_url>
cd Collaboration-Exercise
git checkout -b feature/add-contact-page
# Add and modify files (contact.html, styles.css)
git add .
git commit -m "Add contact page"
git push origin feature/add-contact-page

# Periodically sync with the main branch
git checkout main
git pull origin main
git checkout feature/add-contact-page
git merge main
# Resolve conflicts if any, commit changes, and push again
```
