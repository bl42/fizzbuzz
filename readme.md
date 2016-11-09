Fizzbuzz

A friend had this coding test, so i thought id do my version

"Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”."

```javascript
(function count(i){
 var fizzbuzz = (i % 15 === 0) ? "fizzbuzz": 
                 (i % 5 === 0) ? "fizz" :
                   (i % 3 === 0) ? "buzz" :
                     null;
 if(fizzbuzz)
   console.log(fizzbuzz);
 
 if(i <= 100)
   count(i+1);
})(0);

```
