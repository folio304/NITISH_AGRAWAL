<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Agrawal | CA Finalist</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet" />
  <style>
    body {
      background-color: #f9f9f9;
      color: #333;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }
    .hero {
      text-align: center;
      padding: 60px 20px 50px;
    }
    .hero img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #dcdcdc;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    @media (min-width: 768px) {
      .hero img {
        width: 300px;
        height: 300px;
      }
    }
    .hero h1 {
      font-size: 2rem;
      margin-top: 20px;
      font-weight: 700;
    }
    .hero h2 {
      font-size: 1.2rem;
      color: #666;
      margin-bottom: 10px;
    }
    .hero p {
      color: #777;
      max-width: 600px;
      margin: 0 auto 20px;
    }
    .section-title {
      text-align: center;
      margin-bottom: 40px;
      font-weight: 700;
      color: #555;
    }
    .service-card {
      background: #fff;
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: all 0.3s ease;
    }
    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }
    .service-icon {
      font-size: 40px;
      color: #666;
      margin-bottom: 15px;
    }
    .upi-section {
      text-align: center;
      margin-top: 50px;
    }
    .upi-section img {
      width: 200px;
      height: 200px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .btn-custom {
      background-color: #555;
      color: white;
      border-radius: 25px;
      padding: 10px 20px;
      border: none;
      transition: 0.3s;
    }
    .btn-custom:hover {
      background-color: #333;
    }
    footer {
      text-align: center;
      padding: 30px 0;
      background-color: #fff;
      color: #777;
      border-top: 1px solid #eee;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="hero">
    <img src="profile.jpg" alt="Profile Photo">
    <h1>Nitish Agrawal</h1>
    <h2>CA Finalist</h2>
    <p>Providing professional financial and taxation services along with managing multiple business ventures.</p>
    <a href="Nitish_Agrawal.vcf" download class="btn btn-custom"><i class="bi bi-person-lines-fill"></i> Save Contact</a>
  </section>

  <!-- Services Section -->
  <section id="services" class="container my-5">
    <h2 class="section-title">Services Offered</h2>
    <div class="row g-4 text-center">
      <div class="col-12 col-md-3">
        <div class="service-card">
          <i class="bi bi-file-earmark-text service-icon"></i>
          <h5>ITR Filing</h5>
          <p>Accurate and timely Income Tax Return filing for individuals and businesses.</p>
        </div>
      </div>
      <div class="col-12 col-md-3">
        <div class="service-card">
          <i class="bi bi-receipt service-icon"></i>
          <h5>GST Services</h5>
          <p>Comprehensive GST registration, filing, and compliance services.</p>
        </div>
      </div>
      <div class="col-12 col-md-3">
        <div class="service-card">
          <i class="bi bi-cash-coin service-icon"></i>
          <h5>Tax Audit</h5>
          <p>Professional audit support ensuring accuracy and adherence to tax regulations.</p>
        </div>
      </div>
      <div class="col-12 col-md-3">
        <div class="service-card">
          <i class="bi bi-bank service-icon"></i>
          <h5>Bank Audit</h5>
          <p>Efficient and compliant bank audit services for enhanced financial transparency.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Business Ventures -->
  <section id="ventures" class="container my-5">
    <h2 class="section-title">Business Ventures</h2>
    <div class="row g-4 text-center">
      <div class="col-12 col-md-4">
        <div class="service-card">
          <i class="bi bi-shop service-icon"></i>
          <h5>Poonam Kapda Dukan</h5>
          <p>Retail store offering a wide range of quality garments at affordable prices in Saraipali.</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="service-card">
          <i class="bi bi-cup-hot service-icon"></i>
          <h5>Poonam Bartan Dukan</h5>
          <p>Trusted shop for all household utensils and kitchenware essentials.</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="service-card">
          <i class="bi bi-tree service-icon"></i>
          <h5>Poonam Krishi Sewa Kendra</h5>
          <p>Providing agricultural products and services to support local farmers’ needs.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- UPI Section -->
  <div class="upi-section">
    <h4>Scan to Pay by any UPI app (PhonePe, GPay, Paytm)</h4>
    <img src="phonepayqr.jpg" alt="UPI QR Code">
    <div class="mt-3">
      <a href="phonepayqr.jpg" download class="btn btn-custom"><i class="bi bi-download"></i> Download UPI QR</a>
    </div>
  </div>

  <!-- Contact Section -->
  <section id="contact" class="container my-5">
    <h2 class="section-title">Contact</h2>
    <div class="text-center">
      <p><i class="bi bi-envelope"></i> nitishagrawal.ca@gmail.com</p>
      <p><i class="bi bi-geo-alt"></i> Saraipali, Chhattisgarh</p>
      <p><i class="bi bi-instagram"></i> <a href="https://www.instagram.com/nitishagrawal.ca" target="_blank">@nitishagrawal.ca</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Nitish Agrawal | All Rights Reserved</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
