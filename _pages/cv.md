---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* **Research Assistant**, University of Florida (05/2024 - present)
  * Building data-driven simulation in the latent space using diffusion models for scientific simulation applications such as weather prediction and CFD simulations.
  * Working on world models to bridge the gap between deep-learning models used in the self-driving domain and the explainability required for smarter public infrastructure.
  * Built a traffic simulation model using a Transformer architecture to model multi-agent (vehicles, pedestrians, signals) interactions, and a data harmonization framework to combine data from multiple scenes and generalize to held-out scenes, showing a 36% improvement over a model trained on a single scene with strong zero-shot results.
  * Developed a variational autoencoder based trajectory prediction model combining curvilinear coordinates with intersection-related controls, performing 17% better on displacement metrics than a strong baseline.
  * Worked on a novel "simulation-in-the-loop" framework to evaluate trajectory prediction models on multi-agent simulation tasks, proposing a set of traffic-engineering-based metrics: unsafe deceleration, lane following and red-light violations.
  * Maintained and operated the end-to-end computer vision data pipeline for traffic-intersection video analytics, configuring YOLOv7 object detection and DeepSORT tracking to deliver high-quality trajectory data for near-miss conflict analysis, maintaining uptime of over 99%.

* **Software Intern**, Nutanix, San Jose, CA (05/2023 - 08/2023)
  * Engineered an efficient messaging bus for a security policy framework to send and receive security policies between the hypervisor and management VM, stress tested to 1 million+ policies and beating the existing pipeline by over 10 percent.
  * Created a front-end page using React with dynamic page refresh to show the security policies applied to containers running on the hypervisor, with controls for adding subnet masks and IP addresses.

* **Member of Technical Staff**, VMware, Bangalore, India (07/2020 - 07/2022)
  * Worked on the Edge-Routing team developing routing protocols for the open-stack routing framework Free Range Routing (FRR).
  * Designed and implemented data structures for transaction-driven asynchronous CRUD operations for management of network routing information without compromising transaction consistency.
  * Contributed features such as commit-rollback (reversing the transaction), asynchronous read operations (for fetching large operational data without delaying other transactions), and wildcard query resolution.

* **Undergraduate Researcher**, BITS Pilani, India (08/2018 - 05/2019)
  * Created and scaled a community detection, feature extraction and event prediction pipeline for a social network dataset of more than 64K nodes and 1.5M edges using Apache Spark, with a modularity of 0.91.
  * Implemented an ensemble learning algorithm combining the output of standard ML algorithms such as gradient boosting, random forest and SVM for event classification, with a test accuracy of 82%.

Education
======
* **University of Florida** (08/2022 - present)
  * Ph.D., Computer Science
  * M.Sc. (Hons.), Computer Science
  * Thesis: *Probabilistic Modelling of Driving Behaviour at a Traffic Intersection*
  * Advisors: Dr. Sanjay Ranka, Dr. Anand Rangarajan

* **BITS Pilani, India** (08/2016 - 06/2020)
  * B.E. (Hons.), Computer Science

Technical expertise
======
* **Languages:** Python, C, C++, GoLang, Java, JavaScript, Erlang
* **Machine learning:** PyTorch, CUDA, cuDNN, Apache Spark, Hadoop, YOLOv7, DeepSORT
* **Tools:** SUMO, CARLA, TensorBoard, Weights & Biases, Git, GitHub, Docker

Publications
======
{% include publication-list.html %}
