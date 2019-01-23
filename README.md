## Welcome to CMD-INDEX!  :)
<br>
<form name="form" method="post" onsubmit="return check()">
  <font color="green" style="黑体" >Welcome to CMD-INDEX!&nbsp;&nbsp;&nbsp; :)</font>
  <br>
  <br>
  <table width="350" border="0">
  <tbody>
    <tr>
    <td><font color="red" style="黑体" >WARNING: </font></td>
      <td align="left"><font color="red" style="黑体" >LEVEL 7 Authorisation Needed!</font></td>
    </tr>
    <tr>
    <td><font color="green" style="黑体">ACCOUNT:</font></td>
      <td align="left"><input  id="account" type="text" placeholder="input your account" required ></td>
    </tr>
    <tr>
      <td><font color="green" style="黑体" >PASSWORD:</font></td>
      <td align="left"><input id="password" type="password" placeholder="input your password" required ></td>
    </tr>  
    <tr>
      <td><input type="button" value="SUBMIT" onClick="check()"></td>
    </tr>
  </tbody>
</table>
  
  
  <script>
function check(){
   var account = document.getElementById("account").value;
   var password = document.getElementById("password").value;
   if(password ==  7777 && account == 'MarsGuo18'){
        alert("Welcome! MarsGuo!!!!!!!!")
        return true;
   }
   if(password ==  7777 && account == 'Monarchh'){
        alert("Welcome! StephenLi!!!!!!!!")
        return true;
   }
  else{
   alert("I am so sorry to tell you that you don't have permission to log in this website.Please consult the network administrator for details.Sorry for the inconvenience.");
   return false;
  }
}
</script> 
  </form>