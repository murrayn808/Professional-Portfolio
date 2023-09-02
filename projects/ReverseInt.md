---
layout: project
type: project
image: img/Reverseintsquare.png
title: "Reverseint.c"
date: 2022
published: true
labels:
  -C Language
summary: "An simple coding assignment from EE361 that required us to reverse a given integer."
---

<pre>
  <code>
   #include &lt;stdlib.h&gt;
   #include &lt;stdio.h&gt;

   int reverse_int(int n)
   {
   int remainder;
   int reverse = 0;

   while (n != 0) {
   remainder = n % 10;
   reverse = reverse * 10 + remainder;
   n /= 10;
   }

   return reverse;
   }

   int main()
   {


   int m = 456;
   printf("n = %d, reverse = %d\n", m, reverse_int(m));
   m = -456;
   printf("n = %d, reverse = %d\n", m, reverse_int(m));
   m = 3400;
   printf("n = %d, reverse = %d\n", m, reverse_int(m));


   }

  </code>
</pre>

Here's a breakdown of how it works:

int reverse_int(int n): This function takes an integer n as input and returns its reverse.

Inside the function, there are two variables:

remainder: This variable is used to store the remainder when n is divided by 10.

reverse: This variable is used to build the reversed integer.
The while loop continues until n becomes 0:

remainder = n % 10;: This line calculates the last digit of n by taking the remainder when n is divided by 10.

reverse = reverse * 10 + remainder;: This line updates the reverse variable by shifting its digits one place to the left and adding the calculated remainder. 
This effectively builds the reverse integer digit by digit.

n /= 10;: This line removes the last digit from n by dividing it by 10.
Once the loop finishes, the reverse variable contains the reversed integer, which is then returned.

In the main function:

Three different integers (m) are defined (456, -456, and 3400), and the reverse_int function is called for each of them.
The program then prints the original integer (n) and its reverse, as calculated by the reverse_int function.

Here's how the program works with the provided test cases:

For m = 456, the reversed integer is calculated as 654, so it prints "n = 456, reverse = 654".

For m = -456, the reversed integer is calculated as -654, so it prints "n = -456, reverse = -654".

For m = 3400, the reversed integer is calculated as 43, so it prints "n = 3400, reverse = 43".
