---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Itohan-Osa Abu | Geospatial AI Scientist</title>

  <meta name="description" content="Itohan-Osa Abu is a Geospatial AI Scientist building trustworthy AI systems for Earth observation, climate risk, disaster analytics, environmental monitoring, insurance intelligence, and decision support." />
  <meta name="keywords" content="Itohan-Osa Abu, Geospatial AI, Remote Sensing, GIS Automation, Google Earth Engine, Climate Risk Analytics, Environmental Monitoring, Disaster Analytics, Spatial Machine Learning, Satellite Data, Earth Observation AI" />
  <meta name="author" content="Itohan-Osa Abu" />

  <meta property="og:title" content="Itohan-Osa Abu | Geospatial AI Scientist" />
  <meta property="og:description" content="Geospatial AI, Earth observation, remote sensing, climate-risk analytics, disaster mapping, environmental monitoring, insurance intelligence, and decision-support systems." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://itohanosa.github.io/" />

  <style>
    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #050b14;
      color: #eef4ff;
      line-height: 1.6;
    }

    a {
      color: #7dd3fc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    header {
      padding: 22px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(5, 11, 20, 0.94);
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(12px);
    }

    .logo {
      font-weight: 900;
      color: #ffffff;
      letter-spacing: 0.3px;
      font-size: 1rem;
    }

    nav {
      display: flex;
      gap: 18px;
      flex-wrap: wrap;
    }

    nav a {
      color: #cbd5e1;
      font-size: 0.92rem;
      font-weight: 700;
    }

    section {
      padding: 76px 8%;
      max-width: 1240px;
      margin: auto;
    }

    h1 {
      font-size: clamp(2.8rem, 7vw, 5.8rem);
      line-height: 1.02;
      margin: 0 0 24px;
      color: #ffffff;
      letter-spacing: -2px;
    }

    h2 {
      font-size: clamp(2rem, 4vw, 3.1rem);
      line-height: 1.15;
      margin: 0 0 20px;
      color: #ffffff;
      letter-spacing: -0.9px;
    }

    h3 {
      color: #ffffff;
      margin: 0 0 10px;
      font-size: 1.35rem;
    }

    p {
      color: #cbd5e1;
      font-size: 1.04rem;
      margin: 0 0 16px;
    }

    .hero {
      min-height: 88vh;
      display: grid;
      grid-template-columns: 1.25fr 0.75fr;
      gap: 46px;
      align-items: center;
      background:
        radial-gradient(circle at 20% 20%, rgba(56, 189, 248, 0.18), transparent 32%),
        radial-gradient(circle at 80% 40%, rgba(34, 197, 94, 0.12), transparent 30%);
    }

    .eyebrow {
      color: #38bdf8;
      font-weight: 900;
      text-transform: uppercase;
      letter-spacing: 1.7px;
      margin-bottom: 18px;
      font-size: 0.82rem;
    }

    .hero-text {
      font-size: 1.22rem;
      max-width: 820px;
      color: #dbeafe;
    }

    .buttons {
      margin-top: 30px;
    }

    .button {
      display: inline-block;
      margin: 9px 8px 0 0;
      padding: 12px 18px;
      border-radius: 999px;
      font-weight: 900;
      border: 1px solid rgba(255, 255, 255, 0.22);
      color: #e2e8f0;
      text-decoration: none;
    }

    .button.primary {
      background: #38bdf8;
      color: #06111f;
      border-color: #38bdf8;
    }

    .button:hover {
      opacity: 0.9;
      text-decoration: none;
      transform: translateY(-1px);
    }

    .card {
      background: linear-gradient(180deg, rgba(15, 27, 45, 0.98), rgba(10, 20, 36, 0.98));
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 26px;
      padding: 28px;
      margin-bottom: 24px;
      box-shadow: 0 24px 70px rgba(0, 0, 0, 0.28);
    }

    .hero-card {
      border: 1px solid rgba(56, 189, 248, 0.28);
      background:
        radial-gradient(circle at top left, rgba(56, 189, 248, 0.24), transparent 35%),
        linear-gradient(180deg, rgba(15, 27, 45, 0.98), rgba(10, 20, 36, 0.98));
    }

    .hero-card strong {
      display: block;
      color: #ffffff;
      font-size: 2.15rem;
      line-height: 1;
      margin-top: 12px;
    }

    .section-lead {
      max-width: 880px;
      font-size: 1.14rem;
      margin-bottom: 30px;
      color: #dbeafe;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .two-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 22px;
    }

    .tag {
      display: inline-block;
      background: rgba(56, 189, 248, 0.12);
      border: 1px solid rgba(56, 189, 248, 0.25);
      color: #7dd3fc;
      padding: 5px 10px;
      border-radius: 999px;
      margin: 4px 4px 8px 0;
      font-size: 0.84rem;
      font-weight: 800;
    }

    .project-card {
      transition: transform 0.2s ease, border-color 0.2s ease;
    }

    .project-card:hover {
      transform: translateY(-4px);
      border-color: rgba(56, 189, 248, 0.45);
    }

    .project-title a {
      color: #ffffff;
    }

    .project-title a:hover {
      color: #7dd3fc;
    }

    .metric-row {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 18px;
      margin-top: 30px;
    }

    .metric {
      background: rgba(15, 27, 45, 0.82);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 22px;
      padding: 22px;
    }

    .metric strong {
      display: block;
      color: #ffffff;
      font-size: 2.1rem;
      line-height: 1;
      margin-bottom: 8px;
    }

    .small-note {
      color: #94a3b8;
      font-size: 0.95rem;
    }

    .highlight {
      color: #7dd3fc;
      font-weight: 900;
    }

    footer {
      text-align: center;
      padding: 42px 8%;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: #94a3b8;
      font-size: 0.95rem;
    }

    @media (max-width: 900px) {
      header {
        display: block;
      }

      nav {
        margin-top: 14px;
      }

      section {
        padding: 58px 6%;
      }

      .hero {
        display: block;
        min-height: auto;
      }

      .hero-card {
        margin-top: 30px;
      }

      .grid,
      .two-grid,
      .metric-row {
        grid-template-columns: 1fr;
      }

      h1 {
        letter-spacing: -0.8px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">Itohan-Osa Abu</div>
    <nav>
      <a href="#systems">AI Systems</a>
      <a href="#impact">Impact</a>
      <a href="#expertise">Expertise</a>
      <a href="#publications">Research</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div>
      <div class="eyebrow">Geospatial AI · Earth Observation · Climate Risk Intelligence</div>

      <h1>Building AI systems that turn satellite data into climate-risk intelligence.</h1>

      <p class="hero-text">
        I develop geospatial artificial intelligence systems that transform satellite imagery,
        climate observations, environmental indicators, and machine learning outputs into practical
        decision tools for governments, insurers, infrastructure planners, researchers, and environmental organizations.
      </p>

      <div class="buttons">
        <a class="button primary" href="#systems">View Flagship AI Systems</a>
        <a class="button" href="mailto:abuitohanosa@gmail.com">Contact Me</a>
        <a class="button" href="https://github.com/itohanosa" target="_blank" rel="noopener noreferrer">GitHub</a>
      </div>
    </div>

    <div class="card hero-card">
      <h2>Research + Product Signal</h2>

      <strong>7+</strong>
      <p>Years building remote sensing, GIS, and environmental intelligence workflows.</p>

      <strong>26+</strong>
      <p>Research outputs listed on ResearchGate across Earth observation and environmental monitoring.</p>

      <strong>4M+</strong>
      <p>Hectares of cocoa landscapes mapped in West Africa using satellite evidence.</p>

      <strong>60%</strong>
      <p>Workflow speed improvement through Google Earth Engine automation.</p>
    </div>
  </section>

  <section id="positioning">
    <h2>From satellite evidence to decisions that matter.</h2>

    <p class="section-lead">
      My work sits at the intersection of <span class="highlight">artificial intelligence</span>,
      <span class="highlight">Earth observation</span>, and <span class="highlight">risk intelligence</span>.
      I build systems that connect scientific data with real-world use cases: wildfire underwriting,
      flood awareness, urban heat planning, pollution monitoring, conservation, and population exposure analysis.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Scientific AI</h3>
        <p>
          Machine learning workflows for environmental prediction, risk screening,
          explainable modeling, satellite-based intelligence, and decision support.
        </p>
      </div>

      <div class="card">
        <h3>Earth Observation</h3>
        <p>
          Large-scale analysis of Sentinel, Landsat, MODIS, CHIRPS, WorldCover,
          WorldPop, and other geospatial datasets.
        </p>
      </div>

      <div class="card">
        <h3>Decision Intelligence</h3>
        <p>
          Translating complex geospatial data into maps, dashboards, indicators,
          and products that support action.
        </p>
      </div>
    </div>
  </section>

  <main>
    <section id="systems">
      <h2>Flagship AI Systems</h2>

      <p class="section-lead">
        These projects show ho
        
        
      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/wildfire-insurance-risk-intelligence/" target="_blank" rel="noopener noreferrer">
            Wildfire Insurance Intelligence
          </a>
        </h3>
        <p>
          A geospatial risk intelligence project for wildfire exposure screening, insurance analytics,
          catastrophe monitoring, portfolio exposure analysis, and climate-risk decision support.
        </p>
        <span class="tag">Wildfire Risk</span>
        <span class="tag">Insurance Analytics</span>
        <span class="tag">Satellite Data</span>
        <span class="tag">Streamlit</span>
        <br />
        <a class="button primary" href="https://geospatial-ai-portfolio-3o5dmze6m2y4bc4ktk4zep.streamlit.app" target="_blank" rel="noopener noreferrer">Open Live App</a>
        <a class="button" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/wildfire-insurance-risk-intelligence/" target="_blank" rel="noopener noreferrer">Read Case Study</a>
      </div>

      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/floodwatch-map/" target="_blank" rel="noopener noreferrer">
            FloodWatch — Real-Time Flood Intelligence
          </a>
        </h3>
        <p>
          A public-facing geospatial news and flood-awareness map for tracking flood-related
          information and supporting location-based disaster communication.
        </p>
        <span class="tag">Flood Risk</span>
        <span class="tag">Interactive Map</span>
        <span class="tag">Disaster Communication</span>
        <br />
        <a class="button primary" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/floodwatch-map/" target="_blank" rel="noopener noreferrer">Open Project</a>
      </div>

      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/niger-delta-gas-flares/" target="_blank" rel="noopener noreferrer">
            Satellite Monitoring of Niger Delta Gas Flares
          </a>
        </h3>
        <p>
          Remote sensing project for monitoring gas flaring, environmental pressure,
          and pollution-related spatial patterns in the Niger Delta.
        </p>
        <span class="tag">Gas Flaring</span>
        <span class="tag">Environmental Monitoring</span>
        <span class="tag">Remote Sensing</span>
        <br />
        <a class="button primary" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/niger-delta-gas-flares/" target="_blank" rel="noopener noreferrer">Read Case Study</a>
      </div>

      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/cocoa-protected-areas/" target="_blank" rel="noopener noreferrer">
            Cocoa Expansion and Protected Areas
          </a>
        </h3>
        <p>
          Earth observation project examining cocoa plantation expansion and its implications
          for protected landscapes and conservation planning in West Africa.
        </p>
        <span class="tag">Land Cover</span>
        <span class="tag">Protected Areas</span>
        <span class="tag">Conservation</span>
        <br />
        <a class="button primary" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/cocoa-protected-areas/" target="_blank" rel="noopener noreferrer">Read Case Study</a>
      </div>

      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/baltimore-heat-index/" target="_blank" rel="noopener noreferrer">
            Urban Heat Intelligence
          </a>
        </h3>
        <p>
          Urban heat and climate-risk analysis using land surface temperature, land cover,
          vegetation, census variables, and environmental indicators.
        </p>
        <span class="tag">Urban Heat</span>
        <span class="tag">Climate Risk</span>
        <span class="tag">Google Earth Engine</span>
        <br />
        <a class="button primary" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/baltimore-heat-index/" target="_blank" rel="noopener noreferrer">Read Case Study</a>
      </div>

      <div class="card project-card">
        <h3 class="project-title">
          <a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/floodclaims-intelligence/" target="_blank" rel="noopener noreferrer">
            Flood Claims Intelligence
          </a>
        </h3>
        <p>
          Spatial insurance analytics project for understanding flood claims, exposure,
          and risk patterns.
        </p>
        <span class="tag">Flood Claims</span>
        <span class="tag">Insurance</span>
        <span class="tag">Spatial Analytics</span>
        <br />
        <a class="button primary" href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/floodclaims-intelligence/" target="_blank" rel="noopener noreferrer">Open Project</a>
      </div>
    </section>

    <section id="impact">
      <h2>Research Impact and Applied Scale</h2>
      <p class="section-lead">
        My work combines peer-reviewed research, operational geospatial workflows, and deployable
        decision-support tools across environmental monitoring, climate risk, land-use change,
        disaster analytics, and population exposure.
      </p>

      <div class="metric-row">
        <div class="metric">
          <strong>7+</strong>
          <p>Years of applied geospatial science, remote sensing, and environmental analytics.</p>
        </div>
        <div class="metric">
          <strong>26+</strong>
          <p>Research outputs listed on ResearchGate.</p>
        </div>
        <div class="metric">
          <strong>4M+</strong>
          <p>Hectares of cocoa landscapes mapped in West Africa.</p>
        </div>
        <div class="metric">
          <strong>60%</strong>
          <p>Reduction in processing time through Google Earth Engine workflow automation.</p>
        </div>
      </div>
    </section>

    <section id="expertise">
      <h2>What I Can Help Build</h2>
      <p class="section-lead">
        I help teams move from raw satellite and climate data to usable intelligence products:
        maps, dashboards, models, indicators, automated workflows, and decision-support systems.
      </p>

      <div class="grid">
        <div class="card">Satellite-based environmental monitoring</div>
        <div class="card">Climate and disaster-risk mapping</div>
        <div class="card">Google Earth Engine applications</div>
        <div class="card">GIS automation and spatial data pipelines</div>
        <div class="card">Population exposure and vulnerability analysis</div>
        <div class="card">Interactive maps and decision dashboards</div>
      </div>
    </section>

    <section id="toolkit">
      <h2>Technical Toolkit</h2>

      <div class="two-grid">
        <div class="card">
          <h3>Geospatial</h3>
          <p>Google Earth Engine, ArcGIS Pro, QGIS, spatial analysis, web mapping, GIS automation.</p>
        </div>

        <div class="card">
          <h3>Remote Sensing</h3>
          <p>Sentinel, Landsat, MODIS, ESA WorldCover, WorldPop, satellite classification, environmental monitoring.</p>
        </div>

        <div class="card">
          <h3>Programming</h3>
          <p>Python, R, JavaScript, Streamlit, GitHub Pages, reproducible geospatial workflows.</p>
        </div>

        <div class="card">
          <h3>Applications</h3>
          <p>Climate risk, disaster analytics, environmental monitoring, land-use change, population exposure, decision support.</p>
        </div>
      </div>
    </section>

    <section id="publications">
      <h2>Selected Publications and Research</h2>

      <div class="card">
        <p>
          <strong>Detecting cocoa plantations in Côte d’Ivoire and Ghana and their implications on protected areas.</strong>
          Ecological Indicators, 2021.
        </p>

        <p>
          <strong>Environmental contamination of a biodiversity hotspot—Action needed for nature conservation in the Niger Delta, Nigeria.</strong>
          Sustainability, 2022.
        </p>

        <p class="small-note">
          Additional publications and research outputs are available through Google Scholar, ResearchGate, and ORCID.
        </p>

        <a class="button primary" href="https://scholar.google.com/citations?user=eHVvCCkAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>
        <a class="button" href="https://www.researchgate.net/profile/Itohan-Osa-Abu/research" target="_blank" rel="noopener noreferrer">ResearchGate</a>
      </div>
    </section>

    <section id="contact">
      <h2>Let’s build AI systems for climate and environmental decisions.</h2>

      <p class="section-lead">
        I am open to senior geospatial AI, climate AI, Earth observation, environmental intelligence,
        insurance analytics, and research scientist opportunities.
      </p>

      <a class="button primary" href="mailto:abuitohanosa@gmail.com">Email Me</a>
      <a class="button" href="https://github.com/itohanosa" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a class="button" href="https://github.com/itohanosa/geospatial-ai-portfolio" target="_blank" rel="noopener noreferrer">Portfolio Repository</a>
      <a class="button" href="https://www.linkedin.com/in/itohan-osa-abu-155032b1/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a class="button" href="https://www.researchgate.net/profile/Itohan-Osa-Abu/research" target="_blank" rel="noopener noreferrer">ResearchGate</a>
      <p class="small-note">ORCID: 0000-0002-7450-0601</p>
    </section>
  </main>

  <footer>
    © 2026 Itohan-Osa Abu · Geospatial AI · Remote Sensing · Climate Risk Analytics
  </footer>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Itohan-Osa Abu",
    "url": "https://itohanosa.github.io/",
    "sameAs": [
      "https://github.com/itohanosa",
      "https://www.linkedin.com/in/itohan-osa-abu-155032b1/",
      "https://scholar.google.com/citations?user=eHVvCCkAAAAJ&hl=en",
      "https://www.researchgate.net/profile/Itohan-Osa-Abu/research"
    ],
    "jobTitle": "Geospatial AI Scientist",
    "knowsAbout": [
      "Geospatial AI",
      "Remote Sensing",
      "GIS Automation",
      "Google Earth Engine",
      "Climate Risk Analytics",
      "Disaster Analytics",
      "Environmental Monitoring",
      "Spatial Machine Learning",
      "Earth Observation AI"
    ],
    "email": "mailto:abuitohanosa@gmail.com"
  }
  </script>

</body>
</html>
w I convert satellite observations, spatial analytics, and AI workflows
        into usable products for climate-risk and environmental decision-making.
      </p>
