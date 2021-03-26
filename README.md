# Dom---Manipulation.js
Assignment 1

<!doctype html>
<html>
    <body>

        <h1>My name is Anuj Kafaliya</h1>
        <p class="class1">My name is Anuj Kafaliya</p>
        <h1 id="id1">My name is Anuj Kafaliya</h1>

        
        <script src="./Assign.js">
        
            
        </script>
      
    </body>
</html>

var ele1=document.getElementsByTagName('h1');
console.log(ele1[0]);
var ele2=document.getElementsByClassName('class1');
console.log(ele2[0]);
var ele3=document.getElementById('id1');
console.log(ele3);

ele2[0].innerText="Hello Javascript!!";
