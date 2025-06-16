---
title: "YADTQ - Yet Another Distributed Task Queue"
description: "A Scalable Distributed Task Queue using Kafka and Redis"
layout: page
---

# [YADTQ - Yet Another Distributed Task Queue](https://github.com/OmkarKashyap/Yet-Another-Distributed-Task-Queue)

**YADTQ** is a distributed task queue system designed to manage and execute tasks across multiple worker nodes efficiently. Built using Kafka and Redis, it ensures scalability, fault tolerance, and high throughput for background task processing in distributed environments.

## Project Context

This project was part of my Big Data course at PES University, aimed at understanding how distributed task queues are designed and implemented in real-world systems. The project uses Kafka for handling messaging between systems and Redis for managing task coordination. YADTQ shows how tasks can be distributed across multiple producers and consumers, enabling efficient processing in a scalable, distributed architecture.

## Features

- **Distributed Task Management**  
  Efficiently dispatch and process tasks across multiple workers with support for parallel execution.

- **Reliable Messaging System**  
  Integration with Apache Kafka ensures fault-tolerant, high-performance message delivery.

- **Task Coordination with Redis**  
  Redis is used for fast task lookup, state management, and system coordination.

- **Scalable Architecture**  
  Easily scale by adding more workers without affecting overall system performance.

## Tech Stack

- **Languages:** Python
- **Message Broker:** Apache Kafka
- **Task State Management:** Redis
- **Orchestration:** CLI-based interaction, Kafka topics per task type

## Repository

Explore the full project here: [YADTQ GitHub Repository](https://github.com/OmkarKashyap/Yet-Another-Distributed-Task-Queue)

---

Feel free to fork the repo, raise issues, or contribute new features. Whether you're experimenting with distributed systems or working on a task queue, I hope **YADTQ** can be useful for your project!
