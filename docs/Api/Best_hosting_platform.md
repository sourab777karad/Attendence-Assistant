# Comparsion between AWS, Azure and Google Cloud

## Introduction

| Feature | AWS                       | Azure                                    | Google Cloud                                             |
| ------- | ------------------------- | ---------------------------------------- | -------------------------------------------------------- |
| Compute | AWS EC2                   | Azure container service                  | custom and predefined machine types,per-second invoicing |
| Storage | S3, EBS, and EFS          | Blob storage, file storage, disk storage | SQL-based                                                |
| Pricing | US$69/month 3.84TB of RAM | US$70/month 3.89TB of RAM                | US$52/month 3.75TB                                       |

# Service Integration

## AWS

Aws makes it simple for usersto combine services such as Amazon EC2, Amazon S3,Beans
talk and others

## Azure

Azure allows customers to effortlessly combine azure VM, Azure App Service, SQL databases and other services

## Google Cloud

Users can utilize GCP to combine services such as compute Engine, Cloud Storage, Cloud SQL and others

# Compute/Tools

## AWS

Elastic compute cloud(EC2) offers wide range of features including many instance, support for both Windows and linux and more

Amazon's container services has docker
, kubernetes, which automates server and cluster management

## Azure

Virtual Machines includes Linux, Windows server, OPerating system with better security and microsoft program integration

Azures uses Virtual machines scale sets of two container services: azure container service and container service

## Google Cloud

offers custom and predefined machine types,per-second invoicing, linux and windwos support

For
enterprises interested in deploying containers,Google offers the kubernetes Engine

# Storage

## AWS

Simple storage service S3, Elastic Block Store(EBS), and Elastic File System(EFS)

Realtional database service(RDS), DynamoDB NoSQL database, and Redshift data warehouse, etc.

## Azure

Blob storage, file storage, disk storage
SQL database,MYSQL database, and PostgreSQL database, etc.

## Google Cloud

SQL-based
The SQL-based cloud-sqland cloud spanner

# Pricing

## AWS

Basic instance costs around US$69(5,726.50 Indian Rupee) per month and the largest instance around US$3.97/hour(329.48 Indian Rupee) with two virtual CPUs and 8 gigabytes of RAM and largets instance with 3.84TB of RAM and 12vcpus

It provides spot instances, reserved instances, and dedicated hosts

## Azure

Here it is done in
mintues basis the smallestinstance the largets instance cost around US$70/month and US$6.79/hour with two cpus and 8 GB of RAM and the largest instance with 3.89TB of RAM and 128vcpus
It provides developers discount and hybrid benefits

## Google Cloud

it provides basic
instance around
US$52/month andthe largest instance around US$5.32/Hour with two virtual CPUs and 8 gigabytes of RAM and the largest instance with 3.75TB of RAM and 160vcpus
it gives you sustained use discounts and preemptible discount

# Conclusion

AWS turned out to be more
complete
and more flexible.
AWS is known for its reliability and robustness

Azure is more user-friendly.
Azure is particularly strong in areas of AI and machine learning

GCP is more easy to start with.
GCP is a great choice for those who want a more open and flexible platform

#

# AWS

## Differences between EC2 vs LAMBDA

### EC2

Elatic Compute Cloud (EC2): It is a web service that provides resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. It provides the following features:

- Virtual computing environments, known as instances
- Has flexible options for CPU, memory, storage, and networking
- Compute, Memory , GPU everything comes in a tiered pricing model
- can be picked any model according to the requirement

### LAMBDA

Lambda is a "serverless" computing service provided by AWS. It is a compute service that runs code in response to events and automatically manages the computing resources required by that code. It provides the following features:

- Low flexibility
- Low maintenance

| Feature       | EC2                                                                | Lambda                                                                          |
| ------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| Cost          | Renting machines(with number of machine we have) according to hour | We pay by number of invokations, we pay by number of memory, we pay by duration |
| Flexibility   | HIGH                                                               | LOW                                                                             |
| Integration\* | No easy integrations available                                     | API/GW,SNS, SQS                                                                 |
| Speed         | HIGH                                                               | VERY HIGH                                                                       |
|               |                                                                    |                                                                                 |

## AWS Storage

### Choosing the Best Storage Facility:

- If you need scalable and durable object storage, choose Amazon S3.
- For block storage volumes for EC2 instances, consider Amazon EBS.
- If you require shared file storage across multiple EC2 instances, go \* for Amazon EFS.
- For managed relational databases, choose Amazon RDS.
- If you need a fully managed NoSQL database, consider Amazon DynamoDB.

# Google Cloud

To create a cloud-based service for maintaining appointments via slots for personal meetings using Google Cloud Platform (GCP), you can leverage various GCP services. Below are the key requirements and services you may consider for your project:

Compute Engine or App Engine:
Choose either Compute Engine or App Engine to host your web application. Compute Engine provides more control over the infrastructure, while App Engine is a fully managed platform that automatically scales based on demand.

Google Cloud SQL:
Use Cloud SQL to store and manage your application's relational database. You can use it to store user data, appointment details, and other relevant information.

Firebase Authentication:
Implement Firebase Authentication to manage user authentication securely. This will allow users to sign in using their Google accounts or other authentication providers.
Google Cloud Storage:

Utilize Google Cloud Storage to store static assets, such as images, stylesheets, and client-side scripts for your web application.

Cloud Endpoints or API Gateway:
Create RESTful APIs to handle communication between your frontend and backend. Cloud Endpoints or API Gateway can be used to manage and secure your APIs.

Google Cloud Pub/Sub:
Use Cloud Pub/Sub for handling real-time updates and notifications. You can notify users about upcoming appointments or changes in their schedules.

Cloud Scheduler or Cloud Tasks:
Schedule tasks or events related to appointment management. Cloud Scheduler or Cloud Tasks can be used to trigger events like appointment reminders or cleanup tasks.

Firebase Realtime Database or Firestore:
If you need a NoSQL database for real-time synchronization, consider using Firebase Realtime Database or Firestore. This can be useful for updating appointment statuses in real-time.

Cloud Identity and Access Management (IAM):
Implement IAM policies to control access to your resources. Define roles and permissions to ensure that only authorized users can modify or access sensitive information.

# References

- [Reference 1](https://youtu.be/Vnk0p-63mHQ?si=41GTuAueqaBnb3mQ)
- [Reference 2](https://youtu.be/4AVQchL9tTo?si=sCzYjf_d3dyUxRUM)
- [Reference 3](https://youtu.be/-L6g9J9_zB8?si=vkoC3Ufk_2TgfOE-)
- [Reference 4](https://ieeexplore.ieee.org/document/9337100)
