## [1](/expose/pipeline/part2-question1.js)
"console will print 3, the length of prices, becuase the var i will increment to the length of the price array and then the loop will stop, but the value of i will not change after that, and is still accesable because var is global"
## [2](/expose/pipeline/part2-question2.js)
"the console will print 150, the discounted price for the last item in the loop"
## [3](/expose/pipeline/part2-question3.js)
"the console will print 150, the finalPrice of the last item in the loop"

## [4](/expose/pipeline/part2-question4.js)
"this function will return the array of prices with the discount applied to them"
## [5](/expose/pipeline/part2-question5.js)
"function will return an error, i is not defined outside the scope of the for loop"
## [6](/expose/pipeline/part2-question6.js)
"function will return an error, discountedPrice is not defined outside the scope of the for loop"
## [7](/expose/pipeline/part2-question7.js)
"finalPrice is declared in the scope of the whole function so it will return whatever was last stored in it, and in this case it is the last item in the list of prices after the discoutn has been applied, 150"
## [8](/expose/pipeline/part2-question8.js)
"the function will return the array of discounted prices stored in discounted"
## [9](/expose/pipeline/part2-question9.js)
"console will throw an error becuase i is not within the scope of the call, it is only declared in the for loop"
## [10](/expose/pipeline/part2-question10.js)
"console will return the length of the prices array, in this case, 3"
## [11](/expose/pipeline/part2-question11.js)
"the function will return the discounted prices array, but the discountedPrice variable is declared as a const inside the for loop, so it will be redeclared every time the loop runs. So, the discountedPrice variable should be declared outside the loop with the tag let."
## [JavaScript for 12](/expose/pipeline/part2-question12.js)
```
A. console.log(student.name);
B. console.log(student["Grad Year"]);
C. student.greeting();
D. console.log(student["Favorite Teacher"].name);
E. console.log(student.courseLoad[0]);
```
## [13](/expose/pipeline/part2-question13.js)
``` A. '3' + 2 = '32' ```
"outputs a string representation of the number 3 concatenated with the number 2"

```B. '3' - 2 = 1 ```
"converts the string number into a integer before performing the subtraction operation"

``` C. 3 + null = 3 ```
"null is converted into 0 before performing the addition operation, it does nothing to the 3"

``` D. '3' + null = '3null' ```
"null is converted into a string before performing the addition operation, so it concatenates them"

``` E. true + 3 = 4 ``` 
"true is converted into 1 before the additon operation, resulting in 4"

``` F. false + null = 0 ```
"false and null are both converte into 0 before completing the addition operation, resulting in 0"

``` G. '3' + undefined = '3undefined' ```
"undefined is converted into a string before performing the addition operation, so it concatenates them"

``` H. '3' - undefined = NaN ```
"undefined is converted into an integer, but it equals NaN so the result is just NaN"
## [JavaScript for 14](/expose/pipeline/part2-question14.js)
``` A. '2' > 1 = true```
"the sring is converted into an integer and then the comparison operator is applied, returning true"

```B. '2' < '12' = false```
"the strings are compared in order, and 1 is less than 2, so the result is false"

``` C. 2 == '2' = true```
"one of the two parameters is converted into the same type as the other before the comparison operator is applied, returning true"

``` D. 2 === '2' = false```
"triple equals is doing a strict equality comparison, so the result is false, becuase the right side is a string and doesn't really equal 2"

``` E. true == 2 = false``` 
"returns false, becuase true is equal to 1 numerically"

``` F. true === Boolean(2) = true```
"the Boolean operation always returns true unless the paramter is null, undefined, NaN or 0, so this is true"

## [JavaScript for 15](/expose/pipeline/part2-question15.js)
"== is the equal operator, it compares the items on both sides and does not consider the variable type, for example '2' == 2 will return true"
"=== is the strictly equals operator, it compares the items on both sides and takes into account what type of variable it is, if they are different it results in false, if they are the same type, and are equal, it returns true"
## [JavaScript for 16](/expose/pipeline/part2-question16.js)
## [JavaScript for 17](/expose/pipeline/part2-question17.js)
## [JavaScript for 18](/expose/pipeline/part2-question18.js)
## [JavaScript for 19](/expose/pipeline/part2-question19.js)