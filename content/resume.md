---
title: "Resume"
date: 2021-02-13T00:39:47-08:00
draft: false
---
## tl;dr
I'm a highly adaptable and versatile site reliability engineer with a wide variety of experiences across technical environments, dedicated to making development and operations as painless as possible. I have both a strong systems and software engineering background, having designed CI/CD pipelines, wrangled Kubernetes clusters, ran multiple 100+ node distributed computing clusters, and turned fragile, opaque, automation into scalable, resilient, transparent, services throughout my career. I'm a whole-systems thinker, believe that reliability is everyone's responsibility, and know that empathy and moral decision making are key engineering skills.

## Experience

As I mentioned in my about, I was most recently a Site Reliability Engineer at Box, from February 2022 to September 2023. Some high-level highlights of my time there was creating and piloting formalized engagement contracts between tenants and platform owners for two different teams (resulting in a ~50%-~30% reduction in tenant-generated operational work and a ~35%-~55% reduction in time to resolution for said work), being the engineering lead & project manager for the evaluation of & migration to Temporal Cloud from self-managed Temporal, and being the architect & project lead for a custom Box-integrated runbook automation platform, designed to reduce mean time to diagnosis by providing a system of diagnostic checks defined in a YAML or JSON workflow spec that centralized multiple sources of service health data (such as metrics, distributed traces, logs, cloud provider service status, & Kubernetes workload status) into a single pane of diagnostic glass, implemented in Go with UI prototypes in TypeScript and SvelteKit, backed by GCP CloudSQL and PubSub, instrumented with Prometheus, and running on GKE.

Before Box, I was a DevOps Engineer at Jama Software, the leader in requirements management software, from Dec 2020 to the tail end of Feb 2022, part of an Agile team committed to code ownership from development through deployment, acting as ambassadors of holistic DevOps to the company. There, I designed & built microservice-based infrastructure automation service for internal customers, increasing team's clock speed and maintainability of internal tools; further automated release process, resulting in a >75% reduction of team's manual release labor; led cross-team tooling research and evaluation for Kubernetes migration; was a key contributor to the design and implementation of a new CI/CD pipeline, and was one of many hands involved in our move to Kubernetes, on premise, in the cloud, and as a dev environment, amongst many other things. I left to work at Box.

I was formerly the lead (and sole!) DevOps & support engineer and system administrator for [ChamberDS](http://www.chamberds.com) in Portland, OR, from Feb 2020 to Dec 2020, a SaaS mobile app incubator driven to empower clients to truly add value and make an impact in someone else's life. I was building out the infrastructure and support side of the business, automating, architecting, rearchitecting, and implementing a wide range of solutions. Specifically, I have was the infrastructure architect for a new client, building out a highly scalable, continuously integrated, enterprise-grade architecture to serve both web and mobile clients, with an autoscaling API cluster; automating existing support solutions for all of our current clients to greatly reduce MTTR and increase client communication; and re-architecting existing infrastructure to better meet an world-class, enterprise standard, in addition to the day-to-day support and infrastructure operations of the company. I left to work at Jama.

From Jan 2019 to Jun 2019 I was an Associate Support Engineer at [Chrome River Technologies](https://www.chromeriver.com) in Los Angeles, CA, an accounts payable SaaS company valued at over $1 billion (a unicorn). At Chrome River, I first supported higher-education clients using the EXPENSE product, and enabled excellent customer experience by applying end-to-end product knowledge to customer solutions. I was the SME for mobile apps and email flows. Later I was selected for movement to INVOICE product, a high case-load, more specialized area, where I was once again the SME for emails. During my time at Chrome River I reduced churn by 10% for higher education clients by meeting with them once per investigatory case to keep them informed of outcomes and ask directly for their feedback about what my team could be doing,  automated email batch troubleshooting via SQL to reduce MTTR by 50% for 15% of batch cases, increased team effectiveness and cohesiveness via interteam leadership, and was a month-to-month leader in customer satisfaction surveys. I was laid off, along with ~15% of other employees, from Chrome River due to a reduction in force directed by new ownership.

From May 2018 to Jan 2019, and from Aug 2019 to Dec 2019 I was a freelance Solutions Specialist, working first in the Los Angeles, CA area and later in Portland, OR. I served small-and-medium business clients, and clients adjacent to academia, meeting their needs in UNIX-like issues. I wound down to work first at Chrome River, and then at ChamberDS.

From Aug 2016 to May 2018 I was a Technical Support Analyst, Lead, at Occidental College Information Technology Services in Los Angeles, CA. I was the team lead & technical support analyst, and partial systems administrator for day-to-day operations of a 3000+ user higher education environment, providing front-line and deep technical support to foster both the fulfillment of individual aspirations and a deeply rooted commitment to the public good. I architected a digital signage server cluster to enhance community CX; increased institutional knowledge by providing training, guidance, mentorship and documentation for macOS and Linux desktop support to coworkers and supervisors; consulted on support best practices and pain points to decrease MTTR and increase support effectiveness; decreased MTTR by 25% via bash & python automation; and provided world class, VIP support for the Office of the Dean of the College.

## Skills

- __Programming/Scripting Languages:__ Python (FastAPI, Flask, Celery, etc.), Go (Echo, Watermill, GORM, etc.), JavaScript/TypeScript (Node.js, Deno, SvelteKit, React.js, etc.), Bash, HTML, CSS, SQL, some Rust (PyO3), some Java, some Groovy

- __Databases:__ MySQL, PostgreSQL, MongoDB, ElasticSearch, Redis, BigTable, BigQuery, etcd, some Neo4j

- __Messaging & Streaming:__ Apache Kafka, Apache Storm, GCP PubSub, Redis

- __Linux:__ Debian, Ubuntu, CentOS, RHEL, Alpine, etc.

- __Infrastructure as Code:__ Terraform, Terragrunt, CDKTF, Pulumi, Ansible, AWS CloudFormation

- __Configuration as Code:__ Packer, Puppet, Ansible, cdk8s, Helm

- __Container Orchestration:__ Docker, ECS, Kubernetes, GKE, EKS, k3s, Istio, Traefik, cdk8s, Helm, Kustomize

- __CI/CD:__ Drone CI, AWS CodeBuild, TeamCity, Jenkins, GitHub Actions, FluxCD, etc.

- __Version Control:__ Git, GitHub

- __REST APIs:__ Design & implementation, OpenAPI/Swagger, Swagger UI, Swagger/OpenAPI Codegen

- __Observability, Monitoring, & Logging:__ Splunk, Wavefront, Sensu Go, Prometheus, Datadog, New Relic, AWS CloudWatch, etc.

- __AWS__: ECS, EC2, ELB, S3, RDS, AuroraDB, EKS, CloudWatch, CloudFront, CodeBuild, etc.

- __GCP__: GKE, GCE, GCS, Cloud Load Balancing, CloudSQL, PubSub, BigTable, BigQuery, Dataproc, Dataflow, etc.

- __Workflow Orchestration:__ Temporal, Apache Airflow

- __Web Servers:__ Nginx, Apache, HAProxy

- __Other:__ SDLC, Process re-engineering, SRE/DevOps strategy, Agile (kanban, scrum, Jira).

## Education

I have an A.B. (_artium baccalaureus_, Bachelor's degree) in Philosophy from Occidental College, in Los Angeles, CA. I worked mainly in philosophy of language, semantics, metaphilosophy, formal logic, and moral psychology. This strong background in rigorous analytical thinking, combined with Computer Science coursework (Oxy only recently created a CompSci major) and my own technical background helped me succeed as a software engineer.
