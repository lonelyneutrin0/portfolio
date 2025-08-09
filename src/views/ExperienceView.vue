<template>
  <div class="experience">
    <div class="container">
      <h1 class="page-title">Experience</h1>

      <!-- Professional Experience -->
      <section id="experience" class="experience-section">
        <h2 class="section-title">Experience</h2>
        <div class="timeline">
          <div class="timeline-item">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <h3 class="job-title">Undergraduate Research Assistant</h3>
              <h4 class="company">Vermaas Lab, Plant Research Laboratory</h4>
              <p class="duration">Dec 2024 - Present</p>
              <ul class="responsibilities">
                <li>
                  Investigated the interaction of chloroplast targeting protein (At4g16060) with
                  thylakoid membranes using molecular dynamics.
                </li>
                <li>
                  Analyzed the effect of PDLP-5 (Plasmodesmata Located Protein) on water flow rates
                  through PIP-1;4 aquaporin tetramer using grid-steered molecular dynamics.
                </li>
                <li>
                  Calculated protein transition kinetics using Markov State Models (MSMs) with
                  PyEMMA
                </li>
                <li>Conducted pore radius profile and hydrogen bond analysis using MDAnalysis</li>
              </ul>
              <div class="technologies">
                <span class="tech-tag red">VMD</span>
                <span class="tech-tag purple">NAMD</span>
                <span class="tech-tag green">Python</span>
                <span class="tech-tag cyan">TCL</span>
                <span class="tech-tag orange">NumPy</span>
                <span class="tech-tag pink">MDAnalysis</span>
                <span class="tech-tag yellow">PyEMMA</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Education -->
      <section id="education" class="education-section">
        <h2 class="section-title">Education</h2>

        <!-- Academic Programs -->
        <div class="subsection">
          <h3 class="subsection-title">Academic Programs</h3>
          <div class="education-grid">
            <div class="education-item">
              <h3>Bachelor of Science in Computer Science</h3>
              <h4>Michigan State University, Honors College</h4>
              <p class="duration">2024 - 2027</p>
              <p class="description">
                Relevant Coursework: Honors Linear Algebra, Modern Physics, Data Structures and
                Algorithms, Computer Architecture
              </p>
              <p class="description"><b>GPA:</b> 4.0</p>
            </div>
          </div>
        </div>

        <!-- Scholarships & Awards -->
        <div class="subsection">
          <h3 class="subsection-title">Scholarships & Awards</h3>
          <div class="awards-grid">
            <!-- Add your scholarships and awards here -->
            <div class="award-item">
              <h4>Senator Joe and Mary Conroy Endowed Scholarship</h4>
              <p class="award-organization">College of Engineering, Michigan State University</p>
              <p class="award-year">2024</p>
            </div>

            <div class="award-item">
              <h4>MSU President's Scholarship</h4>
              <p class="award-organization">Michigan State University</p>
              <p class="award-year">2024-2025</p>
            </div>

            <div class="award-item">
              <h4>Dean's List</h4>
              <p class="award-organization">Michigan State University</p>
              <p class="award-year">Fall 2024 - Present</p>
            </div>
          </div>
        </div>
      </section>

      <!-- Research & Publications -->
      <section id="research" class="research-section">
        <h2 class="section-title">Research & Publications</h2>

        <!-- Research Projects -->
        <div class="subsection">
          <h3 class="subsection-title">Current Research</h3>
          <div class="research-grid">
            <div class="research-item">
              <h4>Water Transit Modulation in Aquaporins</h4>
              <p class="research-lab">Vermaas Lab, Plant Research Laboratory</p>
              <p class="research-status">Ongoing Research</p>
              <p class="research-description">
                Exploring water transit modulation in aquaporins using grid-steered molecular
                dynamics to understand water transport mechanisms at the molecular level.
              </p>

              <!-- MD Simulation Video -->
              <div class="research-video">
                <div class="video-container">
                  <video
                    controls
                    autoplay
                    loop
                    muted
                    preload="metadata"
                    class="md-simulation-video"
                  >
                    <source src="/src/assets/movie.mp4" type="video/mp4" />
                    Your browser does not support the video tag.
                  </video>
                  <div class="video-caption">
                    <h5>Molecular Dynamics Simulation</h5>
                    <p>
                      The video showcases the aquaporin (orange) with a protein cap (green) embedded
                      in a membrane.
                    </p>
                  </div>
                </div>
              </div>

              <div class="research-techniques">
                <span class="technique-tag purple">Molecular Dynamics</span>
                <span class="technique-tag orange">NAMD</span>
                <span class="technique-tag green">VMD</span>
                <span class="technique-tag pink">Grid-Steered MD</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Publications Section -->
        <div id="publications" class="subsection">
          <h3 class="subsection-title">Publications & Abstracts</h3>
          <div class="publications-grid">
            <!-- Add your papers/abstracts here -->
            <div class="publication-item">
              <h4>
                <a
                  href="https://acs.digitellinc.com/p/s/aquaporin-water-transit-modulation-via-protein-capping-638984"
                  class="publication-title-link"
                >
                  Aquaporin Water Transit Modulation via Protein Capping
                  <svg
                    class="link-icon"
                    width="16"
                    height="16"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M10 6H6a2 2 0 00-2 2v6a2 2 0 002 2h10a2 2 0 002-2v-6a2 2 0 00-2-2h-4M14 6V4a2 2 0 00-2-2h-4a2 2 0 00-2-2v2m8 0l-5 5-3-3"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </a>
              </h4>
              <p class="publication-authors">
                Nitin Kumar Singh, Hrishikesh Belagali, Kyaw Aung, Josh V. Vermaas
              </p>
              <p class="publication-venue">ACS Fall Conference, 2025</p>
              <p class="publication-status">Status: Submitted</p>
              <p class="publication-abstract">
                Aquaporins are essential membrane proteins responsible for regulating water
                transport across biological membranes, playing a crucial role in maintaining osmotic
                balance within cells. Recent findings suggest that PLASMODESMATA-LOCATED PROTEIN 4
                (PDLP5) interacts with PLASMA MEMBRANE INTRINSIC PROTEIN 1;4 (AtPIP1;4, also known
                as aquaporin) to regulate the transport of water and hydrogen peroxide. Using
                AlphaFold 3, a tight complex between PDLP5 and AtPIP1;4 was predicted, where the
                ectodomain of PDLP5 appears to cap the aquaporin channel, potentially blocking the
                extracellular face of PIP1;4 to reduce water transit. In this study, we employ
                all-atom molecular dynamics (MD) simulations to investigate how the interaction
                between PDLP5 and AtPIP1;4 influences water transport dynamics. Our simulation
                design incorporates a double bilayer system, simulating both capped and uncapped
                AtPIP1;4 aquaporins. The results indicate that the presence of the PDLP5 cap reduces
                water permeation through the aquaporin channel under equilibrium conditions, with
                water translocation rates decreasing from 460±80 to 290±60 molecules per
                microsecond. Additionally, we performed MD simulations to evaluate the effect of
                osmotic and ionic gradients on water permeability, assessing the response to osmotic
                and ionic shocks. These simulation setups explore a range of conditions encountered
                during drought and salt stress in plants. This work aims to provide insights into
                the molecular mechanisms by which PDLP5 modulates aquaporin water transport,
                potentially offering new strategies for improving plant resilience to environmental
                stress.
              </p>
              <div class="publication-tags">
                <span class="pub-tag">Abstract</span>
                <span class="pub-tag">Presentation</span>
              </div>
            </div>

            <div class="publication-item">
              <h4>
                <span class="publication-title-nolink">
                  Evaluating the Interaction of Chloroplast-targeting Protein (At4g16060) with
                  Thylakoid Membrane
                </span>
              </h4>
              <p class="publication-authors">
                Nitin Kumar Singh, Hrishikesh Belagali, Hiruni Weerasooriya, Jianping Hu, Josh V.
                Vermaas
              </p>
              <p class="publication-venue">First Great Lakes Plant Science Conference, 2025</p>
              <p class="publication-status">Status: Submitted</p>
              <p class="publication-abstract">
                Chloroplasts are eukaryotic photosynthetic organelles that play a pivotal role in
                the global carbon cycle by capturing light energy and converting it into chemical
                energy. While many chloroplast proteins involved in photosynthesis have been
                studied, a significant portion of the chloroplast proteome remains functionally
                uncharacterized. One such protein is encoded by the AT4g16060 gene in Arabidopsis
                thaliana, which produces a chloroplast-targeting protein (cTP) consisting of 228–289
                amino acids, depending on the cleavage of its transit peptide. This protein
                localizes to both the chloroplast stroma and cytosol, with close homologs identified
                in rice and maize, suggesting a conserved function. This study investigates the
                structural characteristics and membrane association dynamics of AT4g16060 protein,
                particularly in relation to the thylakoid membrane—a phospholipid bilayer enriched
                in glycolipids and galactolipids that is essential for the light-dependent reactions
                of photosynthesis. The three-dimensional structure of AT4g16060 was predicted using
                AlphaFold3. The predicted structure for AT4g16060 was simulated through classical
                molecular dynamics (MD) simulations conducted at physiological conditions (300 K and
                1 bar) in aqueous environments and in the presence of a model thylakoid membrane.
                From six independent simulation starting points, AT4g16060 consistently showed
                interaction between the N-terminal region and the membrane surface. We quantify this
                observation through cumulative contact analysis, highlighting the persistent
                membrane-binding orientation mediated by N-terminal residues, as well as
                measurements of the penetration depth of specific protein residues into the
                thylakoid membrane model. Together, these results suggest that the N-terminal region
                plays a primary role in facilitating membrane association. These results provide
                preliminary insights into the potential membrane-interacting mechanism of this
                uncharacterized chloroplast protein and lay the groundwork for future functional
                studies.
              </p>
              <div class="publication-tags">
                <span class="pub-tag">Abstract</span>
                <span class="pub-tag">Poster</span>
              </div>
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

