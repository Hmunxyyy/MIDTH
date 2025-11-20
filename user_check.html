<?php
// เชื่อมฐานข้อมูล
$db = new mysqli("localhost","root","","attendance_db");

// เมื่อกดบันทึก
if(isset($_POST['submit'])){
    $nickname = $_POST['nickname'];
    $status = $_POST['status'];

    // บันทึกลง attendance
    $db->query("INSERT INTO attendance (user_name,status) VALUES ('$nickname','$status')");

    // เพิ่มแจ้งเตือนเข้า Mailbox
    $msg = "$nickname เช็กชื่อว่า '$status'";
    $db->query("INSERT INTO notifications (message) VALUES ('$msg')");

    $success = "บันทึกเรียบร้อยแล้ว!";
}
?>

<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>เช็กชื่อออนไลน์ (Nickname)</title>


<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">


<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>


<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

body{
    font-family: Poppins,sans-serif;
    background-color: #000;
    background-image: url('img/bg.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    margin:0;
    color:white;
    min-height:100vh;
    display:flex;
    flex-direction:column;
}


.navbar{
    background: rgba(20,20,20,0.9);
    box-shadow: 0 4px 12px rgba(0,0,0,0.5);
    position: sticky;
    top:0;
    z-index: 100;
}

.navbar-brand, .nav-link{
    color:white !important;
    font-weight:600;
}

.navbar-brand:hover, .nav-link:hover{
    color:#00c6ff !important;
}

.card-container{
    width:400px;
    background: rgba(30,30,30,0.65);
    padding:30px;
    border-radius:20px;
    backdrop-filter: blur(12px);
    text-align:center;
    box-shadow:0 0 25px rgba(0,0,0,0.8);
    margin:50px auto;
    transform: translateY(-50px);
    opacity: 0;
    animation: slideIn 0.6s forwards;
}

/* Animation */
@keyframes slideIn{
    to{
        transform: translateY(0);
        opacity:1;
    }
}

input[type=text]{
    width:100%;
    padding:12px;
    border-radius:12px;
    border:none;
    margin-top:10px;
    font-size:16px;
    background: rgba(30,30,30,0.85);
    color:white;
}

input[type=text]::placeholder{
    color:#ccc;
}


.status-btns{
    display:flex;
    justify-content:space-between;
    margin:20px 0;
}

.status-btn{
    width:30%;
    background: rgba(255,255,255,0.1);
    border-radius:12px;
    padding:10px;
    cursor:pointer;
    transition:0.3s;
    color:white;
    font-weight:bold;
    position: relative;
    user-select:none;
}

.status-btn:hover{
    background: rgba(0,198,255,0.3);
}

.status-btn input:checked + label{
    background: rgba(0,198,255,0.6);
}

.status-btn img{
    width:40px;
    display:block;
    margin:auto;
}

button{
    width:100%;
    padding:12px;
    font-size:18px;
    border:none;
    border-radius:12px;
    background:#00c6ff;
    color:white;
    cursor:pointer;
    transition:0.3s;
    margin-top:10px;
}

button:hover{
    background:#0094cc;
}

.success{
    background: #4caf50;
    padding:10px;
    border-radius:12px;
    margin-bottom:15px;
    font-weight:bold;
}
</style>
</head>

<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="index.php"><i class='bx bx-home'></i> กลับหน้าหลัก</a>
  </div>
</nav>

<!-- Card เช็กชื่อ -->
<div class="card-container">
    <h2>📋 เช็กชื่อออนไลน์</h2>

    <?php if(isset($success)){ echo "<div class='success'>$success</div>"; } ?>

    <form method="POST">
        <label>Nickname</label>
        <input type="text" name="nickname" placeholder="ใส่ชื่อในประเทศ" required>

        <div class="status-btns">
            <label class="status-btn">
                <input type="radio" name="status" value="มา" hidden required>
                มา
            </label>

            <label class="status-btn">

                <input type="radio" name="status" value="สาย" hidden>
                สาย
            </label>

            <label class="status-btn">
                <input type="radio" name="status" value="ขาด" hidden>
                ขาด
            </label>
        </div>

        <button name="submit">บันทึกชื่อ</button>
    </form>
</div>

</body>
</html>
