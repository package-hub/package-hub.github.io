---
title: webapps-deploy
categories: ['typescript']
---
## [webapps-deploy](https://github.com/Azure/webapps-deploy)

### Enable GitHub developers to deploy to Azure WebApps using GitHub Actions


With the Azure App Service Actions for GitHub, you can automate your workflow to deploy [Azure Web Apps](https://azure.microsoft.com/services/app-service/web/) or [Azure Web Apps for Containers](https://azure.microsoft.com/services/app-service/containers/) using GitHub Actions.

Get started today with a [free Azure account](https://azure.com/free/open-source).

This repository contains GitHub Action for Azure WebApp to deploy to an Azure WebApp (Windows or Linux). The action supports deploying a folder, *\*.jar*, *\*.war*, and \**.zip* files (except msBuild generated packages).

You can also use this GitHub Action to deploy your customized image into an Azure WebApps container.

For deploying container images to Kubernetes, consider using [Kubernetes deploy](https://github.com/Azure/k8s-deploy) action. This action requires that the cluster context be set earlier in the workflow by using either the [Azure/aks-set-context](https://github.com/Azure/aks-set-context/tree/releases/v1) action or the [Azure/k8s-set-context](https://github.com/Azure/k8s-set-context/tree/releases/v1) action.

The definition of this GitHub Action is in [action.yml](https://github.com/Azure/webapps-deploy/blob/master/action.yml). *startup-command* is applicable only for Linux apps and not for Windows apps. Currently *startup-command* is supported only for Linux apps when SPN is provided and not when publish profile is provided.

NOTE: you must have write permissions to the repository in question. If you're using a sample repository from Microsoft, be sure to first fork the repository to your own GitHub account.
