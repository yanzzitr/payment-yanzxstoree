<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pembayaran QR</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    .payment-methods {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }
    .method {
      background-color: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 200px;
    }
    .method img {
      width: 150px;
      height: 150px;
      object-fit: contain;
      margin-bottom: 10px;
    }
    .method h3 {
      margin: 0;
      font-size: 1.1em;
      color: #555;
    }
  </style>
</head>
<body>

  <h1>Pilih Metode Pembayaran</h1>

  <div class="payment-methods">
    <div class="method">
      <img src="qris.png" alt="QRIS">
      <h3>QRIS</h3>
    </div>
    <div class="method">
      <img src="dana.png" alt="Dana">
      <h3>Dana</h3>
    </div>
    <div class="method">
      <img src="ovo.png" alt="OVO">
      <h3>OVO</h3>
    </div>
    <div class="method">
      <img src="gopay.png" alt="GoPay">
      <h3>GoPay</h3>
    </div>
  </div>

  <p>Scan QR sesuai metode yang Anda gunakan untuk membayar.</p>

</body>
</html>
