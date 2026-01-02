# TUTEDUDE_2
TASK_1
-> it takes an integer input from the user
-> and then modulus of number by 2 is taken , we use % because we have to find out the remainder .
-> if reaminder = 0 , then number is even (completely divisible by 2)
-> if reaminder = 1 , then number is odd (not completely divisible by 2)

TASK_2
-> As a For loop does not produce an iterable collection ,
-> and we are also required to sum up integers , which are simple , atomic values and cannot be broken down into small components to loop through.
-> so there is total_of_sum , which will initially store 0 .
-> then there is a For Loop , which runs from start =1 to end = 51 (to sum up integers between 1 and 50 )
-> there is an iterator (number) , starts from 1
-> total_of_sum += number 
-> means 0 += 1 =>  0 = 0 + 1  => now , total_of_sum = 1 
-> the same steps will continue until (iterator) number = 50 
