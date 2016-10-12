Binary shifts are the equivalent of the decimal or denary shifts that we are all used to.

If we want to multiply an integer denary number by 10 we add a 0.
e.g. 9 * 10 = 90
What we have done is moved the number to the left by one place value and replaced it with a 0.

![](.guides/img/gridc.png)

If we multiplied it by 100 $(10^2)$ then we move it two places to the left.

When dividing we move the digits to the right.
e.g. 90 / 10 = 9

Similarly, we can also use a left shift in binary when we are multiplying by powers of 2.

If we multiply the 8-bit binary number 00001101 (denary 13) by 4 which is 22, we would do two left binary shifts.

![](.guides/img/gridd.png)

Therefore 00001101 x 22 = 00110100
We can check this as 0110100 is equal to 52 in denary which is equal to 13 * 4.
So it works!


If we divide the same number by 4 (22) there should be two shifts to the right. This time the rightmost bits drop off the end and are replaced by 0s at the left.

![](.guides/img/gride.png)

Therefore 00001101 / 22 = 0000011 which is equal to 3 in denary.
But 13 / 4 = 3.25 and so there has been a loss of precision as the result is given to the nearest lower integer. 