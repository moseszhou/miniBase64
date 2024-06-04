# str-base64
## Base64 Encoding and Decoding Library
This JavaScript library provides methods to encode and decode strings using Base64 encoding. The library includes functions to handle UTF-8 encoding and decoding to ensure proper encoding of Unicode characters.

## Features
Base64 Encoding: Convert a string to its Base64 encoded representation.
Base64 Decoding: Convert a Base64 encoded string back to its original representation.
UTF-8 Encoding: Convert a string to its UTF-8 encoded representation (internal use).
UTF-8 Decoding: Convert a UTF-8 encoded string back to its original representation (internal use).
## Usage
### Importing the Library
You can import the Base64 library in your JavaScript project:

```js
import { Base64 } from 'str-base64';
```
### Creating an Instance
Create an instance of the Base64 class:

```js
const base64 = new Base64();
```
### Encoding a String
Use the encode method to encode a string to Base64:

```js
const encodedString = base64.encode('Hello, World!');
console.log(encodedString); // Outputs: "SGVsbG8sIFdvcmxkIQ=="
```
### Decoding a String
Use the decode method to decode a Base64 encoded string:

```js
const decodedString = base64.decode('SGVsbG8sIFdvcmxkIQ==');
console.log(decodedString); // Outputs: "Hello, World!"
``` 
## License
This library is released under the MIT License. Feel free to use, modify, and distribute it as needed.

This README provides an overview of the Base64 library, including its features, usage instructions, and the complete source code for reference.