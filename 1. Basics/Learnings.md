## Initialization
There are four mains ways to initialize variables in C++:
1. Default initialization:  ```int x;```
2. Copy initialization:  ```int x = 5;```
3. Direct initialization: ```int x(5);```
4. List initialization: 
    - Direct list initialization ```int x{5};```
    - Copy list initialization ```int x = {5};```
    - Value list initialization ```int x = {};```

The preferred way in modern C++ is to use list initialization because it maintains the integrity of the data type (won't convert float to int). In C++ speak, list initialization prevents narrowing.

However, a more recent source (2022) suggests only using list initialization for element initializers like vectors and use = anywhere else.

## Operator return values
Operators have return values and side effects. For instance, the binary operator+ returns the sum of the two operands. There's no side effect here. 

However, the operator= has a side effect of assigning the value given to the operand (x=5 would assign 5 to the value of x). The return value of this statement would be x. For example, x = (y = 5) would yield x = 5 since y = 5 returns y so it becomes x = y.

## Resources
[Blog about initialization](https://quuxplusone.github.io/blog/2019/02/18/knightmare-of-initialization/)
