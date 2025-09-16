---
layout: default
title: Home
---

<link rel="stylesheet" href="/assets/css/custom.css">

<!-- NAV like the reference -->
<nav class="navbar">
  <a href="#home">HOME</a>
  <a href="#portfolio">PORTFOLIO</a>
  <a href="#tools">TOOLS AND COMPETENCES</a>
  <a href="#experience">EXPERIENCE</a>
  <a href="#contact">CONTACT</a>
</nav>

<!-- HOME -->
<div id="home" class="section">
  <div class="hero">
    <img src="/assets/img/headshot.jpg" alt="Ebenezer Oloyede">
    <div>
      <h1 class="hero-title">I'M<br/>EBENEZER  FIYINFOLUWA  OLOYEDE</h1>
      <div class="hero-sub">DATA / BUSINESS INTELLIGENCE ANALYST</div>
      <p>I turn complex data into clear, actionable insights using <strong>Power BI, SQL, Python</strong> and <strong>analytics automation</strong>.</p>
      <p>
        <a href="mailto:fiyinoloyede84@gmail.com">fiyinoloyede84@gmail.com</a> ·
        <a href="https://linkedin.com/in/ebenezeroloyede">LinkedIn</a> ·
        <a href="https://github.com/fiyinoloyede">GitHub</a> ·
        <a href="/assets/cv/Ebenezer_Oloyede_CV.pdf">Download CV</a>
      </p>
    </div>
  </div>
  <div class="banner"></div> <!-- optional hero image; remove if not using -->
  <p style="margin-top:10px;">
    I’m a data professional with over 5 years of experience across <em>business intelligence, analytics automation, and data science</em>. I build high-impact dashboards, streamline data pipelines, and solve data quality challenges so teams can make better decisions.
  </p>
</div>

<!-- TOOLS AND COMPETENCES (logos first, like reference) -->
<div id="tools" class="section">
  <h2>Tools and competences</h2>
  <div class="logo-grid">
    <div class="logo-item"><img src="/assets/logos/skills/excel.png" alt="Excel"><span>Microsoft Excel</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/python.png" alt="Python"><span>Python</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/power-bi.png" alt="Power BI"><span>Power BI</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/sql.png" alt="SQL"><span>SQL</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/power-automate.png" alt="Power Automate"><span>Power Automate</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/spark.png" alt="Spark"><span>Apache Spark</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/r.png" alt="R"><span>R Programming</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/salesforce.png" alt="Salesforce"><span>Salesforce</span></div>
    <div class="logo-item"><img src="/assets/logos/skills/jira.png" alt="Jira"><span>Jira</span></div>
  </div>

  <h3 style="margin-top:1.6rem;">CERTIFICATION</h3>
  <div class="logo-grid">
    <div class="logo-item"><img src="/assets/logos/certs/azure-ai-fundamentals.png" alt="Azure AI"><span>Microsoft Azure AI Fundamentals (AI-900) – 2025</span></div>
    <div class="logo-item"><img src="/assets/logos/certs/azure-data-fundamentals.png" alt="Azure Data"><span>Microsoft Azure Data Fundamentals (DP-900) – 2024</span></div>
    <div class="logo-item"><img src="/assets/logos/certs/ibm-data-science.png" alt="IBM"><span>IBM Data Science Certificate – 2023</span></div>
    <div class="logo-item"><img src="/assets/logos/certs/google-data-analytics.png" alt="Google"><span>Google Data Analytics Certificate – 2022</span></div>
    <div class="logo-item"><img src="/assets/logos/certs/rice-university.jpg" alt="Rice University"><span>Business Statistics & Analysis (Rice University) – 2022</span></div>
  </div>
</div>

