# Liquibase Pro Implementation Guide

Copy the contents of this repository to your own repository.

1. Clone this repository at the same level as your own 'my-repo':

`git clone git@github.com:liquibase/cs-impl-guide-examples-automations.git`

2. Copy the visible contents to your own repository. (Workflows are stored in directories beginning with '.' and are therefore invisible, so we'll come to them in the next step):

`cp -R ./cs-impl-guide-examples-automations/* ./my-automations-repo`

3. If you are implementing GitHub Actions, copy the GitHub Actions workflows directory (.github) to your own:

`cp -R ./cs-impl-guide-examples-automations/.github ./my-automations-repo`

4. If you are implementing Azure Pipelines, copy the Azure Pipelines workflows directory (.azure_pipelines) to your own:

`cp -R ./cs-impl-guide-examples-automations/.azure_pipelines ./my-automations-repo`
