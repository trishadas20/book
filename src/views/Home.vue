<template>
  <section class="banner-section">
    <div class="banner-overlay">
      <div class="banner-content">

        <!-- LEFT SIDE TEXT -->
        <div class="banner-left">
          <h1>Welcome to Our Book Store</h1>
          <p>
            Explore a wide range of books, from academic to fiction and
            competitive exam guides. Discover knowledge, inspiration, and 
            imagination—all in one place. Order your favorite books easily!
          </p>
        </div>

        <!-- RIGHT SIDE FORM (Buy Book Form) -->
        <div class="banner-right">
          <form class="banner-form">
            <h2 class="form-title">Buy Your Book</h2>

            <input type="text" placeholder="Your Full Name" />
            <input type="email" placeholder="Email Address" />
            <input type="tel" placeholder="Phone Number" />

            <select>
              <option disabled selected>Select Book Category</option>
              <option>Academic Books</option>
              <option>School Books</option>
              <option>College Books</option>
              <option>Competitive Exam Books</option>
              <option>Story Books</option>
              <option>Kids Books</option>
            </select>

            <input type="text" placeholder="Book Name (if known)" />

            <textarea rows="3" placeholder="Any special request or author name"></textarea>

            <button type="submit">Place Order</button>
          </form>
        </div>

      </div>
    </div>
  </section>


  <section class="book-category-section">
  <h2 class="section-title">Explore Our Book Categories</h2>

  <div class="category-grid">

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/graduation-cap-books_23-2147501518.jpg?w=740" alt="Academic Books">
      <h3>Academic Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-photo/back-school-concept-with-notepad-books_23-2148632601.jpg?w=740" alt="School Books">
      <h3>School Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/stack-books-illustration_1308-171934.jpg?w=740" alt="College Books">
      <h3>College Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/online-test-illustration_23-2148575934.jpg?w=740" alt="Competitive Exams">
      <h3>Competitive Exam Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/book-lover-concept-illustration_114360-23503.jpg?w=740" alt="Story Books">
      <h3>Story Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/funny-kids-reading-books_23-2147652654.jpg?w=740" alt="Kids Books">
      <h3>Kids Books</h3>
    </div>

    <!-- NEW 4 CARDS -->
    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/realistic-education-book-composition_1284-11256.jpg?w=740" alt="Reference Books">
      <h3>Reference Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/psychology-concept-illustration_114360-9802.jpg?w=740" alt="Self-Help Books">
      <h3>Self-Help Books</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/creative-writing-abstract-concept_335657-3033.jpg?w=740" alt="Novel & Literature">
      <h3>Novels & Literature</h3>
    </div>

    <div class="category-card">
      <img src="https://img.freepik.com/free-vector/science-book-concept-illustration_114360-8030.jpg?w=740" alt="Science Books">
      <h3>Science Books</h3>
    </div>

  </div>
</section>

<section class="promo-banner-section">

  <!-- CARD 1 -->
  <div class="promo-card card1">
    <div class="promo-left">
      <img src="https://d34a0mln2492j4.cloudfront.net/unsigned/resize:fit:498:593:0/gravity:sm/plain/https%3A%2F%2Fimage-hub.reproindialtd.com%2F9780143475507.jpg" alt="Book">
    </div>
    <div class="promo-right">
      <h4 class="promo-subtitle">Meet The New-Age Queen</h4>
      <h2 class="promo-title">Manisha Rani’s Bold, Unfiltered Story</h2>
      <button class="promo-btn">Pre-Order Now</button>
    </div>
  </div>

  <!-- CARD 2 -->
  <div class="promo-card card2">
    <div class="promo-left">
      <img src="https://d34a0mln2492j4.cloudfront.net/unsigned/resize:fit:498:593:0/gravity:sm/plain/https%3A%2F%2Fimage-hub.reproindialtd.com%2F9780143457770.jpg" alt="Book">
    </div>
    <div class="promo-right">
      <h4 class="promo-subtitle">The Empress Who Defied An Empire</h4>
      <h2 class="promo-title">The Daring, Unforgettable Rise Of Nur Jahan</h2>
      <button class="promo-btn">Buy Now</button>
    </div>
  </div>
</section>

