Simple Object Designer - Release Notes
======================================

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


