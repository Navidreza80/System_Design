# System-Design
In this repository I share my system design journey with you as a full-stack javascript web developer, with toturials, youtube videos, resources, roadmap and everyhting

# Roadmap
30-Day System Design Master Plan
A structured 30-day curriculum to master system design fundamentals, distributed systems, microservices architecture, and production-ready systems.

# 📅 Week 1 - Foundations
## Days 1-2: System Design Basics
Learn: Scalability, Latency vs Throughput, High Availability, Fault Tolerance
### Videos:
• What's Scalibility? https://youtu.be/EWS_CIxttVw?si=OqD-C38w8v3BFcuu

• Horizantal vs Vertical Scaling https://youtu.be/xpDnVSmNFX0?si=EQEquHarfcJCojI3

• What's Load Balancing? https://youtu.be/K0Ta65OqQkY?si=KCwjezRDxDqZ1mgE

• Throughput vs Latancy:

• https://youtu.be/ryzF1vO7N4w?si=tvV2lGCQXU1KyT61

• https://youtu.be/84ZLMbHefJI?si=CXgrMhxsjZm5J4Qi

• Highly Available Patterns https://youtu.be/LdvduBxZRLs?si=4UJSqpmlogwlgloA

• Fault Tolerant System https://youtu.be/3Lis4w4_bBc?si=vs1XJkWv-cPwXfZ0

• System Design Interview Template https://youtu.be/OWVaX_cBrh8?si=5qQ7dDS4gMX-xQmq

Project: Design Basic Web App Architecture with load balancing, database, and caching

Output: Architecture diagram in Excalidraw/Lucidchart/Figma
<img width="1362" height="532" alt="image" src="https://github.com/user-attachments/assets/2ac0e711-f4b8-42ab-ab78-5b6a745b73f4" />
*Simple Blog App Tolerant With My Tech Stack as Full-Stack Js Developer, You Can Tolerate It With Yours*

FigmaJam Link: https://www.figma.com/board/nozVlcKsIzgh0Q2Q65TrTG/Untitled?node-id=0-1&p=f&t=t96S0qW9S7Weeryy-0

## Days 3-4: Database Systems
Learn: SQL vs NoSQL, Indexing, Sharding, Replication

• If you have no clue what SQL (query language) is, I recommend you to watch this toturial: https://youtu.be/7S_tz1z_5bA?si=1QiLguPJPwXQqqNb

• SQL vs NoSQL https://youtu.be/t0GlGbtMTio?si=qEkJRcoERPhSRLGt

• Replication & sharding explained https://youtu.be/jLEp1XI_L6Q?si=SsQqXD-FBqU8mnB2

Project: Model an E-commerce Database in both SQL and NoSQL

Output: GitHub repo with schema diagrams

Chekout my repo at: https://github.com/Navidreza80/ECommerce_Store_DB_Model
<img width="1002" height="819" alt="image" src="https://github.com/user-attachments/assets/809cb480-39fa-4ec1-a03d-d023f487edf5" />
*ECommerce Store DB Model Repository*

## Day 5: Caching Strategies
Learn: Redis, CDNs, cache eviction policies

• Redis crash course https://youtu.be/jgpVdJB2sKQ?si=25vF-xW2OPqDRq12

• What's CDN? https://youtu.be/RI9np1LWzqw?si=ehB_pPHWtYudkCli

• Cache eviction policies https://youtu.be/ZqI7i3v4baQ

• Project: Build a Node.js API with Redis cache

Output: Performance benchmarks comparing cached vs non-cached

<img width="1166" height="469" alt="image" src="https://github.com/user-attachments/assets/091866ed-92e2-4f4c-8b39-54de8f89e827" />
*Express.js backend with mongoDB, cached vs non-cached api calls leveraging redis*

## Day 6: Load Balancing & Networking
Learn: DNS, L4/L7 Load Balancing, Nginx, Reverse Proxies

