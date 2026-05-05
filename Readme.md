## **PROJECT OVERVIEW**

#### **🔐 Project 1: Centralized Zero Trust Identity Provider**

##### **Technology: Keycloak**



**Domain: Identity \& Access Management (IAM)**



A production-ready Identity Provider implementing:



Single Sign-On (SSO)

Multi-Factor Authentication (MFA)

Conditional Access Policies

Role-Based Access Control (RBAC)

OpenID Connect (OIDC)

Federated Identity (Google Workspace)



###### **🏗️ Architecture Overview**

The CDOC architecture is divided into two security layers:



Identity Layer (Access Control)

Keycloak (Dockerized)

PostgreSQL Backend

OIDC Client Integration

Conditional MFA Enforcement



###### **📆 Project Timeline Structure**

Each project is executed over 4 structured weeks.



###### **🔐 Project 1 – IAM (Keycloak)**



**Week 1 – Infrastructure Deployment**

Deploy Keycloak (Docker)

Configure PostgreSQL backend

Create Realm

Define Roles (Admin, Developer, Viewer)

Secure Admin Console



**Week 2 – Application Integration**

Register OIDC Client

Integrate Flask/Express Application

Validate SSO Flow



**Week 3 – Advanced Policies**

Implement Conditional MFA

Configure RBAC policies

Inspect JWT tokens for claims validation



**Week 4 – Auditing \& Hardening**

Enable Event Logging

Customize Login Theme

Perform Security Testing (Session Fixation / Redirect Checks)

