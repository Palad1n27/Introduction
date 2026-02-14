<template>
  <div class="app-container">
    <!-- Navbar -->
    <header class="navbar">
      <div class="navbar-inner">
        <h1 class="logo">My Portfolio</h1>
        <nav class="nav-links">
          <router-link to="/" class="nav-link">Home</router-link>
          <router-link to="/projects" class="nav-link">Projects</router-link>
        </nav>
      </div>
    </header>

    <!-- Page content -->
    <main class="main-content">
      <router-view />
    </main>

    <!-- Footer -->
    <footer class="footer">
      © {{ new Date().getFullYear() }} My Portfolio. All rights reserved.
    </footer>
  </div>
</template>

<script setup></script>