• What's DNS? https://youtu.be/27r4Bzuj5NQ?si=2BK3BdM0YGZkI9a7

• L4/L7 Load Balancing https://youtu.be/WHDwVn7mkqA?si=bh0SLN5jC_LD-Lai

• NGINX crash course https://youtu.be/7VAI73roXaY?si=kkBJ9-kFvCRLRNyc

Project: Configure Nginx as reverse proxy for a sample API

## Day 7: Mini Case Study
Design a complete URL Shortener System

Output: Architecture diagram with written trade-offs
<img width="1038" height="685" alt="image" src="https://github.com/user-attachments/assets/89161e6a-cd6f-44dc-974c-3d63d52bb4e3" />
*URL Shortener System Design*

FigmaJam Link: https://www.figma.com/board/mO2wKwjiVOCQS2p34HUBVJ/Untitled?node-id=0-1&p=f&t=v9L0k6VSgG103dXE-0

# 📅 Week 2 - Distributed Systems
Goal: Master how large-scale systems operate

## Days 8-9: Distributed Systems Fundamentals
Learn: CAP theorem, Consistency models, Leader election, Raft

• What's CAP theorem? https://youtu.be/BHqjEjzAicA?si=VUGRIeksGnsVX8Gq

• Consistency models https://youtu.be/Fm8iUFM2iWU?si=EXTk65NGCSiaFUtn

• Leader election https://youtu.be/TzwiGTbUSHg?si=FyII12SOCRLy79LF

• RAFT algorithm https://youtu.be/IujMVjKvWP4?si=NR1MpDivDJ3wfloq

Project: Implement a leader election simulation in JavaScript

## Day 10: Data Partitioning
Learn: Sharding strategies, Consistent Hashing

• What's sharding? https://youtu.be/be6PLMKKSto?si=mGxZG_v7fb1m6mYd

• Sharding strategies? https://youtu.be/JepwOrjeLnk?si=FPVx7Qzw7NAzKEf1

• Consistant hasing https://youtu.be/UF9Iqmg94tk?si=DYhMlamu3T3v1PVD

Project: Build consistent hashing implementation for data distribution

<img width="1636" height="656" alt="image" src="https://github.com/user-attachments/assets/27870095-418d-4f77-946c-ce72f84472b9" />
*I implemeneted Express.js + locally hosted postgres DB to test 3-sharding distribution by docker*

## Days 11-12: Messaging Systems
Learn: Kafka, RabbitMQ, Pub/Sub patterns, Event-driven architecture

• What's Kafka? https://youtu.be/-RDyEFvnTXI?si=O8H3-q9S8_VJbOBT

• RebbitMQ vs Kafka https://youtu.be/PQHf_IzmUXE?si=gA_SrbSK6UR8LTIY

• Pub/Sub patterns https://youtu.be/FMhbR_kQeHw?si=_izv-7SMfumBiAsR

• Event-driven architecture https://youtu.be/rJHTK2TfZ1I?si=mziv2AahPuZUiSV_

Project: Create a notification system with Kafka or Node.js simulation

<img width="1915" height="1018" alt="image" src="https://github.com/user-attachments/assets/eb53208b-b5c5-42b0-bac0-db1a0e973d3e" />
*Producer/Consumer simulation using Kafka, Zookeeper & Node.js*

https://github.com/Navidreza80/event-driven-architecture
*Repo*

## Day 13: Advanced Patterns
Learn: Event Sourcing, CQRS pattern

• Event sourcing https://youtu.be/ID-_ic1fLkY?si=wBFxm7i9Pm3YIZDE

• CQRS https://youtu.be/SvjdJoNPcHs?si=rmSO5uHCAtJRnENe

Project: Design an Order Management System using CQRS

<img width="1060" height="594" alt="image" src="https://github.com/user-attachments/assets/d72c9865-69c8-4032-98da-d336fb10df25" />

## Day 14: Case Study
Design a WhatsApp Messaging System with delivery guarantees

