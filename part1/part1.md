1) It will output prices.length because var has no block scope
2) It will output the value of (prices[prices.length-1] * (1-discount)) because var has no block scope
3) It will output the proper, intended, value of finalPrice
4) It outputs [50, 100, 150] because with these parameters the function cuts the prices in half
5) Error, let does not exists, outside of scope
6) Error, let does not exists, outside of scope
7) Output will be the same as 3)
8) Output will be the same as 4)
9) Error, let does not exists, outside of scope
10) Error, const does not exists because it is out of scope
11) Error for trying to reassign a const variable
12) Function won't return any value because there is an error trying to reassign a const variable
13) 
    A) student.name
    B) student["Grad Year"]
    C) student.greeting()
    D) student["Favorite Teacher"].name
    E) student.courseLoad[0]
14) 
    A) '32' because it reads the expression as string concatenation
    B) 1 because you can't subtract from a string, so it is casted to an int
    C) 3 because null acts as 0 when added
    D) 3null because '3' and 'null' are concatenated together
    E) 4 because true acts as 1, 1+3 = 4
    F) 0 because false and null act as 0, 0 + 0 = 0
    G) 3undefined because 'undefined' is concatenated to '3'
    H) NaN because you can't subsract an undefined value from something
15) a
    A) True, b/c '2' is converted to 2
    B) False, b/c '1' < '2'
    C) True, '2' is converted to 2
    D) False, because it doesn't convert types, it strictly compares the value and its type
    E) False, because true is converted to 1, 1 == 2 -> false
    F) True, Boolean(2) is converted to true, true == true -> true
16) '==' converts types to integers and compares, while '===' strictly compares the value and its type
17) 'How are you?' because 2 gets type converted to true and the else at the end is ignored
18) separate file
19) [6, 8, 10], because our Callback function adds 2 to whatever value is used as its parameter. Which that value then gets multiplied by 2 and then added to newArr. 
20) separate file
21) "1 4 3 2", lines are executed in order, however 1 & 4 don't have a set delay. Although 3's delay is set to 0 milliseconds, JS still reads that as a very minor delay, so it is logged after 4. 2 is logged last since it has a 1 second delay.