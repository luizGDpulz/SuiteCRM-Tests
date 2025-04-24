### **Test Case 22 – System Logs and Audit Verification**

**Date:** 2025-04-24

---

### **Title of the Test:** System Logs and Audit Verification

### **Description**

This test assesses whether the system correctly logs user activities and errors, enabling administrators to audit key operations such as logins, record creation, edits, and deletions.

### **Objective**

To ensure the system provides proper logging and auditing functionality for monitoring and accountability purposes.

### **What is Being Tested**

- Logging of user activities (login, creation, edit, deletion)
- Logging of system errors
- Accessibility and visibility of logs for audit purposes

### **Prerequisites**

- Access to SuiteCRM with administrator privileges.
- At least one user account to simulate various actions.
- Access to both the main dashboard and the admin panel.

### **Test Procedure**

1. Log into the system using a standard and an administrator account.
2. Perform a series of actions including creating, editing, and deleting records.
3. Navigate to the main dashboard and look for visible logs or activity feeds.
4. Access the Admin panel and locate error logs or audit tools.
5. Review how the logs are presented and if they are sufficient for auditing purposes.

### **Expected Result**

The system should:
- Record and present user actions such as logins, creations, and edits in an accessible log view.
- Store error logs and activity logs in a centralized, user-friendly interface.
- Enable administrators to monitor user activity efficiently.

### **Actual Result**

⚠️ Partial functionality:
- The system logs creation actions on the main screen through an activity feed.
- The Admin section only provides access to error logs.
- There is no centralized or unified audit log interface.
- Visual representation and organization of logs are limited and not intuitive.

### **Result Analysis**

⚠️ The test was partially successful. While some logs are generated, they are fragmented and difficult to audit in a comprehensive manner. The system lacks a unified and well-structured logging/auditing interface.

### **Error Description**

- Activity logs are limited to visual dashboard feed.
- Error logs are separated and only available in the admin section.
- No consolidated audit trail across all user actions.

### **Evidence**

- Actions tested: record creation, edit, and login with two user types.
- Logs confirmed in dashboard (creation) and admin panel (errors).
- No visual or downloadable audit trail for all user activities.