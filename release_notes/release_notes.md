## FECFile Release Notes

# March 12, 2025 (Sprint 57)

## Feature updates:

- Schedule E: Auto-populate of the Treasurer details on the on all Schedule E transaction displays. [FECFILE-593](https://fecgov.atlassian.net/browse/FECFILE-593) 

## Design (UX/UI) enhancements:

- There were no design enhancements included in this release

## Bug fixes:

- When creating a Form 3x monthly report March 20 the covering period is incorrect. This has been resolved. [FECFILE-2062](https://fecgov.atlassian.net/browse/FECFILE-2062)
- Aggregate calculation (for Schedule A) not working as expected. This has been resolved [FECFILE-2044](https://fecgov.atlassian.net/browse/FECFILE-2044)
- Your Downloads tray (window/drawer) not collapsing when changing pages. This was corrected. [FECFILE-2039](https://fecgov.atlassian.net/browse/FECFILE-2039)
- Print preview error when itemization on receipt transaction was manually changed This has been resolved. [FECFILE-1991](https://fecgov.atlassian.net/browse/FECFILE-1991) 

## System performance and security:

- Several performance and security enhancements are included in this release
  
_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

----

# February 28, 2025 (Sprint 56)

## Feature updates:

- Roles and Permissions: Added user role of Manager. Committee Administrator can add or update the role of a user as a Manager  [FECFILE-1840](https://fecgov.atlassian.net/browse/FECFILE-1840), [FECFILE-1846]( https://fecgov.atlassian.net/browse/FECFILE-1846), [FECFILE-1886]( https://fecgov.atlassian.net/browse/FECFILE-1886)

## Design (UX/UI) enhancements:

- No Design (UX/UI) enhancements in this sprint

## Bug fixes:

- No bugs or defects in this sprint

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

----

# February 18, 2025 (Sprint 55)

## Feature updates:

- Report Workflow: For Form 3X, remove delete function from receipt transactions created by loans. [FECFILE-1829](https://fecgov.atlassian.net/browse/FECFILE-1829) 
- Form 3: Add Form 3 to the report selection (behind a feature flag so that it is currently only visible in DEV and STAGE [FECFILE-422](https://fecgov.atlassian.net/browse/FECFILE-422)
- Form 3X: Schedule C: System will now delete loans and debts in future reports when the loan or debt is paid off in the current reporting period [FECFILE-1662](https://fecgov.atlassian.net/browse/FECFILE-1662)
- Login Management and Workflow: System will update email address in application when email is updated in login.gov and system will recognize when a user logs in with a new login.gov account, but having the same email address as a user in the system [FECFILE-1988]( https://fecgov.atlassian.net/browse/FECFILE-1988), [FECFILE-1989]( https://fecgov.atlassian.net/browse/FECFILE-1989)

## Design (UX/UI) enhancements:

- No Design (UX/UI) enhancements in this sprint

## Bug fixes:

- No bugs or defects in this sprint

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._

----
# January 15, 2025 (Sprint 52)

## Feature updates:

- For Form 3X, Update January 1 Cash on Hand to look back to the most recent report from a prior year [FECFILE-1770](https://fecgov.atlassian.net/browse/FECFILE-1770) 

## Design (UX/UI) enhancements:

- Several 508 Compliance issues were corrected, to provide consistent styling and updates to correct some issues with screen readers.  [FECFILE-392](https://fecgov.atlassian.net/browse/FECFILE-392), [FECFILE-1768](https://fecgov.atlassian.net/browse/FECFILE-1768), [FECFILE=1841](https://fecgov.atlassian.net/browse/FECFILE-1841), [FECFILE-1832](https://fecgov.atlassian.net/browse/FECFILE-1832), [FECFILE-1833](https://fecgov.atlassian.net/browse/FECFILE-1833) 


## Bug fixes:

- When the date popup appeared on an In-kind transaction was cleared, the vertical scroll bar on the web browser disappeared. This was corrected. [FECFILE-1718](https://fecgov.atlassian.net/browse/FECFILE-1718)
- When creating an In-kind receipt transaction, if the above date error was later cleared, the In-kind Out was still displaying the date error popup. This has been resolved. [FECFILE-1719](https://fecgov.atlassian.net/browse/FECFILE-1719)
- When a Tier 1 Independent Expenditure on Form 3X is assigned to a Form 24, if that transaction had a linked Tier 2, the linked transaction was not also brought over to the Form 24. [FECFILE-1767](https://fecgov.atlassian.net/browse/FECFILE-1767)
- The ‘Transaction Delete’ function was not available on Loan and Debt repayment transactions, so those transactions could not be deleted. The ‘Delete’ function has been restored to those transactions. [FECFILE-1830](https://fecgov.atlassian.net/browse/FECFILE-1830)
- The ‘Official Website of the US’ Banner was not collapsing when going to other pages after it had been expanded once [FECFILE-1835](https://fecgov.atlassian.net/browse/FECFILE-1835)
- When adding or updating a contact, if the user clicks in the (Optional) Phone field, the system flagged this as an error and did not allow the user to save the contact or the transaction. This is resolved. [FECFILE-1861](https://fecgov.atlassian.net/browse/FECFILE-1861)
-  The Date Signed field on the Form 3X print preview was not being populated. This has been corrected and will display the date after the report has been submitted. [FECFILE-1874](https://fecgov.atlassian.net/browse/FECFILE-1835)
- Date Received field for both Schedule A and Schedule B transactions was not displaying "This is a required field" if it was left blank. [FECFILE-1880](https://fecgov.atlassian.net/browse/FECFILE-1880) 

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._




----

# December 4, 2024 (Sprint 51)

## Feature updates:

- Report Workflow: For Form 3X, remove default report coverage dates from election and special election reports which do not have non-standard dates and alert users to always validate the report coverage dates for the reports where the dates are usually standard monthly or quarterly dates. [FECFILE-1604](https://fecgov.atlassian.net/browse/FECFILE-1604) , [FECFILE-1605](https://fecgov.atlassian.net/browse/FECFILE-1605)
- Contact Management: Updated rules to always display ‘00’ for candidates in single district states and at-large districts [FECFILE-1686](https://fecgov.atlassian.net/browse/FECFILE-1686)

## Design (UX/UI) enhancements:

- Updated user profile page so that names are now populated and entered in ‘First Name’ and ‘Last Name’ order [FECFILE-1690](https://fecgov.atlassian.net/browse/FECFILE-1690)
- Updated input field sizes for fields on the Account Information Page to be more consistent with all other forms on the site. [FECFILE-1758](https://fecgov.atlassian.net/browse/FECFILE-1758)
- Updated stock images throughout the site [FECFILE-1772](https://fecgov.atlassian.net/browse/FECFILE-1772)

## Bug fixes:

- When creating a Loan, the Date Due and Interest Rate fields were not being updated or saved correctly if non-standard dates or rates were entered. This has been resolved. [FECFILE-1786](https://fecgov.atlassian.net/browse/FECFILE-1786)
- First Name and Last Name of Committee Treasurer were populating in reverse when creating a Loan transaction. This has been corrected, and the displayed fields have also been reversed, so it displays as First Name, Last Name. [FECFILE-1756](https://fecgov.atlassian.net/browse/FECFILE-1756)
- On Independent Expenditures, the Candidate District was ‘read only’ if the Candidate Office was ‘House’. That has been updated to now be editable. [FECFILE-1746](https://fecgov.atlassian.net/browse/FECFILE-1746)
- When saving an In-kind Contribution to Candidate, the system would try to save the candidate name as the organization. This has been resolved. [FECFILE-1649](https://fecgov.atlassian.net/browse/FECFILE-1649) 

## System performance and security:

- Several performance and security enhancements are included in this release

_For a more detailed look at what has changed, refer to the technical release notes for our code repositories: [fecfile-web-app](https://github.com/fecgov/fecfile-web-app/releases), [fecfile-web-api](https://github.com/fecgov/fecfile-web-api/releases), [fecfile-api-proxy](https://github.com/fecgov/fecfile-api-proxy/releases), [fecfile-validate](https://github.com/fecgov/fecfile-validate/releases)._
