<h1 align="center">Playing-with-Matches</h1>

# Problem
Chef's son Chefu found some matches in the kitchen and he immediately starting playing with them.

The first thing Chefu wanted to do was to calculate the result of his homework — the sum of A and B, and write it using matches. Help Chefu and tell him the number of matches needed to write the result.

Digits are formed using matches in the following way:

![image](https://user-images.githubusercontent.com/90305324/234870080-aa80b5d2-55bf-4f85-baa7-45a2828c4ec7.png)

# Input

▶The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.

▶The first and only line of each test case contains two space-separated integers A and B.

# Output

▶For each test case, print a single line containing one integer — the number of matches needed to write the result (A+B).

# Constraints

▶1≤T≤1,000

▶1≤A,B≤10^6

# Sample 1:

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>3</td>
  </tr>
  <tr>
    <td>123 234</td>
    <td>13</td>
  </tr>
  <tr>
    <td>10101 1010</td>
    <td>10</td>
  </tr>
  <tr>
    <td>4 4</td>
    <td>7</td>
  </tr>
</table>

# Explanation:

▶ Example case 1: The result is 357. We need 5 matches to write the digit 3, 5 matches to write the digit 5 and 3 matches to write the digit 7.

▶Example case 2: The result is 11111. We need 2 matches to write each digit 1, which is 2⋅5=10 matches in total.
