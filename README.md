### Intersection

~~~javascript
var a1 = [1,2,4,5,7]
var a2 = [2,3,4,7]

var intersection = a1.filter(i => a2.includes(i));
console.log(intersection); // result [2,4,7]
~~~

### Palindrome

~~~javascript
var isPalindrome = function(x) {
   return x == String(x).split("").reverse().join("")
};
isPalindrome(121) // true
isPalindrome(122) // false
~~~
