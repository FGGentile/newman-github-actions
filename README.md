# Description:
This repository contains the setup for a simple yet effective API test automation framework using Newman, GitHub Actions, and Slack. It demonstrates how to implement a CI/CD pipeline for running Postman collections and reporting results
## Features:
- Newman: Utilizes Newman for running Postman collections.
- GitHub Actions: Implements GitHub Actions for automated test execution upon code pushes or pull requests.
## Setup
- Clone the Repository
### Running Tests
- newman run Personal.postman_collection.json -e reqres.postman_environment.json -r htmlextra --reporter-htmlextra-export ./results/report.html