.page-title {
  text-align: center;
  font-size: clamp(2.5rem, 5vw, 4rem);
  font-weight: 800;
  margin-bottom: 4rem;
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

.experience-section {
  margin-bottom: 6rem;
}

.section-title {
  font-size: clamp(1.75rem, 4vw, 2.25rem);
  font-weight: 700;
  margin-bottom: 3rem;
  color: var(--color-primary);
  letter-spacing: -0.02em;
  position: relative;
}

.section-title::after {
  content: '';
  position: absolute;
  bottom: -0.5rem;
  left: 0;
  width: 40px;
  height: 3px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.timeline {
  position: relative;
  padding-left: 3rem;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 1.5rem;
  top: 0;
  bottom: 0;
  width: 3px;
  background: var(--gradient-primary);
  border-radius: 2px;
}

.timeline-item {
  position: relative;
  margin-bottom: 4rem;
}

.timeline-marker {
  position: absolute;
  left: -2.25rem;
  top: 1rem;
  width: 1.5rem;
  height: 1.5rem;
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  border-radius: 50%;
  border: 4px solid var(--color-background);
  box-shadow: var(--shadow-md);
  z-index: 2;
}

.timeline-content {
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  padding: 3rem;
  border-radius: 2rem;
  margin-left: 1.5rem;
  border: 1px solid var(--color-border);
  position: relative;
  transition: all 0.3s ease;
  overflow: hidden;
}

.timeline-content::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.timeline-content:hover::before {
  transform: scaleX(1);
}

.timeline-content:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-xl);
}

