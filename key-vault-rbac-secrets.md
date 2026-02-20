# Azure Key Vault — RBAC & Secret Management

## 🎯 Objective
Securely store sensitive information using Azure Key Vault and resolve access issues using RBAC.

## 🛠️ What Was Implemented

- Created a Key Vault named `kv-security-lab`
- Encountered RBAC permission error when accessing secrets
- Assigned **Key Vault Secrets Officer** role to grant least-privilege access
- Successfully created and stored a secret

## 🔐 Key Security Concepts

### Least Privilege Access
Access was granted using the **Key Vault Secrets Officer** role, allowing secret management without full administrative control.

### RBAC vs Access Policies
Azure Key Vault uses RBAC to control data-plane access, improving centralized access control.

### Secure Secret Storage
Secrets such as passwords should never be hard-coded in applications and should be stored securely in Key Vault.

## 🧠 What I Learned

- How to troubleshoot RBAC permission errors
- How to assign least-privilege roles
- How Azure Key Vault protects sensitive data

## 📌 Real-World Relevance

Azure Key Vault is used in enterprise environments to:

- Protect credentials and secrets
- Enable secure application authentication
- Enforce centralized access control
