<?php
$conn = mysqli_connect('localhost','root','senior_care');
if(!$conn) {
     die('เชื่อมต่อฐานข้อมูลไม่สำเร็จ' . mysqli_connect_error($conn));
}else {
     echo"เชื่อมต่อฐานข้อมูลสำเร็จ";
}
?>
