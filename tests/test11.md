### **Test Case 11 – Performance on Data Queries**

**Date:** 2025-04-21

---

### **Description**

This test measures the system's response time when executing queries over large volumes of data to ensure performance stays within acceptable limits.

### **Objective**

To evaluate the system's performance in terms of response time when querying large datasets and compare it with expected time frames.

### **What is Being Tested**

System performance and query speed when handling large volumes of data.

### **Prerequisites**

- Access to the SuiteCRM instance at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br) using a supported browser (Chrome, Firefox, or Edge).
- Sufficient data volume is present in the system (e.g., multiple records in Contacts, Leads, etc.).
- A stable internet connection.

### **Test Procedure**

1. Navigate to [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
2. Perform queries on data-heavy modules such as Contacts, Leads, or Opportunities.
3. Measure the time it takes for the system to return results.
4. Repeat the query multiple times to check consistency and identify performance trends.

### **Expected Result**

- The system should return query results within an acceptable time frame (e.g., under 5 seconds for basic queries).
- The performance should remain stable even under the load of larger datasets.

### **Actual Result**

- The system performed queries as expected, though there was a slight delay due to server performance. However, the results still came within acceptable response times and did not significantly affect usability.

### **Result Analysis**

✅ The test passed. The system's query performance is within acceptable limits, though there was a minor delay caused by server performance. This delay did not severely impact user experience.

### **Error Description (if applicable)**

N/A – Performance was slightly slower than expected, but within a reasonable range.

### **Evidence**

- **System Specifications:** 

  - OS: Windows 11 Home Single Language, Version 24H2
  - Build: 26100.3775
  - Processor: AMD Ryzen 5 5500U with Radeon Graphics 2.10 GHz
  - RAM: 20.0 GB (15.9 GB usable)
  - System Type: 64-bit
  - Browser: Google Chrome Version 135.0.7049.96 (Official build) 64-bit
  - Screen Resolution: 1920x1080

- **Screenshots and/or Video Evidence:**
  - Video with infos:
  

