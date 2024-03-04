# Helm Charts

## Overview

This repository contains Helm charts to simplify the deployment of a sample MySQL application. Helm is a package manager for Kubernetes that makes it easy to define, install, and upgrade even the most complex Kubernetes applications.

## Helm Charts

### 1. MySQL Helm Chart

#### Description

This Helm chart simplifies the deployment of a MySQL database in a Kubernetes cluster. It includes configurable parameters to customize the deployment according to your specific needs.

You can download and install helm from [here](https://github.com/helm/helm/releases)

#### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/veera-damisetti/helm.git

2. Go to the directory

   ```bash
   cd helm/

3. Install mysql application on your cluster

   ```bash
   helm install <name for release > mysql-app/ --values mysql-app/values.yaml
   
