<template>
  <div class="projects">
    <div class="container">
      <h1 class="page-title">Projects</h1>
      <p class="page-subtitle">
        Here are some of my recent projects that showcase my skills and experience
      </p>

      <div class="projects-grid">
        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">aqua-blue</h3>
              <div class="project-icons">
                <a
                  href="https://pypi.org/project/aqua-blue/"
                  class="project-icon"
                  target="_blank"
                  title="View on PyPI"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path d="M12 2L2 7L12 12L22 7L12 2Z" fill="currentColor" />
                    <path
                      d="M2 17L12 22L22 17"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                    <path
                      d="M2 12L12 17L22 12"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </a>
                <a
                  href="https://github.com/jwjeffr/aqua-blue"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.30.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>
            <p class="project-description">
              Secondary maintainer of aqua-blue, a lightweight reservoir computing framework.
            </p>
            <div class="project-features">
              <h4>Key Contributions:</h4>
              <ul>
                <li>
                  Implemented reservoir state time-lag, sparsity, and spectral radius to improve
                  prediction accuracy.
                </li>
                <li>
                  Introduced timezone-aware datetime support for seamless interfacing with data
                  pipelines.
                </li>
                <li>
                  Developed comprehensive testing cases using pytest for improved code quality.
                </li>
              </ul>
            </div>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag purple">NumPy</span>
              <span class="tech-tag green">pytest</span>
              <span class="tech-tag yellow">Ruff</span>
              <span class="tech-tag cyan">mypy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">neurop</h3>
              <div class="project-icons">
                <a
                  href="https://pypi.org/project/neurop/"
                  class="project-icon"
                  target="_blank"
                  title="View on PyPI"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path d="M12 2L2 7L12 12L22 7L12 2Z" fill="currentColor" />
                    <path
                      d="M2 17L12 22L22 17"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                    <path
                      d="M2 12L12 17L22 12"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </a>
                <a
                  href="https://github.com/lonelyneutrin0/neurop"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>
            <p class="project-description">
              Primary maintainer of neurop, a Python package implementing Neural Operators.
            </p>
            <div class="project-features">
              <h4>Key Contributions:</h4>
              <ul>
                <li>Developed Fourier Neural Operator architecture for solving PDEs</li>
                <li>
                  Implemented a Fractional Fourier Transform with bandlimited interpolation for use
                  in Neural Operators.
                </li>
                <li>Created comprehensivepackage documentation using pdoc.</li>
                <li>
                  Built CI/CD pipeline with GitHub Actions for automated testing and deployment.
                </li>
              </ul>
            </div>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag blue">PyTorch</span>
              <span class="tech-tag orange">opt-einsum</span>
              <span class="tech-tag green">pytest</span>
              <span class="tech-tag yellow">Ruff</span>
              <span class="tech-tag cyan">mypy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">aqua-blue-hyperopt</h3>
              <div class="project-icons">
                <a
                  href="https://pypi.org/project/aqua-blue-hyperopt/"
                  class="project-icon"
                  target="_blank"
                  title="View on PyPI"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path d="M12 2L2 7L12 12L22 7L12 2Z" fill="currentColor" />
                    <path
                      d="M2 17L12 22L22 17"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                    <path
                      d="M2 12L12 17L22 12"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </a>
                <a
                  href="https://github.com/lonelyneutrin0/aqua-blue-hyperopt"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>
            <p class="project-description">
              Primary maintainer of aqua-blue-hyperopt, a package implementing hyperparameter
              optimization functionality for aqua-blue models.
            </p>
            <div class="project-features">
              <h4>Key Contributions:</h4>
              <ul>
                <li>
                  Created modular hyperparameter optimization functionality for aqua-blue reservoir
                  computers.
                </li>
                <li>
                  Demonstrated prediction accuracy by forecasting quantum time evolution in Gaussian
                  wave packets.
                </li>
                <li>Set up GitHub Actions CI/CD for automated test cases and linting.</li>
              </ul>
            </div>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag yellow">NumPy</span>
              <span class="tech-tag orange">hyperopt</span>
              <span class="tech-tag green">mypy</span>
              <span class="tech-tag purple">Ruff</span>
              <span class="tech-tag cyan">pytest</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Adiabatic Quantum Computation</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/Adiabatic-Quantum-Computation"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
                <button
                  @click="
                    openPdfModal(
                      'https://github.com/lonelyneutrin0/Adiabatic-Quantum-Computation/blob/main/formulation/main.pdf',
                    )
                  "
                  class="project-icon"
                  title="View Project Report"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      fill="none"
                    />
                    <polyline
                      points="14,2 14,8 20,8"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      fill="none"
                    />
                    <line
                      x1="16"
                      y1="13"
                      x2="8"
                      y2="13"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                    />
                    <line
                      x1="16"
                      y1="17"
                      x2="8"
                      y2="17"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                    />
                    <polyline
                      points="10,9 9,9 8,9"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </button>
              </div>
            </div>

            <p class="project-description">
              Implemented a quantum adiabatic algorithm to solve QUBO type problems using the
              Trotter-Suzuki approximation and quantum Ising formulation techniques.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag purple">Qiskit</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Quantum Arithmetic Circuits</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/Quantum-Arithmetic-Circuits"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>

            <p class="project-description">
              Built quantum circuits to perform addition, subtraction and multiplication using the
              Quantum Fourier Transform.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag purple">Qiskit</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Protein Structure Prediction</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/Protein-Structure-Prediction"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
                <button
                  @click="
                    openPdfModal(
                      'https://github.com/lonelyneutrin0/Protein-Structure-Prediction/blob/main/ga/final_report.pdf',
                    )
                  "
                  class="project-icon"
                  title="View Project Report"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      fill="none"
                    />
                    <polyline
                      points="14,2 14,8 20,8"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      fill="none"
                    />
                    <line
                      x1="16"
                      y1="13"
                      x2="8"
                      y2="13"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                    />
                    <line
                      x1="16"
                      y1="17"
                      x2="8"
                      y2="17"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                    />
                    <polyline
                      points="10,9 9,9 8,9"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </svg>
                </button>
              </div>
            </div>

            <p class="project-description">
              Monte Carlo genetic algorithm to determine protein structures through the optimization
              of Irbäck's off-lattice model.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Quadratic Unconstrained Binary Optimization</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/qubo"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>

            <p class="project-description">
              Stochastic tunneling enhanced simulated annealing for solving QUBO problems.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Monte Carlo Integration</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/MNI"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>

            <p class="project-description">
              Monte Carlo Integration with importance sampling to numerically evaluate complex
              integrals.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>

        <div class="project-card">
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">Langevin Monte Carlo</h3>
              <div class="project-icons">
                <a
                  href="https://github.com/lonelyneutrin0/LMC"
                  class="project-icon"
                  target="_blank"
                  title="View on GitHub"
                >
                  <svg
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12 0C5.374 0 0 5.373 0 12 0 17.302 3.438 21.8 8.207 23.387c.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"
                      fill="currentColor"
                    />
                  </svg>
                </a>
              </div>
            </div>

            <p class="project-description">
              Metropolis-adjusted Langevin algorithm for sampling from complex distributions.
            </p>
            <div class="project-tech">
              <span class="tech-tag red">Python</span>
              <span class="tech-tag green">NumPy</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- PDF Modal -->
    <div v-if="showPdfModal" class="pdf-modal-overlay" @click="closePdfModal">
      <div class="pdf-modal" @click.stop>
        <div class="pdf-modal-header">
          <h3>Project Report</h3>
          <button @click="closePdfModal" class="modal-close-btn">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <line
                x1="18"
                y1="6"
                x2="6"
                y2="18"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
              />
              <line
                x1="6"
                y1="6"
                x2="18"
                y2="18"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
              />
            </svg>
          </button>
        </div>
        <div class="pdf-modal-content">
          <div class="pdf-message">
            <svg
              width="64"
              height="64"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="pdf-icon"
            >
              <path
                d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"
              />
              <polyline
                points="14,2 14,8 20,8"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"
              />
              <line
                x1="16"
                y1="13"
                x2="8"
                y2="13"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
              />
              <line
                x1="16"
                y1="17"
                x2="8"
                y2="17"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
              />
              <polyline
                points="10,9 9,9 8,9"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
            <h4>View Project Report</h4>
            <p>Click the button below to open the PDF in a new tab for viewing.</p>
            <a :href="currentPdfUrl" target="_blank" class="pdf-view-btn">
              <svg
                width="20"
                height="20"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <polyline
                  points="15,3 21,3 21,9"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <line
                  x1="10"
                  y1="14"
                  x2="21"
                  y2="3"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                />
              </svg>
              Open PDF
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const showPdfModal = ref(false)
const currentPdfUrl = ref('')

