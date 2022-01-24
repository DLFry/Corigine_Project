<h1>Factorial digit summation</h1>

<p>The project calculates the factorial of a postive integer from the command line argument.<br />Error checking is done to determine whether the argument is indeed a positive integer.</p>

<p>Once a valid integer is input, The factorial of the input is calculated using the numpy factorial function. The value is then stored and called by a self made function that calulates the sum of the digits of the stored value.</p>

<p>The calculation is done by determining the least significant digit (LSD) with the use of the numpy modulo function. The LSD is the remainder when the integer is divided by 10. The LSD is then added to a variable that is the sum of the digits. The factorial is then divided 10 and rounded down to get rid of the LSD and move on to the next. This is done with the numpy floor divide function. This function loops until all the digits are determined and then the total summation is printed in the terminal window.</p>

<p><em><strong>Note: </strong>The numpy mod() and floor_divide() functions use floating point arithmetic which causes imprecisions in the result. This problem has been alleviated with the Fraction function.</em></p>