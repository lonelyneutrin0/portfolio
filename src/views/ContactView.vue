<template>
  <div class="contact">
    <div class="container">
      <h1 class="page-title">Get In Touch</h1>
      <p class="page-subtitle">
        I'm always interested to learn new things and explore new opportunities! Let's connect and
        discuss how we can work together!
      </p>

      <div class="contact-content">
        <div class="contact-info">
          <h2>Contact Information</h2>

          <div class="contact-item">
            <div class="contact-icon">📧</div>
            <div class="contact-details">
              <h3>Email</h3>
              <p>hkbelagali@gmail.com</p>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">📍</div>
            <div class="contact-details">
              <h3>Location</h3>
              <p>East Lansing, MI</p>
            </div>
          </div>

          <div class="social-links">
            <h3>Connect with me</h3>
            <div class="social-grid">
              <a href="https://github.com/lonelyneutrin0" target="_blank" class="social-link">
                <span class="social-icon">💻</span>
                GitHub
              </a>
              <a href="https://linkedin.com/in/hkbel" target="_blank" class="social-link">
                <span class="social-icon">💼</span>
                LinkedIn
              </a>
              <a href="mailto:hkbelagali@gmail.com" class="social-link">
                <span class="social-icon">📧</span>
                Email
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// Contact page - no form submission needed
</script>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.page-title {
  text-align: center;
  font-size: clamp(2.5rem, 5vw, 4rem);
  font-weight: 800;
  margin-bottom: 1.5rem;
  color: var(--color-heading);
  letter-spacing: -0.02em;
  position: relative;
}

.page-title::after {
  content: '';
  position: absolute;
  bottom: -0.75rem;
  left: 50%;
  transform: translateX(-50%);
  width: 60px;
  height: 4px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.page-subtitle {
  text-align: center;
  font-size: 1.25rem;
  color: var(--color-text-mute);
  margin-bottom: 4rem;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
  line-height: 1.7;
}

.contact-content {
  max-width: 800px;
  margin: 0 auto;
}

.contact-info h2 {
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: 2.5rem;
  color: var(--color-primary);
  letter-spacing: -0.02em;
  position: relative;
}

.contact-info h2::after {
  content: '';
  position: absolute;
  bottom: -0.5rem;
  left: 0;
  width: 40px;
  height: 3px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.contact-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 2rem;
  padding: 2rem;
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  border-radius: 1.5rem;
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
}

.contact-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.contact-item:hover::before {
  transform: scaleX(1);
}

.contact-item:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-lg);
}

.contact-icon {
  font-size: 2.5rem;
  margin-right: 1.5rem;
  min-width: 3.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  background: rgba(59, 130, 246, 0.1);
  border-radius: 1rem;
  height: 3.5rem;
}

.contact-details h3 {
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  color: var(--color-text);
}

.contact-details p {
  color: var(--color-text-mute);
  font-size: 1rem;
  margin: 0;
}

.social-links {
  margin-top: 3rem;
}

.social-links h3 {
  font-size: 1.375rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
  color: var(--color-text);
}

.social-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
}

.social-link {
  display: flex;
  align-items: center;
  padding: 1.25rem;
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  border-radius: 1rem;
  text-decoration: none;
  color: var(--color-text);
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
}

.social-link::before {
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

.social-link:hover::before {
  opacity: 1;
}

.social-link:hover {
  color: white;
  transform: translateY(-3px);
  box-shadow: var(--shadow-md);
}

.social-icon {
  font-size: 1.5rem;
  margin-right: 1rem;
  position: relative;
  z-index: 2;
}

.social-link span:last-child {
  position: relative;
  z-index: 2;
  font-weight: 600;
}

@media (max-width: 768px) {
  .container {
    padding: 0 1rem;
  }

  .page-title {
    font-size: 2.5rem;
  }

  .page-subtitle {
    font-size: 1.125rem;
    margin-bottom: 3rem;
  }

  .contact-content {
    gap: 2rem;
  }

  .social-grid {
    grid-template-columns: 1fr;
  }

  .contact-item {
    padding: 1.5rem;
  }

  .contact-icon {
    font-size: 2rem;
    min-width: 3rem;
    height: 3rem;
    margin-right: 1rem;
  }
}
</style>
