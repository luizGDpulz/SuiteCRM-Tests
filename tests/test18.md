### **Test Case 18 – Report Export**

**Date:** 2025-04-24

---

### **Title of the Test:** Report Export

### **Description**

This test assesses the ability of the system to export reports in common formats while ensuring data consistency and usability.

### **Objective**

To ensure that generated reports can be exported in formats such as PDF or Excel while maintaining data integrity and usability.

### **What is Being Tested**

Export capabilities for data and reports from the SuiteCRM system.

### **Prerequisites**

- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- At least one dataset available for export (e.g., Contacts).

### **Test Procedure**

1. Navigate to a module containing records, such as Contacts.
2. Attempt to export the data using the system’s built-in export options.
3. Select PDF format and attempt to export multiple records.
4. Repeat the process using the CSV export option.
5. Verify the format, content, and data integrity of exported files.

### **Expected Result**

- Users should be able to export multiple records at once in formats like PDF and Excel.
- Exported data should retain structure and integrity.

### **Actual Result**

- Export to PDF only supports one record at a time (e.g., individual contact export).
- Export to Excel is not available.
- Export to CSV works for bulk data export and preserves information properly.

### **Result Analysis**

⚠️ The test is **partially completed**. While the system allows data export via CSV in bulk, PDF export is restricted to one record at a time and Excel format is not supported.

### **Error Description (if applicable)**

- PDF export lacks bulk capabilities.
- No native support for Excel export.

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