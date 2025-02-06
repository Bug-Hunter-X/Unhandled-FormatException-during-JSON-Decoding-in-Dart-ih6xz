# Unhandled FormatException in Dart JSON Decoding

This example demonstrates a common error in Dart applications when handling JSON responses from network requests. The code attempts to decode a JSON response, but does not handle the potential `FormatException` that can occur if the response is not valid JSON. This can lead to unexpected crashes.

The `bug.dart` file contains the buggy code, while `bugSolution.dart` shows how to correctly handle the exception using a `try-catch` block.