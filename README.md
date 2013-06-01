zipfile.js
==========

Unzip files from .zip archives in JavaScript.

Pass the .zip file to the constructor as an ArrayBuffer. read() will return an Uint8Array of the uncompressed data for each file. I didn't add an API to list files yet because my use case didn't need it. Patches welcome!