.job-title {
  font-size: 1.75rem;
  font-weight: 700;
  margin-bottom: 0.75rem;
  color: var(--color-text);
  letter-spacing: -0.01em;
}

.company {
  font-size: 1.375rem;
  font-weight: 600;
  color: var(--color-primary);
  margin-bottom: 0.75rem;
}

.duration {
  color: var(--color-text-mute);
  font-weight: 600;
  margin-bottom: 1rem;
  font-size: 1rem;
  background: rgba(59, 130, 246, 0.1);
  padding: 0.5rem 1rem;
  border-radius: 2rem;
  display: inline-block;
}

.responsibilities {
  margin-bottom: 2rem;
  padding-left: 0;
  list-style: none;
}

.responsibilities li {
  margin-bottom: 1rem;
  line-height: 1.7;
  color: var(--color-text);
  position: relative;
  padding-left: 2rem;
  font-size: 1rem;
}

.responsibilities li::before {
  content: '→';
  position: absolute;
  left: 0;
  color: var(--color-primary);
  font-weight: 700;
  font-size: 1.2rem;
}

.responsibilities li:last-child {
  margin-bottom: 0;
}

.technologies {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.tech-tag {
  background: var(--color-primary);
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 2rem;
  font-size: 0.875rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  box-shadow: var(--shadow-sm);
  transition: all 0.2s ease;
}

.tech-tag:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.tech-tag.blue {
  background: var(--color-primary);
}
.tech-tag.purple {
  background: var(--color-purple);
}
.tech-tag.pink {
  background: var(--color-pink);
}
.tech-tag.orange {
  background: var(--color-orange);
}
.tech-tag.green {
  background: var(--color-green);
}
.tech-tag.cyan {
  background: var(--color-cyan);
}
.tech-tag.yellow {
  background: var(--color-yellow);
}
.tech-tag.red {
  background: var(--color-red);
}

.education-section {
  margin-bottom: 3rem;
}

.research-section {
  margin-bottom: 5rem;
}

.subsection {
  margin-bottom: 4rem;
}

.subsection:last-child {
  margin-bottom: 0;
}

.subsection-title {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 2rem;
  color: var(--color-text);
  letter-spacing: -0.01em;
  position: relative;
  padding-left: 1rem;
}

.subsection-title::before {
  content: '';
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 4px;
  height: 24px;
  background: linear-gradient(180deg, var(--color-primary), var(--color-primary-light));
  border-radius: 2px;
}

.education-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.awards-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.education-item,
.award-item {
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  padding: 2.5rem;
  border-radius: 2rem;
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
}

.education-item::before,
.award-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.education-item:hover::before,
.award-item:hover::before {
  transform: scaleX(1);
}

.education-item:hover,
.award-item:hover {
  transform: translateY(-6px);
  box-shadow: var(--shadow-lg);
}

.education-item h3,
.award-item h4 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: var(--color-text);
  letter-spacing: -0.01em;
}

