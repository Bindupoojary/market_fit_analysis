<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Air Quality, Health & Market Demand Analysis — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0b1116;--card:#17232b;--muted:#94a3b8;--accent:#14b8a6}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,Arial;background:var(--bg);color:#e6eef6}
    .wrap{max-width:1100px;margin:28px auto;padding:28px}
    header{display:flex;gap:16px;align-items:center}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#0fbf9a);display:flex;align-items:center;justify-content:center;font-weight:800;color:#042b26}
    h1{font-size:20px;margin:0}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .section{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:16px;border-radius:10px;margin-top:18px;border:1px solid rgba(255,255,255,0.03)}
    .gallery-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:12px}
    .gallery-grid img{width:100%;height:180px;object-fit:cover;border-radius:8px}
    a.powerbi{color:var(--accent);font-weight:700}
    pre {background:#071018;padding:12px;border-radius:8px;overflow:auto;color:#86e1c4}
    ul{margin:8px 0 0 18px}
    @media(max-width:900px){.gallery-grid{grid-template-columns:repeat(2,1fr)} }
    @media(max-width:560px){.gallery-grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">AQ</div>
      <div>
        <h1>Air Quality, Health Impact & Market Demand Analysis</h1>
        <p class="lead">Integrated Power BI analysis combining AQI, respiratory health data and market intelligence for targeted interventions and commercial strategies.</p>
      </div>
    </header>

    <section class="section">
      <h2>Project Summary</h2>
      <p>This project presents a unified analytical framework connecting air pollution metrics, public health outcomes, and market demand signals to provide actionable recommendations for policymakers and consumer brands.</p>
    </section>

    <section class="section">
      <h2>Dashboard Preview & Live Link</h2>
      <p>Open the interactive report: <a class="powerbi" href="https://app.powerbi.com/view?r=eyJrIjoiZjIzY2Y2YjUtODRlYS00OWEyLWE1YmQtYTNiYmQyOGQzYTJmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" target="_blank">🔗 Live Power BI Dashboard</a></p>

      <div class="gallery-grid">
        <img src="/mnt/data/8c5ad604-1fbc-4488-8139-d6b5b1497c71.png" alt="Dashboard 1" />
        <img src="/mnt/data/505e6cc5-16ce-4190-a408-0ac072f8a47f.png" alt="Dashboard 2" />
        <img src="/mnt/data/0e528358-518b-41a3-a825-b6806f647d37.png" alt="Dashboard 3" />
        <img src="/mnt/data/7b204dd3-2254-4b32-8cc0-de93ac13ec3a.png" alt="Dashboard 4" />
        <img src="/mnt/data/1a837dee-7aa0-4a70-9c09-eb882d959049.png" alt="Respiratory Health 1" />
        <img src="/mnt/data/8e840021-b442-46de-af06-9f6ec275da1f.png" alt="Respiratory Health 2" />
        <img src="/mnt/data/fd1fc076-e3b8-462b-9f96-eb399d16f2c7.png" alt="Market 1" />
        <img src="/mnt/data/849683e3-14b3-4a4d-915d-10ca38033c15.png" alt="Market 2" />
        <img src="/mnt/data/042c3108-7335-4a7d-a0d1-031f0182ed9c.png" alt="Market 3" />
      </div>
    </section>

    <section class="section">
      <h2>Detailed Breakdown of Dashboard Views</h2>

      <h3>1. AQI Severity & Environmental Risk View</h3>
      <p>This view provides a macro-level understanding of India's air quality landscape. It highlights:</p>
      <ul>
        <li><strong>Monthly AQI fluctuations</strong> with YoY comparison to assess improvement or deterioration.</li>
        <li><strong>State-wise AQI bubble distribution</strong> to visually identify geographic pollution clusters.</li>
        <li><strong>Critical days count</strong> indicating extreme pollution events requiring urgent intervention.</li>
        <li><strong>Pollutant composition analysis</strong> (PM2.5, PM10, SO₂, NO₂, O₃) to trace emission sources.</li>
        <li><strong>Weekday vs weekend AQI variations</strong> showing behavioral or industrial impact on pollution.</li>
        <li><strong>EV vehicle penetration</strong> compared with AQI to evaluate early transition impact.</li>
      </ul>

      <h3>2. Health Impact & Respiratory Disease View</h3>
      <p>This module overlays air quality indicators with health outcomes to understand how environmental degradation influences public health. Key insights include:</p>
      <ul>
        <li><strong>Disease case trends</strong> by month showing seasonal outbreak patterns aligned with pollution peaks.</li>
        <li><strong>Disease-wise breakdown</strong> including influenza-like illnesses, H1N1 and other respiratory conditions.</li>
        <li><strong>State-wise respiratory disease distribution</strong> identifying medically vulnerable zones.</li>
        <li><strong>AQI vs respiratory case correlation table</strong> quantifying exposure–impact relationships.</li>
        <li><strong>Total deaths vs reported cases</strong> offering severity understanding for healthcare planning.</li>
      </ul>

      <h3>3. Executive Market Demand & Opportunity View</h3>
      <p>This view is tailored for business, product, and strategy teams to evaluate the commercial landscape for air purifiers. It consolidates:</p>
      <ul>
        <li><strong>Priority score by state</strong> combining AQI severity, income, disease load, and market triggers.</li>
        <li><strong>Competitive analysis</strong> of major purifier brands on pricing, CADR, features, and coverage.</li>
        <li><strong>Feature gap scoring</strong> to identify strengths and weaknesses of competitors.</li>
        <li><strong>State-wise pollutant mapping</strong> and recommended filter types based on pollutant dominance.</li>
        <li><strong>Income vs AQI scatter correlation</strong> to identify high-demand/high-affordability consumer segments.</li>
      </ul>

      <h3>Overall Project Outcomes</h3>
      <ul>
        <li><strong>Holistic Risk Identification:</strong> Integrated AQI–health–economic signals revealed 8–12 states requiring urgent policy and business attention.</li>
        <li><strong>Actionable Market Intelligence:</strong> Mid-range air purifiers emerged as optimal for most Indian states due to price–feature balance.</li>
        <li><strong>Filter Technology Mapping:</strong> Provided pollutant-specific filter recommendations enabling companies to localize product variants.</li>
        <li><strong>Seasonal Intervention Strategy:</strong> Identified winter and early monsoon as the most critical windows for both health advisories and purifier sales surges.</li>
        <li><strong>High-Value Decision Framework:</strong> Produced a multi-layer system usable by government bodies, healthcare organizations, and consumer brands.</li>
      </ul>
    </section>

    <footer style="margin-top:20px;color:#94a3b8">Prepared by — Data Analyst Portfolio • Includes visualization and decision insights ready for interviews</footer>
  </div>
</body>
</html>
