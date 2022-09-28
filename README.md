database
========

## Schema

Available in [tables.sql](tables.sql) file.

## UML

**NOTE: THIS DIAGRAM IS OUT-OF-DATE AND NEEDS UPDATING TO REFLECT THE LATEST V15 DATABASE**

![ER diagram](tables.png)

Relations not implemented at SQL level:

* CUSTOMFIELDDATA.REFID (depends on CUSTOMFIELD.REFTYPE)
* ATTACHMENT.REFID (depends on ATTACHMENT.REFTYPE)
* TRANSLINK.LINKRECORDID (depends on TRANSLINK.LINKTYPE)

## Initialization

Initial category / subcategory hierarchy:

* Bills
  * Telephone
  * Electricity
  * Gas
  * Internet
  * Rent
  * Cable TV
  * Water
* Food
  * Groceries
  * Dining out
* Leisure
  * Movies
  * Video Rental
  * Magazines
* Automobile
  * Maintenance
  * Gas
  * Parking
  * Registration
* Education
  * Books
  * Tuition
  * Others
* Homeneeds
  * Clothing
  * Furnishing
  * Others
* Healthcare
  * Health
  * Dental
  * Eyecare
  * Physician
  * Prescriptions
* Insurance
  * Life
  * Home
  * Health
  * Auto
* Vacation
  * Travel
  * Lodging
  * Sightseeing
* Taxes
  * Income Tax
  * House Tax
  * Water Tax
  * Others
* Miscellaneous
* Gifts
* Income
  * Salary
  * Reimbursement/Refunds
  * Investment Income
* Other Income
* Other Expenses
* Transfer
