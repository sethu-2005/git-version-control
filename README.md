# DevOps Task 4: Version-Controlled Project with Git

## Objective
Manage a DevOps project applying Git best practices, including branch management, pull requests, and tagging, to establish a standard continuous integration workflow.

## Tools Used
* **Version Control:** Git
* **Repository Hosting:** GitHub

## Workflow Executed

1. **Repository Initialization:** 
   * Initialized a local Git repository and connected it to a remote GitHub repository.
   * Configured a `.gitignore` file to exclude environment variables (`.env`) and dependencies (`node_modules/`).
2. **Branching Strategy:** 
   * Created a standard multi-tier branch architecture: `main` (production), `dev` (staging/testing), and `feature` (development).
3. **Feature Development & Documentation:** 
   * Authored project documentation (`execution-docs.md`) directly within the `feature` branch to simulate active development.
4. **Pull Requests (PR) & Merging:** 
   * Opened and merged a PR from `feature` into `dev`.
   * Opened and merged a secondary PR from `dev` into `main` to simulate a production release.
5. **Release Tagging:** 
   * Created an annotated release tag (`v1.0.0`) on the `main` branch to establish an immutable milestone for the completed task.

## Key Learnings
* Resolving code effectively across multiple branches.
* Simulating a real-world CI/CD pipeline foundation using GitOps principles.
* Ensuring clean repository history using structured commits and PRs.