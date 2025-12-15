<template>
  <section class="about-section">
    <div class="about-container">

      <!-- Left Image -->
      <div class="about-image">
        <img src="../assets/about.jpg" alt="Book Store" />
      </div>

      <!-- Right Content -->
      <div class="about-content">
        <h1>About Us</h1>
        <p>
          Welcome to our Book Store — your trusted place for knowledge,
          imagination, and inspiration. We offer a wide collection of books,
          from academic to fiction, competitive exams, children’s stories,
          journals, and more.
        </p>

        <p style="margin-bottom: 30px;">
          Our mission is to make reading accessible and enjoyable for everyone.
          We believe that every book has the power to spark curiosity and shape
          minds. With a commitment to quality, affordability, and customer
          satisfaction, we continue to grow as a community of book lovers.
        </p>

       <router-link to="/books" class="about-btn">Explore Books</router-link>

      </div>

    </div>
  </section>

  <section class="why-section">
    <h2 class="why-title">Why Choose Our Book Store?</h2>

    <div class="why-container">

      <div class="why-box">
        <h3>📚 Wide Collection</h3>
        <p>
          Thousands of books across genres — academic, fiction, competitive
          exams, kids’ books, journals, and more.
        </p>
      </div>

      <div class="why-box">
        <h3>💸 Affordable Prices</h3>
        <p>
          We provide quality books at the best prices so everyone can enjoy
          reading without hesitation.
        </p>
      </div>

      <div class="why-box">
        <h3>🚚 Fast Delivery</h3>
        <p>
          Get your favorite books delivered quickly and safely to your doorstep.
        </p>
      </div>

      <div class="why-box">
        <h3>⭐ Trusted by Readers</h3>
        <p>
          Thousands of happy customers trust our service and book quality.
        </p>
      </div>

    </div>
  </section>

  <section class="mission-section">
    <div class="mission-container">

      <div class="mission-box">
        <h2>📘 Our Mission</h2>
        <p>
          Our mission is to provide readers with access to quality books that inspire,
          educate, and empower. We aim to make reading a joyful and accessible
          experience for people of all ages.
        </p>
      </div>

      <div class="mission-box">
        <h2>🎯 Our Vision</h2>
        <p>
          Our vision is to build a strong community of book lovers by offering
          a diverse collection, seamless service, and innovative reading
          experiences that shape the future of learning.
        </p>
      </div>

    </div>
  </section>

  <footer class="footer-section">

    <!-- TOP GRID -->
    <div class="footer-container">

      <!-- ABOUT -->
      <div class="footer-col">
        <h3 class="footer-title">BookStore</h3>
        <p class="footer-text">
          Your trusted place to buy academic books, novels, study guides, and more.
        </p>
      </div>

      <!-- QUICK LINKS -->
      <div class="footer-col">
        <h4 class="footer-subtitle">Quick Links</h4>
        <ul class="footer-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Books</a></li>
          <li><a href="#">Authors</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>

      <!-- CUSTOMER SERVICE -->
      <div class="footer-col">
        <h4 class="footer-subtitle">Customer Service</h4>
        <ul class="footer-links">
          <li><a href="#">Shipping Policy</a></li>
          <li><a href="#">Return Policy</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">FAQs</a></li>
        </ul>
      </div>

      <!-- CONTACT -->
      <div class="footer-col">
        <h4 class="footer-subtitle">Contact Us</h4>
        <ul class="footer-contact">
          <li>Email: support@bookstore.com</li>
          <li>Phone: +91 98765 43210</li>
          <li>Address: Kolkata, India</li>
        </ul>
      </div>

    </div>

    <!-- BOTTOM COPYRIGHT -->
    <div class="footer-bottom">
      © 2025 BookStore. All Rights Reserved.
    </div>

  </footer>
</template>

<style scoped>
.about-section {
  padding: 60px 20px;
  background: #f8f6ff;
}

.about-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 40px;
  max-width: 1100px;
  margin: auto;
  flex-wrap: wrap;
}

.about-image img {
  width: 100%;
  max-width: 320px;
  border-radius: 12px;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
}

.about-content {
  flex: 1;
  min-width: 300px;
}

.about-content h1 {
  font-size: 36px;
  margin-bottom: 15px;
  color: #2a1e50;
}

.about-content p {
  line-height: 1.7;
  margin-bottom: 15px;
  color: #444;
}

.about-btn {
  background: #2a1e50;
  color: #fff;
  padding: 12px 25px;
  border-radius: 8px;
  font-size: 16px;
  border: none;
  cursor: pointer;
  transition: 0.3s;
}

.about-btn:hover {
  background: #1b1333;
}

/* Responsive */
@media(max-width: 768px) {
  .about-container {
    flex-direction: column;
    text-align: center;
  }

  .about-image img {
    max-width: 100%;
  }
}
</style>

<style scoped>
.why-section {
  padding: 60px 20px;
  background: #ffffff;
  text-align: center;
}

.why-title {
  font-size: 32px;
  margin-bottom: 40px;
  color: #2a1e50;
}

.why-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
  max-width: 1100px;
  margin: auto;
}

.why-box {
  background: #f3f0ff;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.why-box h3 {
  font-size: 20px;
  margin-bottom: 10px;
  color: #2a1e50;
}

.why-box p {
  color: #444;
  line-height: 1.6;
}
</style>
<style scoped>
.mission-section {
  padding: 60px 20px;
  background: #ffffff;
}

.mission-container {
  max-width: 1100px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.mission-box {
  background: #f8f6ff;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.mission-box h2 {
  color: #2a1e50;
  margin-bottom: 12px;
  font-size: 24px;
}

.mission-box p {
  color: #444;
  line-height: 1.8;
  font-size: 16px;
}
</style>

<style>
.footer-section {
  background: #1f1a38;
  color: #fff;
  padding: 60px 20px 20px;
  margin-top: 40px;
}

.footer-container {
  max-width: 1200px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 40px;
}

.footer-title {
  font-size: 26px;
  font-weight: 700;
  margin-bottom: 15px;
}

.footer-subtitle {
  font-size: 20px;
  margin-bottom: 15px;
  color: #f2c94c;
}

.footer-text {
  line-height: 1.6;
  color: #ddd;
}

.footer-links li,
.footer-contact li {
  list-style: none;
  margin-bottom: 8px;
}

.footer-links a {
  color: #ddd;
  text-decoration: none;
}

.footer-links a:hover {
  color: #f2c94c;
}

.footer-bottom {
  text-align: center;
  padding-top: 25px;
  border-top: 1px solid #3a335c;
  margin-top: 30px;
  color: #bbb;
  font-size: 14px;
}

/* RESPONSIVE */
/* RESPONSIVE */
@media (max-width: 900px) {
  .footer-container {
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
  }
}

@media (max-width: 550px) {
  .footer-section {
    padding: 35px 15px 15px; /* Smaller padding */
  }

  .footer-container {
    grid-template-columns: 1fr; /* Single column */
    gap: 15px; /* Smaller gap */
  }

  .footer-title {
    font-size: 20px; /* smaller title */
    margin-bottom: 8px;
  }

  .footer-subtitle {
    font-size: 16px;
    margin-bottom: 8px;
  }

  .footer-text {
    font-size: 14px;
    line-height: 1.4;
  }

  .footer-links li,
  .footer-contact li {
    font-size: 14px; /* smaller text */
    margin-bottom: 5px;
  }

  .footer-bottom {
    font-size: 12px;
    padding-top: 15px; /* smaller bottom padding */
  }
}

</style>