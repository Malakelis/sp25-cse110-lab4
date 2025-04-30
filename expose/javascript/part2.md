1. It will print 3 because it was declared with var and will still exist after the loop. 
2. It will print 150 because discountedPrice was declared with var, so it’s function‐scoped and still exists after the loop holding the last computed value (300 × (1–0.5)).
3. It will print 150 because finalPrice was declared with var (function-scoped), so after the loop it still exists and holds the last computed value (300 × (1–0.5)), rounded to two decimals.
4. It returns [50, 100, 150] – the code builds an array by pushing each price × (1–0.5), rounded to two decimals.
5. Error occurs because i was declared with let in the for loop, so it isn’t defined at line 12.
6. Error occurs because discountedPrice was declared with let inside the for block, so it doesn’t exist at line 13.
7. It will print 150 — finalPrice is declared with let at the function level, so it’s still in scope after the loop and holds the last rounded value.
8. It will return [50, 100, 150] because it computes each price × (1–discount), rounds to two decimals, pushes those into discounted, then returns that array.
9. Error occurs because i was declared with let inside the for loop, so it doesn’t exist at line 11.
10. It will print 3, length was declared with const at the top of the function, so it’s in scope and holds prices.length.
11. The function will return the array of discounted prices which is [50, 100, 150] since the variable is in the function body's scope.

12.
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

13.
A. '32'  
B. 1  
C. 3  
D. '3null'  
E. 4  
F. 0  
G. '3undefined'  
H. NaN  

14.
A. true  
B. false  
C. true  
D. false  
E. false   
F. true  

15. `==` compares for equality after converting the two values to a common type, whereas `===` compares for equality without any type conversion where both value and type must match.

17. The function above will return `[2, 4, 6]`, because inside `modifyArray` we create an empty `newArr` and then loop over each element of array pushing `callback((array[i]))` where `callback` calls `doSomething` and multiplies each number by 2 so the final array is the original array but modified to be multiplied by 2 for each element.

19. `console.log(1)` will print 1 immediately then the first setTimeout will schedule to print 2 one second later and then print 3 will occur as soon as the other calls are done with 0 delay. `console.log(4)` runs immediately after scheduling and then 3 is printed and one second later 2 is printed. The order will be 1 then 4 then 3 then 2.
