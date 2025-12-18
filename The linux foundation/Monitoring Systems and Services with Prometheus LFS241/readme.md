# Monitoring Systems and Services with Prometheus (LFS241)

This course leads new Prometheus users through many of its major features, best practices, and use cases. Course participants are expected to have basic experience with Linux/Unix system administration, as well as some development experience in Go and/or Python.

# In short

The *Monitoring Systems and Services with Prometheus (LFS241)* course provides a structured and in-depth introduction to **cloud-native observability**, focusing on monitoring modern distributed systems and Kubernetes workloads. It covers the **Prometheus data model**, pull-based scraping, **time-series storage internals (WAL, blocks, compaction)**, and metric types (counters, gauges, histograms, summaries), together with **PromQL** for querying, aggregation, and alert evaluation. The course explains integration with **Kubernetes service discovery**, **labeling and relabeling pipelines**, and exporters such as **Node Exporter**, **cAdvisor**, **blackbox exporter**, and **Pushgateway**, as well as custom instrumentation in **Go and Python**. It explores **alerting architectures** using **Alertmanager**, including grouping, routing, deduplication, and high availability via gossip protocols. Practical laboratories include **remote storage integrations** using **SeaweedFS** and **MinIO** (S3-compatible object storage) together with **Thanos** for long-term storage, query federation, and globally scalable Prometheus architectures. Overall, the course provides hands-on experience operating **scalable, highly available observability stacks** in production and edge-oriented environments.

official link [here](https://training.linuxfoundation.org/training/monitoring-systems-and-services-with-prometheus-lfs241/)

# Who Is It For
The LFS241 course is built for DevOps engineers, SREs, and system admins ready to level up observability skills and get Prometheus-ready for high-impact roles in modern, cloud-native environments. The PCA is a pre-professional certification designed for an engineer or application developer with special interests in observability and monitoring.

# What You’ll Learn
Walk away knowing how to monitor real-world systems with Prometheus—track containers, catch issues early, use service discovery, and build production-grade observability into your Kubernetes stack.

# What It Prepares you for

Prepare for real-world observability challenges—whether you're deploying at scale, building dashboards, or setting alerts. This course, along with real-world experience and study, will provide the skills and knowledge also tested by the Prometheus Certified Associate (PCA) exam

# Course Outline
Chapter 1. Course Introduction <br>
Chapter 2. Introduction to Observability<br>
Chapter 3. Introduction to Prometheus<br>
Chapter 4. Installing and Setting Up Prometheus<br>
Chapter 5. Basic Querying<br>
Chapter 6. Dashboarding<br>
Chapter 7. Monitoring Host Metrics<br>
Chapter 8. Monitoring Container Metrics<br>
Chapter 9. Instrumenting Code<br>
Chapter 10. Building Exporters<br>
Chapter 11. Advanced Querying<br>
Chapter 12. Relabeling<br>
Chapter 13. Service Discovery<br>
Chapter 14. Blackbox Monitoring<br>
Chapter 15. Pushing Data<br>
Chapter 16. Alerting<br>
Chapter 17. Making Prometheus Highly Available<br>
Chapter 18. Recording Rules<br>
Chapter 19. Scaling Prometheus Deployments<br>
Chapter 20. Local Storage<br>
Chapter 21. Remote Storage Integrations<br>
Chapter 22. Transitioning From and Integration with Other Monitoring Systems<br>
Chapter 23. Monitoring and Debugging Prometheus<br>
Chapter 24. Prometheus and Kubernetes<br>