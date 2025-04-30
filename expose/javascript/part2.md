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
11. 