.education-item h4,
.award-organization {
  color: var(--color-primary);
  font-weight: 600;
  margin-bottom: 0.75rem;
  font-size: 1.125rem;
}

.award-year {
  color: var(--color-text-mute);
  font-weight: 600;
  margin-bottom: 1rem;
  font-size: 1rem;
  background: rgba(59, 130, 246, 0.1);
  padding: 0.5rem 1rem;
  border-radius: 2rem;
  display: inline-block;
}

.research-grid,
.publications-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

.research-item,
.publication-item {
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
  padding: 2.5rem;
  border-radius: 2rem;
  transition: all 0.3s ease;
  border: 1px solid var(--color-border);
  position: relative;
  overflow: hidden;
}

.research-item::before,
.publication-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--color-cyan), var(--color-primary));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.research-item:hover::before,
.publication-item:hover::before {
  transform: scaleX(1);
}

.research-item:hover,
.publication-item:hover {
  transform: translateY(-6px);
  box-shadow: var(--shadow-lg);
}

.research-item h4,
.publication-item h4 {
  font-size: 1.375rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: var(--color-text);
  letter-spacing: -0.01em;
  line-height: 1.3;
}

.research-lab,
.publication-authors {
  color: var(--color-primary);
  font-weight: 600;
  margin-bottom: 0.5rem;
  font-size: 1rem;
}

