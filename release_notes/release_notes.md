## FECfile+ Release Notes

# May XX, 2026 (Sprint 86)

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
