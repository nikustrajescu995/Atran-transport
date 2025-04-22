<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Artan Transport LLC</title>
  <style>
    :root {
      --primary: #d32f2f;
      --secondary: #000000;
      --light: #ffffff;
      --background: #f8f8f8;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      color: var(--secondary);
      background-color: var(--background);
      line-height: 1.6;
    }
    header {
      background-color: var(--secondary);
      color: var(--light);
      padding: 1.5rem;
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
    }
    header img {
      max-height: 80px;
      width: auto;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      font-weight: 700;
    }
    header p {
      margin: 0.2rem 0 0;
      font-size: 1.2rem;
      font-style: italic;
      color: #ccc;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 2rem;
      background: var(--light);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
      border-radius: 8px;
    }
    .section {
      margin-bottom: 2.5rem;
    }
    .section h2 {
      color: var(--primary);
      font-size: 1.8rem;
      margin-bottom: 0.5rem;
      border-bottom: 2px solid var(--primary);
      padding-bottom: 0.3rem;
    }
    .section p, .section ul {
      font-size: 1.05rem;
    }
    ul {
      padding-left: 1.2rem;
    }
    ul li {
      margin-bottom: 0.5rem;
    }
    .contact {
      background-color: #fff5f5;
      padding: 1.5rem;
      border-left: 4px solid var(--primary);
      border-radius: 8px;
    }
    .contact p {
      margin: 0.5rem 0;
      font-size: 1.1rem;
    }
    footer {
      background-color: var(--secondary);
      color: var(--light);
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      font-size: 0.95rem;
    }
    a {
      color: var(--primary);
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      header {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Artan Transport LLC Logo" />
    <div>
      <h1>Artan Transport LLC</h1>
      <p>Reliable. Professional. Nationwide.</p>
    </div>
  </header>

  <div class="container">
    <div class="section">
      <h2>About Us</h2>
      <p>
        At Artan Transport LLC, we pride ourselves on delivering freight with speed, safety, and reliability. Our experienced team and modern fleet make us the preferred partner for transportation solutions across the nation.
      </p>
    </div>

    <div class="section">
      <h2>Company Info</h2>
      <ul>
        <li><strong>MC Number:</strong> 1286430</li>
        <li><strong>USDOT Number:</strong> 3689304</li>
        <li><strong>Phone:</strong> <a href="tel:8642374320">864-237-4320</a></li>
      </ul>
    </div>

    <div class="section">
      <h2>Our Services</h2>
      <p>We offer a wide range of professional transportation services tailored to meet your needs:</p>
      <ul>
        <li><strong>Full Truckload (FTL) Services:</strong> Ideal for large shipments requiring dedicated transport.</li>
        <li><strong>Long-Haul & Regional Transport:</strong> Efficient logistics solutions covering coast-to-coast and regional hauls.</li>
        <li><strong>Time-Sensitive Deliveries:</strong> On-time, every time — we understand deadlines matter.</li>
        <li><strong>Dedicated Freight Solutions:</strong> Customized freight handling and regular routes for our valued partners.</li>
      </ul>
    </div>

    <div class="section contact">
      <h2>Contact Us</h2>
      <p>Ready to move with a company you can trust?</p>
      <p><strong>Call us:</strong> <a href="tel:8642374320">864-237-4320</a></p>
      <p><strong>Email:</strong> <a href="mailto:info@artantransport.com">info@artantransport.com</a></p>
    </div>
  </div>

  <footer>
    &copy; 2025 Artan Transport LLC. All rights reserved.
  </footer>
</body>
</html>