.research-status,
.publication-venue,
.publication-status {
  color: var(--color-text-mute);
  font-weight: 500;
  margin-bottom: 1rem;
  font-size: 0.95rem;
}

.publication-venue {
  font-style: italic;
}

.research-description,
.publication-abstract {
  color: var(--color-text);
  line-height: 1.7;
  margin-bottom: 1.5rem;
  font-size: 1rem;
}

.research-video {
  margin: 2rem 0;
}

.video-container {
  background: linear-gradient(135deg, var(--color-background-mute), var(--color-background-soft));
  border-radius: 1.5rem;
  padding: 2rem;
  border: 1px solid var(--color-border);
  transition: all 0.3s ease;
  overflow: hidden;
  max-width: 600px;
  margin: 0 auto;
}

.video-container:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-lg);
}

.md-simulation-video {
  width: 100%;
  height: auto;
  max-width: 500px;
  border-radius: 1rem;
  box-shadow: var(--shadow-md);
  transition: all 0.3s ease;
  display: block;
  margin: 0 auto;
}

.md-simulation-video:hover {
  box-shadow: var(--shadow-xl);
}

.video-caption {
  text-align: center;
  margin-top: 1.5rem;
}

.video-caption h5 {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--color-text);
  margin-bottom: 0.75rem;
  letter-spacing: -0.01em;
}

.video-caption p {
  color: var(--color-text-mute);
  font-size: 1rem;
  line-height: 1.6;
  margin: 0;
}

.video-placeholder {
  background: linear-gradient(135deg, var(--color-background-mute), var(--color-background-soft));
  border: 2px dashed var(--color-border);
  border-radius: 1.5rem;
  padding: 3rem 2rem;
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.video-placeholder::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(
    45deg,
    transparent 30%,
    rgba(59, 130, 246, 0.05) 50%,
    transparent 70%
  );
  opacity: 0;
  transition: opacity 0.3s ease;
}

.video-placeholder:hover::before {
  opacity: 1;
}

.video-placeholder:hover {
  border-color: var(--color-primary);
  transform: translateY(-4px);
  box-shadow: var(--shadow-lg);
}

.video-icon {
  color: var(--color-primary);
  margin-bottom: 1.5rem;
  opacity: 0.8;
  transition: all 0.3s ease;
}

.video-placeholder:hover .video-icon {
  opacity: 1;
  transform: scale(1.1);
}

.video-placeholder h5 {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--color-text);
  margin-bottom: 0.75rem;
  letter-spacing: -0.01em;
}

.video-placeholder p {
  color: var(--color-text-mute);
  font-size: 1rem;
  margin-bottom: 2rem;
  line-height: 1.6;
}

.video-btn {
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  border: none;
  padding: 0.875rem 2rem;
  border-radius: 2rem;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: var(--shadow-sm);
  letter-spacing: -0.01em;
}

.video-btn:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
  background: linear-gradient(135deg, var(--color-primary-dark), var(--color-primary));
}

.video-btn:active {
  transform: translateY(0);
}

.research-techniques {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.technique-tag {
  background: var(--color-cyan);
  color: white;
  padding: 0.375rem 0.875rem;
  border-radius: 1.5rem;
  font-size: 0.85rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  box-shadow: var(--shadow-sm);
  transition: all 0.2s ease;
}

.technique-tag:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.technique-tag.purple {
  background: var(--color-purple);
}

.technique-tag.orange {
  background: var(--color-orange);
}

.technique-tag.green {
  background: var(--color-green);
}

.technique-tag.pink {
  background: var(--color-pink);
}

.publication-links {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.publication-tags {
  display: flex;
  gap: 0.75rem;
  flex-wrap: wrap;
}

.publication-title-link {
  color: var(--color-text);
  text-decoration: none;
  transition: all 0.3s ease;
  position: relative;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
}

.publication-title-link:hover {
  color: var(--color-primary);
  text-decoration: none;
}

.publication-title-link::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--color-primary), var(--color-primary-light));
  transition: width 0.3s ease;
}

