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

13. * A. The output is '32'. The number 2 is converted into a string as we are concatenating an number and string where the final output will be a string. The + means we convert the number to a string.
    * B. The output is 1.  The string 3 is converted into an number as we are subtracting a string from an number which will give as an number as the final output.
    * C. The output is 3. The null acts as a zero in this case and has no effect on the addition of the number 3.
    * D. The output is '3null' of the type string. Here null is converted into a string as we are concatenating with a  string '3'.
    * E. The output is 4. The 3 remains as an number and the value of true is converted to 1 as true maps to 1. Hence adding 3 and 1 will give us 4.
    * F. The output is 0. The value of false maps to 0 and as stated in question C null has no effect on the addition and it will act like a 0. Hence 0 + 0 will give us 0.
    * G. The output is '3undefined'. The undefined is converted into string 'undefined' as we concatenating with a string '3'. When we concatenate with a string the end result will also be a string.
    * H. The output is NaN. This is because even though the 3 can be converted into an number it can't be subtracted from undefined. For example, 3 - infinity is not computable. The same thing applies here.

14. * A. The output is true. This is because the string '2' becomes a number and since 2 is greater than 1 it is true.
    * B. The output is false. This is because we are comparing two strings. When we compare two string we compare  letter by letter of each string and decide. Since '2' is not less than '1' we get a false.
    * C. The output is true. This is because javascript will convert the string to a number when doing the comparision between a number and a string. Since 2 is same as 2 we get true as our result.
    * D. The output is false. This is because the string 2 and the number 2 belond to different datatypes. Hence the === operator will give us a false.
    * E. The output is false. The value of true maps to 1 and compares if both are equal. Since 1 is not equal to 2 we get false.
    * F. The output is true. The datatypes are the same as both the variables are of the type boolean. Boolean(0) maps to false where are Boolean(1 and above) maps to true. Since true === true this will gives us a boolean true.

15. In Javascript '==' is used to compare two variables and it ignore the datatype of the variable. Whereas, the '===' operator is used to compare two variables but also checks if they have the same datatype and as well as the values. For example, 2 == '2' is true because it ignores whether the variables or a string/number and it only checks if the values are the same. In the case of 2 === '2' it checks if both variables are of the same datatype ie; string or number and also checks for the value.
16. 