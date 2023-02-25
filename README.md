# Documentation for GitHub Bot
#### This is a GitHub bot that creates a comment on all open issues in a repository. It uses the Octokit library to interact with the GitHub API.

# Prerequisites
#### Before using this bot, you need to:

1. Have a GitHub account
2. Create a personal access token with the necessary permissions to create comments on issues. You can create a personal access token here. Make sure to copy the token and keep it safe, as you won't be able to see it again.
3. Installation
### To use this bot, follow these steps:
1. Clone the repository:
` git clone https://github.com/mikeyolang/testingGithubBot.git `
2. Install the required dependencies:
` npm install @octokit/rest `
3. Replace the `auth` value in the code with your personal access token:
``` 
const octokit = new Octokit({
  auth: "your-personal-access-token",
});

```
