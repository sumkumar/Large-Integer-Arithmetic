Functions:

add_dig : creates a new node
		head : Pointer to the large integer representation
		val	 : Value to be added in the integer


op_num : performs the arithmetic operations addition and multiplication of large unsigned integers
		a_num : Pointer to a large integer
		b_num : Pointer to another large integer
		op 	  : Operator which decides addition or multiplication on the two integers 
	Returns a new Pointer to large integer in case of multiplication

print_num : outputs a large unsigned integer to stdout in the format used for input, showing each “digit” as 4 decimal digits
		num : Pointer to the large integer

get_number_input : inputs a large unsigned integer from stdin as comma separated “digits” in decimal, ordered on decreasing significance and terminated by a $
	Returns a new Pointer to large integer

Variables:

BASE :	Number base of all the large unsigned integer representations

