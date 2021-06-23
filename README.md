# TXTintro
First ever TXT coding Challenge. Goal is to allow anyone to turn the bulb off and on. 

JS Bin to practice as a base, Hustle N Code to submit

Bulb On/Off [project](url)
<HTML>
    <!DOCTYPE html>
<html>
<body>
  <h2>
    click on light Bulb to turn on
  
<img id="myImage" onclick="changeImage()" src="https://www.w3schools.com/js/pic_bulboff.gif" width="100" height="180">
     

             


</body>
</html>
</HTML>
<CSS>
   cbody{
  background: black;
  color:white
} 
</CSS>
<JavaScript>
    function changeImage() {
    var image = document.getElementById('myImage');
    if (image.src.match("bulbon")) {
        image.src = "https://www.w3schools.com/js/pic_bulboff.gif";
    } else {
        image.src = "https://www.w3schools.com/js/pic_bulbon.gif";
    }
}

</JavaScript>
