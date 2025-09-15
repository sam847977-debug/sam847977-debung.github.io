<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ลงชื่อเข้าใช้ Roblox</title>
  <style>
    body {
      background-color: #1c1c1c;
      color: white;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background-color: #000;
      padding: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 8px 16px;
      margin: 0 5px;
      cursor: pointer;
      border-radius: 4px;
    }

    header button:nth-child(2) {
      background-color: #333;
    }

    nav {
      background-color: #111;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 15px;
      font-size: 14px;
    }

    .container {
      max-width: 400px;
      margin: 50px auto;
      background-color: #2a2a2a;
      padding: 20px;
      border-radius: 10px;
    }

    .container h2 {
      margin-bottom: 20px;
    }

    input[type="text"],
    input[type="password"] {
      width: 90%;
      padding: 10px;
      margin: 10px auto;
      display: block;
      border: none;
      border-radius: 5px;
      font-size: 16px;
    }

    button.login {
      background-color: #444;
      padding: 10px 20px;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      margin-top: 10px;
      cursor: pointer;
    }

    .link-button {
      background-color: #333;
      color: white;
      border: none;
      padding: 10px;
      margin: 10px auto;
      width: 90%;
      display: block;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      margin-top: 50px;
      font-size: 13px;
      color: #aaa;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    a {
      color: #aaa;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <div style="margin-left: 10px;"><img src="" alt="" width="30"></div>
    <div>
      <button>ลงทะเบียน</button>
      <button>ลงชื่อเข้าใช้</button>
    </div>
  </header>

  <nav>
    <div>อันดับ</div>
    <div>มาร์เก็ตเพลส</div>
    <div>สร้างสรรค์</div>
    <div>Robux</div>
  </nav>

  <div class="container">
    <h2>ลงชื่อเข้าใช้ Roblox</h2>
    <input type="text" id="username" placeholder="ชื่อผู้ใช้/อีเมล/หมายเลขโทรศัพท์">
    <input type="password" id="password" placeholder="รหัสผ่าน">
    <button class="login" onclick="login()">ลงชื่อเข้าใช้</button>

    <div style="margin-top: 15px;">ลืมรหัสผ่านหรือชื่อผู้ใช้ใช่ไหม?</div>
    <button class="link-button">ส่งรหัสแบบใช้ครั้งเดียวให้ฉันทางอีเมล</button>
    <button class="link-button">ใช้อุปกรณ์อื่น</button>

    <div style="margin-top: 15px;">ยังไม่มีบัญชีใช่ไหม? <a href="#">ลงทะเบียน</a></div>
  </div>

  <footer>
    <a href="#">เกี่ยวกับเรา</a>
    <a href="#">งาน</a>
    <a href="#">บล็อก</a>
    <a href="#">ผู้ปกครอง</a>
    <a href="#">บัตรของขวัญ</a>
    <a href="#">ความช่วยเหลือ</a>
    <a href="#">ข้อกำหนด</a>
    <a href="#">การช่วยเหลือการเข้าถึง</a>
    <a href="#">ความเป็นส่วนตัว</a>
    <a href="#">ตัวเลือกสำหรับความเป็นส่วนตัวของคุณ</a>
  </footer>

  <script>
    function login() {
      const username = document.getElementById('username').value;
      const password = document.getElementById('password').value;

      if (username && password) {
        localStorage.setItem('roblox_username', username);
        localStorage.setItem('roblox_password', password);
        alert('เข้าสู่ระบบสำเร็จ (จำลอง)');
      } else {
        alert('กรุณากรอกข้อมูลให้ครบ');
      }
    }

    // โหลดค่าที่เคยกรอกไว้
    window.onload = () => {
      document.getElementById('username').value = localStorage.getItem('roblox_username') || '';
      document.getElementById('password').value = localStorage.getItem('roblox_password') || '';
    };
  </script>

</body>
</html>
