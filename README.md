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
2. Create _jar_ file by running Maven build _clean, package_.
3. Put the generated jar file (Custom_JsonSchemaAssertion_component.jar) from _target_ folder to JMeter _JMeter home directory/lib/ext/_ directory.


## Notes
- This assertion are costly and avoid using its during load tests.
- This product includes https://github.com/daveclayton/json-schema-validator (LGPLv3 (or later), ASL 2.0)


## Tasks List
- [x] Create Maven version (plugin)
- [x] Add test class JSONSchemaAssertionTest
- [x] Add flag schema/response
- [ ] Add textarea for a schema
- [ ] Add schema validation by button


## Changelog
**v0.1**, _06 mar 2017_
  - [created] initial release
  
**v0.2**, _23 mar 2017_
  - [fixed] failure message for the validation error cases
  - [added] object flag of the source error (response/schema) into failure message

**v0.3**, _26 mar 2017_
  - [fixed] failure message in cases of the object flag usaging


## Roadmap
- [ ] Add schema generation (from/based on a response)
- [ ] Integrate JSON & XML Scheme Assertions in one component (add radio-box / autodetection ? - protocol type switching)
- [ ] Add support of variables / properties - pass json schema by variable (or/and properties)


## Troubleshooting


## Support

