# Ada: Potential Array Bounds Errors and Unhandled Exceptions

This repository contains examples of potential code errors in Ada, specifically focusing on array handling and exception management. The `bug.ada` file showcases code that could be prone to runtime errors if not carefully handled, while `bugSolution.ada` demonstrates the improved code with these issues addressed.

**Key Issues Addressed:**

* **Array Bounds Checking:** Ada's strong typing system generally prevents array out-of-bounds errors at compile time. However, dynamic array manipulation or issues with loop index range can still lead to problems. 
* **Exception Handling:** The example includes an improved `exception` block that is more robust and informative than simple "Error" messages.  Robust error handling can lead to better debugging.

**How to Reproduce the Issues (in `bug.ada`):** 

Modify the loop limits or array index access in `bug.ada` to intentionally cause an out-of-bounds access.  The original code prevents this error, however, a modified version could demonstrate the problem. Observe the program's behavior to see how exceptions are handled (or not).
