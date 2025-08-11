# Git workflow

We use Git and GitHub to collaborate on code and track changes.

## Repository structure

For the main structure of the projects, and why we adopt that structure, see [code-structure](code-structure.md).

## Key Concepts

- **Repository**: Project container
- **Branch**: Copy of code you're working on
- **Commit**: Savepoint
- **Pull Request**: Code review and merge request

## Standard Workflow

1. **Clone the repo**

```bash
git clone https://github.com/your-org/project-name.git
```

2. **Create a new branch**

```bash
git checkout -b feature/my-experiment
```

3. **Make changes through commits with clear messages**

```bash
git add .
git commit -m "informative message"
```

When committing changes, make sure you use clear messages:

- best practice is to use imperative style (add plot condition B) instead of descriptive (added plot condition B)
- we have a preference for small, focused commits. Commit early, commit often.

4. **Push branch**

```bash
git push origin feature/my-experiment
```

5. **Open a pull request (PR)**

- Target the `dev`branch
- Link to the related issues (e.g. `closes #12`)
- If the update is big, request review from someone else in the lab

7. **Merge to `dev` when approved**

## Other

### Pull request checklist

- [ ] descriptive title and summary
- [ ] links to related issues
- [ ] code is documented or commented
- [ ] notebooks run start-to-finish

### Git resources

- [Github Docs](https://docs.github.com/)
- [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Atlassian git tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control)
