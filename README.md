{% include feature_row %}

<!-- markdownlint-disable-file first-line-heading -->

## What are gHacks?

gHacks are a set of challenge based hackathons that can be hosted in-person or virtually via Google Meet.

Attendees work in teams of 3 to 5 people to solve a series of technical challenges for a given technology or solution scenario. Challenges describe high-level tasks and goals to be accomplished. gHacks are **NOT** step-by-step labs.

gHacks are designed to be a collaborative learning experience.  Attendees "learn from" and "share with" each other. Without giving step-by-step instructions for the challenges, attendees have to work hard to solve the challenges together as a team.  This results in greater knowledge retention for the attendees.

Teams are not left on their own to solve the challenges. Coaches work with each team to provide guidance for, but not answers to, the challenges.  The coaches may also provide lectures and/or demos to introduce concepts needed to solve the challenges, as well as review challenge solutions throughout the event.

## The gHacks Collection

### Data & AI

- [Introduction to GenAI](./hacks/genai-intro/README.md)
  > **UPDATED FOR GEMINI** We will build a system to catalog scientific papers. Whenever new papers are uploaded to Cloud Storage a Cloud Function will be triggered and use Vertex AI Foundation Model LLM to extract the title and summarize the paper. We'll store this data in BigQuery and use an LLM directly from BigQuery to classify the papers into distinct categories and then implement semantic search using text embeddings and finally we'll use Vector Search as a scalable solution.
- [MLOps on GCP](./hacks/mlops-on-gcp/README.md)
  > We will be implementing the full lifecycle of an ML project. We'll provide you with a sample code base and you'll work on automating continuous integration (CI), continuous delivery (CD), and continuous training (CT) for a machine learning (ML) system.
- [Crash Course in AI: Formula E Edition](./hacks/genai-fe/README.md)
  > We'll analyze multimodal data to detect crashes and find the drivers that were involved by using Gemini.
- [Modernizing Classic Data Warehousing with BigQuery](./hacks/bq-dwh/README.md)
  > In this hack we'll implement a classic data warehouse using modern tools, such as Cloud Storage, BigQuery, Dataform and Looker Studio. We'll start with a modified version of the well known AdventureWorks OLTP database, and we'll implement a dimensional model to report on business questions using a BI visualization tool.
- [Introduction to Conversational Agents](./hacks/conv-agents-intro/README.md)
  > This hack will be an introduction to the world of Customer Engagement modernization. We will teach you how to build a robust Conversational Agent using Google Cloud’s Customer Engagement Suite.
- [Real-time analytics with Change Data Capture (CDC)](./hacks/realtime-analytics/README.md)
  > We will be going through replicating and processing operational data from an Oracle database into Google Cloud in real time. You'll also figure out how to forecast future demand, and how to visualize this forecast data as it arrives.
- [Hack to the Future: Data Track](./hacks/httf-data/README.md)
  > In this hack we'll help the fictitious Cymbal Shops e-commerce platform to modernize their tech stack, primarily focusing on the migration of the legacy application MySQL database to Cloud Spanner. From that point we'll create BigQuery analytics datasets to handle both historical and live data using federation, use advanced generative AI to enhance the existing dataset with descriptions and images, and finally implement semantic search on this dataset.

### Infrastructure

- [Security with reCAPTCHA and Cloud Armor](./hacks/recaptcha-cloudarmor-security/README.md)
  > We will be setting up gHacks+, the hottest new streaming site. We will configure an HTTP Load Balancer in front of the site and then you'll learn how to set up a reCAPTCHA session token site key and embed it the site. You will also learn how to set up redirection to reCAPTCHA Enterprise manual challenge. We will then configure a Cloud Armor bot management policy to showcase how bot detection can protect gHacks+ from malicious bot traffic.
- [Infrastructure as Code with Terraform](./hacks/iac-with-tf/README.md)
  > This gHack is intended as an introduction to provisioning GCP resources using Terraform. We'll start with the basics of Infrastructure as Code (IaC) and help you automate the process of infrastructure provisioning.

### Application Development

- [Intro to Google Kubernetes Engine](./hacks/intro-to-gke/README.md)
  > We will experience what a cloud developer needs to go through to successfully deploy an application to Google Kubernetes Engine. You will learn how to containerize a monolithic application; create a cluster; deploy, run and scale the application and then update the application and rollout the new version with zero downtime.
- [Modernizing the Monolith: Containerizing and Deploying to Kubernetes](./hacks/modernizing-monoliths/README.md)
  > Learn Docker and GKE with a web application that you can play! You will compose your own Dockerfile to containerize an existing web application and get practice in creating a cluster, creating node pools, and running deployments and services.
- [Ready, Steady, Cloud Run!](./hacks/cloud-run/README.md)
  > We'll be using Cloud Run to quickly configure, deploy and troubleshoot a web service. During the process we'll introduce different ways to store data for the web service and learn about how to discover and fix issues.
- [GenAI App Development with Genkit](./hacks/genai-genkit/README.md)
  > Learn how to create and deploy a GenAI application with Google Cloud and Firebase Genkit.
- [Monitor GenAI apps with Firebase Genkit](./hacks/genai-monitoring/README.md)
  > We will be mastering operating Large Language Model applications using Firebase Genkit, and Genkit Monitoring by stepping into the role of Site Reliability Engineers for a fictional GenAI app. We will dive into troubleshooting live issues, fixing issues, and optimizing performance to ensure our GenAI app runs flawlessly.
- [Practical SRE](./hacks/practical-sre/README.md)
  > In this gHack, you'll step into the role of SREs and Product Owners for a cutting-edge app. Your mission is to ensure that this app delivers a smooth, reliable, and responsive experience for its users.

### Industry Solutions

- [Gaming on Google Cloud](./hacks/gaming-on-gcp/README.md)
  > Learn how to deploy and manage game servers using Agones. Experience how Open Match integrates with Agones to assign players to game servers and protects servers with players from premature scale down operations.

### SAP

- [Agentic AI and SAP](./hacks/agentic-ai-and-sap/README.md)
  > This hackathon challenges participants to build intelligent applications by unifying SAP and other enterprise data in BigQuery. Participants will then use Google's no-code and advanced agent development tools to create conversational AI and automate complex business processes, such as creating purchase requisitions directly within SAP.

### Stay tuned for more

We've got more hacks in development and feel free to suggest new ones...

## License

This repository is licensed under Apache2 license. More info can be found [here](./LICENSE).
