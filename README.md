# HW6

a. Why can you only use certain pins for analogWrite()?

Because these pins are able to output "a steady square wave of the specified duty cycle".

b. What is the range the map() function maps the value to? Why this range?

0 -1023, and 0 -250. This is so that the analog signal (1023) can get mapped to the full duty cycle of the digital signal(255). 
