# Password-Visibility-Toggle
<html>
<head>
  <title>Password Toggle</title>
</head>
<body>

  Password:
  <input type="password" id="pass">

  <br><br>

  <input type="checkbox" onclick="showPassword()"> Show Password

  <script>
    function showPassword() {
      var x = document.getElementById("pass");

      if (x.type === "password") {
        x.type = "text";
      } else {
        x.type = "password";
      }
    }
  </script>

</body>
</html>
