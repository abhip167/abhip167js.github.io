<!DOCTYPE html>
<html>
   <head>
       <style>
           body{
               text-align: center;
               background-color:#53DF83;
           }
       </style>
    <body>
        <header><h1><strong>ABHISHEK PATEL</strong></h1></header>
        <br>
        <h2>My First Javascript Tutorial</h2>
        <button type="button" onclick='document.getElementById("demo").innerHTML=Date()'>
            Click Here To Display Date And Time
        </button>
        <p id="demo"></p>
        
        <br>
    
       
        <h2>Javascript Bulb Lighter</h2>
        <p><light>Changing The Source Attribute</light></p>
        <button onclick="document.getElementById('myImage').src='https://www.w3schools.com/js/pic_bulbon.gif'">Turn On The Bulb</button>
        <img id="myImage" src="https://www.w3schools.com/js/pic_bulbon.gif" style="width=100%">
        
        <button onclick="document.getElementById('myImage').src='https://www.w3schools.com/js/pic_bulboff.gif'">Turn Off The Bulb</button>
        <br>
        <br>
        
       <script>var user = prompt("What would you love to do with your crush?(Sex,Love,Only Kiss)" ).toUpperCase();

switch(user){
    case "SEX":
        var condom = prompt("Do you know how to use condom?(YES or NO )").toUpperCase();
        var procedure = prompt("Do you watch porn movies?(YES or NO)").toUpperCase();
        
        if(condom == "YES" || procedure == "YES"){
            document.write("<h1>Wow you are going to have fun tonight!</h1>");
        }
        else{
            document.write("<h1>Fakir tera kuch bhi nai ho sakta saale to virgin hi marega...</h1>");
        }
        
        break;
        
        
    case "LOVE":
        var realLove = prompt("do you really Love her?(YES or NO)").toUpperCase();
        var like = prompt("Do you like her from your heart?(YES or NO)").toUpperCase();
        
        if(realLove == "YES" || like == "YES"){
            document.write("<h1>Congratulations we will guide you further !!</h1>");
        }
        else{
            document.write("<h1>Saale aisa hai to porn hi dekh le..</h1>");
        }
        break;
        
        
    case "KISS" :
        var howTo = prompt("Do you know how to kiss a girl?(YES or NO)").toUpperCase();
        var impress = prompt("DO you know how to impress her for a kiss?(YES or NO)").toUpperCase();
        
        if(howTo == "YES" || impress =="YES"){
            document.write("<h1>Hope you get a good girl ..humari aur se koi aasha mat rakhna kameene..</h1>");
        }
        else{
            document.write("<h1>Saale kuch karna to hai nai sub hum hi karenge kya!!!</h1>");
        }
        break;
        
        
        default:
        document.write("<h1>Sir/Madam aap ek kaam karo kindly aap BHAAD me jaao..</h1>");
        
}
</script>
       
        
    </body>
</html>
