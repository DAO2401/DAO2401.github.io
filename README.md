# DAO2401.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Tradify-like Website</title>
  <style>
    /* Reset and base styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background: #f9fafb;
      color: #333;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: #2563eb;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 2rem 0;
    }
    header {
      background: #2563eb;
      color: white;
      padding: 1rem 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-weight: 700;
      font-size: 1.5rem;
    }
    nav a {
      margin-left: 1.5rem;
      font-weight: 600;
    }
    /* Hero */
    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      padding: 3rem 0;
    }
    .hero-text {
      flex: 1 1 400px;
    }
    .hero-text h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero-text p {
      font-size: 1.2rem;
      margin-bottom: 1.5rem;
      color: #555;
    }
    .btn {
      background: #2563eb;
      color: white;
      padding: 0.8rem 1.5rem;
      border-radius: 4px;
      font-weight: 600;
      cursor: pointer;
      border: none;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #1e40af;
    }
    .hero-image {
      flex: 1 1 400px;
      text-align: center;
    }
    .hero-image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    /* Features */
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap: 2rem;
      margin: 4rem 0;
    }
    .feature {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgb(0 0 0 / 0.05);
      text-align: center;
    }
    .feature h3 {
      margin-bottom: 1rem;
      color: #2563eb;
    }
    /* Testimonials */
    .testimonials {
      background: #2563eb;
      color: white;
      padding: 3rem 2rem;
      border-radius: 8px;
      margin-bottom: 4rem;
    }
    .testimonials h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-weight: 700;
    }
    .testimonial {
      max-width: 700px;
      margin: 0 auto 2rem;
      font-style: italic;
    }
    .testimonial strong {
      display: block;
      margin-top: 0.5rem;
      font-style: normal;
      text-align: right;
    }
    /* Pricing */
    .pricing {
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
      margin-bottom: 4rem;
    }
    .plan {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgb(0 0 0 / 0.05);
      flex: 1 1 250px;
      text-align: center;
    }
    .plan h3 {
      margin-bottom: 1rem;
      color: #2563eb;
    }
    .plan-price {
      font-size: 2rem;
      margin-bottom: 1rem;
      font-weight: 700;
    }
    .plan-features {
      margin-bottom: 1.5rem;
      list-style: none;
      color: #555;
      text-align: left;
      padding-left: 0;
    }
    .plan-features li {
      padding: 0.3rem 0;
    }
    /* Footer */
    footer {
      text-align: center;
      padding: 1rem 0;
      background: #1e40af;
      color: white;
      font-size: 0.9rem;
    }
    /* Responsive */
    @media (max-width: 768px) {
      .hero {
        flex-direction: column;
      }
      .pricing {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header class="container">
    <h1>Tradify</h1>
    <nav>
      <a href="#features">Features</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#pricing">Pricing</a>
      <a href="#signup">Sign Up</a>
    </nav>
  </header>

  <section class="hero container">
    <div class="hero-text">
      <h2>Manage Your Trades & Jobs Seamlessly</h2>
      <p>Tradify helps small business owners and tradies simplify quoting, scheduling, and invoicing in one easy app.</p>
      <button class="btn">Get Started Free</button>
    </div>
    <div class="hero-image">
      <img src="https://via.placeholder.com/500x300?text=App+Screenshot" alt="App screenshot" />
    </div>
  </section>

  <section id="features" class="container features">
    <div class="feature">
      <h3>Job Management</h3>
      <p>Create and track jobs from start to finish with ease.</p>
    </div>
    <div class="feature">
      <h3>Scheduling</h3>
      <p>Manage your team schedules and deadlines effortlessly.</p>
    </div>
    <div class="feature">
      <h3>Invoicing</h3>
      <p>Send invoices and get paid faster with automated tools.</p>
    </div>
    <div class="feature">
      <h3>Quoting</h3>
      <p>Generate professional quotes in minutes to win more work.</p>
    </div>
  </section>

  <section id="testimonials" class="testimonials">
    <h2>What Our Customers Say</h2>
    <div class="testimonial">
      "Tradify has transformed the way we run our business — more efficient and less stress!"  
      <strong>- Sarah T, Electrician</strong>
    </div>
    <div class="testimonial">
      "The invoicing feature alone has saved us hours each week."  
      <strong>- Mike P, Plumber</strong>
    </div>
  </section>

  <section id="pricing" class="container pricing">
    <div class="plan">
      <h3>Basic</h3>
      <div class="plan-price">$10/mo</div>
      <ul class="plan-features">
        <li>Up to 5 jobs</li>
        <li>Email support</li>
        <li>Basic reports</li>
      </ul>
      <button class="btn">Choose Plan</button>
    </div>
    <div class="plan">
      <h3>Pro</h3>
      <div class="plan-price">$25/mo</div>
      <ul class="plan-features">
        <li>Unlimited jobs</li>
        <li>Priority support</li>
        <li>Advanced reporting</li>
      </ul>
      <button class="btn">Choose Plan</button>
    </div>
  </section>

  <footer>
    &copy; 2025 Tradify. All rights reserved.
  </footer>
</body>
</html>
