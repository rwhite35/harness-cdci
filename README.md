# Continuous Deployment Project

A simple Node.js application deployed on Docker-Kubernetes cluster with continuous deployment support provided by Harness CDCI. Project unit test updates are automatically tested using Harness Delegate CD Pipeline configuration and Harness Manager controllers. Testing is injected before the push to a remote location, in this case, github. See the doc/ directory for setup and configuration.

## Prerequisites

> - [Node.js](https://nodejs.org/en/download/) installed and globally available.
> - [Docker Desktop](https://app.docker.com/) requires a FREE account and Docker Hub project setup.
> - [Kubernetes](https://kubernetes.io/) requires installing Kubernetes extension through Docker Desktop.
> - [Harness cloud](https://app.harness.io/) requires a FREE account to set up continuous integration.

## References

This project reference two other projects which are linked here for credit/convenience.

> - [Harness Community Example](https://github.com/harness-community/harnesscd-example-apps/) lots of examples.
> - [Note App CDCI](https://github.com/pavanbelagatti/notes-app-cicd.git) Paven Belagatti's implementation project.

Enjoy
