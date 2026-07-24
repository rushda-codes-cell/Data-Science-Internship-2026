# Day 24 – GitHub Actions CI/CD Pipeline

## Objective

The objective of Day 24 was to implement a GitHub Actions CI/CD pipeline to automate the project's build and validation process. The workflow ensures that every code update is automatically verified, improving development efficiency and code reliability.

---

## Tasks Performed

### 1. Created GitHub Actions Workflow

- Created a GitHub Actions workflow using `python-ci.yml`.
- Configured the workflow to trigger automatically on every push and pull request.

---

### 2. Set Up Python Environment

- Configured Python 3.12 using GitHub Actions.
- Prepared a consistent execution environment for the project.

---

### 3. Installed Project Dependencies

Installed the required Python libraries:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit

---

### 4. Automated Validation

The workflow performs the following actions automatically:

- Checks out the project repository.
- Sets up the Python environment.
- Installs required dependencies.
- Verifies the Python installation.
- Executes a validation step to confirm successful workflow execution.

---

## Outcome

Successfully implemented a GitHub Actions CI/CD pipeline that automates the project's validation process. The workflow now runs automatically whenever changes are pushed to the repository or a pull request is created.

---

## Tools & Technologies Used

- GitHub
- GitHub Actions
- YAML
- Python 3.12
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit

---

## Conclusion

The GitHub Actions CI/CD pipeline automates repetitive development tasks, maintains a consistent execution environment, and helps ensure that project updates are validated automatically, improving the overall software development workflow.
