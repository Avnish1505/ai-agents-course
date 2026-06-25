# 🤝 Contributing to AI Agents Course

First off, thank you for considering contributing! Your help is essential for keeping this project great.

This project is both a course and a codebase. Contributions can range from fixing a typo in a lesson to adding a new feature to the capstone project.

## Code of Conduct

We have a [Code of Conduct](./CODE_OF_CONDUCT.md) to ensure our community is welcoming and inclusive. Please read and follow it in all your interactions with the project.

## How Can I Contribute?

### 🐛 Reporting Bugs

If you find a bug in the course material or the code, please [open a bug report](https://github.com/Avnish1505/ai-agents-course/issues/new?template=bug_report.md). A good bug report includes:
- A clear title and description.
- Steps to reproduce the bug.
- What you expected to happen vs. what actually happened.

### ✨ Suggesting Enhancements

Have an idea for a new feature, a new lesson, or an improvement to an existing one? [Open a feature request](https://github.com/Avnish1505/ai-agents-course/issues/new?template=feature_request.md).

### 💻 Your First Code Contribution

Unsure where to begin? Look for issues tagged with `good first issue`. These are tasks that are perfect for new contributors.

### Pull Request Process

1.  **Fork the repository:** Create your own copy of the project.
2.  **Clone your fork:** `git clone https://github.com/YOUR_USERNAME/ai-agents-course.git`
3.  **Create a new branch:** `git checkout -b your-feature-name`
    - Use a descriptive branch name, like `fix-lesson-05-typo` or `feature-add-critic-agent`.
4.  **Set up your environment:** Follow the instructions in the main `README.md`.
    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
5.  **Make your changes!**
6.  **Format and lint your code:** We use `black` for formatting and `flake8` for linting.
    ```bash
    pip install black flake8
    black .
    flake8 .
    ```
    Please fix any issues before committing.
7.  **Commit your changes:** `git commit -m "feat: Add a brief, descriptive commit message"`
    - We follow the Conventional Commits specification.
8.  **Push to your branch:** `git push origin your-feature-name`
9.  **Open a Pull Request:** Go to the original repository and open a PR from your forked branch.
    - Fill out the PR template with details about your changes.

## Styleguides

- **Python:** Follow PEP 8. Use `black` to format your code automatically.
- **Documentation:** Use Markdown. Try to be clear and concise.

## Any questions?

Feel free to open an issue if you're stuck or have questions. We're here to help!