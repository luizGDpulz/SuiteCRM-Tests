### **Test Case 5 – Delete Contact**

**Date:** 2025-04-18

---

### Description

This test ensures that the SuiteCRM system successfully deletes a contact record when the delete action is triggered from the contact's detail view.

### Objective

To confirm that the contact deletion functionality works as intended and removes the selected record from the system.

### What is Being Tested

The deletion mechanism for contact records within the Contacts module.

### Prerequisites

- Access to a valid SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- At least one contact previously created in the system.
- User with permissions to delete contacts.
- Stable internet connection and a supported browser (Chrome, Firefox, or Edge).

### Test Procedure

1. Navigate to the main dashboard.
2. Click on **Contacts > View Contacts** in the top navigation menu.
3. The system redirects to the list view: `https://crm.alunostds.dev.br/#/contacts/index?return_module=Contacts&return_action=DetailView`
4. Select a contact by clicking on it.
5. On the contact's detail view page, click **Actions** > **Delete**.
6. Confirm the deletion when prompted.
7. Observe the behavior after deletion.

### Expected Result

The system should prompt the user for confirmation and, upon confirmation, remove the contact from the database. The user should be redirected back to the contact list, where the deleted contact no longer appears.

### Actual Result

The deletion process was completed successfully. The contact was removed from the system and no longer appears in the list view.

### Result Analysis

✅ The test passed. The system effectively removed the selected contact, and the user was properly redirected.

### Error Description (if applicable)

N/A – The deletion process worked as expected.

### Evidence

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
  - Deleting an existing Contact:
  ![Image](https://github.com/user-attachments/assets/7770a995-d381-4d6f-b58d-6258ad27c07c)

