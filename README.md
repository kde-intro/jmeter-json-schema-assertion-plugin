# JSON Schema Assertion component for Apache JMeter
This component allows the user to validate a response against an JSON Schema.

![Screenshot for Control-Panel of JSON Schema Assertion](/JSONSchemaAssertion.png)

### Parameters
Attribute | Description | Required
------------ | ------------- | -------------
_Name_ | Descriptive name for this element that is shown in the tree. | No
_File Name_ | Specify JSON Schema File Name. | Yes


## Installation
1. Checkout the source.
2. Build extension - create _jar_ file by running Maven build _package_ (cli: _mvn package_).
3. Put the generated jar file (Custom_JsonSchemaAssertion_component.jar) from _target_ folder to JMeter _JMeter home directory/lib/ext/_ directory.


## Notes
- This assertion are costly and avoid using it during load tests.
- This product includes https://github.com/daveclayton/json-schema-validator (LGPLv3 (or later), ASL 2.0).


## Tasks List
- [x] Create Maven version (plugin).
- [x] Add test class JSONSchemaAssertionTest.
- [x] Add flag schema/response.
- [ ] Add schema validation on click (add the button).


## Changelog
**v0.1**, _06 mar 2017_
  - [created] Initial release.
  
**v0.2**, _23 mar 2017_
  - [fixed] Failure message for the validation error cases.
  - [added] Object flag of the source error (response/schema) into failure message.

**v0.3**, _26 mar 2017_
  - [fixed] Failure message in cases of the object flag using.

**v0.4**, _14 jun 2017_
  - [added] Support of passing json schema by variable and string at the parameter 'File Name'. _You can pass a path or json schema by variable or property. For example you can use Variable definition panel to describe json schema and pass it to the assertion into File Name parameter as the variable._


## Roadmap
- [ ] Add schema generation (from/based on a response).
- [ ] Unify JSON & XML Schema Assertions and add the protocol type switcher (add radio-box / autodetection?).
- [x] Add support of variables / properties - pass json schema by variable (or/and properties).


## Troubleshooting


## Support

