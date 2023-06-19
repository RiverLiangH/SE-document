A program accepts three integers representing the lengths of a triangle’s sides. It outputs “scalene” (no equal sides), “isosceles” (two
equal sides), or “equilateral” (three equal sides). Write an effective (finds common bugs) and efficient (as few tests as possible) set of test cases. Usually, a test case consists of tester action, data, and expected result, but here the action is generally “input data”.



Effective and Efficient Test Cases:

\1. Test for scalene triangle:

\- Input: 3, 4, 5

\- Expected Output: “scalene”

\2. Test for isosceles triangle:

\- Input: 5, 5, 7

\- Expected Output: “isosceles”

\3. Test for equilateral triangle:

\- Input: 6, 6, 6

\- Expected Output: “equilateral”

\4. Test for invalid triangle with one side length equal to or less than zero:
 \- Input: 0, 4, 5
 \- Expected Output: “Invalid triangle”

\5. Test for invalid triangle with two sides length less than or equal to the third side:
 \- Input: 2, 5, 10

\- Expected Output: “Invalid triangle”

\6. Test for invalid triangle with negative side length:
 \- Input: 3, -4, 5

\- Expected Output: “Invalid triangle”

\7. Test for invalid input with non-integer input:
 \- Input: 3, 4.5, 6

\- Expected Output: “Invalid input”

By testing the above cases, we can ensure that the program works correctly and covers most of the common bugs that may occur, such as invalid input, invalid triangle, and different types of triangles (scalene, isosceles, equilateral).