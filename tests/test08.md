### **Test Case 8 – Data Export Functionality**

**Date:** 2025-04-21

---

### Description

This test verifies whether the SuiteCRM export functionality allows users to correctly export data from the system into an appropriate file format.

### Objective

To ensure that the data export mechanism works properly and that the generated file contains the expected and accurate information.

### What is Being Tested

Data export feature in the Contacts module of SuiteCRM.

### Prerequisites

- At least one valid contact record exists in the system.
- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- Stable internet connection and a supported browser (Chrome, Firefox, or Edge).

### Test Procedure

1. Log in to the SuiteCRM system.
2. From the dashboard, navigate to **Contacts > View Contacts**.
3. Select at least one contact from the list.
4. In the **Bulk Action** dropdown, choose **Export**.
5. Confirm the export and observe the download process.

### Expected Result

A file (e.g., CSV) is generated containing the selected contact data, accurately reflecting the current records in the system.

### Actual Result

✅ The selected contact was successfully exported. The generated file included all the correct details and data of the chosen contact.

### Result Analysis

The export feature worked as expected. Data was exported correctly and in an accessible format.

### Error Description (if applicable)

N/A – The test was executed without errors.

### Evidence

- ✅ **System Specifications:**
  - OS: Windows 11 Home Single Language, Version 24H2
  - Build: 26100.3775
  - Experience Pack: 1000.26100.66.0
  - Processor: AMD Ryzen 5 5500U with Radeon Graphics 2.10 GHz
  - RAM: 20.0 GB (15.9 GB usable)
  - System Type: 64-bit
  - Browser: Google Chrome Version 135.0.7049.96 (Official build) 64-bit
  - Screen Resolution: 1920x1080

- **Screenshots and/or Video Evidence:**
  - Video demonstrating the data export process for a contact from the Contacts module:
  ![GIF](https://github.com/user-attachments/assets/e1c76b0f-565d-4045-bfd0-0f7e7387db0c)