<img width="1050" height="744" alt="image" src="https://github.com/user-attachments/assets/062d6e82-aff0-48c7-8fcd-772e11b922a9" />

# 📅 Week 3 - Microservices & Advanced Architecture
Goal: Progress from monoliths to enterprise-scale systems

## Days 15-16: Microservices Architecture
Learn: Monoliths vs Microservices, Service Discovery, API Gateways

• Monoliths vs Microservices https://youtu.be/NdeTGlZ__Do?si=aAraicc7bFDmhmzs

• Service discovery https://youtu.be/ecuEkmFs5Vk?si=U4b0fUOz4uvasKkK

• API gateway https://youtu.be/6ULyxuHKxg8?si=x4eZwx0-rRc3WlQV

Project: Develop User and Product microservices with API Gateway

I recommend you to watch this vide toturial to master microservices in Node.js: https://youtu.be/EXDkgjU8DDU?si=FiaY2S_enByyNXQ8
Also I have a solid project following this videos
You can deploy you MS to AWS
But I kept it locally with docker

## Day 17: Resilience Patterns
Learn: Circuit Breakers, Rate Limiting, Backoff strategies

• Circuit Breakers https://youtu.be/dJI2saoM5_k?si=bkq1MMGISjNgR3Lx

• Rate Limiting https://youtu.be/_qNHROq0pGk?si=r6yKWn1-poTP8gm6

• Backoff strategies https://youtu.be/i13aUgp9rcY?si=j4OcqfLOO1YUTrns

Project: Implement token bucket rate limiting in Node.js

Watch this video to create a project with rate limits using redis & node.js https://youtu.be/RgPKPquStF0?si=UzVaH-77pGIr38J7

## Days 18-19: Observability
Learn: Logging, Metrics, Distributed Tracing

• High thoughput logging system https://youtu.be/ak1wTYq_opQ?si=BVqrpNulTv6DDqvg

• Latency metrics https://youtu.be/lJ4NEMNBeS4?si=_qn4JUD93sLzo1IX

• Distributed Tracing https://youtu.be/XYvQHjWJJTE?si=e1LtEsQKrQQhgQT_

Project: Set up Prometheus and Grafana for microservices monitoring

## Day 20: API Design
Learn: REST vs GraphQL, API versioning strategies

• Rest vs GraphQL https://youtu.be/yWzKJPw_VzM?si=gjDsTudBYR4OUVXa

• API versioning https://youtu.be/42J4KMHUJjE?si=dt23h4AcGYDUJAoH

Project: Create dual REST/GraphQL endpoints for your microservices

<img width="1919" height="860" alt="image" src="https://github.com/user-attachments/assets/47f734f0-4e96-41d9-9ced-611b55c89a8a" />
*GraphQL API With Node.js*

## Day 21: Case Study
Design a Twitter News Feed System with timeline and content ranking

<img width="1352" height="570" alt="image" src="https://github.com/user-attachments/assets/cff1c7bb-2819-44ec-91d3-313e07aa8906" />
*Twitter System Design*

# 📅 Week 4 - Production Systems & Portfolio
Goal: Build your portfolio and prepare for interviews

## Days 22-23: Reliability & Security
Learn: SLAs/SLOs, Retry mechanisms, Chaos engineering, OAuth/JWT

Project: Add JWT authentication to your microservices

## Days 24-25: Global-Scale Systems
Learn: Multi-region deployment, CDNs, Data replication

Project: Design Netflix Streaming Architecture

## Days 26-27: Advanced Case Studies
Design Uber Ride Matching with surge pricing

Design Dropbox File Storage with sync and deduplication

## Day 28: Portfolio Development
Organize all diagrams in Notion/Markdown

Publish all code projects to GitHub

## Day 29: Interview Practice
Simulate technical interview scenarios

Record yourself explaining WhatsApp & Uber system designs

Day 30: Final Presentation
Polish diagrams, finalize documentation

Create a 15-20 minute walkthrough presentation

