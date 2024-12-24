# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug involving unexpected type coercion when using loose equality (`==`) with `null`.  The code in `bug.js` incorrectly handles `null` values due to the use of `==` instead of strict equality (`===`).  The corrected code is provided in `bugSolution.js`.

## Problem

JavaScript's loose equality operator (`==`) performs type coercion before comparison, leading to potentially unexpected results. When comparing `null` with `==`, it can lead to incorrect boolean evaluation and logic errors.

## Solution

The solution is to always use strict equality (`===`) when comparing values in JavaScript. This prevents type coercion and ensures that comparisons are accurate.