const openPdfModal = (pdfUrl: string) => {
  currentPdfUrl.value = pdfUrl
  showPdfModal.value = true
  document.body.style.overflow = 'hidden'
}

const closePdfModal = () => {
  showPdfModal.value = false
  currentPdfUrl.value = ''
  document.body.style.overflow = 'auto'
}
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

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(550px, 1fr));
  gap: 3rem;
  margin-bottom: 3rem;
}

.project-card {
  background: linear-gradient(135deg, var(--color-background), var(--color-background-soft));
  border-radius: 2rem;
  overflow: hidden;
  transition: all 0.4s ease;
  border: 1px solid var(--color-border);
  position: relative;
}

.project-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(135deg, rgba(59, 130, 246, 0.1), rgba(99, 102, 241, 0.1));
  opacity: 0;
  transition: opacity 0.3s ease;
  z-index: 1;
}

.project-card:hover::before {
  opacity: 1;
}

.project-card:hover {
  transform: translateY(-12px);
  box-shadow: var(--shadow-xl);
}

.project-content {
  padding: 2.5rem;
  position: relative;
  z-index: 2;
}

.project-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1.25rem;
  gap: 1rem;
}

.project-title {
  font-size: 1.75rem;
  font-weight: 700;
  color: var(--color-text);
  letter-spacing: -0.01em;
  margin: 0;
  flex: 1;
}

