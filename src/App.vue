<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import { useRouter } from 'vue-router'

const router = useRouter()

const scrollToSection = async (sectionId: string) => {
  // Navigate to experience page first
  await router.push('/experience')
  
  // Wait for next tick to ensure the page is rendered
  await new Promise(resolve => setTimeout(resolve, 100))
  
  // Scroll to the section
  const element = document.getElementById(sectionId)
  if (element) {
    element.scrollIntoView({ 
      behavior: 'smooth',
      block: 'start'
    })
  }
}
</script>

<template>
  <div id="app">
    <nav class="navbar">
      <div class="nav-container">
        <RouterLink to="/" class="nav-logo">My Portfolio</RouterLink>
        <ul class="nav-menu">
          <li class="nav-item">
            <RouterLink to="/" class="nav-link">Home</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink to="/about" class="nav-link">About</RouterLink>
          </li>
          <li class="nav-item dropdown">
            <RouterLink to="/experience" class="nav-link">Experience</RouterLink>
            <div class="dropdown-menu">
              <a @click="scrollToSection('experience')" class="dropdown-link">Experience</a>
              <a @click="scrollToSection('education')" class="dropdown-link">Education</a>
              <a @click="scrollToSection('research')" class="dropdown-link">Research & Publications</a>
            </div>
          </li>
          <li class="nav-item">
            <RouterLink to="/projects" class="nav-link">Projects</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
          </li>
        </ul>
      </div>
    </nav>

    <main class="main-content">
      <RouterView />
    </main>

    <footer class="footer">
      <div class="footer-content">
        <p>&copy; 2025 Hrishikesh Belagali. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
#app {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.navbar {
  background-color: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  box-shadow: var(--shadow-sm);
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
  border-bottom: 1px solid var(--color-border);
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 4rem;
}

.nav-logo {
  font-size: 1.5rem;
  font-weight: 700;
  color: var(--color-primary);
  text-decoration: none;
  letter-spacing: -0.02em;
}

.nav-menu {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
  gap: 0;
}

.nav-item {
  margin: 0;
  position: relative;
}

.dropdown {
  position: relative;
}

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  background: var(--color-background);
  border: 1px solid var(--color-border);
  border-radius: 0.75rem;
  box-shadow: var(--shadow-lg);
  min-width: 200px;
  padding: 0.5rem 0;
  opacity: 0;
  visibility: hidden;
  transform: translateY(-10px);
  transition: all 0.2s ease;
  z-index: 1001;
}

.dropdown:hover .dropdown-menu {
  opacity: 1;
  visibility: visible;
  transform: translateY(0);
}

.dropdown-link {
  display: block;
  color: var(--color-text);
  text-decoration: none;
  padding: 0.75rem 1.25rem;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.2s ease;
  border-radius: 0;
  cursor: pointer;
}

.dropdown-link:hover {
  color: var(--color-primary);
  background-color: rgba(139, 92, 246, 0.05);
}

.dropdown-link.router-link-active {
  color: var(--color-primary);
  background-color: rgba(139, 92, 246, 0.1);
}

.nav-link {
  color: var(--color-text);
  text-decoration: none;
  font-weight: 500;
  font-size: 0.95rem;
  padding: 0.5rem 1.5rem;
  border-radius: 0.5rem;
  transition: all 0.2s ease;
  position: relative;
}

.nav-link:hover {
  color: var(--color-primary);
  background-color: rgba(139, 92, 246, 0.05);
}

.nav-link.router-link-active {
  color: var(--color-primary);
  background-color: rgba(139, 92, 246, 0.1);
}

.main-content {
  flex: 1;
  margin-top: 4rem;
}

.footer {
  background-color: var(--color-background-mute);
  border-top: 1px solid var(--color-border);
  padding: 2rem 0;
  text-align: center;
  margin-top: 4rem;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.footer-content p {
  color: var(--color-text-mute);
  font-size: 0.9rem;
  margin: 0;
}

@media (max-width: 768px) {
  .nav-container {
    padding: 0 1rem;
  }

  .nav-menu {
    gap: 0;
  }

  .nav-link {
    padding: 0.5rem 0.75rem;
    font-size: 0.875rem;
  }

  .nav-logo {
    font-size: 1.25rem;
  }

  .dropdown-menu {
    min-width: 180px;
    right: 0;
    left: auto;
  }

  .dropdown-link {
    padding: 0.65rem 1rem;
    font-size: 0.875rem;
  }
}

@media (prefers-color-scheme: dark) {
  .navbar {
    background-color: rgba(15, 15, 15, 0.95);
  }
}
</style>