<section class="featured-books-section">
  <h2 class="section-title">Featured Books</h2>

  <div class="books-grid">

    <div class="book-card">
      <img src="https://d34a0mln2492j4.cloudfront.net/unsigned/resize:fit:498:593:0/gravity:sm/plain/https%3A%2F%2Fbookscape-s3-bucket.s3.amazonaws.com%2Fproduct_images%2F9789356294516.jpg" alt="Book">
      <h3>Modern Physics Basics</h3>
      <p class="price">₹499</p>
      <div class="rating">★★★★☆</div>
      <button class="buy-btn">Buy Now</button>
    </div>

    <div class="book-card">
      <img src="https://d34a0mln2492j4.cloudfront.net/unsigned/resize:fit:498:593:0/gravity:sm/plain/https%3A%2F%2Fbookscape-s3-bucket.s3.amazonaws.com%2Fproduct_images%2F9780143467359.jpg" alt="Book">
      <h3>Creative Writing Guide</h3>
      <p class="price">₹299</p>
      <div class="rating">★★★★★</div>
      <button class="buy-btn">Buy Now</button>
    </div>

    <div class="book-card">
      <img src="https://d34a0mln2492j4.cloudfront.net/unsigned/resize:fit:498:593:0/gravity:sm/plain/https%3A%2F%2Fbookscape-s3-bucket.s3.amazonaws.com%2Fproduct_images%2F9789355439154.jpg" alt="Book">
      <h3>Science Encyclopedia</h3>
      <p class="price">₹699</p>
      <div class="rating">★★★★☆</div>
      <button class="buy-btn">Buy Now</button>
    </div>

    <div class="book-card">
      <img src="https://www.crossword.in/cdn/shop/files/815zsgSV2TL._SL1500.jpg?v=1763379881&width=1000" alt="Book">
      <h3>Advanced Mathematics</h3>
      <p class="price">₹550</p>
      <div class="rating">★★★★★</div>
      <button class="buy-btn">Buy Now</button>
    </div>

  </div>
</section>


<section class="author-section">
    <h2 class="author-main-title">Meet Our Authors</h2>

    <!-- SWIPER -->
    <div class="swiper authorSwiper">
      <div class="swiper-wrapper">

        <!-- SLIDE 1 -->
        <div class="swiper-slide">
          <div class="author-container">
            <div class="author-img-box">
              <img src="../assets/author1.webp" class="author-img" />
            </div>

            <div class="author-content">
              <h2 class="author-title">Johnathan Reed</h2>
              <p class="author-desc">
                Award-winning writer known for emotionally rich storytelling.
              </p>

              <div class="author-book-box">
                <img src="../assets/book1.jpg" class="author-book-img" />
                <div>
                  <h3 class="book-title">The Light Within</h3>
                  <p class="book-desc">A global bestseller full of inspiration.</p>
                  <a href="#" class="author-btn">Buy Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 -->
        <div class="swiper-slide">
          <div class="author-container">
            <div class="author-img-box">
              <img src="../assets/auther2.webp" class="author-img" />
            </div>

            <div class="author-content">
              <h2 class="author-title">Sophia Martinez</h2>
              <p class="author-desc">
                Novelist creating worlds full of imagination.
              </p>

              <div class="author-book-box">
                <img src="../assets/book2.webp" class="author-book-img" />
                <div>
                  <h3 class="book-title">Winds of Destiny</h3>
                  <p class="book-desc">A magical tale of hope and destiny.</p>
                  <a href="#" class="author-btn">Buy Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 3 -->
        <div class="swiper-slide">
          <div class="author-container">
            <div class="author-img-box">
              <img src="../assets/auther3.webp" class="author-img" />
            </div>

            <div class="author-content">
              <h2 class="author-title">Michael Grant</h2>
              <p class="author-desc">
                Motivational author inspiring millions.
              </p>

              <div class="author-book-box">
                <img src="../assets/book3.jpg" class="author-book-img" />
                <div>
                  <h3 class="book-title">Rise Again</h3>
                  <p class="book-desc">Achieve goals & inner strength.</p>
                  <a href="#" class="author-btn">Buy Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 4 -->
        <div class="swiper-slide">
          <div class="author-container">
            <div class="author-img-box">
              <img src="../assets/authe4.webp" class="author-img" />
            </div>

            <div class="author-content">
              <h2 class="author-title">J.S. Gujral</h2>
              <p class="author-desc">
                Vice Chairman, SGI.
              </p>

              <div class="author-book-box">
                <img src="../assets/book4.webp" class="author-book-img" />
                <div>
                  <h3 class="book-title">Rise Again</h3>
                  <p class="book-desc">Achieve goals & inner strength.</p>
                  <a href="#" class="author-btn">Buy Now</a>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>

      

      <!-- PAGINATION -->
      <div class="swiper-pagination"></div>
    </div>
  </section>

