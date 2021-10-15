### Part 2 answers

1. Line 12 prints "3". This is because the variable prices is an array and it is passed in as a parameter to the function with "100,200,300". The length of the array 'prices' is 3 and the for loop is ran 3 times and the variable i can be accessed anywhere within the function. Hence the answer is 3.
2. Line 13 prints "150". This is because on the third iteration of the loop discounted price is assigned with 300(.5) which 150. The variable had no scope issues as it was a var and it can be accessed anywhere within the function.
3. Line 14 prints "150". This is because on the third iteration the variable discounted price gets rounded and assigned to finalPrice. This can be accessed anywhere within the function.
4. 