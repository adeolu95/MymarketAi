<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>My Market AI - Unlock Market Insights with AI</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <!-- Header with Navigation and Hero Section -->
    <header>
      <nav>
        <div class="container">
          <h1 class="logo">My Market AI</h1>
          <ul class="nav-links">
            <li><a href="#hero">Home</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#how-it-works">How It Works</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
      <div id="hero">
        <div class="hero-content">
          <h2>Unlock Market Insights with AI</h2>
          <p>Leverage advanced algorithms to predict market trends and make smarter investment decisions.</p>
          <a href="#signup" class="btn">Get Started for Free</a>
        </div>
      </div>
    </header>

    <!-- Main Content -->
    <main>
      <!-- About Section -->
      <section id="about" class="section">
        <h2>About My Market AI</h2>
        <p>My Market AI uses state-of-the-art machine learning to analyze market data and uncover long-term trends. Our platform is designed to help investors and traders make informed decisions based on deep data insights.</p>
      </section>

      <!-- Features Section -->
      <section id="features" class="section">
        <h2>Features</h2>
        <div class="features-container">
          <div class="feature-item">
            <h3>Accurate Predictions</h3>
            <p>Our algorithms deliver reliable forecasts by detecting subtle, long-term market patterns.</p>
          </div>
          <div class="feature-item">
            <h3>Real-Time Analysis</h3>
            <p>Stay updated with continuous data streams and real-time analytics to keep ahead of trends.</p>
          </div>
          <div class="feature-item">
            <h3>User-Friendly Dashboard</h3>
            <p>Customize your view to track the metrics that matter most to your strategy.</p>
          </div>
        </div>
      </section>

      <!-- How It Works Section -->
      <section id="how-it-works" class="section">
        <h2>How It Works</h2>
        <ol class="steps">
          <li><strong>Data Collection:</strong> Our system aggregates vast amounts of market data.</li>
          <li><strong>Algorithm Analysis:</strong> Advanced models analyze trends and dependencies.</li>
          <li><strong>Insight Delivery:</strong> Receive actionable insights directly to your dashboard.</li>
        </ol>
      </section>

      <!-- Pricing Section -->
      <section id="pricing" class="section">
        <h2>Pricing</h2>
        <div class="pricing-container">
          <div class="pricing-plan">
            <h3>Starter</h3>
            <p class="price">$29/month</p>
            <ul>
              <li>Basic Market Analysis</li>
              <li>Limited Data Access</li>
              <li>Email Support</li>
            </ul>
            <a href="#signup" class="btn">Choose Plan</a>
          </div>
          <div class="pricing-plan">
            <h3>Professional</h3>
            <p class="price">$79/month</p>
            <ul>
              <li>Advanced Analytics</li>
              <li>Real-Time Data</li>
              <li>Priority Support</li>
            </ul>
            <a href="#signup" class="btn">Choose Plan</a>
          </div>
          <div class="pricing-plan">
            <h3>Enterprise</h3>
            <p class="price">Contact Us</p>
            <ul>
              <li>Custom Solutions</li>
              <li>Dedicated Support</li>
              <li>Full Data Integration</li>
            </ul>
            <a href="#contact" class="btn">Contact Sales</a>
          </div>
        </div>
      </section>

      <!-- Signup Call-to-Action Section -->
      <section id="signup" class="section">
        <h2>Start Your Free Trial</h2>
        <p>Experience the power of My Market AI with a 14-day free trial—no credit card required.</p>
        <form action="#" method="post" class="signup-form">
          <input type="email" placeholder="Enter your email" required>
          <button type="submit" class="btn">Sign Up Now</button>
        </form>
      </section>

      <!-- Testimonials Section -->
      <section id="testimonials" class="section">
        <h2>What Our Users Say</h2>
        <div class="testimonial">
          <p>"My Market AI has transformed my trading strategy. The insights are accurate and actionable, giving me a competitive edge in the market."</p>
          <cite>— Alex T., Professional Trader</cite>
        </div>
      </section>
    </main>

    <!-- Footer / Contact Section -->
    <footer id="contact">
      <div class="footer-content">
        <p>Contact us: <a href="mailto:support@mymarketai.com">support@mymarketai.com</a></p>
        <p>&copy; 2025 My Market AI. All rights reserved.</p>
      </div>
    </footer>
  </body>
</html>


/* General Reset and Base Styles */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    color: #333;
  }
  
  a {
    text-decoration: none;
    color: inherit;
  }
  
  .container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  /* Navigation */
  nav {
    background-color: #444;
    color: #fff;
    padding: 10px 0;
  }
  nav .logo {
    font-size: 24px;
    font-weight: bold;
    display: inline-block;
    margin-left: 20px;
  }
  nav .nav-links {
    list-style: none;
    padding: 0;
    margin: 0;
    display: inline-block;
  }
  nav .nav-links li {
    display: inline-block;
    margin: 0 15px;
  }
  nav .nav-links li a {
    color: #fff;
    font-weight: bold;
  }
  
  /* Hero Section */
  #hero {
    background: url('hero-background.jpg') center/cover no-repeat;
    padding: 80px 20px;
    color: #fff;
  }
  .hero-content {
    background-color: rgba(0, 0, 0, 0.5);
    padding: 40px;
    border-radius: 5px;
    display: inline-block;
  }
  .hero-content h2 {
    font-size: 36px;
    margin-bottom: 20px;
  }
  .hero-content p {
    font-size: 18px;
    margin-bottom: 30px;
  }
  .btn {
    background-color: #e67e22;
    color: #fff;
    padding: 12px 25px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
  }
  .btn:hover {
    background-color: #cf711f;
  }
  
  /* Section Styles */
  .section {
    padding: 60px 20px;
    background-color: #fff;
    margin: 20px 0;
  }
  .section h2 {
    font-size: 28px;
    margin-bottom: 20px;
  }
  .section p {
    font-size: 16px;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto 20px;
  }
  
  /* Features Section */
  .features-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .feature-item {
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: 300px;
    margin: 10px;
    padding: 20px;
  }
  .feature-item h3 {
    margin-top: 0;
  }
  
  /* How It Works (Steps) */
  .steps {
    list-style-type: decimal;
    max-width: 600px;
    margin: 0 auto;
    text-align: left;
    padding-left: 40px;
  }
  .steps li {
    margin: 15px 0;
  }
  
  /* Pricing Section */
  .pricing-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .pricing-plan {
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: 300px;
    margin: 10px;
    padding: 20px;
  }
  .pricing-plan h3 {
    margin-top: 0;
  }
  .pricing-plan .price {
    font-size: 24px;
    color: #e67e22;
    margin: 10px 0;
  }
  .pricing-plan ul {
    list-style-type: none;
    padding: 0;
    text-align: left;
  }
  .pricing-plan ul li {
    margin: 8px 0;
  }
  
  /* Signup Form */
  .signup-form {
    max-width: 400px;
    margin: 0 auto;
  }
  .signup-form input[type="email"] {
    width: 70%;
    padding: 10px;
    margin-right: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
  .signup-form button {
    padding: 10px 20px;
    border: none;
    background-color: #e67e22;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
  }
  .signup-form button:hover {
    background-color: #cf711f;
  }
  
  /* Testimonials Section */
  .testimonial {
    max-width: 800px;
    margin: 0 auto;
    font-style: italic;
  }
  .testimonial cite {
    display: block;
    margin-top: 10px;
    font-style: normal;
    color: #555;
  }
  
  /* Footer */
  footer {
    background-color: #444;
    color: #fff;
    padding: 20px 0;
  }
  .footer-content a {
    color: #e67e22;
  }
  
