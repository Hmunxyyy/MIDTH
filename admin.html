<?php 
session_start(); 
if(!isset($_SESSION['admin'])){ header("Location: login.php"); exit; } 

$db = new mysqli("localhost","root","","attendance_db");

$notify = $db->query("SELECT COUNT(*) AS c FROM notifications WHERE is_read = 0");
$count = $notify->fetch_assoc()['c'];


$data = $db->query("SELECT * FROM attendance ORDER BY id DESC");
?>

<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>Admin Dashboard</title>


<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

<style>
body{
    font-family:'Poppins',sans-serif;
    margin:0;
    min-height:100vh;
    padding:20px;
    background:#121212; /* สีดำพื้นหลัง */
    color:white;
}

.mail{
    position:fixed;
    top:20px;
    right:20px;
    font-size:26px;
    cursor:pointer;
    transition:0.3s;
}
.mail:hover{
    transform: scale(1.2);
}
.mail span{
    background:red;
    color:white;
    padding:3px 7px;
    border-radius:50%;
    font-size:14px;
    position:relative;
    top:-10px;
    left:-5px;
}

/* Header */
h2{
    text-align:center;
    margin-bottom:20px;
    animation: fadeSlideDown 0.8s forwards;
}

/* ปุ่มย้อนกลับ */
.back-btn{
    display:inline-block;
    margin-bottom:20px;
    padding:10px 20px;
    background:#ff6a00;
    color:white;
    border-radius:10px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}
.back-btn:hover{
    background:#ff3d00;
}

/* Table Card */
.table-wrapper{
    background: rgba(30,30,30,0.85);
    border-radius:15px;
    padding:20px;
    box-shadow:0 0 20px #0005;
    animation: fadeSlideUp 0.8s forwards;
}

.table{
    width:100%;
    border-collapse:collapse;
    color:white;
}
th{
    background:#ff6a00;
    padding:12px;
    text-align:left;
}
td{
    padding:12px;
    border-bottom:1px solid rgba(255,255,255,0.1);
    transition:0.3s;
}
tr:hover td{
    background: rgba(255,255,255,0.1);
}

/* Animations */
@keyframes fadeSlideDown{
    from {opacity:0; transform:translateY(-30px);}
    to {opacity:1; transform:translateY(0);}
}
@keyframes fadeSlideUp{
    from {opacity:0; transform:translateY(30px);}
    to {opacity:1; transform:translateY(0);}
}

</style>
</head>
<body>

<h2>📊 รายงานการเช็กชื่อ</h2>


<a href="index.php" class="back-btn"><i class='bx bx-arrow-back'></i> กลับหน้าหลัก</a>

<div class="table-wrapper">
    <table class="table">
        <tr>
            <th>ID</th>
            <th>ชื่อ</th>
            <th>สถานะ</th>
            <th>วันที่</th>
        </tr>
        <?php while($r = $data->fetch_assoc()){ ?>
        <tr>
            <td><?= $r['id'] ?></td>
            <td><?= $r['user_name'] ?></td>
            <td><?= $r['status'] ?></td>
            <td><?= $r['date'] ?></td>
        </tr>
        <?php } ?>
    </table>
</div>

</body>
</html>
