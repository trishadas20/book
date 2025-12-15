<template>
  <header class="navbar">
    <!-- LOGO -->
    <div class="logo">
      <img
        src="./assets/logo.jpg"
        alt="Logo"
      />
    </div>

    <!-- HAMBURGER BUTTON (mobile only) -->
    <div class="hamburger" @click="toggleMenu">
      {{ menuOpen ? '✖' : '☰' }}
    </div>

    <!-- NAV MENU -->
    <nav class="nav-menu" :class="{ 'show-menu': menuOpen }">
      <router-link to="/" class="nav-link" exact>Home</router-link>
      <router-link to="/about" class="nav-link">About</router-link>
      <router-link to="/services" class="nav-link">Services</router-link>
      <router-link to="/projects" class="nav-link">Projects</router-link>
      <router-link to="/blog" class="nav-link">Blog</router-link>
      <router-link to="/contact" class="nav-link">Contact</router-link>
    </nav>
  </header>

  <div class="content">
    <router-view />
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    },
  },
};
</script>

<style scoped>
/* ======================= */
/* DESKTOP NAVBAR */
/* ======================= */
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #241746;
  padding: 14px 30px;
  display: flex;
  align-items: center;
  z-index: 1000;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
}

.logo img {
  height: 55px;
  width: auto;
}

/* Desktop navigation */
.nav-menu {
  display: flex;
  gap: 25px;
  margin-left: auto;
  padding-right: 10px;
}

.nav-link {
  color: #ffffff;
  font-size: 17px;
  text-decoration: none;
  padding: 8px 14px;
  border-radius: 6px;
  transition: 0.3s;
  text-transform: uppercase;
}

.nav-link:hover {
  background: #34495e;
}

.router-link-active {
  background: none !important;
  border-bottom: 3px solid #1abc9c;
  padding-bottom: 6px;
  font-weight: 600;
}

.content {
  padding-top: 90px;
}

/* ======================= */
/* HAMBURGER BUTTON */
/* ======================= */
.hamburger {
  display: none;
  font-size: 32px;
  font-weight: bold;
  color: #fff;
  margin-left: auto;
  cursor: pointer;
  user-select: none;
}

/* ======================= */
/* MOBILE VIEW */
/* ======================= */
@media (max-width: 768px) {
  .navbar {
    padding: 12px 18px;
  }

  .logo img {
    height: 45px;
  }

  /* Show hamburger icon */
  .hamburger {
    display: block;
  }

  /* Hide desktop menu */
  .nav-menu {
    display: none;
    flex-direction: column;
    background: #241746;
    width: 100%;
    position: absolute;
    top: 70px;
    left: 0;
    padding: 20px 0;
    text-align: center;
    gap: 18px;
    border-top: 1px solid rgba(255, 255, 255, 0.18);
  }

  /* When menu is open */
  .nav-menu.show-menu {
    display: flex;
  }

  /* Mobile link design */
  .nav-link {
    font-size: 16px;
    padding: 12px 0;
    display: block;
  }

  .router-link-active {
    background: #34495e;
    border-radius: 5px;
    padding: 12px 0;
    border-bottom: none !important;
  }
}

/* Extra small screens */
@media (max-width: 480px) {
  .logo img {
    height: 40px;
  }

  .nav-link {
    font-size: 15px;
  }
}
</style>
