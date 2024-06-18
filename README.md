# GitHub-Actions-Example

## Project Overview
Demo to showcase different types of workflow_dispatch usages. The project consists of 6 different workflows. Part of this project is also the configuration of the environment's secrets and protection rules(reviewers, timers).

## Secret example

```text
Environment secrets
MY_SECRET            dev

Repository secrets
MY_SECRET
```
* if we are working in the dev environment then the MY_SECRET secret from the dev environment would be used.
* if we are working in this case in any other environment then the MY_SECRET for the whole repository would be used.
