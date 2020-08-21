# Anomaly Detection in the Service Mesh

This Jupyter Notebook contains the dataset and machine learning model used in [the accompanying blog post](https://www.fosdick.io/2018/04/17/anomaly-detection-in-the-service-mesh.html).  You can either [run it directly in your browser](https://github.com/fosdickio/blob/master/AnomalyDetectionInTheServiceMesh.ipynb) or follow the instructions below to run it locally.

## Requirements
- Jupyter

## Instructions
```bash
jupyter notebook
```

## Abstract
Microservice architectures enable the continuous delivery and deployment of large, complex applications.  With this architecture choice comes the challenge of connecting, managing, and securing communications between the various microservices.  Recent application level denial of service attacks which target backend services have demonstrated a rising attack vector that is capable of bringing down enterprise level systems with minimal cost and effort.  By targeting expensive services using readily available cloud computing services, a single user is capable of backing up an entire system and causing widespread outages.

This project seeks to research and better understand the feasibility of using machine learning models to analyze traffic between microservices in order to perform anomaly detection in the service mesh.  The eventual goal of this research is to utilize these models to perform real time policy enforcement decisions based on changes in requests between services.