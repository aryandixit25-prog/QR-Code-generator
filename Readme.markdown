<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Hydra Safety QR</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<style>
  body { font-family: Arial; text-align:center; padding:20px; }
</style>
</head>
<body>

<h2>Scan QR Code to open Hydra Safety page</h2>
<div id="qrcode"></div>

<script>
  // Replace with your hosted HTML page URL
  var url = "https://yourdomain.com/hydra_safety.html"; 
  var qrcode = new QRCode(document.getElementById("qrcode"), {
      text: url,
      width: 200,
      height: 200
  });
</script>

</body>
</html>



