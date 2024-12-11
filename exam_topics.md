# LECTURE 5 -- Coordination and Synchronization

## 1.1 Introduction
- Distributed systems' need for coordination.
- Definitions of coordination and synchronization.

## 1.2 Clock Synchronization

### 1.2.1 Issues
- Challenges with the absence of a global clock.

### 1.2.2 Clock Synchronization Algorithms
- **Christian’s Algorithm**
- **Network Time Protocol (NTP)**
- **Berkeley Algorithm**

### 1.2.3 Concepts
- Clock skew.
- Clock drift.

## 1.3 Logical Clocks

### 1.3.1 Key Concepts
- "Happens-before" relationship.
- Lamport's logical clocks.
- Vector clocks and capturing causality.

## 1.4 Mutual Exclusion

### 1.4.1 Need
- Controlling simultaneous access to shared resources.

### 1.4.2 Approaches
- **Centralized**
- **Distributed**
- **Token Ring**
- **Decentralized**

## 1.5 Election Algorithms

### 1.5.1 Importance
- Electing a coordinator in distributed systems.

### 1.5.2 Algorithms
- **Bully Algorithm**
- **Ring Algorithm**
