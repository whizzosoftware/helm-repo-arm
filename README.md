# A Helm repository for ARM devices

This is a Helm repository with charts specifically for ARM devices such as the Raspberry Pi. 

Use at your own risk!

## Installation

To install this repository in Helm, run:

````helm repo add helm-repo-arm https://whizzosoftware.github.io/helm-repo-arm/````

To install a Helm chart from the repo (for example sabnzbd), run:

````helm install helm-repo-arm/sabnzbd --name=sabnzbd````