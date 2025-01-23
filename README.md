# MongoDB Aggregation Pipeline Bug

This repository demonstrates a common error in MongoDB aggregation pipelines involving the `$unwind` and `$group` stages.  The incorrect ordering of these stages leads to unexpected results in the aggregation output.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides the corrected code with proper ordering.  Understanding the correct sequence of these stages is crucial for achieving the desired aggregation results.  Please refer to the MongoDB documentation for detailed explanations of each stage.