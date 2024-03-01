# OpenShift AI

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[Pattern Support Policy(https://validatedpatterns.io/contribute/support-policies/)]

## Start Here

This pattern is still under development. A complete and robust documentation site has not yet been established. Follow the quickstart below to get started! Currently, this pattern deploys the following:

- openshift-gitops
- advanced cluster management
- vault
- external secrets operator
- OpenShift Pipelines
- OpenShift AI

OpenShift AI has an instance of the datascience cluster CRD deployed, as well as a datascience cluster initialization CRD.

## Rationale

The goal for this pattern is to:

- Use a GitOps approach to MLOps workflows
- Incorporate a CI solution with OpenShift Pipelines
- Provide a quick, reliable way to get started with OpenShift AI and OpenShift Pipelines
- Securely manage secrets across the deployment.

## Quick Start

- Fork this repository and clone to your local machine
- Change directories to `openshfit-ai`
- Run `./pattern.sh make install`


