<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>منصة الحضور والتسميع</title>
</head>
<body>
  <h2>قائمة الطلاب</h2>

  <p>أحمد خالد 
    <button onclick="mark('أحمد خالد','حاضر')">حاضر</button>
    <button onclick="mark('أحمد خالد','غائب')">غائب</button>
    <button onclick="mark('أحمد خالد','تسميع')">تسميع</button>
  </p>

  <p>محمد عمر 
    <button onclick="mark('محمد عمر','حاضر')">حاضر</button>
    <button onclick="mark('محمد عمر','غائب')">غائب</button>
    <button onclick="mark('محمد عمر','تسميع')">تسميع</button>
  </p>

  <script>
    function mark(student, status) {
      alert("تم تسجيل: " + student + " - " + status);
    }
  </script>
</body>
</html>
