# JavaScript_code001

This is the first code I made while studying the JavaScript language. It's not much, but it's a start.

This code basically takes the input of a user (for the value that it will be used and also the number of times it will repeat itself)
and returns the result of the following calculus: total_sum = total_sum + (user_value + user_value). 

Ex.: 
    user_value = 2
    num_times = 3
    
    for(var i = 1; i < num_times; i++){
        user_value += user_value;
        total_sum += user_value;
    }
    
    
R: total_sum = (2 + 4 + 8 =) 14

And when the user decides to NOT input a number, the program will then proceed to assign a random number to the variable in question.
