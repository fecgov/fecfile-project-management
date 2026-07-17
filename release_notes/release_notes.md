## FECfile+ Release Notes

# July 23, 2026 (Sprint 90)

## Feature updates:

- When creating an individual (IND) contact within a transaction, a warning message is returned if a contact already exists with the same last name and first name and the contact can be selected for use in the transaction.
- When creating an organization (ORG) contact within a transaction, a warning message is returned if a contact already exists with the same organization name and the contact can be selected for use in the transaction.
- When creating a new contact within a transaction, the contact can be saved without saving the transaction.
- When generating a .fec file for Form 3X/3 report types 12P, 12G, 12R, 12S and 12C, the election code will be included.


## Design (UX/UI) enhancements:

- Minor UX/UI updates for 508 remediation are included in this release.

## Bug fixes:

N/A

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# July 9, 2026 (Sprint 89)

## Feature updates:

- Updated system-generated purpose text and logic for Credit Card, Staff Reimbursement and Payment to Payroll Disbursement transactions on Schedules B & E, as well as Partnership Receipt transactions on Schedule A to be based on the existence of linked memo transactions and whether those transactions are itemized.
- Updated Form 24 independent expenditure entry to prevent linking to a submitted Form 3X report.
- Updated Form 24 to provide ability to edit report type (24-hour or 48-hour).

## Design (UX/UI) enhancements:

- Minor UX/UI updates are included in this release.

## Bug fixes:

- In a Form 99, Filing Frequency Change Notice, the Quarterly / Monthly toggle now clears if the document type is changed to Form 3L Filing Frequency Change Notice (and vice versa).
- When viewing a submitted report, the Report Status option in the left navigation bar now reloads the status page.

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# June 25, 2026 (Sprint 88)

## Feature updates:

- N/A

## Design (UX/UI) enhancements:

- Form 3X Schedule A transaction name and page header "Refund of Receipts from Unregistered Organization"  updated to "Refund of Receipt from Unregistered Organization".
- Additional minor UX/UI updates are also included in this release.

## Bug fixes:

- Form 99 can now be saved after initially selecting Filing Frequency Change Notice then changing to different document type.
- Duplicate ID validation errors now trigger instantly when selecting a committee or candidate ID from the lookup, fixing a bug where the error was delayed until trying to save.

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# June 11, 2026 (Sprint 87)

## Feature updates:

- Form 99 Document Type options were updated for Miscellaneous Electronic Submission to the FEC and C-1/Loan Agreement. Form 99 Document Type now includes two additional options of Loan Forgiveness and Debt Settlement Plan. This conforms to the FEC's updated electronic filing specifications.
- Schedule C loan transactions with an interest rate (%) will be divided by 100 when generating the .fec file. This conforms to the FEC's electronic filing specifications.
- When creating or editing a Form 3X Year-End (YE) report in an election year, the coverage start date now defaults to blank. A user is required to manually enter in the date.

## Design (UX/UI) enhancements:

- Form 24 updated to require unique report name entry after the report type (24-Hour or 48-Hour).
- Form 3X Schedule A transaction name "Refund of Unregistered Receipt from Person" updated to "Refund of Receipt from Unregistered Organization".
- Additional minor UX/UI updates are also included in this release.

## Bug fixes:

- Unamend is no longer allowed for submitted reports.

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# May 28, 2026 (Sprint 86)

## Feature updates:

- Updated Form 99 document type labels to “Miscellaneous Electronic Submission to the FEC” and “C-1/Loan Agreement” in the drop-down selection list.
- Added functionality to create a Form 99 document type for “Loan Forgiveness” or “Debt Settlement Plan".
- Added the “Edit Name” option to the Actions menu in the “Manage users” page to allow users to edit their own profile name.

## Design (UX/UI) enhancements:

- Form 3X Schedule A transaction names and page headers updated from "Receipt from Unregistered Entity"and "Receipt from Unregistered Entity - Returned/Bounced Receipt" to "Receipt from Unregistered Organization" and "Receipt from Unregistered Organization - Returned/Bounced Receipt".
- Additional minor UX/UI updates are also included in this release.

## Bug fixes:

- Resolved page display issue when selecting the "An official website of the United States government Here's how you know" link.
- Committee ID search box now transforms manually entered characters to uppercase.
- Resolved issue that allowed for multiple clicking of the "Save and Add Another” button which resulted in multiple pop-up messages. 
- Resolved issue where some icons were not appearing when using Firefox browser (ex. date picker forward/backward arrows).
- Removed aggregate display and calculation on Conduit Earmarks and PAC Conduit Earmarks transaction pages and in the .fec file.
- Reports can now be amended multiple times, not just for the first amendment.

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# May 14, 2026 (Sprint 85)

## Feature updates:

- Updated default itemization logic for Joint Fundraising Transfer memos to no longer itemize regardless of amount. Joint Fundraising Transfer memos will now be itemized based on the contributor's reported aggregate total.

## Design (UX/UI) enhancements:

- Reports Details page now displays filing frequency above election year and non-election year options when creating or editing a report.
- Left navigation pane updated to float while scrolling on right. 
- System provides a warning message when the API is unavailable on the login screen or while a user is logged in. 
- Additional minor UX/UI updates.

## Bug fixes:

- Resolved issue preventing users from submitting feedback through the Feedback Tab. 
- Validation message for Date Received field now displays at the appropriate time.
- Calendar datepicker no longer opens after clicking the Close button on a modal for dates outside report coverage dates.
- "Add a second committee administrator" modal no longer persists after clicking browser back button. 
- "Terms of service and user agreement" page numbering has been removed.

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# April 30, 2026 (Sprint 84)

## Feature updates:

- Allow users to change contact type when creating a new contact in a transaction.
- Display the report version, Original or Amendment #, within a report.
- Earmark Receipt and Memo should only be itemized when entity (contact) aggregate is > $200 per calendar year. 
- For Reattribution and Redesignation, display a message that there are no in-progress reports available to choose when applicable.

## Design (UX/UI) enhancements:

- Improved calendar date selection through enhanced date picker navigation using forward and back buttons for month and year.
- Additional minor UI updates. 

## Bug fixes:

- Save & Add Another option now available for selection on the 2nd transaction created.
- Form 24: Validation error now updating as expected for Linked Report field. 
- Report name on F99 and F1M now links to form edit page instead of transaction page. 

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

----
