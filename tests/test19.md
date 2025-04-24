### **Test Case 19 – Browser Compatibility**

**Date:** 2025-04-24

---

### **Title of the Test:** Browser Compatibility

### **Description**

This test verifies the compatibility and proper functioning of the SuiteCRM system across various browsers and operating systems.

### **Objective**

To ensure the system operates correctly and maintains its usability across different web browsers and devices.

### **What is Being Tested**

Cross-browser compatibility and user interface behavior.

### **Prerequisites**

- Access to SuiteCRM at [http://crm.alunostds.dev.br](http://crm.alunostds.dev.br).
- Use of the online testing platform [https://www.browserling.com](https://www.browserling.com) to simulate browsers and systems.

### **Test Procedure**

1. Open [https://www.browserling.com](https://www.browserling.com).
2. Select each of the following OS and browser combinations:
   
   **Windows 11:**
   - Google Chrome
   - Microsoft Edge

   **Windows 10:**
   - Google Chrome
   - Microsoft Edge
   - Mozilla Firefox
   - Opera
   - Brave
   - Vivaldi
   - Tor Browser

   **macOS 14 Sequoia:**
   - Safari
   - Google Chrome
   - Mozilla Firefox
   - Microsoft Edge
   - Opera
   - Brave
   - Vivaldi
   - Tor Browser

   **Android 15–10:**
   - Google Chrome
   - Mozilla Firefox

   **Android 4.4 KitKat:**
   - Google Chrome (❌ Did not work)

3. Access the SuiteCRM application in each configuration.
4. Check interface rendering and functional behavior.

### **Expected Result**

The system should load and function normally in all tested environments, except in legacy systems that no longer support modern web standards.

### **Actual Result**

✅ The system functioned correctly on all modern browsers and platforms tested. ❌ On Android 4.4 KitKat, Google Chrome failed to load the application.

### **Result Analysis**

⚠️ The test is considered successful, with a partial limitation noted for Android 4.4 KitKat, which is an outdated system no longer widely used. Browser compatibility is confirmed for all current systems.

### **Error Description (if applicable)**

- Google Chrome on Android 4.4 KitKat could not load the CRM site.

### **Evidence**

- **Testing Tool Used:** [https://www.browserling.com](https://www.browserling.com)
- **Note:** No screenshots or videos were recorded for this test.
- **Browsers Tested:** Chrome, Edge, Firefox, Opera, Brave, Vivaldi, Safari, Tor Browser
- **Systems Tested:** Windows 11, Windows 10, macOS 14 Sequoia, Android 15–10, Android 4.4