.publication-title-link:hover::after {
  width: 100%;
}

.link-icon {
  opacity: 0.6;
  transition: all 0.3s ease;
  flex-shrink: 0;
}

.publication-title-link:hover .link-icon {
  opacity: 1;
  transform: translateX(2px);
}

.publication-title-nolink {
  color: var(--color-text);
}

.pub-tag {
  background: linear-gradient(135deg, var(--color-background-mute), var(--color-background-soft));
  color: var(--color-text);
  padding: 0.375rem 1rem;
  border-radius: 1.5rem;
  font-size: 0.85rem;
  font-weight: 600;
  border: 1px solid var(--color-border);
  box-shadow: var(--shadow-sm);
  transition: all 0.2s ease;
}

.pub-tag:hover {
  transform: translateY(-1px);
  box-shadow: var(--shadow-md);
  background: linear-gradient(135deg, var(--color-background-soft), var(--color-background-mute));
}

.pub-link {
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  padding: 0.5rem 1.25rem;
  border-radius: 1.5rem;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: var(--shadow-sm);
}

.pub-link:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.description {
  color: var(--color-text-mute);
  line-height: 1.7;
  margin-top: 0.5rem;
  font-size: 1rem;
}

@media (max-width: 768px) {
  .container {
    padding: 0 1rem;
  }

  .page-title {
    font-size: 2.5rem;
    margin-bottom: 3rem;
  }

  .timeline {
    padding-left: 2rem;
  }

  .timeline::before {
    left: 1rem;
  }

  .timeline-marker {
    left: -1.75rem;
    width: 1.25rem;
    height: 1.25rem;
  }

  .timeline-content {
    margin-left: 1rem;
    padding: 2rem;
  }

  .job-title {
    font-size: 1.5rem;
  }

  .company {
    font-size: 1.25rem;
  }

  .responsibilities li {
    padding-left: 1.5rem;
    font-size: 0.95rem;
  }

  .technologies {
    gap: 0.5rem;
  }

  .tech-tag {
    font-size: 0.8rem;
    padding: 0.375rem 0.75rem;
  }

  .education-grid {
    grid-template-columns: 1fr;
  }

  .awards-grid {
    grid-template-columns: 1fr;
  }

  .education-item,
  .award-item {
    padding: 2rem;
  }

  .research-item,
  .publication-item {
    padding: 2rem;
  }

  .subsection-title {
    font-size: 1.25rem;
  }

  .research-item h4,
  .publication-item h4 {
    font-size: 1.25rem;
  }

  .technique-tag {
    font-size: 0.8rem;
    padding: 0.25rem 0.75rem;
  }

  .video-container {
    padding: 1.5rem;
    max-width: 100%;
  }

  .md-simulation-video {
    max-width: 100%;
  }

  .video-caption h5 {
    font-size: 1.125rem;
  }

  .video-caption p {
    font-size: 0.95rem;
  }

  .video-placeholder {
    padding: 2rem 1.5rem;
  }

  .video-placeholder h5 {
    font-size: 1.125rem;
  }

  .video-placeholder p {
    font-size: 0.95rem;
    margin-bottom: 1.5rem;
  }

  .video-btn {
    font-size: 0.9rem;
    padding: 0.75rem 1.5rem;
  }

  .pub-link {
    font-size: 0.85rem;
    padding: 0.375rem 1rem;
  }

  .pub-tag {
    font-size: 0.8rem;
    padding: 0.25rem 0.75rem;
  }

  .publication-tags {
    gap: 0.5rem;
  }

  .experience-section,
  .education-section,
  .research-section {
    margin-bottom: 4rem;
  }
}
</style>
