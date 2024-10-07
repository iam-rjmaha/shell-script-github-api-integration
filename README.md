# Shell Script for GitHub API Integration

## Overview
As a DevOps engineer, maintaining Git repositories is a key responsibility. A common task is to check the list of users who have access to a specific repository on GitHub. This project automates that process using a shell script that integrates with the GitHub API.

## Features
- Fetches the list of users with access to a specified GitHub repository.
- Utilizes the GitHub API for seamless data retrieval.
- Easy to configure and run on any Unix-like system.

## Prerequisites
- A GitHub account.
- A Personal Access Token with the necessary permissions to access the repository.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your repo name

   2. Navigate to the project directory:
   ```bash
   cd shell-script-github-api-integration
   ```
3. Make the script executable:
   ```bash
   chmod +x get_repo_users.sh
   ```

## Usage
1. Open the script file `get_repo_users.sh` and configure your GitHub Personal Access Token and the username details:
   ```bash
   export token="your_personal_access_token"
   export username="username"
   ```
2. Run the script: 2 input command arguments are mandatory one is organization name and another one is repo name
   ```bash
   ./get_repo_users.sh org_name repo_name
   ```

## Example
```bash
# Example output
User: user1
User: user2
User: user3
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.



## Acknowledgments
- GitHub API documentation for guidance on accessing repository information.
- [curl](https://curl.se/) for making API requests from the command line.

```

