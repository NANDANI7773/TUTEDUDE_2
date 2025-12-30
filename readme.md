TASK-1 ->
-> it takes an integer input from the user

-> then using if-else conditional statements 

-> if condition is , if num%==0 ,i.e if remainder of num%2 comes out to be 0 (zero) then, it means the entered digit is even.(completely divisible by 2)

-> else , it means the entered digit is odd.(remainder is something other than 0 , not completely divisible by 2)

-------------------------------------------------------------------------------------------------------------------

TASK-2 ->
-> initialized total_of_sum to 0 (zero)
because , by using a for loop to iterate through a range of numbers,we could not sum up the individual integer digits , As for loop does not produces an iterable collection like (list,str,tuple)

-> so , we could get an error which says, TypeError : 'int' object is not iterable , and this error indicates that our code is attempting to iterate over an integer as if it were a sequence of items such as list , string, tuple.
Integers are simple , atomic values and cannot be broken down into smaller components into to loop through.

-> then there is a for loop that runs in a range from start to end , where start is initialized with 1 and end with 51 , as we were required to run the loop from 1 to 50 .

-> then , there is total_0f_sum += number , that means (total_of_sum = total_of_sum + number) (0 = 0+1),
now total_of_sum = 1 , and this will continue.

at the end we display the total_of_sum.
