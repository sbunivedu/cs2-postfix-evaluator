# Postfix Evaluator

The `PostfixEvaluator` class implements the postfix evaluation
algorithm in the `evaluate` method.

Given an expressoion in the __postfix__ format as a Java String
object, the `evaluator` method returns the result as an `int`.
The input expressions must use one or more space characters as
the delimiter between the operators and the operands as
shown in the following test cases:
```
infix                 | postfix       | output
-----------------------------------------------------
10 + 20 * 30          | 10 20 30 * +  | 610
10 + ( 20 - 30 )      | 10 20 30 - +  | 0
( ( 10 + 20 ) * 30 )  | 10 20 + 30 *  | 900
````

You can run the `PostfixTester.java` class with the test cases.
 
 
 
