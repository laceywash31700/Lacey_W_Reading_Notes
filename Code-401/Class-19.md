# Class-19 Reading Notes

## AWS SQS vs SNS

> 1. ***What is the difference betweeen SQS and SNS?***
>Amazon Simple Queue Service (SQS) and Amazon Simple Notification Service (SNS) are both messaging 
services provided by Amazon Web Services (AWS), but they serve different purposes and have distinct 
characteristics: 

SQS:  SQS is a fully managed message queuing service that enables decoupling of components in a 
distributed application. It allows you to send, store, and receive messages between different software 
components without the need for those components to be concurrently available. Messages are placed in a 
queue and delivered to one or more consumers (receivers) in a reliable and highly scalable manner.

SNS: Is similar but it is set up one to one.SNS is a fully managed publish-subscribe (pub-sub) messaging 
service. It allows publishers to send messages to multiple subscribers (endpoints or consumers) using a 
topic-based system. Messages published to a topic are delivered to all subscribed endpoints 
asynchronously.
>
> 2. ***What are some use cases for both SNS and SQS?***
>SQS is designed for decoupling components and workloads. It is used when one component of a system needs to send a message or task to another component without them needing to be online simultaneously. Common use cases include:

Distributing tasks to worker nodes in a scalable processing system.
Buffering requests between web servers and backend services.
>

## AWS SNS and SQS

> 1. ***Describe how to use SQS and SNS in a “fanout” pattern.***
> Step 1: Set Up SNS Topic, Step 2: Set Up SQS Queues, Step 3: Subscribe Queues to the SNS Topic,
Step 4: Publish Messages, Step 5: Messages Distributed to SQS Queues, Step 6: Consumers Process Messages,
Step 7: Scaling and Monitoring
>
> 2. ***Explain how “push notifications” work, using SNS.***
>When you want to send a push notification, you publish a message to the SNS topic. This message can include the content of the notification, metadata, and any necessary information.
You can publish messages to SNS using the AWS SDK, AWS CLI, or other programming languages and tools.
>


## SQS and SNS Basics

> 1. ***How might a large scale, distributed application make use of a Queue system like SQS?***
>  SQS plays a crucial role in building scalable, fault-tolerant, and responsive distributed applications. It promotes loose coupling between components, enables asynchronous processing, and provides mechanisms for handling errors and scaling to meet the demands of large-scale systems.
>



## Things I want to know about
