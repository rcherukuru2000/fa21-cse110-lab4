### Part 2 answers

1. Line 12 prints "3". This is because the variable prices is an array and it is passed in as a parameter to the function with "100,200,300". The length of the array 'prices' is 3 and the for loop is ran 3 times and the variable i can be accessed anywhere within the function. Hence the answer is 3.
2. Line 13 prints "150". This is because on the third iteration of the loop discounted price is assigned with 300(.5) which 150. The variable had no scope issues as it was a var and it can be accessed anywhere within the function.
3. Line 14 prints "150". This is because on the third iteration the variable discounted price gets rounded and assigned to finalPrice. This can be accessed anywhere within the function.
4. The function will return an array of these values "50,100,150". This is because the variable discounted is declared as an array and everytime the loop runs a new finalPrice is pushed into the array corresponding to the prices that are passed in.
5. A reference error is caused as the scope of the variable i is limited. This is because it is declared with the keyword 'let' and it can only be accesed within the block where it is declared in. Since we are calling the variable outside its scope we get an error.
6. A reference error is caused as the scope of the variable discountedPrice is declared within the for loop with the keyword 'let' and since we are trying to access this variable outside its scope we get a reference error.
7. Line 14 prints "150". There is no error here because the variable finalPrice declared using the keyword 'let' has the same scope as the keyword 'var' within the function. Hence finalPrice can be accessed anywhere in the within the scope of the function.
8. The function will return an array of these values "50,100,150". There is no error here as there are no scope issues for any variables within the function. Discounted variable can be accessed anywhere within the function without any errors.
9. Line 11 causes an error as it is trying to access the variable i which is declared with the keyword 'let'. The variable i can only be accessed within the for loop as its scope is very limited and it only exists within the for loop.
10. Line 12 will output "3". There are no errors. This is because the variable length is declared with the keyword 'const' which means it can't be reassigned again. Since we initially initailized with a length of 3 and did not reassign it again we don't have an error.
11. The function will return an array of these values "50,100,150". There is no error here. This tells us that the 'const' keyword on an array will let us change the array such as push a new value or change an exisitng value but it does not let us reassign the entire array itself.
12. * a. student.name
    * b. student["Grad Year"]
    * c. student.greeting()
    * d. student["Favourite Teacher"].name
    * e. student.courseLoad[0]