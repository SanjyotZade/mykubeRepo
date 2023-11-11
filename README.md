# mykubeRepo

This repository follows a CI/CD (Continuous Integration/Continuous Deployment) workflow to streamline development and deployment processes. Below is an overview of the workflow:

### Continuous Integration (CI)

The CI pipeline involves the following steps:

1. **Source:**
   - Developers push code changes to the repository.

2. **Build:**
   - The CI server triggers a build process upon detecting new changes.
   - The build process compiles, tests, and validates the code.

3. **Test:**
   - Automated tests are executed to ensure code quality and reliability.

4. **Artifact:**
   - If the tests pass, artifacts (e.g., Docker images, binaries) are created.

### Continuous Deployment (CD)

The CD pipeline involves the following steps:

1. **Deploy to Staging:**
   - The artifacts are deployed to a staging environment for further testing.
   - Additional tests, such as integration and user acceptance tests, are conducted.

2. **Approval:**
   - Upon successful testing, an approval process is initiated for production deployment.

3. **Deploy to Production:**
   - The artifacts are deployed to the production environment.

## Workflow Visualization

![mlops-flow](./mlops_flow.png)