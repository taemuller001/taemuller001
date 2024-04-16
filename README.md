<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>สมัครสมาชิกฟิตเนสมหาวิทยาลัยศรีปทุม</title>
    
</head>
<body>
    <h1>สมัครสมาชิกฟิตเนสมหาวิทยาลัยศรีปทุม</h1>
    <form action="process_registration.php" method="POST">
        <label for="username">ชื่อผู้ใช้:</label><br>
        <input type="text" id="username" name="username" required><br>

        <label for="email">อีเมล:</label><br>
        <input type="email" id="email" name="email" required><br>

        <label for="password">รหัสผ่าน:</label><br>
        <input type="password" id="password" name="password" required><br>

        <label for="confirm_password">ยืนยันรหัสผ่าน:</label><br>
        <input type="password" id="confirm_password" name="confirm_password" required><br>

        <input type="submit" value="สมัครสมาชิก">
        <input type="cancle" value="ยกเลิกการสมัครสมาชิก">
    </form>
</body>
</html>
