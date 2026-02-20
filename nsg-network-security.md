# Network Security Group (NSG) — Zero Trust Networking

## 🎯 Objective
Implement least-privilege network access using Azure Network Security Groups.

## 🛠️ What Was Implemented

- Created an NSG named `nsg-security-lab`
- Reviewed default inbound rules (DenyAllInbound)
- Added a rule to allow RDP (3389) with controlled priority
- Applied Zero Trust principle: deny by default, allow explicitly

## 🔐 Key Security Concepts

### Default Behavior
Azure NSGs deny all inbound traffic unless explicitly allowed.

### Least Privilege
Only required ports should be opened. In this lab, RDP was allowed for administrative access.

### Priority-Based Rules
Lower numbers = higher priority. Custom rules must be prioritized correctly.

## 🧠 What I Learned

- How Azure enforces Zero Trust networking
- How to create and prioritize NSG rules
- How default deny protects resources

## 📌 Real-World Relevance

NSGs are used in enterprise environments to:

- Restrict unauthorized access
- Segment networks
- Enforce security policies
