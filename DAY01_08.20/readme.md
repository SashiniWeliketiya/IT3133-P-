
### 01)Swap two numbers without temporary variable

~~~
a = 5
b = 10

a = a + b   
b = a - b   
a = a - b   

console.log(a)  
console.log(b)  
~~~


### 02)Find three large numbers Among given array of numbers

~~~
function findThreeLargest(arr) {
    arr.sort((a, b) => b - a); 
    return arr.slice(0, 3);    
}

console.log(findThreeLargest([25, 1, 89, 56, 74, 12])); 
~~~


