# Incorrect Parameter Label Usage in Swift Function Call
This example demonstrates a common error in Swift: omitting parameter labels when calling a function that expects them. Swift's type system is strong and requires parameter names to be used in function calls, for disambiguation.

**The Bug:** The `calculateArea` function is defined with named parameters (`width` and `height`). If you omit these parameter labels during the function call (as shown in `area2`), a compiler error will occur because Swift is unable to infer the type and position of the parameter 5.