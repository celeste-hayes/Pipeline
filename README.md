# Pipeline

This project showcases a CI/CD pipeline using GitHub Actions to enhance code quality and deployment efficiency. The focus of this project is on Continuous Integration (CI) and Continuous Deployment (CD), two essential DevOps practices that help automate software testing and deployment. By integrating CI/CD, it can accelerate development cycles, reduce human error, and maintain high code quality without manual intervention.

---
### [Deployed Site]()

## Table of Contents
* [Features](#features)
* [Installation](#installation)
* [Testing](#testing)
* [License](#license)
* [Contributing](#contributing)
* [Contact Information](#contact-information)

## Features
- **Automated Testing:** Every Pull Request to develop triggers Cypress component tests, ensuring code changes are stable before merging.
- **Seamless Deployment:** Once code is merged from develop to main, the application is automatically deployed to Render.
- **Improved Workflow:** Enforces best practices, reducing manual intervention and improving release confidence.
- Deployed Application: The deploed application is set up to use Render and MongoDB

## Installation
1. Fork the repo to your local machine
2. Ensure cypress is installed in your project using: 
   ```
   npm install cypress --save-dev
   ```
3. Configure your GitHub Actions workflows:
  - A workflow to run Cypress tests on PRs to ``` develop ```.
  - A workflow to deploy to Render when merging to ``` main ```.
4. Push changes and open a PR to test the CI pipeline.

## Testing

Once the pipeline is configured, every time you push code:
- Create a PR to ``` develop ``` → Cypress tests run automatically.
- Merge to ``` develop ``` when tests pass.
- Merge ``` develop ``` into ``` main``` → Deployment to Render happens automatically.

## License
This project is licensed under the ISC License.

## Contributing
Contributions welcome for this project! Feel free to fork the repository, make your changes, and submit a pull request.

## Contact
If you have any questions or feedback, feel free to reach out!
* GitHub: celeste-hayes 