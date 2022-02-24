---
title: "Arithmetic Progressions"
tags: ["maths", "cbse", "cbse-maths"]
date: 2022-02-24T21:19:29+05:30 
toc: true
note: "Based on the chapter \"Arithmetic Progressions\" from Mathematics for Class 10, NCERT"
author: Navaneeth Krishna
---
  
## Introduction

Arithmetic Progression (AP) is basically a series of numbers that are increasing/progressing by a fixed common difference.

### Examples

**Example 1:** The natural numbers follow an arithmetic progression :

$$ AP: 1, 2, 3, 4, 5, 6, ... $$

Here, one is added to a number to get the next number in the series.

$$ 
1 = 1\\\ 
1+1 = 2\\\
2+1 = 3\\\
3+1 = 4\\\
4+1 = 5\\\
5+1 = 6\\\
...
$$

Here, the **first term** (denoted by _`a`_ ) is 1. The **common difference** (denoted by _`d`_ ) is also 1 here.  
$$
a=1\\\
d=1\\\
\therefore AP = 1, 2, 3, 4 ...
$$

**Example 2:** A taxi service runs only 100 kilometers. Its initial minimum fee is ₹50 and ₹20 is added for each kilometer. 
$$
a=50\\\
d=10\\\
\therefore AP=50, 60, 70 ... 1050
$$

This is an example of a finite AP. It means that this AP has a last term (denoted by _`l`_ ), and it stops there.


$$ \implies l=1050 $$

The first example we looked at was an infinite AP, as natural numners go on till infinity. 




## 1. General Form of an AP  

Let's express APs in a general form applicable to all APs.  
  
Remember that:  
**First term → _a_**  
**Common difference → _d_**

Let's write an AP using just ‘a’ and ‘d’

$$
\text{1st term} = a\\\
\text{2nd term} = a + d\\\
\text{3rd term} = a + 2d\\\
\text{4th term} = a + 3d\\\
$$

That's how it works.


## 2. Testing for AP

To know if a series forms an AP. We find the difference between consecutive terms.

Let's assume a series,

$$ A1, A2, A3, A4 ... A99, A100 $$


If this is an AP, the difference between terms should be constant, right?


So, we check if the _difference is the same_. If the series is an AP,


$$ A2 - A1 = A3 - A2 = A4 - A3 ... = A100 - A99 $$


If the differences are not the same, then it's not an AP.


## 3. Term between two terms in an AP

Let's assume an arithmetic progression,

$$ 3, 6, \text{\textunderscore\textunderscore} , 12 ... $$

In this series, one number is missing between two numbers. To find that number, we just have to take the arithmetic mean of the two numbers beside it.


In this case


$$ \frac{6+12}2 = 9 $$

## 4. _n_ th term of an AP
Let's assume an AP with
$$
a=2\\\
\text{and}\\\
d=2\\\
\implies \text{AP= } 2, 4, 6, 8, 10, 12, 14 ...
$$


In this AP, the first term is 2 and the 4th term is 8. Let's write the same AP in its general form.

$$
2, 2 + 2, 2 + 4, 2 + 6, 2 + 8 ...
$$

Here the 4th term is 2 + 6, which is a + 3d.

Which can be written as:
$$
a + (4-1)d
$$

This works with all terms, so we use a general formula for it.


For an AP, the nth term is :
$$
\tag{1} a+(n-1)d
$$

If a question comes to check if a number is a part of an AP, then you just have to use this formula backwards. If you get a natural number, then it's probably a part of the AP. For eg:-


**Example: Check whether 300 is a term of the AP: 100, 150, 200 ...**

Here,
$$
a=100\\\
d=50
$$

If we substitute the _a_ and the _d_ in formula (1) and simply equate it to 300:
$$
100 + (n-1)50 = 300
$$
After equating we get
$$
n = 5
$$

We get _n_ to be a natural number. This means that 300 is a part of the AP and is the 5th term in it.



**Example: Find the total number of two-digit even numbers.**


The first two digit number, 10, is even. So we can start an AP from 10 to the last two-digit even number, which is 98.

$$
a = 10\\\
l  = 98\\\
d = 2\\\
\text{(}d=2 \because \text{even numbers are multiples of two)}
$$

Using formula (1)
$$
98 = 10+(n-1)2
$$

Do the calculation, you will get…..
$$
n = 45
$$
## 5. Sum of first n terms of an AP
Lets consider the AP:
$$
2, 4, 6, 8, 10 ...
$$

We can write this as the sum of each term,
$$
2+4+6+8+10……..
$$

How do we find, say, the sum of the first five terms of this AP?

For this, we can use the formula:  
$$
S_n=\frac{n}2[2a+(n-1)d]
$$  
where _n_ is the number of terms whose sums is to be calculated.  

> **Note:**
To find the nth term of an AP. Just find the sum of n terms, and subtract sum of _(n-1)_ terms from it.


## 6 Sum of first _n_ natural numbers
As we said before, natural numbers form an AP with  
$$ 
a=1
d=1
$$  
So, to find the sum of first _n_ natural numbers we just have to substitute _a_ and _d_.  
$$
S_n=\frac{n}2[2a+(n-1)d]\\\
S_n=\frac{n}2[2(1)+(n-1)(1)]\\\
S_n=\frac{n}2[2+n-1]\\\
\implies S_n=\frac{n}2[n+1]\\\
$$  
Therefore, the formula to find the first _n_ natural numbers is:  
$$
S_n=\frac{n}2[n+1]\\\
$$
