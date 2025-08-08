<template>
  <div class="about">
    <div class="container">
      <div class="about-hero">
        <div class="about-content">
          <h1 class="page-title">About Me</h1>
          <p class="about-intro">
            Hello! I'm a computer science major in the MSU Honors College. I work as an
            undergraduate research assistant for Vermaas Lab, which is part of the Plant Research
            Laboratory. I am currently exploring water transit in aquaporins using grid-steered
            molecular dynamics.
          </p>
          <p class="about-intro">
            Outside of college, I love to play video games including VALORANT, Apex Legends,
            Minecraft, Besiege, and many more. I'm currently halfway through Cyberpunk 2077 :). I
            also love to run long-distance and cook (Mexican and Italian are my favorite cuisines).
          </p>
        </div>
      </div>

      <!-- Skills & Interests -->
      <section class="skills-interests">
        <div class="skills-column">
          <h2 class="section-title">Technical Skills</h2>
          <div class="skills-categories">
            <div class="skill-category">
              <h3>Languages</h3>
              <div class="skill-tags">
                <span class="skill-tag red">Python</span>
                <span class="skill-tag purple">C</span>
                <span class="skill-tag cyan">C++</span>
                <span class="skill-tag yellow">LaTeX</span>
              </div>
            </div>
            <div class="skill-category">
              <h3>Packages</h3>
              <div class="skill-tags">
                <span class="skill-tag green">NumPy</span>
                <span class="skill-tag red">PyTorch</span>
                <span class="skill-tag yellow">scipy</span>
                <span class="skill-tag purple">Qiskit</span>
                <span class="skill-tag cyan">PyEMMA</span>
                <span class="skill-tag orange">hyperopt</span>
                <span class="skill-tag pink">VMD-Python</span>
                <span class="skill-tag green">pytest</span>
              </div>
            </div>

            <div class="skill-category">
              <h3>Tools & Technologies</h3>
              <div class="skill-tags">
                <span class="skill-tag red">Git</span>
                <span class="skill-tag blue">VMD</span>
                <span class="skill-tag orange">NAMD</span>
                <span class="skill-tag purple">OVITO</span>
                <span class="skill-tag green">LAMMPS</span>
              </div>
            </div>
          </div>
        </div>

        <div class="interests-column">
          <h2 class="section-title">Interests & Hobbies</h2>
          <div class="interests-grid">
            <div class="interest-item">
              <div class="interest-icon">🥘</div>
              <h3>Cooking</h3>
              <p>
                I love cooking and exploring new cuisines! My favorite dishes are burritos and aloo
                paratha.
              </p>
            </div>

            <div class="interest-item">
              <div class="interest-icon">🎮</div>
              <h3>Video Games</h3>
              <p>
                I like playing FPS and open world games. I'm currently enjoying the Just Cause
                series and Cyberpunk 2077!
              </p>
            </div>

            <div class="interest-item">
              <div class="interest-icon">📸</div>
              <h3>Running</h3>
              <p>I enjoy long distance runs. My personal best is a 50 minute 10K :D</p>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.about-hero {
  margin-bottom: 4rem;
  padding: 3rem 0;
}

.page-title {
  font-size: clamp(2.5rem, 5vw, 4rem);
  font-weight: 800;
  margin-bottom: 2rem;
  color: var(--color-heading);
  letter-spacing: -0.02em;
  position: relative;
}

