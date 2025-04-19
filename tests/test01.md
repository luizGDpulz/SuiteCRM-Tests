### **Test Case 1 – Valid Login with Correct Credentials**

**Date:** 2025-04-18

---

### Description

This test verifies that the SuiteCRM login functionality correctly authenticates users when valid credentials are provided.

### Objective

To confirm that users with valid credentials can successfully log in to the SuiteCRM system and are redirected to the main dashboard.

### What is Being Tested

Authentication mechanism and login functionality of the SuiteCRM system.

### Prerequisites

- A valid user account exists in the system.
- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br) using a supported browser (Chrome, Firefox, or Edge).
- Stable internet connection.

### Test Procedure

1. Navigate to [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
2. Enter the following credentials:
   - **Username:** `admin`
   - **Password:** `admin123`
3. Click the **Login** button.
4. Observe the redirection to the main dashboard.
5. Repeat steps 2–4 using the following credentials:
   - **Username:** `usuario`
   - **Password:** `usuario123`

### Expected Result

The system should successfully authenticate both users and redirect them to the main dashboard. Upon login, relevant user information and modules should be displayed accordingly.

### Actual Result

Both the admin and standard user accounts were successfully authenticated. The system redirected each user to the dashboard and displayed the corresponding modules correctly.

### Result Analysis

✅ The test was successful. Both users were able to log in and were redirected to the dashboard as expected, with no discrepancies observed.

### Error Description (if applicable)

N/A – The test passed without any errors.

### Evidence

- ✅ **Users Tested:**

  - Admin User
    - Username: `admin`
    - Password: `admin123`
  - Standard User
    - Username: `usuario`
    - Password: `usuario123`

- **System Specifications:**

  - OS: Windows 11 Home Single Language, Version 24H2
  - Build: 26100.3775
  - Experience Pack: 1000.26100.66.0
  - Processor: AMD Ryzen 5 5500U with Radeon Graphics 2.10 GHz
  - RAM: 20.0 GB (15.9 GB usable)
  - System Type: 64-bit
  - Browser: Google Chrome Version 135.0.7049.96 (Official build) 64-bit
  - Screen Resolution: 1920x1080

- **Screenshots and/or Video Evidence:**\
  - Admin login:
    ![GIF](https://github.com/user-attachments/assets/317fff8e-7d49-4fa7-830f-1a87b8cec6e2)
  - User login:
    ![GIF](https://github.com/user-attachments/assets/1b435af6-a6a1-403e-8274-4c82ce6bdd1e)
   
