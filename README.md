# JavaScript Bug: Handling undefined in length checks

This repository demonstrates a common JavaScript error: attempting to access the `length` property of an undefined variable.  The `bug.js` file contains the erroneous code, which throws a `TypeError`. The `bugSolution.js` file provides a corrected version.

The bug arises from not explicitly checking for `undefined` before accessing the `length` property.  The solution involves adding a check for `undefined` to prevent the error.

## How to reproduce the bug:

1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js`.

## Solution:

The solution is to check for both `null` and `undefined` values before attempting to access the `length` property.  See `bugSolution.js` for the corrected code.