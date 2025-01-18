# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numeric field by a specified value.  However, if the value provided is not a number (e.g., a string), the update may fail silently or produce unexpected results.

**Bug:** The provided JavaScript code incorrectly uses a string value with the `$inc` operator. This can result in the update failing without any explicit error message. 

**Solution:** Ensure the value provided to `$inc` is always a number to correctly update the field.
