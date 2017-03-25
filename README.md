# week-5
-----------------------------
What will be the output of the following code - and more importantly - WHY?
for (var i = 0; i < 3; i++) {
      setTimeout(function() { alert(i); }, 1000 + i);
}
------------------------------
The solution :

This code will show us 3 alert contain number 3 ((alert (i)  )) ,The time difference between them is 1002 ms
Because i is equal to 3.ِ And 1000 + i= 1002 ms  , And that's how long the alert  must implement
 
 -----------------------------------
 
 function addSix(n)
 {
return function (y)

{
    n+y;
};
 };

 var addSix = createBase(6);
 addSix(10);
 addSix(21);
 
 -------------------------
