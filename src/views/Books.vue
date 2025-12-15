<template>
  <section class="books-section">
    <h1 class="page-title">Explore Books</h1>

    <div class="books-grid">

      <div class="book-card" v-for="book in books" :key="book.id">

        <!-- Book badge -->
        <span class="book-badge">Gently Used {{ book.discount }}%</span>

        <!-- Image -->
        <div class="book-image">
          <img :src="book.image" :alt="book.title" />
        </div>

        <!-- Content -->
        <h3 class="book-title">{{ book.title }}</h3>
        <p class="author">by {{ book.author }}</p>

        <p class="prices">
          <span class="old-price">Rs. {{ book.oldPrice }}</span>
          <span class="new-price">Rs. {{ book.newPrice }}</span>
        </p>

        <p class="format">{{ book.format }}</p>

        <!-- Rating -->
        <div class="rating">
          ⭐⭐⭐⭐☆
        </div>

        <!-- Cart -->
        <button class="cart-btn">Add to cart</button>

      </div>
    </div>
  </section>
</template>

<script>
import eb1 from "../assets/eb1.webp";
import eb2 from "../assets/eb2.webp";
import eb3 from "../assets/eb3.webp";
import eb4 from "../assets/eb4.webp";
import eb5 from "../assets/eb5.webp";
import eb6 from "../assets/eb6.avif";
import eb7 from "../assets/eb7.webp";
import eb8 from "../assets/eb8.webp";
import eb9 from "../assets/eb9.webp";
import eb10 from "../assets/eb10.avif";
import eb11 from "../assets/eb11.avif";
import eb12 from "../assets/eb12.avif";
import eb13 from "../assets/eb13.avif";
import eb14 from "../assets/eb14.avif";
import eb15 from "../assets/eb15.avif";
import eb16 from "../assets/eb16.webp";
import eb17 from "../assets/eb17.webp";
import eb18 from "../assets/eb18.webp";
import eb19 from "../assets/eb19.webp";
import eb20 from "../assets/eb20.webp";
export default {
  data() {
    return {
      books: [
        {
          id: 1,
          title: "Pride and Prejudice",
          author: "Jane Austen",
          oldPrice: 599,
          newPrice: 288,
          discount: 50,
          format: "Paperback",
          image: eb1
        },
        {
          id: 2,
          title: "Sinner (The Wolves of Mercy Falls)",
          author: "Maggie Stiefvater",
          oldPrice: 599,
          newPrice: 288,
          discount: 51,
          format: "Paperback",
          image: eb20
        },
        {
          id: 3,
          title: "Forever",
          author: "Maggie Stiefvater",
          oldPrice: 599,
          newPrice: 285,
          discount: 52,
          format: "Paperback",
          image: eb2
        },
        {
          id: 4,
          title: "Frostbitten",
          author: "Kelley Armstrong",
          oldPrice: 599,
          newPrice: 288,
          discount: 51,
          format: "Paperback",
          image: eb3
        },
        {
          id: 5,
          title: "Lovers And Players",
          author: "Jackie Collins",
          oldPrice: 499,
          newPrice: 175,
          discount: 64,
          format: "Paperback",
          image: eb4
        },
        {
          id: 6,
          title: "The Spell-Bound Scholar",
          author: "Christopher Stasheff",
          oldPrice: 499,
          newPrice: 135,
          discount: 72,
          format: "Mass Market Paperback",
          image: eb5
        },
        {
    id: 7,
    title: "The Great Gatsby",
    author: "F. Scott Fitzgerald",
    oldPrice: 499,
    newPrice: 220,
    discount: 56,
    format: "Paperback",
    image: eb6
  },
  {
    id: 8,
    title: "1984",
    author: "George Orwell",
    oldPrice: 499,
    newPrice: 210,
    discount: 58,
    format: "Paperback",
    image: eb7
  },
  {
    id: 9,
    title: "The Alchemist",
    author: "Paulo Coelho",
    oldPrice: 399,
    newPrice: 199,
    discount: 50,
    format: "Paperback",
    image: eb8
  },
  {
    id: 10,
    title: "Harry Potter and the Sorcerer's Stone",
    author: "J.K. Rowling",
    oldPrice: 799,
    newPrice: 480,
    discount: 40,
    format: "Paperback",
    image: eb9
  },
  {
    id: 11,
    title: "The Fault in Our Stars",
    author: "John Green",
    oldPrice: 499,
    newPrice: 260,
    discount: 48,
    format: "Paperback",
    image: eb10
  },
  {
    id: 12,
    title: "A Game of Thrones",
    author: "George R. R. Martin",
    oldPrice: 999,
    newPrice: 550,
    discount: 45,
    format: "Paperback",
    image: eb11
  },
  {
  id: 13,
  title: "The Alchemist",
  author: "Paulo Coelho",
  oldPrice: 499,
  newPrice: 299,
  discount: 40,
  format: "Paperback",
  image: eb12
},
{
  id: 14,
  title: "Atomic Habits",
  author: "James Clear",
  oldPrice: 799,
  newPrice: 420,
  discount: 47,
  format: "Paperback",
  image: eb13
},
{
  id: 15,
  title: "The Psychology of Money",
  author: "Morgan Housel",
  oldPrice: 599,
  newPrice: 350,
  discount: 42,
  format: "Paperback",
  image: eb14
},
{
  id: 16,
  title: "Rich Dad Poor Dad",
  author: "Robert Kiyosaki",
  oldPrice: 499,
  newPrice: 270,
  discount: 46,
  format: "Paperback",
  image: eb15
},
{
  id: 17,
  title: "Ikigai",
  author: "Héctor García & Francesc Miralles",
  oldPrice: 550,
  newPrice: 300,
  discount: 45,
  format: "Paperback",
  image: eb16
},
{
  id: 18,
  title: "Think and Grow Rich",
  author: "Napoleon Hill",
  oldPrice: 650,
  newPrice: 330,
  discount: 49,
  format: "Paperback",
  image: eb17
},
{
  id: 19,
  title: "Do It Today",
  author: "Darius Foroux",
  oldPrice: 399,
  newPrice: 210,
  discount: 47,
  format: "Paperback",
  image: eb18
},
{
  id: 20,
  title: "The Subtle Art of Not Giving a F*ck",
  author: "Mark Manson",
  oldPrice: 699,
  newPrice: 380,
  discount: 45,
  format: "Paperback",
  image: eb19
}

      ]
    };
  }
};
</script>

