# ☕ Cloud Café - Application Load Balancer (ALB) Project

## Overview

This project demonstrates how AWS Application Load Balancer (ALB) distributes incoming traffic across multiple EC2 instances and ensures high availability through health checks.

## Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- Security Groups
- Amazon Linux 2023
- Nginx

## Architecture

<img width="1536" height="1024" alt="ChatGPT Image Jun 19, 2026, 05_35_50 PM" src="https://github.com/user-attachments/assets/dc4e2611-8ac8-4df0-aa8c-4997ab9d1ff1" />

### Architecture Flow

Users → Application Load Balancer → Target Group → EC2 Instance 1 & EC2 Instance 2

---

## EC2 Instances

<img width="1611" height="462" alt="Screenshot 2026-06-19 174135" src="https://github.com/user-attachments/assets/8511f07c-f88a-4ce1-8509-a7fff95907ca" />

---

## Server One Web Page

<img width="1901" height="866" alt="server-1-webpage" src="https://github.com/user-attachments/assets/b8fbef67-a7f8-4d3c-ae64-21bf0aecf954" />

---

## Server Two Web Page

<img width="1901" height="807" alt="server-2webpage" src="https://github.com/user-attachments/assets/e63d8a34-d282-49cb-ac41-a16da19dbd31" />

---

## Target Group

<img width="1551" height="745" alt="Target-group-healthy" src="https://github.com/user-attachments/assets/5ccfc12b-c256-4a1c-9c26-e2e005c693ac" />

---

## Application Load Balancer

<img width="1601" height="747" alt="ALB-Configuration" src="https://github.com/user-attachments/assets/ab67fcd9-1ec5-40bd-9380-b6d7a9112dcd" />

---

## ALB DNS Output

<img width="1901" height="807" alt="ALBDNS-op-2" src="https://github.com/user-attachments/assets/6cfe0dac-cb79-4f42-bd8a-a4d723590859" />

<img width="1901" height="866" alt="ALBDNS-oP-1" src="https://github.com/user-attachments/assets/7a244154-e22f-41b0-a7ec-e65c5b3bd4a9" />

---

## Features

- Load Balancing
- Health Checks
- High Availability
- Fault Tolerance

---

## Testing

- Verified traffic distribution across EC2 instances
- Simulated server failure
- Confirmed health check functionality
- Automatic recovery and failover

---

## Author

**Sahil Donagre**