.project-icons {
  display: flex;
  gap: 0.75rem;
  flex-shrink: 0;
}

.project-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 0.75rem;
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  text-decoration: none;
  transition: all 0.3s ease;
  box-shadow: var(--shadow-sm);
  position: relative;
  overflow: hidden;
}

.project-icon::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
  transition: left 0.5s;
}

.project-icon:hover::before {
  left: 100%;
}

.project-icon:hover {
  transform: translateY(-2px) scale(1.05);
  box-shadow: var(--shadow-md);
}

.project-icon.disabled {
  background: var(--color-background-mute);
  color: var(--color-text-mute);
  cursor: not-allowed;
  opacity: 0.5;
}

.project-icon.disabled:hover {
  transform: none;
  box-shadow: var(--shadow-sm);
}

.project-icon.disabled::before {
  display: none;
}

.project-links {
  display: flex;
  gap: 1rem;
  margin-top: 2rem;
  flex-wrap: wrap;
}

.project-link {
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  padding: 0.875rem 1.5rem;
  border-radius: 0.75rem;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  box-shadow: var(--shadow-sm);
  flex: 1;
  text-align: center;
  min-width: 120px;
}

.project-link::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
  transition: left 0.5s;
}

.project-link:hover::before {
  left: 100%;
}

.project-link:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.project-link.disabled {
  background: var(--color-background-mute);
  color: var(--color-text-mute);
  cursor: not-allowed;
  opacity: 0.6;
}

.project-link.disabled:hover {
  transform: none;
  box-shadow: var(--shadow-sm);
}

.project-link.disabled::before {
  display: none;
}

.project-description {
  color: var(--color-text-mute);
  line-height: 1.7;
  margin-bottom: 2rem;
  font-size: 1rem;
}

.project-features {
  margin-bottom: 2rem;
  background: rgba(59, 130, 246, 0.05);
  padding: 1.5rem;
  border-radius: 1rem;
  border-left: 4px solid var(--color-primary);
}

.project-features h4 {
  font-size: 1.125rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: var(--color-primary);
}

.project-features ul {
  padding-left: 1.25rem;
  margin: 0;
}

.project-features li {
  color: var(--color-text-mute);
  margin-bottom: 0.5rem;
  font-size: 0.95rem;
  line-height: 1.6;
  position: relative;
}

.project-features li::marker {
  color: var(--color-primary);
}

