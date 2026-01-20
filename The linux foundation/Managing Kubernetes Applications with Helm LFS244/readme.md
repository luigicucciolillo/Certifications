# Managing Kubernetes Applications with Helm (LFS244)

Helm is an emerging technology that enables packaging and running applications on Kubernetes in a simple, efficient way. This course is a deep dive into Helm, and how it's used in real-world scenarios to manage the lifecycle of applications on Kubernetes.

# A description

The course provides a system-level understanding of Helm architecture, chart design, and release management, enabling repeatable, versioned, and production-safe deployments. It covers building production-ready Helm charts, managing installations, upgrades, rollbacks, and working with chart repositories and dependencies. Helm is treated as a control abstraction layer between application intent, Kubernetes primitives, and CI/CD or GitOps workflows, similar to a shipping container that standardizes application delivery across environments. Real-world operational risks such as misconfigured charts, release state drift, and centralized deployment models are analyzed. 

Misconfiguration can impact service availability but is mitigated through linting, validation, and staged rollouts. Release drift is addressed through GitOps reconciliation and strict ownership of resources. In edge computing scenarios, centralized Helm usage may become a single point of failure, mitigated by pre-rendered manifests and decentralized deployment pipelines. Overall, the course strengthens production reliability, operational scalability, and lifecycle control for Kubernetes workloads.

official link [here](https://training.linuxfoundation.org/training/managing-kubernetes-applications-with-helm-lfs244/)


# Who Is It For
Recommended for system administrators, DevOps engineers, SREs, and other software professionals, this course is for any person who wishes to enhance their operational experience running containerized workloads on the Kubernetes platform.

# What You’ll Learn

This course covers the history of the Helm project and its architecture, how to properly install the Helm client, the various components of a Helm chart and how to create one, the command-line actions used for managing an application’s lifecycle, and much more.

# What It Prepares You For
This course provides a full-featured deep dive into the Helm client, Helm charts, and how Helm can prepare you for real-world scenarios managing the full lifecycle of applications on Kubernetes.

# Course Outline

Chapter 1. Course Introduction<br>
Chapter 2. Helm Basics<br>
Chapter 3. Helm Setup and Initial Usage<br>
Chapter 4. Helm Charts<br>
Chapter 5. Application Lifecycle<br>
Chapter 6. Chart Repositories and Other Topics