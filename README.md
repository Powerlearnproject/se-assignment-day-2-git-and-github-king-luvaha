[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18653593&assignment_repo_type=AssignmentRepo)

# SE Day 2: Git and GitHub

## 1. Fundamental Concepts of Version Control & GitHub
Version control tracks changes in code, allowing collaboration and rollback when needed. GitHub is widely used due to its cloud hosting, branch-based workflows, and seamless integration with Git, making version control efficient and collaborative.

## 2. Setting Up a New Repository on GitHub
1. Go to GitHub, click **New Repository**.
2. Name the repository, add a description.
3. Choose **Public** or **Private**.
4. Add **README, .gitignore, and a license** (optional).
5. Click **Create Repository**.

## 3. Importance of README
A README introduces the project, explaining:
- Project purpose
- Installation steps
- Usage instructions
- Contribution guidelines
- License information
A well-written README enhances clarity and collaboration.

## 4. Public vs. Private Repositories
- **Public Repositories**: Open to all, enabling collaboration and visibility.
  - **Pros**: Community contributions, exposure.
  - **Cons**: Less control, security risks.
- **Private Repositories**: Restricted access, ensuring project confidentiality.
  - **Pros**: Secure, controlled collaboration.
  - **Cons**: Limited visibility, requires access management.

## 5. Making Your First Commit
1. Clone or initialize the repo:
   ```sh
   git clone <repo_url>
   git init
   ```
2. Add files:
   ```sh
   git add .
   ```
3. Commit changes:
   ```sh
   git commit -m "Initial commit"
   ```
4. Push to GitHub:
   ```sh
   git push origin main
   ```
Commits track changes and maintain project history.

## 6. Branching in Git
Branches allow independent development without affecting the main codebase.
- Create:
  ```sh
  git branch feature-branch
  ```
- Switch:
  ```sh
  git checkout feature-branch
  git switch feature-branch
  ```
- Merge:
  ```sh
  git checkout main
  git merge feature-branch
  ```
Branches enable parallel development and prevent conflicts.

## 7. Pull Requests (PRs)
Pull Requests propose changes before merging.
1. Push changes to a branch.
2. Open a PR on GitHub.
3. Review, discuss, and approve.
4. Merge into the main branch.
PRs ensure quality and collaboration.

## 8. Forking vs. Cloning
- **Forking**: Copies a repository to your GitHub for independent development. Useful for contributing to open-source projects.
- **Cloning**: Creates a local copy of a repository for personal use.

## 9. Issues & Project Boards
- **Issues**: Track bugs, feature requests, and tasks.
- **Project Boards**: Organize tasks using Kanban-style boards for better workflow management.

## 10. Challenges & Best Practices
- **Common Pitfalls**: Merge conflicts, unclear commit messages, working on `main` directly.
- **Best Practices**: Use branches, write meaningful commits, follow PR reviews, and use `.gitignore`.

