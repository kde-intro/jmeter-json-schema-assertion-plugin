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

This assertion are costly and avoid using its during load tests.


## Tasks List
- [x] Create Maven version (plugin)
- [x] Add test class JSONSchemaAssertionTest
- [ ] Resolve (two) issues
- [ ] Add flag schema/response
- [ ] Add textarea for JSON Schema


## Changelog


## Roadmap

## Troubleshooting

## Support