.page-title::after {
  content: '';
  position: absolute;
  bottom: -0.5rem;
  left: 0;
  width: 60px;
  height: 4px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.about-intro {
  font-size: 1.25rem;
  line-height: 1.8;
  color: var(--color-text-mute);
  max-width: 800px;
  margin-bottom: 1.5rem;
}

.about-intro:last-child {
  margin-bottom: 0;
}

@keyframes shimmer {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.story-section {
  margin-bottom: 4rem;
  padding: 3rem 0;
}

.section-title {
  font-size: clamp(1.75rem, 4vw, 2.25rem);
  font-weight: 700;
  margin-bottom: 2.5rem;
  color: var(--color-primary);
  text-align: center;
  letter-spacing: -0.02em;
  position: relative;
}

.section-title::after {
  content: '';
  position: absolute;
  bottom: -0.75rem;
  left: 50%;
  transform: translateX(-50%);
  width: 40px;
  height: 3px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.story-content {
  max-width: 800px;
  margin: 0 auto;
}

.story-content p {
  font-size: 1.125rem;
  line-height: 1.8;
  margin-bottom: 2rem;
  color: var(--color-text);
  text-align: left;
}

.story-content p:last-child {
  margin-bottom: 0;
}

.skills-interests {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  margin-bottom: 4rem;
  padding: 3rem 0;
}

.skills-column,
.interests-column {
  display: flex;
  flex-direction: column;
}

.skills-categories {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.skill-category {
  background: linear-gradient(135deg, var(--color-background-mute), var(--color-background-soft));
  padding: 2rem;
  border-radius: 1.5rem;
  border: 1px solid var(--color-border);
  transition: all 0.3s ease;
}

.skill-category:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-lg);
}

.skill-category h3 {
  font-size: 1.375rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
  color: var(--color-text);
  position: relative;
}

.skill-category h3::before {
  content: '';
  position: absolute;
  left: -0.5rem;
  top: 50%;
  transform: translateY(-50%);
  width: 4px;
  height: 20px;
  background: linear-gradient(180deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.skill-tag {
  background-color: var(--color-primary);
  color: white;
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
  font-size: 0.85rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.skill-tag:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.skill-tag.blue {
  background-color: var(--color-primary);
}
.skill-tag.purple {
  background-color: var(--color-purple);
}
.skill-tag.pink {
  background-color: var(--color-pink);
}
.skill-tag.orange {
  background-color: var(--color-orange);
}
.skill-tag.green {
  background-color: var(--color-green);
}
.skill-tag.cyan {
  background-color: var(--color-cyan);
}
.skill-tag.yellow {
  background-color: var(--color-yellow);
}
.skill-tag.red {
  background-color: var(--color-red);
}

.skill-tag:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.interests-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

.interest-item {
  background: linear-gradient(135deg, var(--color-background-mute), var(--color-background-soft));
  padding: 2rem;
  border-radius: 1.5rem;
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
}

.interest-item::before {
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

.interest-item:hover::before {
  transform: scaleX(1);
}

.interest-item:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-lg);
}

.interest-icon {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
  display: block;
}

.interest-item h3 {
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: var(--color-text);
}

.interest-item p {
  font-size: 1rem;
  color: var(--color-text-mute);
  line-height: 1.7;
  margin: 0;
}

.values-section {
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  padding: 4rem 3rem;
  border-radius: 2rem;
  margin-bottom: 2rem;
  border: 1px solid var(--color-border);
}

.values-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 3rem;
}

.value-item {
  text-align: center;
  padding: 1.5rem;
  border-radius: 1rem;
  transition: all 0.3s ease;
}

.value-item:hover {
  transform: translateY(-4px);
  background: rgba(59, 130, 246, 0.05);
}

.value-item h3 {
  font-size: 1.375rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: var(--color-primary);
}

.value-item p {
  color: var(--color-text-mute);
  line-height: 1.7;
  margin: 0;
  font-size: 1rem;
}

@media (max-width: 968px) {
  .skills-interests {
    grid-template-columns: 1fr;
    gap: 3rem;
  }
}

@media (max-width: 768px) {
  .container {
    padding: 0 1rem;
  }

  .about-hero {
    text-align: center;
    margin-bottom: 4rem;
  }

  .page-title {
    font-size: 2.5rem;
  }

  .page-title::after {
    left: 50%;
    transform: translateX(-50%);
  }

  .about-intro {
    font-size: 1.125rem;
  }

  .skills-interests {
    grid-template-columns: 1fr;
    gap: 3rem;
  }

  .skills-categories {
    gap: 2rem;
  }

  .interests-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .values-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .values-section {
    padding: 3rem 2rem;
  }

  .story-section,
  .skills-interests {
    margin-bottom: 4rem;
  }

  .skill-category,
  .interest-item {
    padding: 1.5rem;
  }
}
</style>
