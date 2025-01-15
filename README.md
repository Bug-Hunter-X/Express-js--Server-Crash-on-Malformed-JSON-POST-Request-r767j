# Express.js: Handling Malformed JSON in POST Requests

This repository demonstrates a common error in Express.js applications: server crashes due to unhandled exceptions when receiving malformed JSON data in POST requests.

The `bug.js` file shows the problematic code. It lacks proper error handling, leading to a crash if the request body is empty or doesn't conform to the expected structure.

The `bugSolution.js` file presents a corrected version with robust error handling to prevent crashes and provide informative error responses to the client.