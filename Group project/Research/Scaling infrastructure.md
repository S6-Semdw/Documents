<img src="https://i.postimg.cc/pTKWxnFP/docker-security-1200x385.jpg" width="100%" height="300px"/>

# Main question: How do we create an infrastructure that can scale with the demand of the software?

# What is the best technique to make scalable software?

### Dot methods

- Literature study
- Interview

There is no single best technique to make scalable software, as the approach you should take will depend on the specific requirements and constrains of the project that is worked on. But still there are some key points when creating scaling software.

1. Design for scalability: When designing your software architecture, consider how it will need to scale as usage grows. This includes designing for high availability, fault tolerance, and load balancing.

2. Distributed architecture: A distributed architecture can help you scale your software horizontally, by adding more servers or nodes as needed. This can help you handle increased traffic or load, without overloading any single server.

3. Utilize cloud services: Cloud computing platforms like Amazon Web Services, Microsoft Azure, or Google Cloud Platform offer scalable infrastructure and services like load balancing, auto-scaling, and database scaling. Using these services can make it easier to scale your software without having to manage the underlying infrastructure yourself.

4. Containerizaition: Containerization allows you to package your application and its dependencies into a portable container, making it easier to deploy and scale across multiple environments. 

5. Microservices: Microservices architecture can help you break down your software into smaller, independently deployable services that can be scaled separately based on demand.

### Interview

For the interview I talked to an someone and asked him the same question as my sub research question. His name is Mark and I got to know him through the Docker discord server. He is a moderator so this means he knows some stuff about Docker etc. This is the answer I got to the question I asked:

> Certainly, there are several techniques that can help make software scalable. However, the best technique depends on the specific requirements of the software and the underlying infrastructure. Nonetheless, there are some general practices that can help in most cases. One of the most important techniques for making software scalable is to design the software with scalability in mind from the very beginning. This means taking into consideration factors such as load balancing, caching, and horizontal scaling when developing the architecture of the software. By doing this, you can ensure that the software is able to handle increased traffic and usage as it grows. Another important technique for making software scalable is to use distributed systems and microservices. By breaking the software down into smaller, independent services that can communicate with each other, you can achieve greater scalability and flexibility. Additionally, this approach can also help with fault tolerance, as individual services can fail without bringing down the entire system.

# What role do containerization and microservices architecture play in scaling infrastructure software?

### Dot methods

- Literature study
- Brainstorm
- Prototyping

Containerization and microservices architecture play important roles in scaling infrastructure software.

Containerization allows software to be packaged in a lightweight, portable, and standardized way, making it easier to deploy and scale across multiple environments. By using containers, developers can ensure that their software will run the same way on different platforms, and can quickly spin up new instances of their applications to handle increased demand.

Microservices architecture involves breaking down software into smaller, independently deployable services that can be scaled separately based on demand. Each microservice can be developed, deployed, and scaled independently, allowing developers to focus on specific features or functions of the application. This also allows for greater flexibility and resilience, as failures in one microservice do not necessarily affect the entire application.

Together, containerization and microservices architecture can help developers create highly scalable infrastructure software. By packaging software in containers and breaking it down into smaller services, developers can more easily deploy and scale their applications, while ensuring that each component of the application can be scaled independently based on demand.

## Brainstorm

In addition to Mark interviewing me, we also had a brainstorming session together on this subrvague. We talked together about the possibilities of containerization and microservices for scaling the software. We talked about Docker and all its capabilities. We also looked at the group project we are currently working on called Automated trading model and how Docker can be of good use here. A prototype came out of this which ensures that a microservice is in a docker container and can be used from there. This is very useful for the group project we are currently working on.

## Prototyping 

For the prototype I containerized a microservice so this can help the testing it and veryfing the concept. It also helps by reducing the risk because this identifies potential risks beforehand.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/MH6Kggjq/Scherm-afbeelding-2023-03-29-om-22-37-58.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/nhjc84Mj/Scherm-afbeelding-2023-03-29-om-22-39-27.png" width=500 height=250></td>
  </tr>
</table>

On the image above you can see a docker image is made from a microservice and is pushed to docker hub. Now it can be runned as a docker container and able to scale when needed.

# How can we optimize the performance of infrastructure software at scale?

### Dot methods

- Literature study

Optimizing software at scale can be complex but there are some techniques that can help with this:

1. Monitor performance: Regularly monitor the performance of the infrastructure can identify bottlenecks and areas for improvement. There are certains tools like application performance monitoring and log analysis to help pinpoint issues and optimizing code.

2. Distributed architecture: A distributed architecture can help you scale your infrastructure software horizontally, by adding more servers or nodes as needed. This can help handle increased traffic or load, without overloading any single server.

3. Caching: Caching frequently used data or queries can help reduce the load on the backend servers, improving the performance and scalability

4. Optimizing code: Optimize code for performance by using best practices. This can reduce the number of database queries and minimizing network latency.

These techniques can optimize the performance of the software at scale. It can also handle more traffic this way.

# How can we automate the deployment and management of infrastructure software at scale?

### Dot methods

- Literature study
- Brainstorm
- Prototyping

1. Containerization: Containerization can help automate the deployment and management of software applications at scale. By packaging applications and their dependencies into containers. This way you can ensure that they will run consistently across different environments and platforms, while allowing for easy scaling and deployment. This can be achieved with docker for example.

2. Kubernetes: Kubernetes can help automate the deployment, scaling, and management of containerized applications. These tools allow you to define and manage infrastructure as code, automate resource allocation, and ensure high availability and reliability.

3. CI/CD: CI/CD allows you to automate the entire software delivery process, from code changes to production deployment. This includes automated testing, build, and deployment, which can help ensure consistency and reliability of the infrastructure software.

## Brainstorm

In addition to the Docker discord server, there is also a Kubernetes discord server. This is also where I met someone I had a brainstorming session with. His name is Jean and lives in America. He himself already has a lot of experience with Kubernetes at the software company where he works, so I thought it would be a good plan to show the prototype that Milo created for the group. Jean was very satisfied and saw that we made a good step into the world of Kubernetes. He also told me that there are a lot of possibilities and advised me to read the documentation of Kubernetes because there is a lot of information and possibilities here. Furthermore, I could always reach him if we couldn't work it out as a group.

## Prototyping 

1. Kubernetes uses pods that can scale when needed. On the video below you can see 3 pods that are used and are able to scale when needed. Even when a pod is deleted it will make a new one automatically. [@Milo](https://github.com/Milofow) is a a group memeber from the group project I work on called Stockbrood. He made a very good prototype/POC for this.

https://user-images.githubusercontent.com/73555911/231696399-f423322d-51aa-4010-b949-ff2b0f4e2d75.mp4

# Conclusion


# Sources