<section class="six-image-section">
    <div class="image-row">

      <div class="img-box">
        <img src="../assets/img1.png" alt="">
      </div>

      <div class="img-box">
        <img src="../assets/img2.png" alt="">
      </div>

      <div class="img-box">
        <img src="../assets/img3.png" alt="">
      </div>

      <div class="img-box">
        <img src="../assets/img4.png" alt="">
      </div>

      <div class="img-box">
        <img src="../assets/img5.png" alt="">
      </div>

      <div class="img-box">
        <img src="../assets/img6.png" alt="">
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
<!--slider section js-->
<script>
import Swiper from "swiper";
import { Navigation, Pagination, Autoplay } from "swiper/modules";
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";

Swiper.use([Navigation, Pagination, Autoplay]);

export default {
  mounted() {
    new Swiper(".authorSwiper", {
      loop: true,
      slidesPerView: 1,
      spaceBetween: 40,
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
      pagination: {
        el: ".swiper-pagination",
        clickable: true,
      },
      autoplay: {
        delay: 3000,
        disableOnInteraction: false,
      },
    });
  },
};
</script>

<style>
  /* REMOVE ALL GAP */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* FULL WIDTH BANNER */
.banner-section {
  width: 100%;
  height: 700px;
  background: url('../assets/banner.avif') no-repeat center/cover;
  position: relative;
  margin-top: -30px;
}

/* OVERLAY */
.banner-overlay {
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.55);
  display: flex;
  align-items: center;
}

/* CONTENT */
.banner-content {
  width: 100%;
  height: 100%;
  padding: 0 5%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #fff;
}

/* LEFT SIDE */
.banner-left {
  width: 50%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.banner-left h1 {
  font-size: 55px;
  margin-bottom: 20px;
}

.banner-left p {
  font-size: 20px;
  max-width: 550px;
  line-height: 1.6;
}

/* RIGHT SIDE FORM */
.banner-right {
  width: 40%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* FORM */
.banner-form {
  width: 100%;
  max-width: 450px;
  background: #ffffff;
  padding: 35px;
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.banner-form .form-title {
  text-align: center;
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 10px;
  color: #333;
}

.banner-form input,
.banner-form select,
.banner-form textarea {
  padding: 14px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 15px;
  width: 100%;
}

.banner-form button {
  padding: 14px;
  background: #007bff;
  border: none;
  color: #fff;
  font-size: 16px;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.banner-form button:hover {
  background: #0056b3;
}


/* MOBILE VIEW */
@media (max-width: 768px) {

  .banner-section {
    height: auto;
    padding: 0;
  }

  /* Overlay should cover full banner area */
  .banner-overlay {
    width: 100%;
    height: auto;            /* Allow overlay to grow */
    min-height: 100%;        /* Always full height */
    padding: 40px 0;         /* Good spacing */
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  .banner-content {
    flex-direction: column;
    padding: 0 20px;
    text-align: center;
    gap: 25px;
  }

  /* LEFT TEXT */
  .banner-left {
    width: 100%;
    height: auto;
    align-items: center;
  }

  .banner-left h1 {
    font-size: 50px;
    line-height: 1.3;
  }

  .banner-left p {
    font-size: 15px;
    max-width: 100%;
  }

  /* RIGHT FORM */
  .banner-right {
    width: 100%;
    height: auto;
    justify-content: center;
  }

  .banner-form {
    width: 90%;
    max-width: 330px;
    padding: 20px;
    gap: 10px;
  }

  .banner-form input,
  .banner-form select,
  .banner-form textarea {
    padding: 10px;
    font-size: 14px;
  }

  .banner-form button {
    padding: 10px;
    font-size: 14px;
  }
}
</style>

<style>
  .book-category-section {
  padding: 80px 5%;
  text-align: center;
  background: #f4f4f9;
}

.section-title {
  font-size: 36px;
  font-weight: 700;
  margin-bottom: 40px;
  color: #2a1e50;
}

.category-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
}

.category-card {
  background: #fff;
  padding: 20px;
  border-radius: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.10);
  transition: 0.3s;
  cursor: pointer;
}

.category-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 6px 20px rgba(0,0,0,0.15);
}

.category-card img {
  width: 100%;
  height: 160px;
  object-fit: contain;
}

.category-card h3 {
  margin-top: 15px;
  font-size: 18px;
  font-weight: 600;
  color: #333;
}

/* 🔥 MOBILE VIEW — 2 CARDS PER ROW */
@media (max-width: 600px) {
  .category-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
  }

  .category-card img {
    height: 120px;
  }

  .section-title {
    font-size: 28px;
  }
}

</style>


<style>
   /* ---------- PROMO BANNER SECTION ---------- */

.promo-banner-section {
  padding: 80px 5%;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 25px;
}

/* Individual Promo Card */
.promo-card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 18px;
  padding: 40px;
  gap: 25px;
  color: #fff;
}

