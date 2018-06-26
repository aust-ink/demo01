def num_digits():
	number = 8
	count = 0
	while number != 0:
        	count += 1
                number //= 11
  
               return count
	       
	       print(num_digits())
