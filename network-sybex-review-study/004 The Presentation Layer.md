# The Presentation Layer (Layer 6)
<hr>
- The Presentation Layer presents data to the Application Layer

- This Layer is responsible for Encryption/Decryption, Translation and Compression/Decompression

- When a stream of data comes from the lower layers, this layer is responsible for formatting the data and conevrting it back to the original intended application data

- Examples of Functions:
	
	- TLS (Transport Layer Security) -> The webpage is encrypted at the webserver and sent to the client. When the client receives the data, it is decrypted and sent to the Application Layer
	
	- Translation -> Extended Binary Coded Decimal Interchange Code (EBCDIC) to American Standard for Information Exchange (ASCII) to Unicode

	- Compression/Decompression -> Often referred to as codecs are MP3 to network streaming protocols and H.264 video to streaming protocols

	- JPEG, GIF, PICT and TIFF operate at the presentation layer, by compressing and decompressing images in your web-browser