<!-- PORTFOLIO (image grid + “Executive Summary” + buttons — like the reference) -->
<div id="portfolio" class="section">
  <h2>PROFESSIONAL PORTFOLIO</h2>

  <!-- Image grid (clickable) -->
  <div class="grid">
    <a href="https://github.com/FiyinOloyede/Product_Recommendation" title="Product Recommendation System (Python)">
      <img src="/assets/img/projects/reco_overview.png" alt="Product Recommendation System">
    </a>
    <a href="https://github.com/FiyinOloyede/house_prediction_with_pyspark_mllib" title="House Price Prediction (PySpark)">
      <img src="/assets/img/projects/house_overview.jpg" alt="House Price Prediction">
    </a>
    <a href="https://github.com/FiyinOloyede/IBM_Data_Science_SpaceX_Landing_Prediction" title="Predictive Analysis on Space Rocket Data">
      <img src="/assets/img/projects/rocket_overview.png" alt="Space Rocket Prediction">
    </a>
    <a href="https://www.kaggle.com/code/fiyinoloyede/divvy-trip-data-full-year-analysis" title="Cyclistic Bike Share – Case Study (R)">
      <img src="/assets/img/projects/bike_overview.png" alt="Cyclistic Bike Share">
    </a>
    <a href="https://app.powerbi.com/view?r=eyJrIjoiNzAzOTYwZTEtMjJjMy00YjNlLWE0OTQtOGQ0NzFhMDdmMTY4IiwidCI6IjA0NDBlNjdlLTNkYjItNDgxMS05YzEwLWQzZDFmZDI1MmIyZiJ9" title="Udemy Course Dashboard (Power BI)">
      <img src="/assets/img/projects/udemy_overview.png" alt="Udemy Dashboard">
    </a>
    <a href="https://app.powerbi.com/view?r=eyJrIjoiNzc5MzM5NzEtZDcyMi00MWJkLTlmNjAtZDU4MmJiMzhmZjJmIiwidCI6IjA0NDBlNjdlLTNkYjItNDgxMS05YzEwLWQzZDFmZDI1MmIyZiJ9" title="Cribie Dashboard (Power BI)">
      <img src="/assets/img/projects/cribie_overview.png" alt="Cribie Dashboard">
    </a>
    <a href="https://www.kaggle.com/code/fiyinoloyede/airline-passenger-satisfaction" title="Passenger Satisfaction Dashboard (Power BI & R)">
      <img src="/assets/img/projects/psd_overview.png" alt="Passenger Satisfaction Dashboard">
    </a>
  </div>

  <!-- Executive summaries + buttons -->
  <p class="exec">Executive Summary:</p>
  <div class="card">
    <h3>Product Recommendation System (Python)</h3>
    <p>Word2Vec-based recommendation engine that learns product relationships from purchase history to generate personalized suggestions for e-commerce users.</p>
    <p><strong>Dataset:</strong> Online retail transactions (Dec 2010–Dec 2011, UK non-store retailer).</p>
    <p class="btns">
      <a href="https://github.com/FiyinOloyede/Product_Recommendation">View Repo</a>
      <a href="/assets/img/projects/reco_overview.png">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>House Price Prediction (Python with Spark)</h3>
    <p>Built regression models with PySpark MLlib on King County data; selected the optimal model by lowest RMSE and highest R².</p>
    <p><strong>Dataset:</strong> King County sales (May 2014–May 2015).</p>
    <p class="btns">
      <a href="https://github.com/FiyinOloyede/house_prediction_with_pyspark_mllib">View Repo</a>
      <a href="/assets/img/projects/house_overview.jpg">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>Predictive Analysis on Space Rocket Data (Python & SQL)</h3>
    <p>Collected via REST API + web scraping; SQL for EDA and Folium mapping; trained Decision Tree model achieving ~86.2% accuracy for launch success.</p>
    <p class="btns">
      <a href="https://github.com/FiyinOloyede/IBM_Data_Science_SpaceX_Landing_Prediction">View Repo</a>
      <a href="/assets/img/projects/rocket_overview.png">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>Cyclistic Bike Share – Case Study (R)</h3>
    <p>Explored differences between members and casual riders to inform targeted conversion strategy; tidyverse workflow (dplyr, ggplot2).</p>
    <p class="btns">
      <a href="https://www.kaggle.com/code/fiyinoloyede/divvy-trip-data-full-year-analysis">View Notebook</a>
      <a href="/assets/img/projects/bike_overview.png">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>Udemy Course Dashboard (Power BI)</h3>
    <p>Revenue, lectures, subscribers, categories (2012–2017), with pricing and behaviour insights to support content strategy.</p>
    <p class="btns">
      <a href="https://app.powerbi.com/view?r=eyJrIjoiNzAzOTYwZTEtMjJjMy00YjNlLWE0OTQtOGQ0NzFhMDdmMTY4IiwidCI6IjA0NDBlNjdlLTNkYjItNDgxMS05YzEwLWQzZDFmZDI1MmIyZiJ9">View Dashboard</a>
      <a href="/assets/img/projects/udemy_overview.png">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>Cribie Dashboard (Power BI)</h3>
    <p>2023 user registrations, engagement, and order volume by month/region. KPIs monitor growth and highlight regional opportunities.</p>
    <p class="btns">
      <a href="https://app.powerbi.com/view?r=eyJrIjoiNzc5MzM5NzEtZDcyMi00MWJkLTlmNjAtZDU4MmJiMzhmZjJmIiwidCI6IjA0NDBlNjdlLTNkYjItNDgxMS05YzEwLWQzZDFmZDI1MmIyZiJ9">View Dashboard</a>
      <a href="/assets/img/projects/cribie_overview.png">Screenshot</a>
    </p>
  </div>

  <div class="card">
    <h3>Passenger Satisfaction Dashboard (Power BI & R)</h3>
    <p>NPS-driven analysis with EDA in R (tidyverse) and advanced DAX modeling in Power BI to surface operational improvements.</p>
    <p class="btns">
      <a href="https://www.kaggle.com/code/fiyinoloyede/airline-passenger-satisfaction">View Notebook</a>
      <a href="/assets/img/projects/psd_overview.png">Screenshot</a>
    </p>
  </div>
