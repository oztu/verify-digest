# verify-digest

A single-page application for message digest verification. Uses the [crypto.subtle API](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto) to generate SHA-1, SHA-256, SHA-384, and SHA-512 digests and the [SparkMD5](https://github.com/satazor/SparkMD5) library to generate md5 digests of given files.

As of February 2014 Chrome 37+ and Opera 26+ have the native API nescessary for this application to work.