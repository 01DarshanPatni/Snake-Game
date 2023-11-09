# Report on Queueing Theory

## Introduction

Queueing theory is a valuable tool for analyzing and optimizing the performance of systems with waiting lines in various fields. This report provides an overview of queueing theory, its key concepts, and the relevant formulas for both single-queue and multi-queue systems.

## Key Concepts of Queueing Theory

### 1. Queues

A queue, or waiting line, represents a collection of entities waiting for service.

### 2. Arrival Process

The arrival process characterizes how entities enter the queue, following patterns like Poisson or deterministic arrivals.

### 3. Service Process

The service process defines how entities are served once they enter the queue, considering various service disciplines and rates.

### 4. Queueing Models

The M/M/1 (Markovian single-server) and M/M/c (Markovian multi-server) models are commonly used to analyze queues with single and multiple servers, respectively.

### 5. Performance Metrics

Key performance metrics include utilization, average queue length, and average waiting time in the queue. These metrics are essential for assessing system efficiency and customer satisfaction.

## Performance Metrics Analysis

### M/M/1 Queueing Model:

#### Finite Queue Length (M/M/1/K):

- Utilization (U): λ / μ
- Average Queue Length (Lq): ρ(1 - ρ^K) / (1 - ρ^(K+1))
- Average Waiting Time (Wq): Lq / λ

#### Infinite Queue Length (M/M/1):

- Utilization (U): λ / μ
- Average Queue Length (Lq): λ^2 / (μ(μ - λ))
- Average Waiting Time (Wq): λ / (μ - λ)

### M/M/c Queueing Model:

#### Finite Queue Length (M/M/c/K):

- Utilization (U): λ / (cμ)
- Average Queue Length (Lq): cρ(1 - ρ^K) / (1 - ρ^(K+1))
- Average Waiting Time (Wq): Lq / λ

#### Infinite Queue Length (M/M/c):

- Utilization (U): λ / (cμ)
- Average Queue Length (Lq): cρ / (1 - ρ)
- Average Waiting Time (Wq): Lq / λ

## Conclusion

Understanding the performance metrics for both single-queue and multi-queue systems is crucial for optimizing system performance and resource allocation. These metrics play a vital role in providing efficient and reliable services, minimizing waiting times, and enhancing customer satisfaction. By analyzing and applying the appropriate queueing models, organizations can improve operational efficiency and service quality.

