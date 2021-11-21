# k3rn3l4/MathyOracle
writeup for k3rn3l4
From the title, the length of N is 512,and we can guess 600 times.
Obviously, we guess that the number of times is greater than the length--600>500
When the number of guesses is greater than length,we can calculate the value.
For example:
N=1011(Binary),we can guess 6 times.
First we set l=0,k=2-->gcd(1011-0,2)=1-->The last digit of this number is:1
Second we set l=1(The last digit of this number),k=4-->gcd(1011-1,4)=10-->The second-to-last of this number is:1
Set l=3(11),k=8-->gcd(1011-11,8)=0
Set l=3(011),k=16-->gcd(1011-11,16)=1000
So N=1011
Using this method we can find real N
