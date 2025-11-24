# CST8916: Assignment 2

## Name: Kylath Mamman George

## Student Number: 041198835

## 1. Executive Summary

As organizations increasingly depend on low-latency interactions, event-driven processing, and scalable data architectures, it becomes important to understand where each cloud platform excels when choosing a suitable solution.This comparison evaluates five key service domains: REST APIs, GraphQL, WebSockets, data streaming, and streaming analytics. AWS delivers the most gobally available ecosystem, with strong capabilities in API delivery and high-volume streaming scenarios. Azure offers tight alignment with enterprise environments, hybrid deployments, and analytics tools that naturally integrate with Microsoft platforms. GCP differentiates itself through advanced data processing and analytics performance, leveraging Google’s global infrastructure.

## 2. Introduction

The purpose of this assignment is to compare the remote data and real-time application services offered by Azure, AWS and GCP. Between the 3 providers, AWS is the largest provider known for its range of services and global infrastructure which a lot of organizations depend on. Azure is notable for organizations that are invested in the Microsoft ecosystem and from our classes we have learned Azure is generally used in the government. Google Cloud is great for services working with data and analytics.

## 3. Service Comparison

### A. RESTful API Services

Azure uses Azure API management for managing RESTful API. This allows users to publish their API's including REST and allow for managing and monitoring them. Their pricing model is in a tier system that starts at a basic consumption/Developer tier all the way to premium tiers.

Amazon API Gateway is a fully managed service that makes it easy for developers or organizations to create, publish, maintain and monitor API's at any scale. Their pricing system for RESTful API's is paying for the API calls received and the amount of data transferred out.

Google Cloud Endpoints is a fully managed service helping developers create, deploy and manage API's for their applications. Cloud Endpoints takes care of tasks like API key management, access control, monitoring , and logging, allowing developers to focus on writing code. Their pricing system also depends on the number of API calls.

### B. GraphQL Services

Azure does not seem to have any native GraphQL services, it would be possible to use Azure API Management to host a GraphQL server. The pricing would be the same as above.

AWS has a fully managed GraphQL service called AWS AppSync with real time data synchronization. This service uses a pay as you go model with an option to provision a dedicated cache for a price as well.

Google Cloud can implement GraphQL using Apigee and their pricing model follows the pay-as-you-go model.

### C. WebSocket Services

Azure PubSub provides WebSocket subprotocols including MQTT which is what websockets use. The pricing is available in tiers from free, standard or premium and are differentiated by the number of concurrent connections, messages and maximum units allowed.

AWS API Gateway natively supports websockets for real-time applications. The pricing is determined by the messages send and received, metered in 32KB increments,  and the total number of connection minutes.

GCP does not seem to natively support websockets and must use Google run to host it through custom deployments. They have both instance based billing and request based billing.

### D. Data Streaming Services

For Data streaming, Azure Event Hubs provides a native data-streaming service in the cloud that can stream millions of events per second with low latency from any source to destination. They use a tiered system for pricing depending on throughput as well as added features such as geo-replication as you reach Premium and Dedicated Tiers.

Amazon uses Amazon Kinesis to collect, process and analyze real-time video and data streams. Their pricing system seems to be dependent on the amount of data read or written plus an hourly charge on lower tiers, while higher tiers only charge for data ingested.

Google uses Google Pub/Sub for data streaming. Their pricing system depends on the throughput and storage costs.

### E. Streaming Analytics

Azure Stream Analytics is a fully managed stream processing engine that is designed to analyze and process large volumes of data with low latency. Their pricing system depends on the streaming units used with tiered discounts, meaning the more streaming units used the lower the cost per unit.

AWS kinesis has sql based analytics, however I think this is being shut down. I couldn't really find a specifc service that AWS uses for analytics but I found Apache Flink based real time analytics.

Google uses Google Dataflow whihc provides unified stream and batch data processing. Their pricing system is based on the compute resources used to run pipelines paying for the Vcpu and memory consumption for the duration of a job. There are additional charges for persistent disk usage, streaming engine data processing etc.

## 4. Use Case Analysis

### Use Case 1

Azure for internal chat for Microsoft-based organizations:

It would be easier to integrate with the microsoft ecosystem and use Azure Pub/Sub to fit the ecosystem. It will have smooth integration with Microsoft AD/Entra for authentication, 365 and Teams.

### Use Case 2

Gaming Applications

Using AWS for gaming with realtime matchmaking and lobby systems with live score updates with their global network for low latency and DynamoDB for real-time updates.

## 5. Conclusion

All the three cloud providers provide support for remote data and real time applications, which each of them having advantages. For example, AWS offers a lot of services but also has native support for GraphQL, Azure is suited for enterprise environments with easy integration of Microsoft 365 and Teams, GCP has an advantage in analytics with BigQuery. The choice depends on what the workload requires.

## AI Use

AI was used for brainstorming ideas, finding links to certian information as some cloud providers websites aren't easily navigated to find certain information. It was also used to summarize and understand pricing for each cloud provider as they have some complicated pricing systems.