# Automated Network Request Management in ServiceNow

## Project Overview

Automated Network Request Management in ServiceNow is a Service Catalog and workflow automation project designed to streamline network access and network change requests.

The solution provides a structured request process where users submit network requests, requests are validated and routed for approval, approved requests generate fulfillment tasks for the Network Team, and request status is updated throughout the lifecycle.

## Core Workflow

```text
Requester
   |
   v
Network Request Catalog Item
   |
   v
Request Validation
   |
   v
Approval
   |--------------------|
   |                    |
 Approved             Rejected
   |                    |
   v                    v
Network Fulfillment   Close Request
Task
   |
   v
Network Team / Engineer
   |
   v
Task Completion
   |
   v
Request Completed
   |
   v
Requester Notification
```

## Main Features

- Network Request Catalog Item
- Request type, access level, device, priority and business justification
- User/group based request handling
- Approval workflow
- Automated fulfillment task creation
- Network Team assignment
- Request and task status tracking
- Requester notifications
- Reporting and dashboard support
- Role and access-control configuration
- Audit-ready request and task records

## ServiceNow Components

- Service Catalog
- Catalog Item
- Catalog Variables
- Client Scripts / UI Policies
- Flow Designer
- Approvals
- Catalog Tasks
- Groups and Roles
- Notifications
- Reports and Dashboards
- Access Controls

## Request Fields

| Field | Example |
|---|---|
| Request Type | Network Access |
| Access Level | Standard |
| Device | Laptop |
| Priority | Medium |
| Business Justification | VPN access required |
| Additional Details | Project-related network access |

## Project Phases

1. Requirement Analysis & Planning
2. Backend Development & Configurations
3. UI/UX Development & Customization
4. Data Migration, Testing & Security
5. Deployment, Documentation & Final Presentation

## Skills

- ServiceNow Certified System Administrator concepts
- ServiceNow Certified Application Developer concepts
- Service Catalog
- Flow Designer
- Workflow automation
- ServiceNow security and access control

## Project Status

The repository contains the project documentation, architecture, workflow description, configuration plan and supporting project structure. ServiceNow instance implementation evidence and the final demo recording can be added to the repository after the working instance is available.



## Author

Pallem Deva Sathwik
