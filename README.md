# Kubernetes Apache and NGINX Ingress Controller Deployment

This project demonstrates how to deploy containerized web applications using **Kubernetes** with **Apache** and **NGINX**, and how to configure **Ingress** and **ConfigMap** for managing traffic and injecting HTML content into Apache pods.

## Project Overview

In this project, I

- Deployed Apache and a custom NGINX application inside a Kubernetes cluster.
- Exposed these applications via **ClusterIP Services**.
- Configured an **NGINX Ingress Controller** for managing HTTP traffic.
- Used **ConfigMap** to inject a static HTML file into the Apache pod.

## Features

- **Path-based routing**: 
  - `/apache` → Apache pods (with custom HTML injected via ConfigMap)
  - `/custom` → Custom NGINX app

- **Custom Docker Images**: 
  - Apache container using the `httpd:latest` image.
  - Custom NGINX app using the `nginx:alpine` image.

- **Ingress Controller**: Configured to manage external traffic to the Kubernetes cluster.

- **ConfigMap**: Injected an HTML page into Apache pods.

  
### Check out the Document to Know More....
https://www.linkedin.com/posts/shudhodhan-wani-793149221_kubernetes-demo-activity-7325250371226857472-OkSa?utm_source=share&utm_medium=member_desktop&rcm=ACoAADe6YR8BJf6YcSLL4-JwyicwX13D--SW84s
