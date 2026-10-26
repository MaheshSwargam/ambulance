# Smart Ambulance Communication System Using Dynamic Routing Algorithms

## Overview

The Smart Ambulance Communication System is a Java-based project that improves emergency healthcare response using Dynamic Routing Algorithms and TCP/IP Communication. The system calculates the fastest route between an ambulance and a hospital using Dijkstra's Algorithm and automatically updates the route when traffic conditions change. Emergency alerts are simultaneously transmitted to the hospital dashboard, enabling medical teams to prepare before the ambulance arrives.

---

## Problem Statement

In emergency situations, traffic congestion can significantly delay ambulance transport and reduce the chances of patient survival. Traditional routing systems often rely on static routes and do not provide real-time communication with hospitals.

This project aims to:

- Find the fastest route dynamically.
- Adapt to changing traffic conditions.
- Provide real-time ambulance-to-hospital communication.
- Improve emergency response efficiency.

---

## Objectives

- Design a weighted road network model.
- Implement Dijkstra's shortest path algorithm.
- Support dynamic route recalculation during traffic updates.
- Develop reliable client-server communication using TCP sockets.
- Create user-friendly graphical interfaces.
- Simulate ambulance tracking and hospital notification.

---

## Key Features

### Dynamic Routing
- Fastest path calculation using Dijkstra's Algorithm.
- Automatic route updates during congestion.
- Reduced travel delays.

### Real-Time Communication
- TCP/IP-based communication.
- Instant emergency alert transmission.
- Reliable client-server architecture.

### Hospital Dashboard
- Displays incoming ambulance alerts.
- Shows ambulance ID and emergency details.
- Displays fastest route and ETA.
- Maintains alert history.

### Traffic Control Module
- Simulates traffic congestion.
- Updates road travel times.
- Recalculates optimal routes instantly.

### Live Tracking
- Simulates ambulance movement.
- Displays route progress.
- Updates location status dynamically.

---

## System Modules

### 1. Ambulance Control Panel
- Enter ambulance details.
- Select emergency type.
- Calculate fastest route.
- Send emergency alerts.

### 2. Network Model
- Stores road network graph.
- Manages routing operations.
- Runs Dijkstra's Algorithm.

### 3. Traffic Control Module
- Updates road costs.
- Simulates traffic changes.
- Provides route optimization.

### 4. Hospital Dashboard
- Receives alerts.
- Displays alert details.
- Shows server status and alert count.

### 5. Live Tracking Module
- Simulates ambulance movement.
- Updates travel status.
- Tracks route completion.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Java | Application Development |
| Java Swing | GUI Development |
| TCP/IP | Network Communication |
| Socket Programming | Client-Server Communication |
| Multithreading | Concurrent Processing |
| Graph Data Structures | Road Network Modeling |
| Dijkstra Algorithm | Route Optimization |

---

## Network Architecture

The system follows a Client-Server Architecture.

### Client
- Ambulance Control Panel

### Server
- Hospital Dashboard

### Shared Components
- Network Model
- Traffic Control System
- Live Tracking Module

Communication is established using TCP sockets on Port 5000.

---

## Working Procedure

1. Start the Hospital Dashboard.
2. Launch the Ambulance Control Panel.
3. Enter ambulance information.
4. Calculate the fastest route.
5. Update traffic conditions if required.
6. Recalculate the route dynamically.
7. Send emergency alert to hospital.
8. Receive alert at Hospital Dashboard.
9. Track ambulance movement in real time.

---

## Sample Scenario

### Normal Traffic

Route:
Ambulance → B → C → Hospital

Estimated Time:
10 Minutes

### Congested Traffic

When Road B–C becomes congested:

Route:
Ambulance → B → Hospital

Estimated Time:
13 Minutes

Dynamic routing avoids the congested path and reduces overall delay.

---

## Hardware Requirements

- Intel Core i3 Processor or Higher
- 4 GB RAM Minimum
- 500 MB Storage
- Network Interface (Wi-Fi/Ethernet)
- 1366 × 768 Resolution Display

---

## Software Requirements

- Windows / Linux / macOS
- Java JDK 11 or Higher
- Java Swing
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans, VS Code)

---

## Benefits

- Faster emergency response.
- Reduced travel delays.
- Better hospital preparedness.
- Enhanced communication.
- Demonstrates Computer Networks concepts practically.

---

## Future Scope

- GPS Integration
- Real-Time Traffic APIs
- Multiple Ambulances
- Multiple Hospitals
- Bed Availability Monitoring
- Secure Data Communication
- Cloud-Based Deployment
- AI-Based Route Prediction

---

## SDG Mapping

### SDG 3
Good Health and Well-Being

### SDG 9
Industry, Innovation and Infrastructure

### SDG 11
Sustainable Cities and Communities

---
