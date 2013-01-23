# ABAP Object-oriented programming Library
## Summary
This library is a collection of ABAP classes and frameworks.  
Dictionary, message, etc. components are not included, since these cannot be easily transferred to GitHub.  

## Contents
### /collections
Contains a port of the Java 1.4.2 Arraylist.

### /csv
CSV parser which delegates the collection of found values.

### /json
Serialize and deserialize JSON structures.

### /lang
A cl_object class to replace ABAP's default object, and a utility class providing bitwise operations.

### /logging
Simple logging service which uses SAP's application log functionality. Allows asynchronous logging (through a built-in RESTful service), which means you'll never lose your log, even on dumps.

### /oauth
OAuth 1.0 server module. Allows you to authenticate to SAP with OAuth. Administration tools etc. included. The entire protocol is implemented, except for signatures only HMAC-SHA1 is supported.

### /rest
Framework which allows you to quickly create RESTful webservices.

### /unittest
Unit tests for the arraylist and json package

### /xml
XML parser which delegates the collection of found values.
