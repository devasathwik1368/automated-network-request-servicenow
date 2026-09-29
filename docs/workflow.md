# Workflow

## Request Lifecycle

### 1. Request Creation
The requester opens the Network Request catalog item and enters the required details.

### 2. Validation
The submitted values are checked before fulfillment begins.

### 3. Approval
The request is routed to the appropriate approver based on the configured request conditions.

### 4. Approval Decision

**Approved:** A fulfillment task is created and assigned to the Network Team.

**Rejected:** The request is closed/rejected and the requester is notified.

### 5. Fulfillment
A network engineer works on the generated task and records progress in work notes.

### 6. Completion
After the task is completed, the parent request lifecycle is updated.

### 7. Notification
The requester receives status updates at important stages.

## Status Example

```text
New
  ↓
Awaiting Approval
  ↓
Approved
  ↓
In Progress
  ↓
Completed
```
