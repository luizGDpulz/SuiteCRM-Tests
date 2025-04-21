### **Test Case 7 – Data Import Functionality**

**Date:** 2025-04-21

---

### Description

This test evaluates the data import feature in SuiteCRM to ensure that data can be successfully imported via a CSV file into a selected module.

### Objective

To verify that the system can accurately import data from a CSV file, correctly validate and assign fields, and appropriately handle the import process.

### What is Being Tested

The data import functionality and its interface behavior within the Contacts module.

### Prerequisites

- A valid user account with access permissions to import data.
- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- A properly formatted CSV file with contact data.
- Stable internet connection.

### Test Procedure

1. Login to the system at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
2. Navigate to the top menu, go to **Contacts** > **Import Contacts**.
3. Select the CSV file from your local system.
4. Choose the source and proceed.
5. Validate and map the fields shown in the import interface.
6. Click on **Import** to execute the data import.

### Expected Result

The system should import the records successfully, displaying a confirmation message. Fields should be correctly mapped and saved in the Contacts module.

### Actual Result

✅ The import was successful. The tool accurately validated and matched the fields from the CSV file. It allowed the addition or update of records as expected.

⚠️ However, the interface has some usability bugs. After certain interactions, the screen does not scroll back to the top, which can cause confusion and unnecessary delays.

### Result Analysis

✅ The test was generally successful. Despite minor UI issues, the core functionality of data import worked as expected.

### Error Description (if applicable)

- UI Bug: The page does not scroll back to the top automatically after each step, potentially confusing users.

### Evidence

- **CSV file used**: 
```
"First Name","Last Name","ID","Salutation","Job Title","Department","Account Name","Email Address","Non Primary E-mails","Mobile","Office Phone","Home","Other Phone","Fax","Primary Address Street","Primary Address City","Primary Address State","Primary Address Postal Code","Primary Address Country","Alternate Address Street","Alternate Address City","Alternate Address State","Alternate Address Postal Code","Alternate Address Country","Description","Birthdate","Lead Source","Campaign ID","Do Not Call","Reports to ID","Assistant","Assistant Phone","Assigned to","Assigned User","Date Created","Date Modified","Modified By","Created By","Deleted","Photo","Lawful Basis","Lawful Basis Date Reviewed","Lawful Basis Source","Joomla Account ID","Account Disabled","Portal User Type","Address","Geocode Status","Longitude","Latitude"
"Lucas","Ferreira","a1234567-b89c-40d1-a456-556642440000","Mr.","Analista de Sistemas","TI","Liko Tintas","lucas.ferreira@liko.com.br","lucas.alt@gmail.com","51999999999","5133334444","5132221111","5144445555","5144455566","Rua das Acácias, 123","São Leopoldo","RS","93010-020","Brasil","Av. Brasil, 456","Canoas","RS","92425-030","Brasil","Contato criado para demonstração de CRM","1998-09-15","Web Site","camp-001","0","sup-789","","","usuario","9a7463a6-c950-d03e-570d-67f464f0dc9b","2025-04-21 10:00","2025-04-21 10:00","9a7463a6-c950-d03e-570d-67f464f0dc9b","9a7463a6-c950-d03e-570d-67f464f0dc9b","0","","Consent","2025-04-21","Website","joomla-001","0","Single user","","Verified","-51.1497","-29.7547"
```

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
   - Video demonstrating the entire import process: 
   ![GIF](https://github.com/user-attachments/assets/4f5a0f50-73d1-48e9-ad17-a081f106acce)
