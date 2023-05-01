Download Link: https://assignmentchef.com/product/solved-blg335e-project-2-main
<br>
<span class="kksr-muted">Rate this product</span>

In this project you are going to implement algorithm for the following problem.

Problem:

04.04.2019

Multiplying two polynomials efficiently is an important issue in a variety of applications, including signal processing, cryptography and coding theory. Multiplication operations are very costly for very large numbers in terms of time consumption. Especially for algorithms with high mathematical processing density, multiplication and exponent operations should be fast. Therefore, you are expected to develop an application that multiplies binary bit sequences in a way that reduces time complexity.

function multiply(x, y)

Input: Positive integers x and y, in binary Output: Their product

n = max(size of x, size of y) if n = 1: return xy

xL, xR = leftmost [n/2], rightmost [n/2] bits of x yL, yR = leftmost [n/2], rightmost [n/2] bits of y

P1 = multiply(xL, yL)P2 = multiply(xR, yR)P3 = multiply(xL + xR, yL + yR)

returnP1×2n +(P3−P1−P2)×2n/2+P

A) Implementation (50p)

1) Formalize this problem.You may have a look at your course slides or internet resources to find out which method you

can use.2) Reduce the result of time complexity3) Run your algorithm and analyze the results in terms of the running time4) Save time results (time, number of digits) and plot it in a graph for all method. (classical method vs. given method ) (For your report)4) Your program should compile and run using the following commands:

g++ yourStudentID.cpp –o project2 ./project2 output.txt

Given two binary strings that represent value of two integers, find the product of two strings. The

numbers should be 32, 64, 128, 256, 512 and 1024 bits and the result should be in decimal.

if the first bit string is “1000” and second bit string is “1010”, output should be “80”.

For example,

You are expected

to multiply two randomly generated binary numbers by classical method and given methods in

algorithm1. As a result of the operations performed, you are expected to reduce the time complexity of

the multiplication compared to the ordinary multiplication method. You have to show the time values in

the classical method and given method. You are expected to explains which approach you see in the

given algorithm.

Algortihm 1:

B) Report (50p)

1) Explain the multiplication problem with your own words briefly. What do given approach? (max: 3 lines)2) Present your problem formulation in detail.3) How does your algorithms work?

Write your pseudo-code.Write the time complexity of your algorithm on your pseudo-code. Write the time complexity of your reduced method.

4) Analyze and explain the algorithm results on the your graph. See example below: