# github-actions-test

[Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)


## **ENVIRONMENT VARIABLES**
Some environment variables that are set automatically by Github actions in virtual machines

$GITHUB_SHA: Commit hash. Varies based on the type of webhook event<br/>
$GITHUB_REPOSITORY: Name of the GitHub repository<br/>
$GITHUB_WORKSPACE: The workspace directory (same as running pwd command)<br/>
$GITHUB_REF: The branch that triggered the Github action. Varies based on the type of webhook event<br/>
${{ github.token }}: Token that can be used to authenticate with the GitHub repository<br/>
