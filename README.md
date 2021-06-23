# txt
Our Immigration Outreach Network, or ION, aims to help immigrants find shelter and basic necessities. With this we hope to show how productive anyone can be if given the resources.

Visual Studios, Material Theme

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
