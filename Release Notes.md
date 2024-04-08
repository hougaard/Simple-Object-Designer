Simple Object Designer - Release Notes
======================================

11.0.0.422 - Released to AppSource
==================================
* Support for Microsoft's AL compiler

10.0.0.417 - Released to AppSource
==================================
* Query Support
* Lots of new field transfers
* Standard factboxes on features

9.0.0.311 - Released to AppSource
=================================
* Field Groups
* Field Sorting
* Calculated fields can now handle division by zero and empty dates in CalcDate()
* Calculated fields detect flowfields and re-calculate them
* Mandatory fields calculate flowfields on subtables before checking them
* Even more Field Transfers

9.0.0.282 - Released to AppSource
=================================
* Create calculated fields on pages
* Fixed symbols issues

8.0.0.262 - Released to AppSource
=================================
* Create Mandatory Fields conditions

7.0.0.245 - Released to AppSource
=================================
* Store app defintion inside .app file and allow that to be used in "Import App"
* Allow changing options members (with Force Deploy)
* Better analysis for dependencies to other extensions
* Features with a list page gets that assigned as lookup page
* Support for FlowFields
* Support for filtered Lookup fields (supporting lookup into table multiple fields in the primary key
* More symbols tuning
* Allow Symbol download with a delegate admin account
* DrilldownPageId added to flowfields

6.0.0.213 - Released to AppSource
=================================

* Create APIs for (some) Codeunits 
* Major Symbol cleanup

5.0.0.197 - Released to AppSource
=================================
* GitHub and AL-Go! Integration

5.0.0.139 - Released to AppSource
=================================
* Support for creating RoleCenters

4.0.0.117 - Released to AppSource
=================================
* First release with support for creating new tables

4.0.0.118
=========
* New Field Transfer Item Category->Item

4.0.0.119
=========
* Added ExtendedDataType property to new fields and features
* Fix bug regarding customizations on deleted tables
* Start Object Number in Setup must be over 50.000

4.0.0.121 - Released to AppSource
=================================
* Fixed bugs regarding customization on deleted fields
* Prevent treating fields added as "existing fields"
* Changed how list are called to allow filters on field pages
* "Init New App" could create "leftovers" in field properties

4.0.0.123 - Released to AppSource
=================================
* Fixed bug regarding symbols vs
* Added support for exposing APIs to use the secondary readonly database for optimal read performance without impacting the produciton environment.

4.0.0.126 - Released to AppSource
=================================
* Typo on registration page
* Add check to ensure primary keys with number series are Code[20]
* Fixed deployment error when a existing without customization were included in the extension.

4.0.0.127 - Released to AppSource
=================================
* Fixed bug where API page using fields from a different extension could result in an missing dependency error

4.0.0.129 - Released to AppSource
=================================
* Added Fixed Asset and Service Item as anchor tables for the data-related template
* Add tooltip support for new fields and features.

4.0.0.131 - Released to AppSource
=================================
* Fixed bug where Line fields could be placed on head list page
* Added quotes to fields named "area", "field", "group", and "layout"
* Added check for duplciate field names

4.0.0.135 - Released to AppSource
=================================
* Prevent users from creating SystemId (and other System fields)
* Prevent usage of special characters in publisher name
* Fixed bug for missing fields on List pages
* Fix for app.json missing commas
* Fix for fields named "id" in APIs

