# Unit 4: Queuing Theory

## First thing to remember

**Arrival Rate > Service Rate = Queue**

### Queue real-life examples

- Petrol line
- Gas cylinder line
- Hospital services line
- Government offices line

Since a queue forms when the **arrival rate > service rate**, to eradicate or reduce the queue we need to either:

- Decrease the arrival rate, or
- Increase the service rate.

### Applications

- Production system
- Communication system, etc.

### Definition

A queue is a line of customers who remain waiting for getting certain goods or services from a service center.

---

# Essential Elements of Queuing System

- Calling population
- Queuing process
- Queuing discipline
- Service process or mechanism

### Reneging

An impatient customer who leaves a queue after waiting for some time without being served.

---

## 1) Calling Population

It includes:

i) Size of the calling population

- Finite
- Infinite

ii) Behavior of the arrivals

- Patient
- Impatient

iii) Patterns of arrivals

- In batches
- Individually

---

## 2) Queuing Process

Includes:

- Number of queues
- Their respective lengths

---

## 3) Queuing Discipline

The order in which the service center selects the next customer from the waiting line to be served.

Types:

- FIFO (First In First Out)
- LIFO (Last In First Out)
- Service in Random Order (SIRO)
- Priority Service

---

# 3) Service Process

The manner in which customers are served and leave the system.

Types:

i) One queue, one service centre facility  
_(Refer to textbook diagram, page 234.)_

ii) One queue, multiple service centre facility

iii) Single queue, multi-stage facility

iv) Several queues, one service facility

v) Multiple queues and multiple service facilities

---

# Single Channel Queuing Model

This is the simplest and widely used queuing model.

## Assumptions

- Arrivals are served on the **First In First Out (FIFO)** discipline.
- Every arrival waits to be served regardless of the length of the line.
- Service time varies from one customer to another.

---

# Notations Used in Single Channel Queuing System

- **λ (Lambda)** → Arrival rate
- **μ (Mu)** → Service rate
- **1/m** → Mean time per customer served

---

# Operating Characteristics of Queuing System

## 1) Queue Length

The average number of customers waiting in line for getting service in the service center is called **queue length**.

Lq = λ/μ (λ/ (μ - λ))

---

## 2) System Length

The average number of customers in the queue plus customers getting served is called **system length**.

Ls=(λ/ (μ - λ))

---

## 3) Waiting Time in Queue

The average time spent by a customer waiting in line before getting service is called **average waiting time in queue**.

Denoted by **Wq**.

Formula:
Tq = λ/μ (1/ (μ - λ))


---

## 4) Waiting Time in the System

The average time spent by a customer waiting in line and receiving service at the counter is called **average waiting time in the system**.

Denoted by **Ws**.

Formula:

Ts = (1/ (μ - λ))

---

## 5) Service Facility Utilization

The proportion of time that a server actually spends serving customers.

Formula:

ρ=λ/μ

---

# Types of Lines

There are two types of lines:

### 1. Physical Line

Customers remain standing in a line in front of the service counter.

### 2. Dispersed Line (Waiting List)

Instead of standing in a line, customers submit their application and wait until they are called.

---

# Queuing Theory

Queuing theory is the **analysis of**:

- Waiting line of customers
- Behavior of customers
- Pattern of their arrival
- Service time
- Departure time

---

# Objective of Queuing Theory

The main objective of queuing is to manage a good economic balance between:

- Cost of waiting
- Cost of service

The optimal solution is achieved at the point where the **sum of waiting cost and service cost is minimized.**

