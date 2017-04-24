# lab4

A.

Encoded identifiers used for the functions =

	000000000040052d T _Z7averageif		-> int average(int n1, float n2)
	
	00000000004004ed T _Z7averagePdRd	-> double average(double *n1, double &n2)



B.

output = 

1 4

4 4

4 4

8 4


reason:
sizeof(a) = sizeof(char) = 1

sizeof(b) = sizeof(int) = 4

sizeof(c) = sizeof(float) = 4

sizeof(d) = sizeof(double) = 8

sizeof(pa) = sizeof(pb) = sizeof(pc) = sizeof(pd) = (size of memory address) = 4
