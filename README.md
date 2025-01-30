# Objective-C Array Index Out of Bounds

This repository demonstrates a common error in Objective-C: accessing an array element with an index that's outside the valid range (0 to array.count - 1).  This often results in a crash. The solution shows how to safely handle potential out-of-bounds indices.

## Bug
The `bug.m` file contains code that attempts to access an array element using an index that exceeds the array's bounds. This leads to an exception and application termination.

## Solution
The `bugSolution.m` file provides a corrected version. It includes checks to ensure the index is within the valid range before accessing the array element, preventing crashes and ensuring robust code.