**Overview:**
This project demonstrates automated API testing using Postman CLI integration with GitHub Actions. The workflow triggers with every push and executes a Postman collection to validate API responses.

**Key Features:**
 - Runes Postman collection via CLI
 - Uses Github Action for CI
 - Secure API key using GitHub Secrets
 - Automated test execution on push

**Tools/File Involved**
- Postman CLI
- GitHub Actions
- YAML

**Steps of Workflow**
1. Checkout repo
2. Install Postman CLI
3. Authenticate using API key
4. Run Postman collection