<style scoped>
.books-section {
  padding: 50px 20px;
  background: #faf8ff;
}

.page-title {
  text-align: center;
  font-size: 36px;
  color: #2a1e50;
  margin-bottom: 40px;
}

.books-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
  max-width: 1300px;
  margin: auto;
}

.book-card {
  background: #ffffff;
  padding: 15px;
  border-radius: 12px;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
  position: relative;
}

.book-badge {
  position: absolute;
  top: 10px;
  left: 10px;
  background: #c96b07;
  color: #fff;
  padding: 3px 10px;
  font-size: 12px;
  border-radius: 4px;
}

.book-image img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  margin-bottom: 15px;
  border-radius: 6px;
}

.book-title {
  font-size: 17px;
  font-weight: bold;
  color: #222;
  margin-bottom: 5px;
}

.author {
  color: #555;
  font-size: 14px;
  margin-bottom: 8px;
}

.prices {
  margin-bottom: 5px;
}

.old-price {
  text-decoration: line-through;
  color: #777;
  margin-right: 5px;
}

.new-price {
  font-weight: bold;
  color: #000;
}

.format {
  color: #333;
  font-size: 14px;
  margin-bottom: 10px;
}

.rating {
  color: #d48b00;
  margin-bottom: 12px;
}

.cart-btn {
  width: 100%;
  padding: 10px;
  background: #2a1e50;
  color: #fff;
  font-size: 15px;
  border-radius: 6px;
  cursor: pointer;
  border: none;
  transition: 0.3s;
}

.cart-btn:hover {
  background: #1b1333;
}
</style>
