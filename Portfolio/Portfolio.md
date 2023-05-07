# Portfolio S6 Sem de Wilde

## Introduction

This document is created to help the reader easily find the products i made for this semester. The reading guide is written for my personal portfolio and to show all the proof for my learning outcomes. There are 9 outcomes in total and during this semester i will get proof to get at least a proficient for every learning outcome. I will collect this evidence in a group and personal project.

### Group project: Stockbrood

The group project will be made in a group of 5 students. The product owner is a trader and wants a way to automate his trading strategies. The project can be found [here](https://github.com/S-A-RB05).

### Individual project: Twitter clone

The individual project is a twitter clone. This means i will be working with users and tweets that can be made. I will be using microservices en messaging in this project. The tech stack will be react and springboot. The project can be found [here](https://github.com/orgs/S6-Semdw).


# Learning outcomes
Scale for every learning outcomes: undefined, orienting, beginning, proficient, advanced.

## Learning outcome 1 - Future-oriented Organization
You develop and deploy enterprise software, both individually and as a team, that fits the current question and needs of your stakeholders. Your final solution is designed with the possibility for future further development. 

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Proficient |

#### Enterprise software document

- [Tech stack](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/General/Techstack.md)

## Learning Outcome 2 - Investigative Problem-Solving
You deliver professional products according to planning, which is the result of solving problems in a structured and methodical approach. You demonstrate a critical view towards your own and other people’s work. 

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | Beginning |

#### User stories

- [Personal project stories](https://github.com/S6-Semdw/Documents/blob/main/Individual%20project/General/User%20stories.md)

- [Group project stories](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/General/User%20stories.md)

#### Research

- [Personal research document](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/Research/Scaling%20infrastructure.md)

- [Group research document](www.google.com)


## Learning Outcome 3 - Personal Leadership
You acquire skills required for your future career. You are aware of multiple career paths and can reflect which ones fit best, considering your (potential) skills and ambitions. You are aware of developments in software engineering and can signal trends. 

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | Proficient |

#### Future carreer document

- [Future carreer research document](https://github.com/S6-Semdw/Documents/blob/main/Research/Future%20career.md)


## Learning Outcome 4 - Targeted Interaction
You use appropriate communication considering your role in a team, your audience and the medium to convey your message and results of your software development process.

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | Beginning |

#### Standups

As a group we had some good standups. On the images you can see the standups where the semestercoach joined the standups to see how we performed them. We got some great and positive feedback on them so that's why it's good proof for this learning outcome! 

<table>
  <tr>
    <td><img src="https://i.postimg.cc/0yQTJVPr/Scherm-afbeelding-2023-03-29-om-21-53-35.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/VvkRHH7C/Scherm-afbeelding-2023-03-29-om-21-54-04.png" width=500 height=250></td>
  </tr>
</table>


#### Presentation

This is a link to all the presentations we did in the group project. If you click on a certain powerpoint you are able to download it local on your pc.

- [Group presentations](https://github.com/S6-Semdw/Documents/tree/main/Group%20project/Powerpoints)


#### Release notes

- [Release notes sprint 1](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/General/Release%20notes%20sprint%201.md)
- [Release notes sprint 2](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/General/Release%20notes%20sprint%202.md)


#### User stories

- [Personal project stories](https://github.com/S6-Semdw/Documents/blob/main/Individual%20project/General/User%20stories.md)

- [Group project stories](https://github.com/S6-Semdw/Documents/blob/main/Group%20project/General/User%20stories.md)


## Learning Outcome 5 - Scalable Architectures
Besides functionality, you develop the architecture of enterprise software based on quality attributes. You especially consider attributes most relevant to enterprise contexts with high volume data and events. You design your architecture with future adaptation in mind. Your development environment supports this by being able to independently deploy and monitor the running parts of your application. 

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | --- |

#### C1 model twitter

<img src="https://i.postimg.cc/C5M2MnyF/Scherm-afbeelding-2023-04-05-om-12-11-57.png" width=550 height=450>

#### C2 model twitter

<img src="https://i.postimg.cc/6qShs8tb/Scherm-afbeelding-2023-04-05-om-13-30-16.png" width=550 height=450>

#### Kubernetes scaling pods

When a pod is deleted kubernetes automatically adds another pod in the cluster. So i makes sure there is always a pod running that can be used.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/VLFgvbnv/Scherm-afbeelding-2023-04-11-om-17-42-49.png" width=500 height=250></td>
  </tr>
</table>

#### Discovery service

I made a discovery service for the API gateway to discover. As you can see the services are added as clients

<table>
  <tr>
    <td><img src="https://i.postimg.cc/PJjCcKkS/Scherm-afbeelding-2023-04-22-om-22-30-36.png" width=500 height=250></td>
  </tr>
</table>

#### API gateway

On the images below you can see that the API gateway is made and works. I used a yml file to configure it and tested with Postman.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/7YP625PJ/Scherm-afbeelding-2023-04-23-om-00-20-54.png" width=500 height=250></td>
     <td><img src="https://i.postimg.cc/c1h10d7x/Scherm-afbeelding-2023-04-23-om-00-20-17.png" width=500 height=250></td>
  </tr>
</table>



## Learning Outcome 6 - Development and Operations (DevOps)
You set up environments and tools which support your chosen software development process. You provide governance for all stakeholders’ goals. You aim for as much automation as possible, to enable short release times and high software quality.

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | --- |

#### Docker 

On the images below you can see that a docker image is made. This is done automatically with GitHub actions and a Dockerfile ofcourse. On the right image you can that the actual image is pushed on docker hub.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/MH6Kggjq/Scherm-afbeelding-2023-03-29-om-22-37-58.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/nhjc84Mj/Scherm-afbeelding-2023-03-29-om-22-39-27.png" width=500 height=250></td>
  </tr>
</table>


#### Kubernetes

On the first 2 images below you can see that I managed to make a Kubernetes cluster with in this case a pod for the twitteruserservice I made. The docker image I made earlier is actually in the pod so with this Kubernetes can later scale it when needed. On the second 2 images below that there is more proof that shows the information about the pod that is made in the cluster. This is straight from the terminal.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/pV4k3HxV/Scherm-afbeelding-2023-04-10-om-23-17-40.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/VLFgvbnv/Scherm-afbeelding-2023-04-11-om-17-42-49.png" width=500 height=250></td>
  </tr>
  <tr>
    <td><img src="https://i.postimg.cc/90L45Vwm/Scherm-afbeelding-2023-04-10-om-23-31-43.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/mgvPGmkH/Scherm-afbeelding-2023-04-10-om-23-32-00.png" width=500 height=250></td>
  </tr>
</table>

## Learning Outcome 7 - Cloud Services
You can explain what a cloud platform provider is and can deploy (parts of) your application to a cloud platform. You integrate cloud services (for example: Serverless computing, cloud storage, container management) into your enterprise application, and can explain the added value of these cloud services for your application.

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | --- |

#### RabbitMQ 

On the images below you can see that I made a small poc with rabbitMQ. This can also be used for the group project

<table>
  <tr>
    <td><img src="https://i.postimg.cc/zXRrpBfJ/Scherm-afbeelding-2023-04-12-om-00-05-26.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/TwGVNpxB/Scherm-afbeelding-2023-04-12-om-00-05-54.png" width=500 height=250></td>
  </tr>
</table>

#### Docker hub 

On the images below you can see that I made a small poc with rabbitMQ. This can also be used for the group project

<table>
  <tr>
    <td><img src="https://i.postimg.cc/bY1CJ95g/Scherm-afbeelding-2023-04-19-om-09-47-50.png" height=250></td>
  </tr>
</table>


#### Database online

I also managed to put a mysql database online via db4free.net. 

<table>
  <tr>
    <td><img src="https://i.postimg.cc/1tQFYwKR/Scherm-afbeelding-2023-04-18-om-13-37-30.png" height=250></td>
  </tr>
</table>

#### Azure deployment

----

## Learning Outcome 8 - Security by Design
You investigate how to minimize security risks for your application, and you incorporate best practices in your whole software development process. 

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | --- |

#### Authentication

In the user service I made sure that a new user can register himself with this service. When te user is created he is also able to autheticate. Both of the request give the JWT token back so that I can verify that it's working. The proof is on the images below.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/4Nvm562M/Scherm-afbeelding-2023-04-04-om-15-12-18.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/x8LpqfyX/Scherm-afbeelding-2023-04-04-om-15-53-21.png" width=500 height=250></td>
  </tr>
</table>

#### Password hashing

When the user is created he will be saved in the MYSQL database as you can see on the image below. The password is hashed so that only the user knows it so this is very secure.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/66P3t9y9/Scherm-afbeelding-2023-04-04-om-15-16-27.png" width=500 height=250></td>
  </tr>
</table>


#### Roles

For the security by design I looked trough the canvas module. A good way to achieve this learning outcome would be to add roles so that is what i did. 

<table>
  <tr>
    <td><img src="https://i.postimg.cc/y69ZrDtb/Scherm-afbeelding-2023-05-08-om-00-22-33.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/XYNBJQJR/Scherm-afbeelding-2023-05-08-om-00-23-25.png" width=500 height=250></td>
  </tr>
</table>

#### Encrypted secrets

I also added encrypted secrets in my repository for my dockerfile. This means that no one can see my docker username and password but my dockerfile still operates with them. So this is a safe way to still use the credentials that i need to run the file. I also got this from the security and design module on canvas.

<table>
  <tr>
    <td><img src="https://i.postimg.cc/50JV4k9v/Scherm-afbeelding-2023-05-08-om-00-32-20.png" width=500 height=250></td>
  </tr>
</table>



## Learning Outcome 9 – Distributed Data
You are aware of specific data requirements for enterprise systems. You apply best practices for distributed data during your whole development process, both for non-functional and functional requirements. You especially take legal and ethical issues into consideration.

### Score
| Id | Description | Level |
|---|---|---|
| 1.1 | Sprint 1 | Orienting |
| 1.2 | Sprint 2 | --- |

#### Database for every microservice

<table>
  <tr>
    <td><img src="https://i.postimg.cc/ZqfJ67Nn/Scherm-afbeelding-2023-04-17-om-13-19-21.png" width=500 height=250></td>
    <td><img src="https://i.postimg.cc/PrmhSrDB/Scherm-afbeelding-2023-04-17-om-13-19-10.png" width=500 height=250></td>
  </tr>
</table>

#### Distributed data issues (independent database)

Distributed data issues can arise when multiple independent databases are used in an application, which can lead to problems with data consistency and integrity. Some common issues that can occur with independent databases include:

- Data synchronization: Keeping data synchronized across multiple databases can be challenging, especially when different databases are being updated simultaneously. If data is not synchronized correctly, it can result in data inconsistencies and integrity problems. To address this challenge, different synchronization methods can be used. One approach is to use a master-slave replication model, where updates are made to a master database and then propagated to one or more slave databases. This approach can help ensure that all databases have consistent data, but can result in performance issues if the replication process is slow.

- Data fragmentation: Data fragmentation can occur when data is split across multiple databases, making it difficult to access and analyze. It can also lead to data duplication and inconsistencies. Data fragmentation can be addressed by different techniques. One approach is to use data virtualization, where a single view of the data is presented, hiding the complexity of the underlying data sources. Another approach is to use data integration tools that can bring fragmented data together into a unified view

- Security and access control: Different databases may have different security and access control policies, which can make it difficult to manage user access and ensure data security across all databases. There are different approaches to securing independent databases. One approach is to use encryption techniques to protect data at rest and in transit. This can be done using techniques such as database-level encryption, file-level encryption, or column-level encryption. Another approach is to use access controls to limit who can access, modify, or delete data. This can be done using techniques such as role-based access control, attribute-based access control, or mandatory access control.

- Scalability: Scaling a distributed database can be more complex than scaling a single database, as it requires ensuring that data is distributed evenly across all nodes and that performance remains consistent. There are different approaches to achieving scalability in independent databases. One approach is to use horizontal scaling, where additional databases or nodes are added to distribute the workload. This can be done using techniques such as sharding, where data is partitioned across multiple databases, or replication, where data is copied to multiple nodes for redundancy and load balancing. Another approach is to use vertical scaling, where the resources of a single database or node are increased to handle higher workloads. This can be done by adding more processing power, memory, or storage to the system.

Overall, distributed data issues can make it difficult to maintain data consistency, integrity, and security across an application. It requires careful design and management to ensure that data is synchronized correctly and that the system can scale and maintain performance under load.
