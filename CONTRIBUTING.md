# Contributing to the Data Science Job‑Market Analysis Project

Thank you for your interest in contributing!  This project relies on the collective effort of volunteers to analyze the data‑science job market.  We strive to create an inclusive and supportive environment for everyone.  The following guidelines will help you get started.

You have (at least) three ways to contribute to this effort:

1. Read and contribute to our [Discussions](https://github.com/trgardos/data-science-job-market-analysis/discussions). There we can hash out early ideas and coordinate and collaborate our efforts.
2. Take a look at our [Issues](https://github.com/trgardos/data-science-job-market-analysis/issues) list. See if there is an issue you think you can contribute to. Have an idea for an enhancement or change? Feel free to contribute a new issue. Try to use the Issue template that best matches what you have in mind.
3. And finally, contribute to the codebase itself by forking and cloning the repo as described below.

## Contributing to Development

1. **Fork and clone** this repository.  You can work on your fork and submit pull requests against the main repository.
2. **Install the dependencies** listed in `requirements.txt` within a virtual environment.
3. **Familiarize yourself** with the repository structure and the project board to see what tasks are available.

## Choosing an issue

- Visit [issues](https://github.com/trgardos/data-science-job-market-analysis/issues) tab to find open tasks.  Look for issues labeled `good-first-issue` if you’re new.
- If you have an idea or question that doesn’t fit an existing issue, open a new issue using the appropriate template (task, research question or bug).  Provide a descriptive title and fill out all requested sections.
- Self‑assign the issue if you intend to work on it.  Each issue should have one or two assignees and a mentor for guidance.

## Branching and workflow

- **Create a feature branch** off the `main` branch of your forked/cloned repo:
  ```bash
  git checkout -b feature/issue-123-description
  ```
- Keep your changes focused on a single task or topic.  Small, focused pull requests are easier to review.
- Write clear **commit messages** describing what you changed and reference the relevant issue (e.g., `git commit -m "Extract skills for data‑scientist roles (closes #123)"`).

## Pull request process

1. **Test your changes**.  Ensure that notebooks execute without errors and that any scripts you add run correctly.
2. **Update documentation** if your change affects how others use the project (README, comments, docstrings).
3. **Submit a pull request** against `main`.  Use the pull‑request template and describe:
   - What you changed and why.
   - The issue the PR addresses (`Closes #123`).
   - Any follow‑up tasks or outstanding questions.
4. A mentor or reviewer will provide feedback.  Please respond promptly and make any necessary changes.
5. Once approved, the pull request will be merged.  Do **not** merge your own pull requests.

## Labels and milestones

- We use labels to categorize issues by type (`data-collection`, `data-cleaning`, `analysis`, `documentation`, `bug`, etc.), status (`to-do`, `in-progress`, `in-review`, `blocked`, `done`) and difficulty (`good-first-issue`, `intermediate`, `advanced`).
- Milestones track phases such as `Phase 1: Data Collection`, `Phase 2: Cleaning`, etc.  Assign your issue to the appropriate milestone to help with planning.

## Project board

- The project board uses an automated Kanban template with columns for **To Do**, **In Progress**, **Review in Progress**, **Reviewer Approved**, and **Done**.  Linking your issue or pull request to the board will automatically update its status.
- Use custom views to filter tasks by team or label.

## Coding style and guidelines

- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python code.  Use descriptive variable names, docstrings and comments.
- Organize notebooks with clear headings and explanations.  Keep them reproducible by running all cells in order before committing.
- Add tests or assertions when appropriate to ensure your functions work as expected.

## Questions and support

If you’re unsure about anything, open a discussion about your issue.  We’re here to help and want to make contributing a positive experience.
