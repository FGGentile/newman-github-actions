##Features:
- Newman: Utilizes Newman for running Postman collections.
- GitHub Actions: Implements GitHub Actions for automated test execution upon code pushes or pull requests.
## Setup
- Clone the Repository
### Running Tests
- newman run Personal.postman_collection.json -e reqres.postman_environment.json -r htmlextra --reporter-htmlextra-export ./results/report.html
