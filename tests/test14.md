### **Test Case 14 – Task Creation**

**Date:** 2025-04-23

---

### **Title of the Test:** Task Creation

### **Description**

This test verifies the functionality of creating tasks within the SuiteCRM system, ensuring that required fields are enforced and the process completes without errors.

### **Objective**

To confirm that users can create tasks successfully, and that required fields (such as subject, status, and priority) are clearly indicated and validated.

### **What is Being Tested**

Task creation functionality and field validation.

### **Prerequisites**

- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- Valid user credentials.

### **Test Procedure**

1. Navigate to the **Calendar** module.
2. Click on **Create Task**.
3. Fill in the task details:
   - Required fields: **Subject**, **Status**, **Priority**.
4. Click the **Save** button at the top right corner.
5. Observe redirection to the task summary screen.

### **Expected Result**

The system should allow the creation of a new task when all required fields are completed and should redirect the user to a summary view of the task.

### **Actual Result**

The task was created successfully. Required fields were clearly indicated, and the process completed without any bugs.

### **Result Analysis**

✅ Test passed. Task creation behaves as expected and enforces required fields correctly.

### **Error Description (if applicable)**

N/A – No errors encountered.

### **Evidence**

- **System Specifications:**
  - OS: Windows 11 Home Single Language, Version 24H2
  - Build: 26100.3775
  - Experience Pack: 1000.26100.66.0
  - Processor: AMD Ryzen 5 5500U with Radeon Graphics 2.10 GHz
  - RAM: 20.0 GB (15.9 GB usable)
  - System Type: 64-bit
  - Browser: Google Chrome Version 135.0.7049.96 (Official build) 64-bit
  - Screen Resolution: 1920x1080

- **Screenshots and/or Video Evidence:**
  - Video with the process:

