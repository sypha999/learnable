# Learnable

## What is Version Control?

Version control is a system that helps developers **track changes to code over time**. It allows you to:

* See what changes were made and when
* Revert to previous versions if something breaks
* Collaborate with other developers without overwriting each other’s work

---

## Difference Between Git and GitHub

* Git → A tool you install on your computer to track changes
* GitHub → A website where you store and share your code

---

## GitHub Alternatives

Here are 3 popular alternatives:

1. **GitLab** – Offers built-in CI/CD and DevOps tools
2. **Bitbucket** – Popular with teams using Atlassian tools (Jira, etc.)
3. **Azure DevOps Repos** – Microsoft’s solution with strong enterprise integration

---

## Difference Between `git fetch` and `git pull`

### `git fetch`

* Downloads changes from the remote repository
* **Does NOT modify your working code**
* Safe way to check updates

```bash
git fetch
```
---

### `git pull`

* Downloads changes AND merges them into your current branch
* **Updates your working code immediately**

```bash
git pull
```

---

## Git Rebase

Rebase is used to **move your branch on top of another branch**, making the history cleaner and more linear.
Instead of creating a merge commit, it **replays your changes on top of the latest code**.

### Command:

```bash
git rebase main
```

---

## Git Cherry-Pick

Cherry-pick lets you **copy a specific commit from one branch to another**.
Useful when you want **just one change**, not the entire branch.

### Command:

```bash
git cherry-pick <commit-hash>
```
---

