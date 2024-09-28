---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Industrial Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Software Engineer
    company: Sotoon
    company_url: 'https://sotoon.ir'
    company_logo: sotoon
    location: Tehran
    date_start: '2023-01-01'
    description: |2-
        Sotoon is a B2B cloud provider which focuses on diﬀerent aspects of Cloud Computing, such as hardware abstraction,
        Providing storage servers, DNS, CDN, Bigdata solution and managed k8s cluster. I worked in the K8s as a Service team.
            </br>
        Experiences:
        * Using [SIGS/Cluster-api](https://github.com/kubernetes-sigs/cluster-api) to provide a boostraping automation and operations as a service for k8s.
        * Develop and Maintain SotoonCSI, a **CSI implementation** that integerates with Sotoon's storage backend.
        * Develop **node-AutoScaler** for k8s cluster which integerates with Sotoon's Computation backend with the aim of reducing costumers costs.
        * Develop and maintain a **CCM** module to provide loadbalancers for k8s clusters using sotoon's compute infrastructure.
        * Provide additional cluster plugins such as **DNS** and **CNI** as an automated solution.
        * Plan and Lead **Migration** of **over 100 customer**'s k8s-clusters to the new infrastructure with **zero downtime**.

  - title: Data Platform Engineer
    company: Digikala
    company_url: 'https://www.digikala.com'
    company_logo: dk
    location: Tehran
    date_start: '2021-01-01'
    date_end: '2023-01-01'
    description: |2-
        Digikala is the largest e-commerce company in Iran with 40+ million users. As a member of the Bigdata & AI team, my job is
        to provide the necessary infrastructure needed to store and process the data accumulated from the users.
            </br>
        Experiences:
        * Develope Karavan, a **Parallel Processing Engine** for data pipelines on top of Apache Spark.
        * Maintain and Develop our own fork of **Apache Spark operator**.
        * **Reduce Computation time** of Data Pipelines by revising our data retrieval models and Queries.
        * Reduce latency of hot APIs by locating **critical paths** in the codebase of the framework and optimizing them.
        * Use K8s as the main orchestrator with HDFS as the storage backend to provided a variety of tools for the DS/DE team to work with, including **Airﬂow** as our job scheduler and **Spark** as our main batch/stream processor and pipeline engine.
        * maintain **Kafka cluster** as a Sync and **Debezium **to sync external Databases to it.
        * Manage the platform’s infrastructure based on **GitOps** protocols using **ArgoCD**. Automate deployment of our APIs using ArgoCD with **Kustomize** and **Helm** charts.
        * Deploy and maintain a staging environment and build a framework for the Data Science team to better interact with our infrastructure.

  - title: DevOps Engineer
    company: Tapsell
    company_url: 'https://tapsell.com/'
    company_logo: tapsell
    location: Tehran
    date_start: '2020-01-01'
    date_end: '2021-03-01'
    description: |2-
        Tapsell is one of the prominent ad-infrastructure providing company in Iran. As a DevOps engineer, I was tasked with Providing the infrastructure needed by other technical teams in the corporation.
            </br>
        Experiences:
        * Manage and automate deployment procedures of databases such as **MongoDB**, **Cassandra**, and **ElasticSearch** with **Ansible**.
        * Optimize **Cassandra**’s **Disk usage** and life time for diﬀerent workloads; resulting in over **50% reduction in total disk size** of the cluster.
        * Develope a fully automated backup, validity check, and restore tool for managing backups in a cloud native infrastructure.
        * Deploy and maintain the staging cluster using k8s and provide syncing pipelines with the Production environment.
        * **Migrate** CI/CD ﬂows from jenkins to **GitlabCI**.
        * Work with **Terraform** to automate deploying computational infrastructure on VMWare.
        * Administrate Linux-based virtual machines and address networking issues.

design:
  columns: '2'
---
