By: Julien Barbier
 Weight: 1
 Project over - took place from Dec 12, 2022 6:00 AM to Dec 26, 2022 6:00 AM
 An auto review will be launched at the deadline
In a nutshell…
Auto QA review: 0.0/0 mandatory & 0.0/123 optional
Altogether:  0.0%
Mandatory: no mandatory tasks
Optional: 0.0%
Background Context
Before you continue reading, start this song in the background :)




We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won’t get hurt if you don’t do it, but if your current average is greater than your score on this project, your average might go down. Have fun!

Resources
Read or watch:

RSA
How does HTTPS provide security?
Prime Factorization
Why RSA?
Requirements
General
You can choose the language of your choice.
OS needs to be Standard Ubuntu 20.04 LTS/
Tasks
0. Factorize all the things!
#advanced
Score: 0.0% (Checks completed: 0.0%)
Factorize as many numbers as possible into a product of two smaller numbers.

Usage: factors <file>
where <file> is a file containing natural numbers to factor.
One number per line
You can assume that all lines will be valid natural numbers greater than 1
You can assume that there will be no empy line, and no space before and after the valid number
The file will always end with a new line
Output format: n=p*q
one factorization per line
p and q don’t have to be prime numbers
See example
You can work on the numbers of the file in the order of your choice
Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
Time limit: Your program will be killed after 5 seconds if it hasn’t finish
Push all your scripts, source code, etc… to your repository
we will only run your executable factors
julien@ubuntu:~/factors$ cat tests/test00 
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
julien@ubuntu:~/factors$ time ./factors tests/test00
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5