</div>

<!-- EXPERIENCE (cards like reference) -->
<div id="experience" class="section experience">
  <h2>Experience</h2>

  <div class="role">
    <img src="/assets/img/projects/cribie_overview.png" alt="University of Lincoln"> <!-- replace with logo if available -->
    <div>
      <h3>Business Intelligence Analyst — University of Lincoln (Mar 2025 – Present)</h3>
      <ul>
        <li>10+ Power BI dashboards (Appointments, Events, Opportunities, Logins, Skills) across 1M+ rows → 40% lift in data-informed decisions.</li>
        <li>Automated ETL with SQL + Power Query (−60% refresh); optimized models (+70%) using advanced DAX.</li>
        <li>Python analysis uncovered efficiencies → 25% productivity boost.</li>
      </ul>
    </div>
  </div>

  <div class="role">
    <img src="/assets/img/projects/udemy_overview.png" alt="Philip Morris International"> <!-- replace with logo if available -->
    <div>
      <h3>Digital Platform Data Analyst — Philip Morris International (Jul 2023 – Sep 2024)</h3>
      <ul>
        <li>Automated analytics (Power BI + SQL) for 25k+ outlets → 80% less manual reporting; database optimization +65%.</li>
        <li>Python behavior modeling increased weekly returning users by 30%.</li>
        <li>Delivered KPI dashboards for operational & strategic decisions.</li>
      </ul>
    </div>
  </div>

  <div class="role">
    <img src="/assets/img/projects/reco_overview.png" alt="Quantum Expressions"> <!-- replace with logo if available -->
    <div>
      <h3>Data Analyst — Quantum Expressions Media Consult (Jun 2022 – Jun 2023)</h3>
      <ul>
        <li>KPI dashboards (Power BI) improved budget monitoring & activity tracking; +42% revenue, +45% engagement.</li>
        <li>SQL + Python analysis produced insights for monetization & optimization.</li>
      </ul>
    </div>
  </div>

  <div class="role">
    <img src="/assets/img/projects/house_overview.jpg" alt="T. Pumpy Concept"> <!-- replace with logo if available -->
    <div>
      <h3>Data Analyst — T. Pumpy Concept (Dec 2020 – May 2022)</h3>
      <ul>
        <li>Excel & Power BI performance analysis; processed 10k+ sales records with SQL to streamline workflows.</li>
        <li>Implemented CRM across 7 branches to improve customer data management.</li>
      </ul>
    </div>
  </div>
</div>

<!-- CONTACT -->
<div id="contact" class="section">
  <h2>CONTACT</h2>
  <p>
    ✉️ <a href="mailto:fiyinoloyede84@gmail.com">fiyinoloyede84@gmail.com</a><br/>
    📞 +44 7881 162823<br/>
    💼 <a href="https://linkedin.com/in/ebenezeroloyede">linkedin.com/in/ebenezeroloyede</a><br/>
    🖥 <a href="https://github.com/fiyinoloyede">github.com/fiyinoloyede</a><br/>
    📄 <a href="/assets/cv/Ebenezer_Oloyede_CV.pdf">Download CV (General)</a> · <a href="/assets/cv/Ebenezer_Oloyede_CV_Contract.pdf">Download CV (Contract)</a>
  </p>
</div>
