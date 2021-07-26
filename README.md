# github-actions-test

[Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)


## **ENVIRONMENT VARIABLES**
Some environment variables that are set automatically by Github actions in virtual machines

$GITHUB_SHA: Commit hash. Varies based on the type of webhook event<br/>
$GITHUB_REPOSITORY: Name of the GitHub repository<br/>
$GITHUB_WORKSPACE: The workspace directory (same as running pwd command)<br/>
$GITHUB_REF: The branch that triggered the Github action. Varies based on the type of webhook event<br/>
${{ github.token }}: Token that can be used to authenticate with the GitHub repository<br/>

## **CRON Schedule**
Cron scheduled jobs can only be initiated from the master repository. A main branch with a name other than master does not seem to work.

## ****
https://api.github.com/repos/goonerify/github-actions-test/dispatches
