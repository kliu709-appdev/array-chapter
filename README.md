# Ruby Practice

Run your Ruby file by typing `ruby ` and then the name of the file you want to run in the Terminal.

If we want to run `array_count.rb`, we can write the command:

```bash
ruby array_count.rb
```

To re-run this command, you can use the UP and DOWN arrow keys to look at the history of commands you've run in a Terminal.

## Array

### array_element_square.rb
Print the square of the second-to-last number that the user enters.

The expected output will be something like:
```
"Enter at least 2 numbers, separated by spaces:"
9.0
```
### array_count.rb
Create an Array and use the count method to print how many elements are in that Array.

Expected output:
```
"Enter at least 2 numbers, separated by spaces:"
2
```
### array_reverse.rb
Create an Array and use the reverse method to return the array in reverse order.

Expected output: 
```
"Enter at least 2 values, separated by spaces:"
["second", "first", 0]
```

### array_min_max_difference.rb
Create an Array of numbers and output the number with the lowest value in the array, the number with the highest value in the array, and the difference between the highest value and the lowest value.
```
lowest_number
highest_number
difference
```

### array_sum_elements.rb
Output the sum value of all the elements in the array.

## Specs
<details>
  <summary>Click here to see names of each test</summary>

array_count.rb should output '2' given the input '2 9' 

array_count.rb should output '9' given the input '9 12 8 25 16 78 64 0 27' 

array_count.rb should output '5' given the input '9 80 17 28 36' 

array_element_square.rb should output '4.0' given the input '9 2 7' 

array_element_square.rb should output '9.0' given the input '6 4 6 6 6 3 2' 

array_element_square.rb should output '18.49' given the input '3.2 -1.1 -4.3 8.4' 

array_min_max_difference.rb should output '6', '73', and '67' on separate lines 

array_reverse.rb should output '['hello', 'zebra', '35', 'banana']' given the input 'banana 35 zebra hello'. 

array_reverse.rb should output '[4, 3, 2, 1]' given the input '1 2 3 4'. 

array_sum_elements.rb should output '151' 

</details>
