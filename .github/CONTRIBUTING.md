
# Contributing Guidelines

Welcome to our development project for WoPeD! To ensure a smooth and efficient workflow for everyone involved, we follow a structured development process. Please adhere to the following guidelines when contributing.

## Fork the Repository

please begin by forking the repository to your own GitHub account.

You can follow GitHub's official guide here:  
👉 [How to fork a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

Once forked, clone your forked repository locally and work from there.

## Create a new Branch 

Before starting any development work, create a new feature branch from the `main` branch.  
🚫 **Do not develop directly on the `main` branch.**

Branch names should follow this pattern:

```
feature/<short-description>
```
![GitHub Flow Branching Strategy](GitHubFlow.png)
**Examples:**
- `feature/login-page`
- `feature/database-schema` 

## Commit to the Branch

### Commit Naming Convention (Moritz pls. adapt this chapter)

All commits should follow this convention to maintain clarity and traceability:

```
<type>: <concise description>
```

**Examples:**
- `feat: implement user login`
- `fix: correct typo in registration form`

Use the following types:
- `feat` – A new feature  
- `fix` – A bug fix  
... 

### Commit Hooks (Moritz pls. adapt this chapter)

To enforce consistency and code quality, we use Git hooks.

**Hooks in use:**
- `pre-commit`: Runs linting and formating before allowing a commit.  
- `commit-msg`: Verifies that the commit message adheres to our naming convention.  

## Create a Pull Request (Needs a revision by Jona & Leon)

Once your changes are complete and pushed to your feature branch:

1. Open a Pull Request (PR) against the `main` branch of the original repository.
2. Ensure your PR fulfills all the requirements listed in the PR Template
3. Reviewers will check your code for correctness, style, and completeness.
4. Once approved, your PR can be merged.
