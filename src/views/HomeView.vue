<script setup lang="ts">
import { RouterLink, useRouter } from 'vue-router'

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
  <div class="home">
    <!-- Hero Section -->
    <section class="hero">
      <div class="container">
        <div class="hero-content">
          <h1 class="hero-title">Hello, I'm <span class="highlight">Hrishikesh Belagali</span></h1>
          <p class="hero-subtitle">Undergraduate Research Assistant</p>
          <p class="hero-description">
            I am a computer science major with research interests in quantum algorithms, molecular
            dynamics, reservoir computing, and high performance computing.
          </p>
          <div class="hero-buttons">
            <RouterLink to="/projects" class="btn btn-primary">View My Projects</RouterLink>
            <button @click="scrollToSection('publications')" class="btn btn-secondary">View My Publications</button>
            <RouterLink to="/contact" class="btn btn-outline">Contact me</RouterLink>
          </div>
        </div>
        <div class="hero-image">
          <div class="profile-image">
            <img src="/src/assets/profile.jpg" alt="Hrishikesh Belagali" class="profile-photo" />
          </div>
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section class="skills">
      <div class="container">
        <h2 class="section-title">Technologies I Work With</h2>
        <div class="skills-grid">
          <div class="skill-item">
            <h3>Languages</h3>
            <p>Python, C, C++, LaTeX</p>
          </div>
          <div class="skill-item">
            <h3>Packages</h3>
            <p>NumPy, PyTorch, scipy, Qiskit, hyperopt, PyEMMA, MDAnalysis, VMD-python</p>
          </div>
          <div class="skill-item">
            <h3>Softwares</h3>
            <p>NAMD, VMD, LAMMPS, OVITO</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Quick Links Section -->
    <section class="quick-links">
      <div class="container">
        <h2 class="section-title">Explore More</h2>
        <div class="links-grid">
          <RouterLink to="/about" class="link-card">
            <h3>About Me</h3>
            <p>Learn more about my background here :D</p>
          </RouterLink>
          <RouterLink to="/experience" class="link-card">
            <h3>Experience</h3>
            <p>Check out my experience!</p>
          </RouterLink>
          <RouterLink to="/projects" class="link-card">
            <h3>Projects</h3>
            <p>Explore my latest projects!</p>
          </RouterLink>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.hero {
  padding: 6rem 0;
  background: var(--color-background);
  position: relative;
  overflow: hidden;
}

.hero .container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
  position: relative;
  z-index: 1;
}

.hero-title {
  font-size: clamp(2.8rem, 6vw, 4.5rem);
  font-weight: 800;
  margin-bottom: 1rem;
  line-height: 1.1;
  letter-spacing: -0.02em;
  color: var(--color-heading);
}

.highlight {
  color: var(--color-primary);
  position: relative;
}

.hero-subtitle {
  font-size: clamp(1.25rem, 3vw, 1.75rem);
  font-weight: 600;
  color: var(--color-text-mute);
  margin-bottom: 2rem;
  letter-spacing: -0.01em;
}

.hero-description {
  font-size: clamp(1rem, 2.5vw, 1.2rem);
  line-height: 1.8;
  margin-bottom: 3rem;
  color: var(--color-text);
  max-width: 600px;
}

.hero-buttons {
  display: flex;
  gap: 1.5rem;
  flex-wrap: wrap;
}

.btn {
  padding: 1rem 2rem;
  border-radius: 0.75rem;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
  letter-spacing: -0.01em;
}

.btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
  transition: left 0.5s;
}

.btn:hover::before {
  left: 100%;
}

.btn-primary {
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  box-shadow: var(--shadow-md);
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-lg);
}

.btn-secondary {
  background: linear-gradient(135deg, var(--color-orange), var(--color-orange-dark));
  color: white;
  border: none;
  box-shadow: var(--shadow-md);
  cursor: pointer;
}

.btn-secondary:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-lg);
}

.btn-outline {
  background-color: transparent;
  color: var(--color-primary);
  border-color: var(--color-primary);
  box-shadow: var(--shadow-sm);
}

.btn-outline:hover {
  background-color: var(--color-primary);
  color: white;
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.hero-image {
  display: flex;
  justify-content: center;
  align-items: center;
}

.profile-image {
  width: 480px;
  height: 480px;
  border-radius: 50%;
  border: 4px solid var(--color-primary);
  overflow: hidden;
  box-shadow: var(--shadow-xl);
  transition: all 0.3s ease;
  position: relative;
}

.profile-image::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(45deg, transparent, rgba(59, 130, 246, 0.2), transparent);
  opacity: 0;
  transition: opacity 0.3s ease;
  z-index: 1;
}

