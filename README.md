# salesforce-canvas-request

A utility library to support external applications run as Salesforce Canvas using a Node.js backend

## Prerequisites

* [Node.js](https://nodejs.org/en/) >= 8.9.0

## Utilities

### verify(signed_request: String, secret: String) : Object

#### Parameters

* **signed_request**: The full signed request as passed to Canvas to your web API
* **secret**: Your Canvas App's Consumer Secret defined in Salesforce

#### Returns

* The decoded JSON provided by Canvas

## License

MIT


