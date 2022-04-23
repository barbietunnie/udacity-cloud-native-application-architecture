# Cloud Native Application Architecture Program

## Project Overview
**TechTrends** is an online website used as a news sharing platform, that enables consumers to access the latest news within the cloud-native ecosystem. In addition to accessing the available articles, readers are able to create new media articles and share them with the wider community. 

In this project, the role of a platform engineer is assumed, with the main role to package and deploy the application to a Kubernetes platform. 

The application was packages using Docker, and GitHub Actions was used to automate the Continuous Integration process. For the release process, Kubernetes declarative manifests templated with Helm were used.

To automate the Continuous Delivery process, ArgoCD was used.
