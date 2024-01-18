# Encryption-Decryption-algo using Base64
Base64 is a binary-to-text encoding scheme that is commonly used to encode binary data, such as images, audio files, or any other binary content, into a plain text format. It is called "Base64" because it uses a set of 64 characters to represent the binary data.

The Base64 encoding works by breaking the input data into chunks of 3 bytes and then encoding each 3-byte chunk into a set of four printable ASCII characters. These characters are typically A-Z, a-z, 0-9, '+', and '/'. The equal sign '=' may be used as padding at the end of the encoded data to ensure that the length of the encoded data is a multiple of 4.

When you want to transmit or store binary data in a text-based format (such as when sending data in emails or storing data in JSON or XML), you can use Base64 encoding to convert the binary data into a text representation that can be easily handled in those contexts.

In your provided code, Base64 encoding is used to encode and decode the message for the purpose of encryption and decryption.
