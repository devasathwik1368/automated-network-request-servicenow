# ServiceNow Configuration Plan

## 1. Catalog Item

Create:

**Name:** Network Request

Suggested variables:

- Request Type
- Access Level
- Device
- Priority
- Business Justification
- Additional Details

## 2. Groups

Suggested groups:

- Network Team
- Network Approvers
- Network Requesters

## 3. UI Behaviour

Use Catalog UI Policies / Client Scripts to display relevant fields based on the selected request type.

Example:

```text
If Request Type = Network Access
    Show Access Level
    Show Device

If Request Type = Network Change
    Show Device
    Show Change Details
```

## 4. Flow Designer

Suggested flow:

```text
Trigger: Catalog Request Submitted
        ↓
Validate Request
        ↓
Ask for Approval
        ↓
If Approved
        ↓
Create Catalog Task
        ↓
Assign to Network Team
        ↓
Wait for Task Completion
        ↓
Update Request
        ↓
Send Notification
```

## 5. Notifications

Suggested notifications:

- Request submitted
- Approval required
- Request approved
- Request rejected
- Fulfillment task completed
- Request completed
