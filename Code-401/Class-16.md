# Class-16 Reading Notes

## AWS EC2

> 1. **_What is an EC2 Instance?_**
>    Amazon Elastic Compute Cloud (Amazon EC2) is a web service provided by Amazon Web Services (AWS) that  
>    allows users to rent virtual servers, known as instances, on-demand
>
> 2. **_Name 2 use cases for EC2._**
>    Scalability: EC2 instances can be easily scaled up or down based on demand. This elasticity allows you
>    to respond to varying workloads effectively, ensuring optimal performance and cost savings.
>    &
>    Data Storage: EC2 instances can be attached to different types of storage solutions, including Amazon
>    Elastic Block Store (EBS) for block storage and Amazon Elastic File System (EFS) for file storage or  
>    even mongodb.
>
> 3. **_Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com._**
>    it gives way more flexibility for scalability compared to other services and it offers customization >
>    in managing containerized applications. which are a thing and just learned that they compliment sockets

## EC2 For Humans

> 1. **_Where can we find EC2 on the AWS Console?_**
>    in the AWS Dashboard
>
> 2. **_Explain the general difference between T2 Micro and XL._**
>    the primary difference between T2 Micro and T2 XL instances lies in their CPU, memory, and networking capabilities. T2 Micro instances are designed for very lightweight workloads and low-traffic applications, while T2 XL instances provide more resources and are suitable for a broader range of applications with higher compute and memory demands.
>
> 3. **_Explain a “Compute Cycle” to a non-technical friend._**
>    Imagine you're baking cookies in your kitchen. Each step you take to bake a batch of cookies involves a series of actions. For example, you mix the ingredients, shape the dough into cookies, place them on a baking sheet, and then bake them in the oven. Each of these steps is like a "compute cycle" for your baking process.

In the world of computers, a "compute cycle" is similar. It's a basic action that a computer performs when it's doing some kind of work. Just like you follow steps to bake cookies, a computer follows a series of steps to do tasks like calculations, showing pictures on a screen, or running programs.

These "compute cycles" happen really quickly, just like when you're baking lots of cookies in a short time. Computers do many, many compute cycles in just a second, which allows them to do complex tasks and respond to your commands almost instantly.

So, a "compute cycle" is like a tiny step that a computer takes to get things done, and it happens really fast, just like the steps you take when baking cookies in your kitchen!

>

## Elastic Beanstalk

> 1. **_What is Elastic Beanstalk?_**
>    It simplifies the process of deploying, managing, and scaling web applications and services.
>
> 2. **_Describe the relationship between EC2 and Elastic Beanstalk._**
>    Elastic Beanstalk utilizes EC2 instances as part of its infrastructure. When you deploy an application
>    using Elastic Beanstalk, it provisions EC2 instances behind the scenes to run your application.
>
> 3. **_Name some benefits of using Elastic Beanstalk._**
>
> Elastic Beanstalk automatically handles environment provisioning, scaling, load balancing, and  
> resource management. This automation reduces the operational burden on developers.
> Beanstalk provides managed platform updates, including patching and upgrading of the underlying
> infrastructure components. This helps keep your application secure and up-to-date without manual
> intervention

## Things I want to know about
