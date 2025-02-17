# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field by a specified value.  However, if a string value is provided instead of a number, it will not increment correctly, potentially resulting in unexpected behavior or errors.

The `bug.js` file contains the erroneous code, and the `bugSolution.js` file shows the corrected version.
