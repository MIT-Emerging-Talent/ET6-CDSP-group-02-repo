# Contributing to Our Project

Welcome to our climate data science project!  
This guide explains how we work together, organize our files, and make contributions.

---

## 🧰 Tools We Use

We mainly use the following tools:

- Python 3.8+
- Jupyter Notebooks
- VS Code
- Git + GitHub

If you're not familiar with any of these, feel free to ask for help in our team chat.

---

## 📁 How the Repo is Organized

- Each milestone has its **own folder**
(e.g., `0_domain_research/`, `1_problem_identification/`, etc.)
- Add your files to the correct milestone folder
- Meeting notes go in the `meeting column` in our project board
- General thoughts or links can go in the `notes/` folder

Please don’t make changes directly to the `main` branch. Use branches and pull
requests (PRs).

---

## 🔄 Steps to Contribute

1. Make sure your local repo is up to date:

    ```bash
    git checkout main
    git pull origin main
    ```

2. Create a new branch for your task:

    ```bash
    git checkout -b branch-name
    ```

3. After making changes, save and commit:

    ```bash
    git add .
    git commit -m "what you did in this commit"
    ```

4. Push your branch:

    ```bash
    git push origin branch-name
    ```

5. Open a pull request on GitHub and tag a teammate for review.

---

## 🧼 Code Style

- Follow basic Python style (PEP8)
- Use clear variable names and write comments when things might be confusing
- Write functions instead of repeating code
- Add a short docstring to each function or class to explain what it does

We aim to use `ruff` and `pylint` to keep the code clean, so please check your
code with those when you are done.

---

## ✅ Before You Push

- [ ] Did you add your files to the right folder?
- [ ] Does your code run without errors?
- [ ] Is your commit message clear?
- [ ] Did you push to a branch and open a PR?

---

## 💬 Communication

- Use our group chat to ask questions or get help
- If you're not sure where something goes, just ask
- Give kind and helpful feedback in reviews
- Everyone’s input is welcome — we’re all learning together

---

Thanks for contributing! Your work is important to the team and the project.
