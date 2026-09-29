# Solution Architecture

## High-Level Architecture

```text
Service Portal / Service Catalog
              |
              v
     Network Request Catalog Item
              |
              v
       Request / RITM Record
              |
              v
          Flow Designer
              |
       +------+------+
       |             |
       v             v
   Approval       Rejection
       |
       v
 Catalog Task
       |
       v
 Network Team
       |
       v
 Task Completion
       |
       v
 Request Completion + Notification
```

## Main Components

### Service Catalog
Provides the user-facing Network Request form.

### Flow Designer
Automates validation, approval routing, fulfillment task creation and lifecycle updates.

### Approval
Controls whether the requested network access/change can proceed.

### Catalog Task
Represents the work performed by the Network Team.

### Notifications
Keeps the requester informed at important lifecycle stages.

### Security
Groups, roles and access controls restrict administrative, approval and fulfillment activities.
