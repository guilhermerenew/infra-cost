[![.github/workflows/infracost.yml](https://github.com/guilhermerenew/infra-cost/actions/workflows/infracost.yml/badge.svg)](https://github.com/guilhermerenew/infra-cost/actions/workflows/infracost.yml)
## Getting started
Infracost shows cloud cost estimates for Terraform projects. It helps developers, devops and others to quickly see the cost breakdown and compare different options upfront.

## CI/CD integrations
The Infracost CI/CD integration can be used to automatically add a pull request comment showing the cost estimate difference (similar to git diff) between the master branch and the working branch. You can also select to ignore changes with minor cost increase/decreases by setting a percentage threshold for the comment to be added - details are in each integration document.\
Infracost can be used in any CI/CD system using our binary or Docker image. You might also find our CI diff script useful; it's used in the following integrations.
