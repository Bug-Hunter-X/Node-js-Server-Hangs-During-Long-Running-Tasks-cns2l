# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js where long-running operations can cause the server to hang, making it unresponsive to new requests.

The `server.js` file contains a simple HTTP server with a long-running task that simulates a CPU-bound process.  This causes the server to become unresponsive for approximately 5 seconds, preventing it from processing any new requests.

The `serverSolution.js` file offers a solution utilizing asynchronous programming techniques and potentially worker threads to prevent server hangs.