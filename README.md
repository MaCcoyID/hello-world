<html>

<head>
	<title>
		Log-in
	</title>
</head>
<style>
form {
   border-style:inset;
}

input[type=text], input[type=password] {
    width: 50%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 25%;
}

.container {
    padding: 16px;
}



</style>
<body>
<div id="id01"></div>
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript">

</script>
<center><h2>Login Form</h2>

<form action="action_page.php">
  

  <div class="container">
    <label><b>Email</b></label>
    <br>
    <input type="text" placeholder="Enter Username" name="uname" required>
    <br>
    <label><b>Password</b></label>
    <br>
    <input type="password" placeholder="Enter Password" name="psw" required>
    <br>   
    <button type="submit" >Log-in</button>
    <br>
    <input type="checkbox" checked="checked"> Remember me
    <br>
    <a href="file:///C:/Users/Vernom/Desktop/Log-in%20And%20Registration%20FOrm/Registration.html">Register</a>
  </div></center>

 
</form>
</body>
</html>
