Math 490 hw Problem 1
==================

Given: f(x) = x^2 + ax + b, a, b are integers
To Establish a conjecture: Set {f(n): n in Z and f(n) prime} is infinite

Solution:

	Consider Dirichlet's theorem of infinitely many primes.
	for any two positive coprime integers a and d, there are infinitely many primes of the form a + nd
	, where n = 0. In other words, there are infinitely many primes which are congruent to a modulo d.
	
	a, a+d, a+2d, a+3d, a+4d,.....
	
	Since a and b are integer, then if a and b are relatively co-prime they by Dirichlet's theorem
	they generate an arithmetic progression of infinitely many primes.	
	Now, if x/a is an integer, then										
	
	f(x/a) = (x/a)^2 + a*(x/a) + b
	
	=> f(n,x) = a*n + a*(x/a) + b


	where (x/a)^2 can be written as a*n, n>= 0 and x/a can be written as a new variable, y
	Hence,
	f(n,y) = a*n + a*y + b
		= a(n+y)+b 
	f(m) = a(m) + b, since n+y is an integer 	
	
	We see that f(m) = am + b which still fits in our Dirichlet's Theorem of primes. 
	
	Hence, the set {f(n): n in Z and f(n) prime} is infinite provided a and b are relatively co-primes
	and x is divislbe by a.
	

			