.project-features li:last-child {
  margin-bottom: 0;
}

.project-tech {
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
  transition: all 0.3s ease;
}

.tech-tag:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
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

.tech-tag:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

/* PDF Modal Styles */
.pdf-modal-overlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.8);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 1000;
  backdrop-filter: blur(4px);
}

.pdf-modal {
  background: var(--color-background);
  border-radius: 1rem;
  max-width: 90vw;
  max-height: 90vh;
  width: 1000px;
  height: 700px;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-xl);
  border: 1px solid var(--color-border);
}

.pdf-modal-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.5rem;
  border-bottom: 1px solid var(--color-border);
  background: var(--color-background-soft);
  border-radius: 1rem 1rem 0 0;
}

.pdf-modal-header h3 {
  margin: 0;
  color: var(--color-text);
  font-size: 1.25rem;
  font-weight: 700;
}

.modal-close-btn {
  background: none;
  border: none;
  color: var(--color-text-mute);
  cursor: pointer;
  padding: 0.5rem;
  border-radius: 0.5rem;
  transition: all 0.2s ease;
  display: flex;
  align-items: center;
  justify-content: center;
}

.modal-close-btn:hover {
  background: var(--color-background-mute);
  color: var(--color-text);
}

.pdf-modal-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  position: relative;
}

.pdf-viewer {
  flex: 1;
  width: 100%;
  border: none;
  border-radius: 0 0 1rem 1rem;
}

.pdf-fallback {
  position: absolute;
  bottom: 1rem;
  right: 1rem;
  background: var(--color-background-soft);
  padding: 1rem;
  border-radius: 0.75rem;
  border: 1px solid var(--color-border);
  box-shadow: var(--shadow-md);
}

.pdf-fallback p {
  margin: 0 0 0.75rem 0;
  color: var(--color-text-mute);
  font-size: 0.9rem;
}

.pdf-download-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  padding: 0.75rem 1rem;
  border-radius: 0.5rem;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: var(--shadow-sm);
}

.pdf-download-btn:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.pdf-message {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 4rem 2rem;
  height: 100%;
}

.pdf-icon {
  color: var(--color-primary);
  margin-bottom: 2rem;
  opacity: 0.8;
}

.pdf-message h4 {
  font-size: 1.5rem;
  font-weight: 700;
  color: var(--color-text);
  margin-bottom: 1rem;
  letter-spacing: -0.01em;
}

.pdf-message p {
  color: var(--color-text-mute);
  font-size: 1.125rem;
  line-height: 1.6;
  margin-bottom: 2.5rem;
  max-width: 400px;
}

.pdf-view-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.75rem;
  background: linear-gradient(135deg, var(--color-primary), var(--color-primary-dark));
  color: white;
  padding: 1rem 2rem;
  border-radius: 0.75rem;
  text-decoration: none;
  font-size: 1.125rem;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: var(--shadow-lg);
  letter-spacing: -0.01em;
}

.pdf-view-btn:hover {
  transform: translateY(-3px);
  box-shadow: var(--shadow-xl);
  background: linear-gradient(135deg, var(--color-primary-dark), var(--color-primary));
}

/* Responsive Styles */
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

  .projects-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .project-content {
    padding: 2rem;
  }

  .project-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }

  .project-title {
    font-size: 1.5rem;
  }

  .project-icons {
    align-self: flex-end;
  }

  .project-icon {
    width: 36px;
    height: 36px;
  }

  .project-links {
    flex-direction: column;
    align-items: stretch;
    gap: 0.75rem;
  }

  .project-link {
    padding: 0.875rem 1.5rem;
    font-size: 0.9rem;
    text-align: center;
  }

  .project-features {
    padding: 1.25rem;
  }

  .tech-tag {
    font-size: 0.8rem;
    padding: 0.375rem 0.75rem;
  }

  .pdf-modal {
    max-width: 95vw;
    max-height: 95vh;
    width: 100%;
    height: 90vh;
  }

  .pdf-modal-header {
    padding: 1rem;
  }

  .pdf-modal-header h3 {
    font-size: 1.125rem;
  }

  .pdf-fallback {
    position: static;
    margin-top: 1rem;
    text-align: center;
  }
}

@media (max-width: 600px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
}
</style>
