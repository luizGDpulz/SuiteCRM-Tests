### **Test Case 6 – Search Records**

**Date:** 2025-04-21

---

### Description

This test evaluates the SuiteCRM search functionality across different fields to ensure it returns accurate results.

### Objective

To validate the record search mechanism using various criteria (e.g., name, email, phone number) and confirm the system responds quickly and precisely.

### What is Being Tested

The search functionality within the Contacts module.

### Prerequisites

- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br) using a supported browser (Chrome, Firefox, or Edge).
- At least one contact with identifiable fields (name, email, phone number) must exist in the system.
- Stable internet connection.

### Test Procedure

1. Navigate to [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
2. Log in using valid credentials.
3. On the main menu.
4. In the search bar, perform searches using:
   - A contact's **name**.
   - A contact's **email**.
   - A contact's **phone number**.
5. Observe the returned results after each search.

### Expected Result

The system should return relevant records based on the entered criteria, with quick response time and accurate filtering.

### Actual Result

All searches performed (by name, email, and phone number) returned accurate and fast results.

### Result Analysis

✅ The test was successful. The search mechanism is working properly, providing fast and relevant results for all tested criteria.

### Error Description (if applicable)

N/A – The test passed without any issues.

### Evidence

- **Search Criteria Used:**
  - Name
  - Email
  - Phone Number

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
  - Searching Records:
  ![GIF](https://github.com/user-attachments/assets/ee5a3cae-069f-441f-91ff-ecb7b99b8649)