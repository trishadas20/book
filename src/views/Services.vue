<template>
  
  <section class="image-text-section">
  <div class="image-text-container">

    <!-- Left Image -->
    <div class="image">
      <img
        src="../assets/delivery.webp"
        alt="Fast bike delivery"
      />
    </div>

    <!-- Right Content -->
    <div class="text-box">
      <h2>Our Services</h2>

      <p>
        We are committed to providing reliable and efficient services that make
        buying books simple, fast, and stress-free. Our focus is on delivering
        quality books right to your doorstep with complete care and transparency.
      </p>

      <p>
        With a strong delivery network and customer-first approach, we ensure
        that every order is packed securely, delivered on time, and supported
        by a responsive service team whenever you need assistance.
      </p>

      <ul class="service-points">
        <p>✔ Fast bike-based local delivery</p>
        <p>✔ Secure and damage-free packaging</p>
        <p>✔ Affordable pricing with great offers</p>
        <p>✔ Easy returns and customer support</p>
      </ul>
    </div>

  </div>
</section>


  <section class="services-section">
    <h1 class="page-title">Support Services</h1>
    <p class="page-subtitle">
  Discover a seamless book-buying experience with trusted services designed for every reader.
  Our commitment to quality books, secure delivery, easy returns, and dedicated customer support
  ensures a smooth and reliable shopping journey from start to finish.
</p>



    <div class="services-grid">
      <div class="service-card" v-for="service in services" :key="service.id">
        <div class="icon">{{ service.icon }}</div>
        <h3>{{ service.title }}</h3>
        <p>{{ service.description }}</p>
      </div>
    </div>
  </section>

  <section class="why-choose-section">
  <h2 class="section-title">Why Choose Us</h2>
  <p class="section-subtitle">
    We go beyond just selling books — we focus on quality, trust, and customer satisfaction.
  </p>

  <div class="choose-grid">
    <div class="choose-card">
      <h3>✔ Trusted by Readers</h3>
      <p>
        Thousands of readers trust us for affordable pricing, genuine books,
        and consistent service quality.
      </p>
    </div>

    <div class="choose-card">
      <h3>✔ Quality Assurance</h3>
      <p>
        Every book is carefully checked before shipping to ensure it meets
        our quality standards.
      </p>
    </div>

    <div class="choose-card">
      <h3>✔ Reader-Centric Approach</h3>
      <p>
        From easy browsing to smooth checkout and post-delivery support,
        we prioritize your reading experience.
      </p>
    </div>

    <div class="choose-card">
      <h3>✔ Safe & Secure Payments</h3>
      <p>
        Multiple secure payment options ensure your transactions are
        fast, safe, and reliable.
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

<script>
export default {
  data() {
    return {
      services: [
  {
    id: 1,
    icon: "📚",
    title: "Extensive Book Collection",
    description: "Explore a carefully curated collection of new, gently used, and rare books across fiction, non-fiction, academic, and competitive exam categories."
  },
  {
    id: 2,
    icon: "🚚",
    title: "Fast & Reliable Delivery",
    description: "Enjoy quick, safe, and reliable doorstep delivery with real-time order tracking for complete peace of mind."
  },
  {
    id: 3,
    icon: "💰",
    title: "Affordable Prices & Discounts",
    description: "Get the best value for your money with competitive pricing, seasonal offers, and exclusive discounts for book lovers."
  },
  {
    id: 4,
    icon: "🔄",
    title: "Easy Returns & Refunds",
    description: "Simple and transparent return policy ensuring hassle-free replacements or refunds for damaged or incorrect orders."
  },
  {
    id: 5,
    icon: "📦",
    title: "Secure & Eco-Friendly Packaging",
    description: "Every book is packed with care using secure and eco-friendly materials to protect it during transit."
  },
  {
    id: 6,
    icon: "📞",
    title: "Dedicated Customer Support",
    description: "Our friendly support team is always ready to assist you with orders, recommendations, and queries."
  },
  {
    id: 7,
    icon: "⭐",
    title: "Quality Checked Books",
    description: "Each book goes through a quality check to ensure you receive clean, readable, and well-maintained copies."
  },
  {
    id: 8,
    icon: "🎁",
    title: "Special Deals & Gift Options",
    description: "Perfect gifting options with exclusive deals for birthdays, festivals, and special occasions."
  }
]

    };
  }
};
</script>

<style>
  .image-text-section {
  padding: 80px 20px;
  background: #ffffff;
}

.image-text-container {
  max-width: 1200px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 50px;
  align-items: center;
}

.image img {
  width: 90%;
  
}

.text-box h2 {
  font-size: 34px;
  color: #2a1e50;
  margin-bottom: 20px;
}

.text-box p {
  font-size: 15px;
  color: #000;
  line-height: 1.8;
  margin-bottom: 15px;
}

.service-points {
  list-style: none;
  padding-left: 0;
  margin-top: 20px;
}

.service-points li {
  font-size: 15px;
  color: #333;
  margin-bottom: 10px;
}


</style>

<style scoped>
.services-section {
  padding: 60px 20px;
  background: #faf8ff;
  text-align: center;
}

.page-title {
  font-size: 36px;
  color: #2a1e50;
  margin-bottom: 10px;
}

.page-subtitle {
  color: #555;
  font-size: 18px;
  margin-bottom: 40px;
  padding-left:50px;
  padding-right:50px;
}

.services-grid {
  max-width: 1200px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 25px;
}

.service-card {
  background: #ffffff;
  padding: 30px 20px;
  border-radius: 14px;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
  transition: 0.3s;
}

.service-card:hover {
  transform: translateY(-6px);
}

.icon {
  font-size: 40px;
  margin-bottom: 15px;
}

.service-card h3 {
  font-size: 18px;
  color: #222;
  margin-bottom: 10px;
}

.service-card p {
  font-size: 14px;
  color: #555;
  line-height: 1.6;
}
</style>

<style>
  .why-choose-section {
  padding: 70px 20px;
  background: #ffffff;
  text-align: center;
}

.section-title {
  font-size: 32px;
  color: #2a1e50;
  margin-bottom: 10px;
}

.section-subtitle {
  max-width: 700px;
  margin: 0 auto 40px;
  font-size: 16px;
  color: #555;
}

.choose-grid {
  max-width: 1100px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.choose-card {
  padding: 25px 20px;
  border-radius: 14px;
  background: #faf8ff;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.choose-card h3 {
  font-size: 18px;
  color: #222;
  margin-bottom: 10px;
}

.choose-card p {
  font-size: 14px;
  color: #555;
  line-height: 1.6;
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