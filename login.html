<?php
session_start();
$db = new mysqli("localhost","root","","attendance_db");

if(isset($_POST['login'])){
    $username = $_POST['username'];
    $password = $_POST['password'];

    $q = $db->query("SELECT * FROM admin WHERE username='$username' AND password='$password'");

    if($q->num_rows > 0){
        $_SESSION['admin'] = $username;
        header("Location: admin.php");
    } else {
        $error = "ชื่อผู้ใช้หรือรหัสผ่านผิด!";
    }
}
?>

<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>Admin Login</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">


<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>


<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    height:100vh;
    background:#121212;
    color:white;
    display:flex;
    flex-direction:column;
    align-items:center;
}


.navbar{
    background:#1f1f1f;
    width:100%;
    position:fixed;
    top:0;
    z-index:100;
}

.navbar-brand, .nav-link{
    color:white !important;
}


.login-card{
    background: rgba(30,30,30,0.85);
    backdrop-filter: blur(10px);
    border-radius:20px;
    padding:40px 30px;
    width:350px;
    box-shadow:0 10px 30px rgba(0,0,0,0.7);
    text-align:center;
    color:white;
    margin-top:120px;
    opacity:0;
    transform: translateY(-50px);
    animation: slideIn 0.8s forwards;
}


@keyframes slideIn{
    to{
        opacity:1;
        transform: translateY(0);
    }
}

.login-card h1{
    font-size:24px;
    margin-bottom:5px;
    font-weight:600;
    color:#f0f0f0;
}

.login-card h2{
    margin-bottom:20px;
    font-size:20px;
    font-weight:400;
    color:#bbbbbb;
}

.login-card input{
    width:100%;
    padding:12px 15px;
    margin:10px 0;
    border:none;
    border-radius:10px;
    font-size:16px;
    outline:none;
    background:#1e1e1e;
    color:white;
    transition:0.3s;
}

.login-card input:focus{
    background:#2c2c2c;
    box-shadow:0 0 8px #00c6ff;
}

.login-card input::placeholder{
    color:#aaa;
}

.login-card button{
    width:100%;
    padding:12px;
    border:none;
    border-radius:12px;
    background:#ff6a00;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:0.3s;
    margin-top:10px;
}

.login-card button:hover{
    background:#ff3d00;
    transform: scale(1.03);
}

.error-msg{
    background: rgba(255,0,0,0.3);
    padding:8px;
    border-radius:10px;
    margin-bottom:15px;
}

.icon{
    font-size:50px;
    margin-bottom:10px;
    color:#ff6a00;
}

.back-btn{
    margin-top:15px;
    display:inline-block;
    color:#ff6a00;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.back-btn:hover{
    color:#ff3d00;
}
</style>
</head>

<body>

<nav class="navbar navbar-expand-lg shadow-lg">
  <div class="container">
    <a class="navbar-brand" href="index.php">
        <i class='bx bx-home'></i> กลับหน้าแรก
    </a>
  </div>
</nav>

<div class="login-card">
    <i class='bx bxs-lock-alt icon'></i>
    <h1>Boss Winterfell Aaron</h1>
    <h2>Admin Login</h2>

    <?php if(isset($error)) echo "<div class='error-msg'>$error</div>"; ?>

    <form method="POST">
        <input type="text" name="username" placeholder="ชื่อผู้ใช้" required>
        <input type="password" name="password" placeholder="รหัสผ่าน" required>
        <button name="login"><i class='bx bx-log-in'></i> เข้าสู่ระบบ</button>
    </form>

</div>

</body>
</html>
