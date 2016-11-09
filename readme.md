Fizzbuzz

A friend had this coding test, so i thought id do my version


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
