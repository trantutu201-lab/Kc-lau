<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Shop Kim Cương</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    h1 {
      background: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      padding: 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 12px;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #28a745;
      color: white;
      border-radius: 8px;
      text-decoration: none;
    }
    .qr {
      margin-top: 20px;
      text-align: center;
    }
    .qr img {
      width: 200px;
      height: 200px;
    }
  </style>
</head>
<body>
  <h1>Shop Kim Cương</h1>

  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Gói 100 KC">
      <h3>Gói 100 Kim Cương</h3>
      <p>Giá: 20.000đ</p>
      <a href="#qrpay" class="btn">Mua ngay</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Gói 500 KC">
      <h3>Gói 500 Kim Cương</h3>
      <p>Giá: 90.000đ</p>
      <a href="#qrpay" class="btn">Mua ngay</a>
    </div>
  </div>

  <!-- QR Thanh toán -->
  <div id="qrpay" class="qr">
    <h2>Quét mã QR để thanh toán</h2>
    <img src="https://img.vietqr.io/image/vietinbank-1060486089-compact.png?accountName=Tran%20Xuan%20Tu" alt="QR Thanh toán">
    <p>STK: <b>1060486089</b> - VietinBank</p>
    <p>Chủ TK: <b>Tran Xuan Tu</b></p>
  </div>

</body>
</html>
