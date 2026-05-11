## FECfile+ Release Notes

# May 14, 2026 (Sprint 85)

## Feature updates:

- Updated default itemization logic for Joint Fundraising Transfer memos. [FECFILE-3043](https://fecgov.atlassian.net/browse/FECFILE-3043)

## Design (UX/UI) enhancements:

- Report Details page now displays reporting frequency before time period. [FECFILE-2905](https://fecgov.atlassian.net/browse/FECFILE-2905)
- Left navigation pane updated to float while scrolling on right. [FECFILE-2897](https://fecgov.atlassian.net/browse/FECFILE-2897)
- System provides a warning message when the API is unavailable on the login screen or while a user is logged in. [FECFILE-3012](https://fecgov.atlassian.net/browse/FECFILE-3012), [FECFILE-2014](https://fecgov.atlassian.net/browse/FECFILE-2014)
- Additional minor UX/UI updates [FECFILE-2945](https://fecgov.atlassian.net/browse/FECFILE-2945), [FECFILE-2947](https://fecgov.atlassian.net/browse/FECFILE-2947), [FECFILE-2993](https://fecgov.atlassian.net/browse/FECFILE-2993), [FECFILE-3028](https://fecgov.atlassian.net/browse/FECFILE-3028), [FECFILE-3036](https://fecgov.atlassian.net/browse/FECFILE-3036), [FECFILE-3052](https://fecgov.atlassian.net/browse/FECFILE-3052), [FECFILE-3061](https://fecgov.atlassian.net/browse/FECFILE-3061)

## Bug fixes:

- Resolved issue preventing users from submitting feedback through the Feedback Tab.  [FECFILE-3097](https://fecgov.atlassian.net/browse/FECFILE-3097)
- Validation message for Date Received field now displays at the appropriate time. [FECFILE-3081](https://fecgov.atlassian.net/browse/FECFILE-3081)
- Calendar datepicker no longer opens after clicking the Close button on a modal for dates outside report coverage dates. [FECFILE-3082](https://fecgov.atlassian.net/browse/FECFILE-3082)
- "Add a second committee administrator" modal no longer persists after clicking browser back button. [FECFILE-3090](https://fecgov.atlassian.net/browse/FECFILE-3090)
- "Terms of service and user agreement" page numbering has been removed. [FECFILE-3106](https://fecgov.atlassian.net/browse/FECFILE-3106)

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

# April 30, 2026 (Sprint 84)

## Feature updates:

- Allow users to change contact type when creating a new contact in a transaction. [FECFILE-2747](https://fecgov.atlassian.net/browse/FECFILE-2747)
- Display the report version, Original or Amendment #, within a report. [FECFILE-2754](https://fecgov.atlassian.net/browse/FECFILE-2754)
- Earmark Receipt and Memo should only be itemized when entity (contact) aggregate is > $200 per calendar year. [FECFILE-2866](https://fecgov.atlassian.net/browse/FECFILE-2866)
- For Reattribution and Redesignation, display a message that there are no in-progress reports available to choose when applicable.  [FECFILE-2956](https://fecgov.atlassian.net/browse/FECFILE-2956)

## Design (UX/UI) enhancements:

- Improved calendar date selection through enhanced date picker navigation using forward and back buttons for month and year. [FECFILE-1870](https://fecgov.atlassian.net/browse/FECFILE-1870)
- Additional minor UI updates. [FECFILE-2966](https://fecgov.atlassian.net/browse/FECFILE-2966), [FECFILE-3030](https://fecgov.atlassian.net/browse/FECFILE-3030), [FECFILE-3065](https://fecgov.atlassian.net/browse/FECFILE-3065), [FECFILE-3018](https://fecgov.atlassian.net/browse/FECFILE-3018), [FECFILE-3051](https://fecgov.atlassian.net/browse/FECFILE-3051)

## Bug fixes:

- Save & Add Another option now available for selection on the 2nd transaction created. [FECFILE-3023](https://fecgov.atlassian.net/browse/FECFILE-3023)
- Form 24: Validation error now updating as expected for Linked Report field. [FECFILE-3050](https://fecgov.atlassian.net/browse/FECFILE-3050)
- Report name on F99 and F1M now links to form edit page instead of transaction page. [FECFILE-3068](https://fecgov.atlassian.net/browse/FECFILE-3068)

## System performance and security:

- Several performance and security enhancements are included in this release.
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

----
