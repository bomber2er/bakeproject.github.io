<?php 
session_start();
$host = null;
$user = "";
$password = "";
$database = "";
$port = null;
$socket = "";
$conn = new mysqli($host, $user, $password, $database, $port, $socket);
if(mysqli_connect_error()){
  echo mysqli_connect_error();
  exit();
}

$msg = "";
if($_POST) {
  $msg = "";
  $login = $_POST['Username'];
  $password = $_POST['Password'];
  $type = $_POST['type'];
  
  //ถ้าเป็นผู้ทดสอบ
  if($type == "admin") {
    if($login === "admin" && $password === "password") {
      $_SESSION['user'] = "admin";
      header("Location: admin.php");
      exit;
    }
    else { 
      $msg = "Incorrect Login OR Password!!";
    }
  }
  else if($type == "user") {
    //include "dblink.php";
    $sql = "SELECT * FROM studentanswer WHERE login = '$login' AND password = '$password'";
    $_SESSION['login'] = $login;
    $result = mysqli_query($conn, $sql);
    if(!$result) {
      $msg = "Try Again!!!";
    }
    else {
      $r = mysqli_num_rows($result);
      if($r == 1) {
        $row = mysqli_fetch_array($result);
        $_SESSION['user'] = "user";
        $_SESSION['testee_id'] = $row[0];
        $_SESSION['testee_name'] = $row[1] . "  " . $row[2]; 
        
        mysqli_close($conn);
        header("location: user.php");
        exit;
      }
      else {
        $msg = "Incorrect Login OR Password!!!";
      }
    }
    mysqli_close($conn);
  }
}
/*if($_POST) {
  if($_POST['Username'] == "admin" && $_POST['Password'] == "password") {
    $_SESSION['admin'] = 1;
    header("location:admin.php");
    exit;
  }
  else if ($_POST['Username'] == "5988036" && $_POST['Password'] == "5988036"){
    $_SESSION['user'] = 1;
    header("location:user.php");
    exit;
  }
  else {
    $msg = "Incorrect Username or Password !!!";
  }

}*/
?>

<!DOCTYPE html>
<html>
<head>
	<title>Login</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="style.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://fonts.googleapis.com/css?family=Bree+Serif|Cabin|Concert+One|Crete+Round|Indie+Flower|Lora|Pacifico|Patrick+Hand+SC|Permanent+Marker|Quicksand|Roboto+Slab" rel="stylesheet">
</head>


<body>

<!-- Contact Information -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h1 class="w3-center w3-text-teal" style="font-family: 'Crete Round', serif;"><b><u>LOG IN</u></b></h1>
  <h4 class="w3-center" style="font-family: 'Roboto Slab', serif;">Restaurant & Bakery Management System</h4>

  <div class="w3-row w3-padding-32 w3-section">
  	<div class="w3-col m6 w3-center w3-padding-large">
      <img src="restaurant-logo.png" class="w3-round w3-image w3-hover-opacity-off" alt="logo" width="500" height="250">
    </div>

    <div class="w3-col m6 w3-hide-small w3-padding-large">
      
      <h5 style="font-family: 'Crete Round', serif;">Username</h5>
<!-- Button and Form Action -->
      <form method="post" target="_self">
        
        <input class="w3-input w3-border" style="font-family: 'Crete Round', serif;" type="text" placeholder="Username" required name="Username">
        <h5 style="font-family: 'Crete Round', serif;">Password</h5>
        <input class="w3-input w3-border" style="font-family: 'Crete Round', serif;" type="password" placeholder="Password" required name="Password">

      <h6 style="font-family: 'Crete Round', serif;">User Type:</h6>
      <input type="radio" name="type" value="admin"> Admin
      <input type="radio" name="type" value="manager"> Manager
      <input type="radio" name="type" value="staff"> Staff
      <br>
      <h6 class="w3-text-teal" style="font-family: 'Crete Round', serif;">Hint: Username and Password are your Staff ID</h6>
        <button class="w3-button w3-black w3-left w3-section" style="font-family: 'Crete Round', serif;" type="submit" target="_self">
          <i class="fa fa-paper-plane"></i> LOG IN
        </button>
      </form><br><br><br> 
      <h3 style="red" class="err"><?php echo $msg; ?></h3>

    </div>
    <div class="w3-col m4 w3-center w3-padding-large">
      
    </div>

    <div class="w3-col m8 w3-hide-small w3-padding-large w3-container">

    </div>
  </div>
</div>


<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="index.html" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity w3-xxlarge"></i>
    <i class="fa fa-twitter w3-hover-opacity w3-xxlarge"></i>
  </div>
  <h5 style="font-family: 'Ubuntu'">Contact Us: thanachanok.sir@student.mahidol.edu</h5>
</footer>

</body>
</html>