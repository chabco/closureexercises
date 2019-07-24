# Closure Exercises
## Counter
Make a counter function that returns a function that returns a successive number each time it is called.

> var count1 = counter()  
> var count2 = counter()  
> count1()  
1   
> count1()   
2   
> count2()   
1   
> count2()   
2   
> count1()   
3  

## Counter 2
Allow the caller of counter to initialize the count to the first argument that's passed in.

> var count1 = counter(4)   
> count1()   
5   
> count1()   
6  
## Counter 3
Allow the counter to either increment 1 or decrement by 1 by calling the increment and decrement methods, respectively. Note: now the counter needs to return an object rather than a function.

> var count = counter(4);  
> count.increment()   
5   
> count.increment()   
6   
> count.decrement()   
5   
> count.decrement()  
4