/* Card Background Colors */
.card1 {
  background: #4b3a52; /* Dark Purple/Brown */
}

.card2 {
  background: #7875c8; /* Soft Purple */
}

/* LEFT: Book Image */
.promo-left img {
  width: 200px;
  height: auto;
  border-radius: 10px;
  transform: rotate(-5deg);
}

/* RIGHT: Text Content */
.promo-right {
  max-width: 300px;
}

.promo-subtitle {
  font-size: 20px;
  font-weight: 700;
  margin-bottom: 10px;
  color: #ffd740;
}

.promo-title {
  font-size: 22px;
  line-height: 1.4;
  margin-bottom: 20px;
}

/* Button */
.promo-btn {
  padding: 10px 20px;
  border: 2px solid #fff;
  background: transparent;
  color: #fff;
  border-radius: 8px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

.promo-btn:hover {
  background: white;
  color: #333;
}

/* ---------- MOBILE RESPONSIVE ---------- */
@media (max-width: 768px) {
  .promo-card {
    flex-direction: column;
    text-align: center;
  }

  .promo-left img {
    width: 150px;
  }
}

</style>

<style>
  /* --------- FEATURED BOOKS SECTION --------- */

.featured-books-section {
  padding: 80px 5%;
  background: #eafaf1; /* soft mint */
  text-align: center;
}

.books-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
  margin-top: 40px;
}

.book-card {
  background: #fff;
  padding: 20px;
  border-radius: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: 0.3s;
}

.book-card:hover {
  transform: translateY(-7px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.book-card img {
  width: 100%;
  height: 180px;
  object-fit: contain;
  margin-bottom: 15px;
}

.book-card h3 {
  font-size: 18px;
  font-weight: 700;
  margin-bottom: 5px;
}

.price {
  font-size: 17px;
  color: #1e8f57;
  font-weight: 600;
  margin-bottom: 5px;
}

.rating {
  font-size: 16px;
  color: #ffb400;
  margin-bottom: 15px;
}

.buy-btn {
  padding: 10px 18px;
  background: #2a1e50;
  color: #fff;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.buy-btn:hover {
  background: #140d29;
}

/* Mobile View */
@media (max-width: 600px) {
  .books-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
  }

  .book-card img {
    height: 140px;
  }
}

</style>

<style>
 /* SECTION BACKGROUND */
.author-section {
  background: #f7f5ff;
  padding: 70px 0;
  text-align: center;
}

.author-main-title {
  font-size: 56px;
  color: #1abc9c;
  margin-bottom: 40px;
}

/* MAIN CONTAINER */
.author-container {
  max-width: 1100px;
  margin: auto;
  display: flex;
  align-items: center;
  gap: 40px;
  padding: 0 30px;
  padding-bottom:50px;
}

/* AUTHOR IMAGE */
.author-img-box {
  flex: 1;
}

.author-img {
  width: 100%;
  max-width: 380px;
  border-radius: 100px;
  box-shadow: 0 4px 25px rgba(0,0,0,0.1);
}

/* AUTHOR CONTENT */
.author-content {
  flex: 2;
  text-align: left;
}

.author-title {
  font-size: 22px;
  margin-bottom: 15px;
  color: #2a1e50;
}

.author-desc {
  font-size: 17px;
  color: #444;
  margin-bottom: 25px;
  line-height: 1.6;
}

/* BOOK SECTION */
.author-book-box {
  display: flex;
  align-items: center;
  gap: 20px;
  background: #fff;
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}

.author-book-img {
  width: 160px;
  border-radius: 10px;
}

.book-title {
  font-size: 22px;
  margin-bottom: 8px;
}

.book-desc {
  color: #555;
  margin-bottom: 15px;
}

/* BUTTON */
.author-btn {
  padding: 10px 22px;
  background: #4b3bd2;
  color: #fff;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
}

/* RESPONSIVE */
@media (max-width: 768px) {
  .author-container {
    flex-direction: column;
    text-align: center;
  }

  .author-content {
    text-align: center;
  }

  .author-book-box {
    flex-direction: column;
  }

  .author-img {
    max-width: 300px;
  }

  .author-book-img {
    width: 140px;
  }
}

/* SWIPER ARROWS COLOR */
.swiper-button-next, .swiper-button-prev {
  color: #4b3bd2;
}
</style>

<style>
 .six-image-section {
  padding: 60px 60px;
  background: #f7f5ff;
}

.image-row {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 15px;
}

.img-box img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

/* RESPONSIVE */
@media (max-width: 1024px) {
  .image-row {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 600px) {
  .image-row {
    grid-template-columns: repeat(2, 1fr);
  }
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