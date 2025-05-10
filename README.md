<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>تسجيل دخول إنستقرام - محاكاة</title>
  <style>
    body {
      background-color: #fafafa;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      background: white;
      border: 1px solid #ccc;
      padding: 40px;
      border-radius: 10px;
      width: 300px;
      text-align: center;
    }
    input[type="text"], input[type="password"] {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ddd;
      border-radius: 5px;
    }
    button {
      background-color: #3897f0;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 5px;
      cursor: pointer;
    }
    .warning {
      color: red;
      font-weight: bold;
      margin-bottom: 15px;
    }
    .notice {
      margin-top: 20px;
      font-size: 0.9em;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="warning">تنبيه: هذه محاكاة لصفحة تصيّد لغرض التوعية فقط</div>
    <h2>Instagram</h2>
    <form onsubmit="event.preventDefault(); showAlert();">
      <input type="text" placeholder="اسم المستخدم أو البريد الإلكتروني" required>
      <input type="password" placeholder="كلمة المرور" required>
      <button type="submit">تسجيل الدخول</button>
    </form>
    <div class="notice">
      لا تدخل معلوماتك الحقيقية. هذه الصفحة للتوعية فقط.
    </div>
  </div>  <script>
    function showAlert() {
      alert("لقد أدخلت بياناتك في صفحة مزيفة! هذه محاكاة تعليمية، احذر دائمًا وافحص الروابط.");
    }
  </script></body>
</html>
