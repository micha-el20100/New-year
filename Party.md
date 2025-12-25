<!DOCTYPE html>
<html>
<head>
  <title>Christmas 2025</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      background-color: #0B3D2E;
      text-align: center;
      font-family: Arial;
      color: white;
    }

    button {
      background: #3630a3;
      color: white;
      padding: 12px 30px;
      border: none;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
      transition: transform 0.2s;
    }

    button:active {
      transform: scale(1.1);
    }
  </style>
</head>

<body>

  <h2 style="color:#C1121F;">Be a member in this evening 🎄</h2>

  <label style="color:#FFD700;">Name</label><br>
  <input id="username" style="color:blue;"><br><br>

  <button onclick="showMSG()">Done 🎁</button>

  <script>
    function showMSG() {
      var name = document.getElementById("username").value;
      if (name === "") {
        name = "Friend";
      }

      alert(
        "🎄 Merry Christmas " + name + " 🎄\n" +
        "We are so happy for being here with us 😍🎅\n" +
        "Let's start !!"
      );
    }
  </script>

  <br><br>

  <h6 style="color:gray;">
    416, Roushdy floor 3, apartment 14.<br>
    31/1/2025 at 5pm.
  </h6>
  <h6 style="color:gray;">Don't be late!</h6>

  <a href="https://www.instagram.com/micha_el20100?igsh=aW5seTFzcXkwNTg3"
     style="color:white; text-decoration:none;">
    Call us
  </a>

</body>
</html>
