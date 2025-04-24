# SuiteCRM-Tests

![CRMLogo](./evidence/company_logo.png)

## Summary
- [Table of Contents](#table-of-contents)
- [Test Summaries](#test-summaries)
- [Quantitative Test Table](#quantitative-test-table)
- [Conclusions](#conclusions)

## Table of Contents
1. [Test Case 1 – Valid Login with Correct Credentials](./tests/test01.md)
2. [Test Case 2 – Invalid Login Attempt](./tests/test02.md)
3. [Test Case 3 – Create New Contact](./tests/test03.md)
4. [Test Case 4 – Edit Existing Contact](./tests/test04.md)
5. [Test Case 5 – Delete Contact](./tests/test05.md)
6. [Test Case 6 – Search Records](./tests/test06.md)
7. [Test Case 7 – Data Import Functionality](./tests/test07.md)
8. [Test Case 8 – Data Export Functionality](./tests/test08.md)
9. [Test Case 9 – Interface Responsiveness on Various Devices](./tests/test09.md)
10. [Test Case 10 – Access to Restricted Features](./tests/test10.md)
11. [Test Case 11 – Performance on Data Queries](./tests/test11.md)
12. [Test Case 12 – Email Integration](./tests/test12.md)
13. *Test Case 13 - Skipped due to inability to perform test*
14. [Test Case 14 – Task Creation](./tests/test14.md)
15. [Test Case 15 – Task Assignment](./tests/test15.md)
16. [Test Case 16 – Notification Generation](./tests/test16.md)
17. [Test Case 17 – Custom Report Generation](./tests/test17.md)
18. [Test Case 18 – Report Export](./tests/test18.md)
19. [Test Case 19 – Browser Compatibility](./tests/test19.md)
20. [Test Case 20 – Required Fields Validation](./tests/test20.md)
21. [Test Case 21 – Sales Module Integration](./tests/test21.md)
22. [Test Case 22 – System Logs and Audit Verification](./tests/test22.md)

## Test Summaries

- **Test Case 1 – Valid Login with Correct Credentials**  
  - **Objective:** Confirm that valid users can log in and reach the main dashboard.  
  - **Expected Result:** Successful authentication and redirection to dashboard.  
  - **Actual Result:** Both admin and standard users logged in and reached the dashboard correctly.

- **Test Case 2 – Invalid Login Attempt**  
  - **Objective:** Ensure the system blocks invalid credentials with proper error messaging.  
  - **Expected Result:** Access denied and display of "Invalid credentials" message.  
  - **Actual Result:** Invalid login attempts were blocked and an appropriate error was shown.

- **Test Case 3 – Create New Contact**  
  - **Objective:** Verify creation of a new contact with required validation.  
  - **Expected Result:** Contact created when last name provided; error if omitted.  
  - **Actual Result:** Contact creation succeeded with last name; validation error appeared when omitted.

- **Test Case 4 – Edit Existing Contact**  
  - **Objective:** Confirm editing of contact records is saved and displayed correctly.  
  - **Expected Result:** Updated contact details reflect after saving.  
  - **Actual Result:** Job Title field updated and displayed properly.

- **Test Case 5 – Delete Contact**  
  - **Objective:** Confirm deletion removes the contact from the system.  
  - **Expected Result:** Contact no longer appears in list after deletion.  
  - **Actual Result:** Contact was removed successfully and no longer appeared.

- **Test Case 6 – Search Records**  
  - **Objective:** Validate search across name, email, and phone fields.  
  - **Expected Result:** Accurate and quick search results.  
  - **Actual Result:** Search returned relevant records promptly for all criteria.

- **Test Case 7 – Data Import Functionality**  
  - **Objective:** Verify importing data via CSV with field mapping.  
  - **Expected Result:** Bulk import succeeds with correct field validation.  
  - **Actual Result:** Import worked; minor UI bug in scrolling noted.

- **Test Case 8 – Data Export Functionality**  
  - **Objective:** Ensure data can be exported correctly to file.  
  - **Expected Result:** Export selected contacts to CSV/PDF accurately.  
  - **Actual Result:** CSV export bulk succeeded; PDF export per record only.

- **Test Case 9 – Interface Responsiveness on Various Devices**  
  - **Objective:** Test responsiveness on desktop, tablet, and mobile.  
  - **Expected Result:** UI adapts smoothly without layout issues.  
  - **Actual Result:** Responsive across common resolutions; breaks only on exotic sizes.

- **Test Case 10 – Access to Restricted Features**  
  - **Objective:** Verify role-based access control for Admin vs Standard users.  
  - **Expected Result:** Admin sees admin panel; standard user does not.  
  - **Actual Result:** Permissions enforced correctly between roles.

- **Test Case 11 – Performance on Data Queries**  
  - **Objective:** Measure response times on large data queries.  
  - **Expected Result:** Queries return within acceptable timeframe (<5s).  
  - **Actual Result:** Slight delay due to server, but within acceptable limits.

- **Test Case 12 – Email Integration**  
  - **Objective:** Test email notification via SMTP.  
  - **Expected Result:** Emails dispatched and received correctly.  
  - **Actual Result:** SMTP not configured; emails cannot be sent.

- **Test Case 14 – Task Creation**  
  - **Objective:** Ensure tasks can be created with required fields.  
  - **Expected Result:** Task created when subject, status, and priority provided.  
  - **Actual Result:** Task creation succeeded without issues.

- **Test Case 15 – Task Assignment**  
  - **Objective:** Test assigning tasks and notification triggers.  
  - **Expected Result:** Assigned users receive task notifications.  
  - **Actual Result:** Assignment worked; notifications not tested due to UI complexity.

- **Test Case 16 – Notification Generation**  
  - **Objective:** Verify system notifications on record actions.  
  - **Expected Result:** Real-time notifications displayed.  
  - **Actual Result:** Only activity logs appear; no visible notifications.

- **Test Case 17 – Custom Report Generation**  
  - **Objective:** Validate custom report builder feature.  
  - **Expected Result:** Generate multi-record reports with filters.  
  - **Actual Result:** No dedicated report interface; CSV/PDF export only.

- **Test Case 18 – Report Export**  
  - **Objective:** Ensure reports export to PDF/Excel properly.  
  - **Expected Result:** Bulk export supported in both formats.  
  - **Actual Result:** CSV bulk export works; PDF single-record only; no Excel.

- **Test Case 19 – Browser Compatibility**  
  - **Objective:** Test in Chrome, Firefox, Edge, Safari, etc.  
  - **Expected Result:** System functions across all modern browsers.  
  - **Actual Result:** Works on all but Chrome on Android 4.4 KitKat.

- **Test Case 20 – Required Fields Validation**  
  - **Objective:** Verify required field enforcement across modules.  
  - **Expected Result:** System blocks saving incomplete records with error.  
  - **Actual Result:** Validation enforced correctly in all tested modules.

- **Test Case 21 – Sales Module Integration**  
  - **Objective:** Test creation/management of sales opportunities.  
  - **Expected Result:** Sales module available and integrated with Contacts/Tasks.  
  - **Actual Result:** Sales module missing; functionality unavailable.

- **Test Case 22 – System Logs and Audit Verification**  
  - **Objective:** Validate logging and audit of user actions.  
  - **Expected Result:** Unified log interface for actions and errors.  
  - **Actual Result:** Activity logs and error logs exist separately; no unified view.

## Quantitative Test Table

| Test # | Title                                 | Status    | Observations                                                   |
|-------:|--------------------------------------:|----------:|----------------------------------------------------------------|
|      1 | Valid Login with Correct Credentials  | Approved  | —                                                              |
|      2 | Invalid Login Attempt                | Approved  | —                                                              |
|      3 | Create New Contact                   | Approved  | —                                                              |
|      4 | Edit Existing Contact                | Approved  | —                                                              |
|      5 | Delete Contact                       | Approved  | —                                                              |
|      6 | Search Records                       | Approved  | —                                                              |
|      7 | Data Import Functionality            | Approved  | Minor UI scrolling bug                                         |
|      8 | Data Export Functionality            | Approved  | PDF export limited to single record                            |
|      9 | Interface Responsiveness             | Approved  | Breaks only at exotic resolutions                              |
|     10 | Access to Restricted Features        | Approved  | —                                                              |
|     11 | Performance on Data Queries          | Approved  | Slight server delay                                            |
|     12 | Email Integration                    | Rejected  | SMTP not configured                                            |
|     14 | Task Creation                        | Approved  | —                                                              |
|     15 | Task Assignment                      | Rejected  | Notifications not tested; UI complexity                        |
|     16 | Notification Generation               | Rejected  | Only activity logs, no visible notifications                  |
|     17 | Custom Report Generation             | Rejected  | No dedicated report interface; export only                     |
|     18 | Report Export                        | Rejected  | CSV OK; PDF single; no Excel                                  |
|     19 | Browser Compatibility                | Approved  | Failure on Android 4.4 KitKat                                  |
|     20 | Required Fields Validation           | Approved  | —                                                              |
|     21 | Sales Module Integration             | Rejected  | Module missing                                                 |
|     22 | System Logs and Audit Verification    | Rejected  | Fragmented logs                                                |

## Conclusions

Overall, SuiteCRM demonstrates essential CRM capabilities such as user authentication, contact and task management, data import/export, and cross-browser compatibility. However, the software is still in an emergent state, exhibiting several limitations:

- **Missing Features:** Sales module is unavailable; email integration is unconfigured.
- **Limited Export/Reporting:** No true custom report builder; PDF export restricted to single records; no Excel support.
- **User Experience Issues:** Interface scrolling and UI pathways are unintuitive in import and notification modules.
- **Fragmented Logging:** Activity and error logs are separated without a unified audit view.
- **Performance Constraints:** Server response delays under heavy queries, though within acceptable limits.

**Recommendations:**
1. Implement a dedicated report builder with multi-record PDF and Excel export.
2. Configure and integrate SMTP mail services for email notifications.
3. Develop and enable a Sales/Opportunities module to support full sales workflows.
4. Consolidate logging into a unified audit interface for better traceability.
5. Refine UI elements and workflows for import, notifications, and task assignment.
6. Optimize server performance to reduce query response times further.

In conclusion, while SuiteCRM provides core CRM functionalities, it requires significant enhancements to reporting, notifications, module availability, and user experience to meet enterprise-grade standards.