.profile-image:hover::before {
  opacity: 1;
}

.profile-image:hover {
  transform: scale(1.05);
  box-shadow: var(--shadow-2xl);
}

.profile-photo {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center top;
  transition: all 0.3s ease;
}

@keyframes shimmer {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.skills {
  padding: 5rem 0;
}

.section-title {
  text-align: center;
  font-size: clamp(2rem, 4vw, 2.5rem);
  font-weight: 700;
  margin-bottom: 3rem;
  color: var(--color-heading);
  letter-spacing: -0.02em;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.skill-item {
  background: var(--color-background-soft);
  padding: 2.5rem;
  border-radius: 1.5rem;
  text-align: center;
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
  box-shadow: var(--shadow);
}

.skill-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: var(--gradient-primary);
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.skill-item:nth-child(1)::before {
  background: var(--gradient-primary);
}

.skill-item:nth-child(2)::before {
  background: var(--gradient-secondary);
}

.skill-item:nth-child(3)::before {
  background: var(--gradient-success);
}

.skill-item:hover::before {
  transform: scaleX(1);
}

.skill-item:hover {
  transform: translateY(-8px);
}

.skill-item:nth-child(1):hover {
  box-shadow: var(--shadow-blue);
}

.skill-item:nth-child(2):hover {
  box-shadow: var(--shadow-pink);
}

.skill-item:nth-child(3):hover {
  box-shadow: var(--shadow-cyan);
}

.skill-item h3 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

.skill-item:nth-child(1) h3 {
  color: var(--color-primary);
}

.skill-item:nth-child(2) h3 {
  color: var(--color-pink);
}

.skill-item:nth-child(3) h3 {
  color: var(--color-cyan);
}

.skill-item p {
  color: var(--color-text-mute);
  line-height: 1.7;
  font-size: 1rem;
}

.quick-links {
  padding: 5rem 0;
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.link-card {
  background-color: var(--color-background);
  padding: 2.5rem;
  border-radius: 1.5rem;
  text-decoration: none;
  color: var(--color-text);
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
  box-shadow: var(--shadow-sm);
}

.link-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-light));
  opacity: 0;
  transition: opacity 0.3s ease;
  z-index: 1;
}

/* Individual gradients for each link card */
.link-card:nth-child(1)::before {
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-light));
}

.link-card:nth-child(2)::before {
  background: linear-gradient(135deg, var(--color-pink), var(--color-pink-dark));
}

.link-card:nth-child(3)::before {
  background: linear-gradient(135deg, var(--color-orange), var(--color-orange-dark));
}

.link-card::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: var(--color-background);
  z-index: 2;
  transition: transform 0.3s ease;
}

.link-card:hover::before {
  opacity: 1;
}

.link-card:hover::after {
  transform: scale(0.98);
}

.link-card:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-xl);
}

.link-card h3 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  position: relative;
  z-index: 3;
}

.link-card:nth-child(1) h3 {
  color: var(--color-primary);
}

.link-card:nth-child(2) h3 {
  color: var(--color-pink);
}

.link-card:nth-child(3) h3 {
  color: var(--color-orange);
}

.link-card p {
  color: var(--color-text-mute);
  line-height: 1.7;
  position: relative;
  z-index: 3;
  margin: 0;
}

@media (max-width: 768px) {
  .container {
    padding: 0 1rem;
  }

  .hero {
    padding: 4rem 0;
  }

  .hero .container {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 3rem;
  }

  .hero-title {
    font-size: clamp(2.2rem, 8vw, 3rem);
    margin-bottom: 1rem;
  }

  .hero-subtitle {
    font-size: clamp(1.1rem, 4vw, 1.4rem);
    margin-bottom: 1.5rem;
  }

  .hero-description {
    font-size: clamp(0.95rem, 3vw, 1.1rem);
    margin-bottom: 2.5rem;
  }

  .hero-buttons {
    justify-content: center;
    gap: 1rem;
  }

  .btn {
    padding: 0.875rem 1.25rem;
    font-size: 0.9rem;
    flex: 1;
    min-width: 0;
    text-align: center;
  }

  .profile-image {
    width: 420px;
    height: 420px;
  }

  .skills {
    padding: 4rem 0;
  }

  .quick-links {
    padding: 4rem 0;
  }

  .skills-grid,
  .links-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .skill-item,
  .link-card {
    padding: 2rem;
  }
}

@media (max-width: 480px) {
  .hero-buttons {
    flex-direction: column;
    gap: 1rem;
  }
  
  .btn {
    width: 100%;
  }
}
</style>
