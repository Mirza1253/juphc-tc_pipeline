# Epic and User Stories

## Epic: Modernize and automate Tax Calculator delivery
As a development team, we want to containerize the Tax Calculator, add automated tests, and create CI/CD so the application can be tested and deployed consistently.

### Story 1 — Containerize the application
As a developer, I want a Dockerfile so the Tax Calculator runs in a reproducible container.

### Story 2 — Automate unit testing
As a developer, I want Jasmine tests to run automatically so calculation errors are detected before deployment.

### Story 3 — Build and publish the image
As a developer, I want the application image built and pushed to IBM Cloud Container Registry so it is available for deployment.

### Story 4 — Automate deployment
As a developer, I want Tekton tasks to test, build, and deploy the application so releases are repeatable.

### Story 5 — Verify the deployed application
As a user, I want the deployed Tax Calculator to be accessible in a browser so I can verify the release.
