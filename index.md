---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Itohan-Osa Abu | Geospatial AI Scientist</title>

  <meta name="description" content="Itohan-Osa Abu is a Geospatial AI Scientist specializing in remote sensing, GIS automation, Google Earth Engine, climate-risk analytics, disaster mapping, environmental monitoring, and spatial machine learning." />
  <meta name="keywords" content="Itohan-Osa Abu, Geospatial AI, Remote Sensing, GIS Automation, Google Earth Engine, Climate Risk Analytics, Environmental Monitoring, Disaster Analytics, Spatial Machine Learning, Satellite Data" />
  <meta name="author" content="Itohan-Osa Abu" />

  <meta property="og:title" content="Itohan-Osa Abu | Geospatial AI Scientist" />
  <meta property="og:description" content="Geospatial AI, remote sensing, GIS automation, climate-risk analytics, disaster mapping, and environmental monitoring portfolio." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://itohanosa.github.io/" />

  <style>
    :root {
      --bg: #f6f3ec;
      --ink: #172033;
      --muted: #5f6b7a;
      --accent: #0f766e;
      --accent2: #2563eb;
      --card: #ffffff;
      --line: #e5dfd4;
      --soft: #eef7f5;
      --shadow: 0 18px 45px rgba(23, 32, 51, 0.10);
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Inter, Arial, sans-serif;
      background:
        radial-gradient(circle at top left, #dff7ef 0, transparent 35%),
        radial-gradient(circle at top right, #e8edff 0, transparent 30%),
        var(--bg);
      color: var(--ink);
      line-height: 1.65;
    }

    a {
      color: var(--accent2);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .page {
      max-width: 1080px;
      margin: auto;
      padding: 22px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 18px;
      padding: 18px 0 28px;
      flex-wrap: wrap;
    }

    .brand {
      font-weight: 800;
      color: var(--ink);
      letter-spacing: -0.03em;
    }

    .navlinks {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
      font-size: 14px;
      font-weight: 700;
    }

    .navlinks a {
      color: #334155;
    }

    .hero {
      background: rgba(255, 255, 255, 0.82);
      border: 1px solid var(--line);
      border-radius: 28px;
      padding: 42px 28px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(10px);
    }

    .eyebrow {
      display: inline-block;
      background: var(--soft);
      color: var(--accent);
      border: 1px solid #ccebe5;
      padding: 7px 12px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: 800;
      margin-bottom: 18px;
    }

    h1 {
      font-size: clamp(42px, 7vw, 78px);
      line-height: 0.95;
      margin: 0;
      letter-spacing: -0.07em;
      color: #0f172a;
    }

    .subtitle {
      font-size: clamp(20px, 4vw, 30px);
      color: var(--muted);
      margin-top: 18px;
      max-width: 860px;
      letter-spacing: -0.03em;
    }

    .intro {
      max-width: 780px;
      font-size: 18px;
      color: #334155;
      margin-top: 24px;
    }

    .buttons {
      margin-top: 28px;
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }

    .button {
      display: inline-block;
      padding: 12px 18px;
      border-radius: 999px;
      border: 1px solid #cbd5e1;
      color: var(--ink);
      background: #ffffff;
      font-weight: 800;
      box-shadow: 0 6px 15px rgba(15, 23, 42, 0.06);
    }

    .button.primary {
      background: var(--ink);
      color: #ffffff;
      border-color: var(--ink);
    }

    section {
      margin-top: 62px;
    }

    .section-title {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 20px;
      border-bottom: 1px solid var(--line);
      padding-bottom: 12px;
      margin-bottom: 24px;
    }

    h2 {
      margin: 0;
      font-size: 30px;
      letter-spacing: -0.04em;
    }

    .section-note {
      color: var(--muted);
      font-size: 14px;
      margin: 0;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 18px;
    }

    .project {
      background: var(--card);
      border: 1px solid var(--line);
      border-radius: 22px;
      padding: 22px;
      box-shadow: 0 10px 28px rgba(23, 32, 51, 0.07);
      min-height: 255px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .project:hover {
      transform: translateY(-3px);
      transition: 0.2s ease;
      box-shadow: 0 16px 35px rgba(23, 32, 51, 0.12);
    }

    .icon {
      font-size: 28px;
      margin-bottom: 12px;
    }

    .project h3 {
      margin: 0 0 8px;
      font-size: 21px;
      line-height: 1.2;
      letter-spacing: -0.03em;
    }

    .project h3 a {
      color: var(--ink);
    }

    .project p {
      color: #475569;
      margin: 0 0 16px;
      font-size: 15px;
    }

    .tags {
      margin-top: auto;
    }

    .tag {
      display: inline-block;
      background: #f1f5f9;
      color: #334155;
      padding: 5px 9px;
      margin: 4px 4px 0 0;
      border-radius: 999px;
      font-size: 12px;
      font-weight: 700;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 16px;
    }

    .box {
      background: rgba(255,255,255,0.86);
      padding: 18px;
      border-radius: 18px;
      border: 1px solid var(--line);
      font-weight: 700;
      box-shadow: 0 8px 24px rgba(23, 32, 51, 0.06);
    }

    .toolkit {
      background: #101827;
      color: #e5e7eb;
      border-radius: 24px;
      padding: 28px;
      box-shadow: var(--shadow);
    }

    .toolkit h2 {
      color: #ffffff;
      border: 0;
    }

    .toolkit p {
      color: #cbd5e1;
    }

    .toolkit strong {
      color: #ffffff;
    }

    footer {
      padding: 42px 0 60px;
      color: var(--muted);
      font-size: 14px;
      text-align: center;
    }

    @media (max-width: 640px) {
      .page {
        padding: 16px;
      }

      nav {
        align-items: flex-start;
      }

      .navlinks {
        gap: 12px;
      }

      .hero {
        padding: 34px 20px;
        border-radius: 24px;
      }

      .subtitle {
        font-size: 21px;
      }

      .intro {
        font-size: 16px;
      }

      .section-title {
        display: block;
      }

      .section-note {
        margin-top: 6px;
      }
    }
  </style>
</head>

<body>

<div class="page">

  <nav>
    <a class="brand" href="#">Itohan-Osa Abu</a>
    <div class="navlinks">
      <a href="#projects">Projects</a>
      <a href="#services">Services</a>
      <a href="#toolkit">Toolkit</a>
      <a href="https://github.com/itohanosa" target="_blank">GitHub</a>
      <a href="https://scholar.google.com/citations?user=eHVvCCkAAAAJ&hl=en" target="_blank">Scholar</a>
      <a href="https://www.linkedin.com/in/itohan-osa-abu-155032b1/" target="_blank">LinkedIn</a>
    </div>
  </nav>

  <header class="hero">
    <span class="eyebrow">Geospatial AI · Remote Sensing · Climate Intelligence</span>

    <h1>Itohan-Osa Abu</h1>

    <div class="subtitle">
      I build satellite-powered AI tools for environmental risk, disaster intelligence, and decision support.
    </div>

    <p class="intro">
      My work transforms satellite imagery, environmental data, and machine learning outputs
      into practical maps, dashboards, and geospatial intelligence systems for climate risk,
      disaster analytics, environmental monitoring, and population exposure.
    </p>

    <div class="buttons">
      <a class="button primary" href="#projects">View Featured Projects</a>
      <a class="button" href="mailto:abuitohanosa@gmail.com">Contact Me</a>
      <a class="button" href="https://github.com/itohanosa/geospatial-ai-portfolio" target="_blank">Portfolio Repository</a>
    </div>
  </header>

  <section id="projects">
    <div class="section-title">
      <h2>Featured Projects</h2>
      <p class="section-note">Selected work across climate risk, disasters, insurance, and environmental monitoring.</p>
    </div>

    <div class="projects">

      <div class="project">
        <div>
          <div class="icon">🔥</div>
          <h3><a href="https://github.com/itohanosa/geospatial-ai-portfolio/tree/main/projects/wildfire-insurance-risk-intelligence" target="_blank">Wildfire Insurance Intelligence</a></h3>
          <p>Geospatial risk intelligence for wildfire exposure screening, insurance analytics, and climate-risk decision support.</p>
        </div>
        <div class="tags">
          <span class="tag">Wildfire Risk</span>
          <span class="tag">Insurance</span>
          <span class="tag">Satellite Data</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🌊</div>
          <h3><a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/floodwatch-map/" target="_blank">FloodWatch</a></h3>
          <p>Real-time flood intelligence map for tracking flood-related news and supporting location-based awareness.</p>
        </div>
        <div class="tags">
          <span class="tag">Flood Risk</span>
          <span class="tag">Interactive Map</span>
          <span class="tag">Disaster Communication</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🛰️</div>
          <h3><a href="https://github.com/itohanosa/geospatial-ai-portfolio/tree/main/projects/niger%20delta%20gas%20flares" target="_blank">Niger Delta Gas Flares</a></h3>
          <p>Satellite monitoring of gas flaring, environmental pressure, and pollution-related spatial patterns.</p>
        </div>
        <div class="tags">
          <span class="tag">Gas Flaring</span>
          <span class="tag">Pollution</span>
          <span class="tag">Remote Sensing</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🍫</div>
          <h3><a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/cocoa-protected-areas/" target="_blank">Cocoa & Protected Areas</a></h3>
          <p>Earth observation analysis of cocoa plantation expansion and implications for protected landscapes.</p>
        </div>
        <div class="tags">
          <span class="tag">Land Cover</span>
          <span class="tag">Conservation</span>
          <span class="tag">Protected Areas</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🌡️</div>
          <h3><a href="https://itohanosa.github.io/geospatial-ai-portfolio/projects/baltimore-heat-index/" target="_blank">Urban Heat Intelligence</a></h3>
          <p>Urban heat and climate-risk analysis using temperature, land cover, vegetation, and environmental indicators.</p>
        </div>
        <div class="tags">
          <span class="tag">Urban Heat</span>
          <span class="tag">Climate Risk</span>
          <span class="tag">Google Earth Engine</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🏠</div>
          <h3><a href="https://github.com/itohanosa/geospatial-ai-portfolio/tree/main/projects/floodclaims-intelligence" target="_blank">Flood Claims Intelligence</a></h3>
          <p>Spatial insurance analytics for understanding flood claims, exposure patterns, and risk concentration.</p>
        </div>
        <div class="tags">
          <span class="tag">Flood Claims</span>
          <span class="tag">Insurance</span>
          <span class="tag">Spatial Analytics</span>
        </div>
      </div>

      <div class="project">
        <div>
          <div class="icon">🧠</div>
          <h3><a href="https://github.com/itohanosa/geospatial-ai-portfolio/tree/main/projects/georisk-os" target="_blank">GeoRisk OS</a></h3>
          <p>A geospatial operating-system concept for environmental intelligence, hazard monitoring, and AI-assisted decision support.</p>
        </div>
        <div class="tags">
          <span class="tag">Geospatial AI</span>
          <span class="tag">Decision Support</span>
          <span class="tag">Risk Intelligence</span>
        </div>
      </div>

    </div>
  </section>

  <section id="services">
    <div class="section-title">
      <h2>What I Can Help With</h2>
      <p class="section-note">Consulting and research support for geospatial decision systems.</p>
    </div>

    <div class="grid">
      <div class="box">Satellite-based environmental monitoring</div>
      <div class="box">Climate and disaster-risk mapping</div>
      <div class="box">Google Earth Engine applications</div>
      <div class="box">GIS automation and spatial data pipelines</div>
      <div class="box">Population exposure and vulnerability analysis</div>
      <div class="box">Interactive maps and decision dashboards</div>
    </div>
  </section>

  <section id="toolkit" class="toolkit">
    <h2>Technical Toolkit</h2>
    <p><strong>Geospatial:</strong> Google Earth Engine, ArcGIS Pro, QGIS, spatial analysis, web mapping</p>
    <p><strong>Remote Sensing:</strong> Sentinel, Landsat, MODIS, ESA WorldCover, WorldPop</p>
    <p><strong>Programming:</strong> Python, R, JavaScript, Streamlit, GitHub Pages</p>
    <p><strong>Applications:</strong> Climate risk, disaster analytics, environmental monitoring, land-use change, population exposure, decision support</p>
  </section>

  <section>
    <div class="section-title">
      <h2>Selected Links</h2>
      <p class="section-note">Research, code, and professional profiles.</p>
    </div>

    <p>
      <a href="https://github.com/itohanosa" target="_blank">GitHub</a> ·
      <a href="https://github.com/itohanosa/geospatial-ai-portfolio" target="_blank">Portfolio Repository</a> ·
      <a href="https://www.linkedin.com/in/itohan-osa-abu-155032b1/" target="_blank">LinkedIn</a> ·
      <a href="https://scholar.google.com/citations?user=eHVvCCkAAAAJ&hl=en" target="_blank">Google Scholar</a>
    </p>

    <p>ORCID: 0000-0002-7450-0601</p>
  </section>

  <footer>
    © 2026 Itohan-Osa Abu · Geospatial AI · Remote Sensing · Climate Risk Analytics
  </footer>

</div>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Itohan-Osa Abu",
  "url": "https://itohanosa.github.io/",
  "sameAs": [
    "https://github.com/itohanosa",
    "https://www.linkedin.com/in/itohan-osa-abu-155032b1/",
    "https://scholar.google.com/citations?user=eHVvCCkAAAAJ&hl=en"
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
    "Spatial Machine Learning"
  ],
  "email": "mailto:abuitohanosa@gmail.com"
}
</script>

</body>
</html>
