---
slug: demo-08
date: 2010-10-05
title: 'AKS effort estimation'
description: 'Effort estimation for projects on AKS'
published: true
banner: './banner.png'
---

1. Prerequisites

Azure Enterprise Account

2. Concept planning

Create high-level design and Technical design architecture documentation

1. Conduct alignment sessions on concept and gather approvals with TACO application IT Stakeholders

2. Create communication plan and materials based on pilot migration concept 

3. Detailed architecture design has to be created for Network Design, Access management, Container registry,Kubernetes Clusters, storage, database, Backup, Monitoring, Logging and Alerting for the TACO application deployment

4. Plan for the AKS cluster nodes and sizing depending on the application requirement  to provide high availablility, security and resilience

5. Plan for migrating the monolith Application to microservices

6. Create a pilot for implementation, migration, cutover and rollback concepts

7. Gather approvals for migration, cut-over, rollback and communication plan


3. Preparation
Preparing the Azure Infrastructure for 

1. Get  Access to all the team members on azure subscription and azure devops 

2. Prepare the scripts for Infrastructure deployment (Infra-as-Code) using terraform modules for the azure resources

3. Containerize the old application and design cluster management and scaling

4. Use Helm/Helm Chart to maintain the lifecycle of the application deployment

5. Develop the pipeline to Test the application, adjust and then deploy to the production enviroment

4. Implementation
Build and deploy the Infrastructure 

1. Understand and Identify reference architechture

2. Create a project in Azure devops and collaborate with all the teams to create the terraform and application modules

3. Clusters governance, security and protection

4. Implement container registry configuration Application gateway and Ingress controller for AKS

5. Create Namespace for app Isolation / RBAC concept

6. Check for Application remediation to be containerization ready

7. Generate and build app manifest

8. Build application Docker Container and unit test in dev environment 

9. Deploy and configure monitoring, logging and Alerting 

10. Create CI/CD pipeline to deploy infrastructure,containers and implement image update and versioning in container registry  

11. Basic smoke test acceptance to be taken from the client  

12. Create detailed documentation for the scripts and pipelines implemented



5. Handover
Knowledge transfer to the operation team


1. Handover all the techinical documents and Devops Project 

2. Provide knowledge transfer to service team regarding the architecture and Cluster Management and scaling

