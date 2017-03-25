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
 
 function addSix(n) {return function (y){n+y};};

 var addSix = createBase(6);
 
 addSix(10);
 
 addSix(21);
 
 -------------------------
<button id="btn-0">Button 1!</button>

<button id="btn-1">Button 2!</button>

<button id="btn-2">Button 3!</button>

<script type="text/javascript">

    var prizes = ['A Unicorn!', 'A Hug!', 'Fresh Laundry!'];
    
    function fun (btnNum){return function (){alert(prizes[btnNum]);};};
    
    for (var btnNum = 0; btnNum < prizes.length; btnNum++) {

        
        document.getElementById('btn-' + btnNum).onclick =fun(btnNum);
    };
</script>


