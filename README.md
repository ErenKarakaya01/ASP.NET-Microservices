# Project Overview

This repository contains the source code and documentation for an extensive software development project focused on building a microservices-based application. The project covers various aspects of software development, including microservices architecture, Docker and Kubernetes deployment, database management, asynchronous messaging with RabbitMQ, and gRPC implementation. 

The project's contents are organized into sections, each corresponding to a specific aspect of the application's development. Below is an overlay of what you can expect to find in this repository:

## Introduction & Theory

In this section, we provide an overview of the project's approach, objectives, and the tools and technologies used. It introduces the concept of microservices and presents an overview of the microservices used in this project. It also outlines the solution and application architecture.

## Building the First Service

This section is dedicated to the initial microservice development. It covers the creation of the microservice's structure, data layer setup, including models and repositories, and the configuration of the database. It also addresses the creation of controllers and actions to handle HTTP requests.

## Docker & Kubernetes

Here, you'll find information on containerization with Docker and deployment with Kubernetes. The section reviews Docker, containerizes the first microservice, and explains the process of pushing container images to Docker Hub. Additionally, it offers an overview of Kubernetes architecture and demonstrates the deployment of a microservice on a Kubernetes cluster.

## Starting Our 2nd Service

The second microservice development begins in this section. It starts with scaffolding the service and adding controllers and actions. It discusses synchronous and asynchronous messaging, HTTP client integration, and deployment to Kubernetes. An API Gateway is also introduced.

## Starting with SQL Server

This part is dedicated to integrating SQL Server. It covers the setup of a Persistent Volume Claim and Kubernetes Secret. It explains the deployment of SQL Server to Kubernetes and demonstrates how to access SQL Server using Management Studio. The Platform Service is updated to use SQL Server.

## Multi-Resource API

This section dives into the development of a multi-resource API, focusing on the Commands Service. It reviews the endpoints, data layer models, repositories, DTOs, and AutoMapper profiles. Controller and actions for this service are also created.

## Message Bus & RabbitMQ

Here, the project's solution architecture is discussed, and RabbitMQ is introduced. It explains how to deploy RabbitMQ to Kubernetes to enable asynchronous messaging.

## Asynchronous Messaging

This section focuses on asynchronous messaging using RabbitMQ. It covers adding a message bus publisher to the Platform Service, testing the publisher, and establishing the groundwork for the Command Service. Event processing is discussed, and an event listener is added for testing locally. The services are then deployed to Kubernetes.

## gRPC

This final section provides an overview of gRPC, a high-performance, open-source framework for building remote procedure call (RPC) APIs. It includes configuration details for Kubernetes networking and demonstrates how to work with Protocol Buffers. A gRPC server is added to the Platform Service, a gRPC client to the Commands Service, and a database prep class for the Commands Service. The section concludes with local testing and deployment to Kubernetes.

