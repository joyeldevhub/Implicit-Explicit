# Implicit-Explicit
Implicit and Explicit typecasting in Java

My code demonstrates both implicit and explicit type conversion in Java. Here's a breakdown:

1. **Implicit Type Conversion:**
   - In the `implicit()` method, I have an `int` variable `a` initialized to 10 and a `char` variable `c` initialized to 'A'.
   - Then, I perform an arithmetic operation `b = a + c`. Here, the `char` type `c` is implicitly promoted to an `int` type before the addition operation is performed.
   - Finally, the result is printed, which will be the ASCII value of 'A' (65) added to 10, resulting in 75.

2. **Explicit Type Conversion:**
   - In the `explicit()` method, I have two `int` variables `a` and `b` initialized to 15 and 2 respectively.
   - Then I perform division `c = (double) a / b`, where `a` is explicitly cast to `double` before the division operation is performed.
   - This explicit casting ensures that the division is performed in floating-point arithmetic, and the result is stored in the `double` variable `c`.
   - Finally, the result is printed, which will be the floating-point division result of 15 by 2.

My code serves as a good example to understand both implicit and explicit type conversions in Java. It's important to note the differences and use cases for both types of conversions. If you have any further questions or need clarification, feel free to ask!
