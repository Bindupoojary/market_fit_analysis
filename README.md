
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Air Quality, Health & Market Demand Analysis — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1b24; --card:#17232b; --muted:#94a3b8; --accent:#0fbf9a; --accent-2:#14b8a6; --glass:rgba(255,255,255,0.03);
      --card-border: rgba(255,255,255,0.03);
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#0b1116 0%, #081218 100%);color:#e6eef6}
    .container{max-width:1100px;margin:28px auto;padding:28px}
    header{display:flex;align-items:center;gap:18px}
    .logo{width:64px;height:64px;background:linear-gradient(135deg,var(--accent),var(--accent-2));border-radius:12px;display:flex;align-items:center;justify-content:center;box-shadow:0 6px 22px rgba(11,22,26,0.6)}
    .logo h1{margin:0;font-size:22px;color:#042b26}
    .title{flex:1}
    h1.project{margin:0;font-size:22px;font-weight:700}
    p.lead{color:var(--muted);margin:6px 0 0}

    .meta{display:flex;gap:10px;margin-top:18px;flex-wrap:wrap}
    .pill{background:var(--card);padding:8px 12px;border-radius:8px;border:1px solid var(--card-border);color:var(--muted);font-weight:600;font-size:13px}

    .hero{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:22px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid var(--card-border)}
    .overview{line-height:1.6;color:#d7e6f2}

    .kpis{display:flex;gap:12px;margin-top:12px}
    .kpi{flex:1;background:var(--card);padding:14px;border-radius:10px;border:1px solid var(--card-border)}
    .kpi .num{font-size:20px;font-weight:800}
    .kpi .lbl{color:var(--muted);font-size:12px;margin-top:6px}

    .gallery{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:14px}
    .gallery img{width:100%;height:220px;object-fit:cover;border-radius:8px;border:1px solid rgba(255,255,255,0.03);box-shadow:0 6px 18px rgba(2,6,9,0.6)}

    h2.section{font-size:18px;margin:20px 0 10px}
    .two-col{display:grid;grid-template-columns:1fr 420px;gap:18px}

    .features{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .feature{background:var(--card);padding:12px;border-radius:10px}
    .feature h4{margin:0 0 8px}
    .feature p{margin:0;color:var(--muted);font-size:14px}

    .impact-list{background:var(--card);padding:14px;border-radius:10px}
    .impact-list ul{margin:8px 0 0;padding-left:18px;color:#dbeaf0}
    .impact-list li{margin:8px 0}

    pre.code{background:#071018;padding:12px;border-radius:8px;color:#86e1c4;overflow:auto}

    footer{margin-top:28px;color:var(--muted);font-size:13px;text-align:center}

    @media (max-width:980px){.hero{grid-template-columns:1fr} .two-col{grid-template-columns:1fr} .gallery{grid-template-columns:1fr} }

    .btn{display:inline-flex;gap:8px;align-items:center;background:linear-gradient(90deg,var(--accent),var(--accent-2));border:none;color:#042b26;padding:10px 12px;border-radius:10px;font-weight:700;cursor:pointer}
    .mutebtn{background:transparent;border:1px solid var(--card-border);color:var(--muted);padding:8px 10px;border-radius:8px}

    .tags{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .tag{background:#0c2730;padding:6px 10px;border-radius:999px;color:var(--muted);font-weight:600;font-size:13px}

    .table{width:100%;border-collapse:collapse;margin-top:10px}
    .table th{ text-align:left;color:var(--muted);font-size:13px;padding:8px}
    .table td{padding:8px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border-top:1px solid rgba(255,255,255,0.02)}

    .priority{display:flex;gap:8px;align-items:center}
    .dot{width:10px;height:10px;border-radius:99px;background:var(--accent)}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo" aria-hidden><h1>AQ</h1></div>
      <div class="title">
        <h1 class="project">Air Quality, Health Impact & Market Demand Analysis</h1>
        <p class="lead">Integrated Power BI analysis connecting environmental, public health and market data to produce policy and commercial recommendations across India.</p>
        <div class="meta">
          <div class="pill">Power BI • Python • Dataful</div>
          <div class="pill">ETL | DAX | Mapping | Scoring</div>
          <div class="pill">Portfolio Case Study • Recruiter-ready</div>
        </div>
      </div>
      <div style="display:flex;flex-direction:column;gap:8px;align-items:flex-end">
        <button class="btn" onclick="window.print()">Export / Print</button>
        <button class="mutebtn" onclick="document.getElementById('gallery').scrollIntoView({behavior:'smooth'})">Preview Visuals</button>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="card overview">
          <h2 class="section">Project Summary</h2>
          <p>This multi-module analysis identifies where air pollution and respiratory health risks overlap with market demand for air purifiers. It combines time-series AQI analysis, pollutant breakdowns, disease incidence mapping, competitor benchmarking, and a priority/market-score to recommend targeted interventions and product strategies.</p>

          <div class="kpis">
            <div class="kpi">
              <div class="num">Avg AQI</div>
              <div class="lbl">State & national severity profiling</div>
            </div>
            <div class="kpi">
              <div class="num">Resp Disease</div>
              <div class="lbl">Linked to pollution spikes</div>
            </div>
            <div class="kpi">
              <div class="num">Market Score</div>
              <div class="lbl">Demand + Income + Disease</div>
            </div>
          </div>

          <div class="tags">
            <div class="tag">Mapping & Geo Analysis</div>
            <div class="tag">Seasonal Trend Analysis</div>
            <div class="tag">Feature Gap Analysis</div>
            <div class="tag">Priority Scoring Model</div>
          </div>

          <h2 class="section">Key Achievements</h2>
          <ul class="impact-list">
            <li>Identified high-priority states for policy and market action using a composite priority score.</li>
            <li>Mapped pollutant dominance per state and recommended filter types (HEPA, Activated Carbon, Chemical Scrubber).</li>
            <li>Built competitor feature and pricing matrix to derive market positioning and gaps for mid-range purifiers.</li>
            <li>Highlighted seasonal windows where health interventions or product promotions will have highest ROI.</li>
          </ul>

        </div>

        <aside class="card" style="display:flex;flex-direction:column;gap:12px">
          <div>
            <h3 style="margin:0 0 8px">Role & Responsibilities</h3>
            <div style="color:var(--muted);font-size:14px">Data Cleaning & ETL (Python) • Model & Measures (Power BI DAX) • Mapping & Visualization • Market Research • Insight storytelling</div>
          </div>

          <div>
            <h3 style="margin:0 0 8px">Impact Metrics</h3>
            <table class="table"><thead><tr><th>Outcome</th><th>Value</th></tr></thead>
            <tbody>
              <tr><td>High-priority states flagged</td><td>~10 states (top-tier)</td></tr>
              <tr><td>Dominant pollutant mapping</td><td>PM2.5 / PM10 + region-specific SO₂/NO₂</td></tr>
              <tr><td>Recommended purifier tier</td><td>Mid-range best product-market fit</td></tr>
            </tbody></table>
          </div>

          <div>
            <h3 style="margin:0 0 8px">Download</h3>
            <div style="display:flex;gap:8px"><button class="mutebtn">Download PBIX</button><button class="mutebtn">View Source Notebook</button></div>
          </div>
        </aside>
      </section>

      <section id="gallery">
        <h2 class="section">Dashboard Visuals (Selected)</h2>
        <div class="gallery">
          <img src="https://github.com/user-attachments/assets/fcb8b993-2a2b-4eeb-b358-dad1c1f07ad2" alt="AQI Dashboard 1" />
          <img src="https://github.com/user-attachments/assets/6f6291d9-004d-40e2-8c10-f9ba125c5c6a" alt="AQI Dashboard 2" />
          <img src="https://github.com/user-attachments/assets/b7e10afa-df43-4eac-bf87-9f6484d8e11e" alt="Market Module" />
          <img src="https://github.com/user-attachments/assets/849683e3-14b3-4a4d-915d-10ca38033c15.png" alt="Respiratory Module" />
        </div>
      </section>

      <section class="two-col">
        <div>
          <h2 class="section">Analytical Approach</h2>
          <div class="card">
            <h3 style="margin-top:0">Data & Preprocessing</h3>
            <p class="overview">Collected AQI timeseries, pollutant composition, state-wise EV & vehicle stats, respiratory disease incidence, and economic indicators. Performed cleaning and normalization in Python (pandas), imputed missing values using rolling seasonal median, and harmonized administrative boundaries for mapping.</p>

            <h3>Modeling & Measures</h3>
            <ul>
              <li>Composite Priority Score = weighted sum(AQI severity, respiratory case load, income-adjusted demand potential, competitor penetration)</li>
              <li>Seasonal spike detection = month-over-month delta + thresholding to identify outbreak windows</li>
              <li>Pollutant-to-filter mapping (rule-based): PM → HEPA; VOC/SO₂ → Chemical scrubber/activated carbon</li>
            </ul>

            <h3>Visualization & Delivery</h3>
            <p class="overview">Deployed as an interactive Power BI report with tooltips, cross-filtering and drill-through. Included geo-bubble maps, time-series, radar plots, and tabular leaderboards for decision makers.</p>
          </div>

          <h2 class="section">Top Insights & Actionable Recommendations</h2>
          <div class="card">
            <ol style="margin:8px 0 0;padding-left:18px;color:#dbeaf0">
              <li><strong>Target mid-range purifier promotion</strong> in states with high AQI + moderate income. Promotions during pre-winter months increase conversion by targeting demand windows.</li>
              <li><strong>Filter inventory alignment:</strong> Stock HEPA + Activated Carbon combos for PM-dominant states; chemical scrubbers for industrial SO₂ hotspots.</li>
              <li><strong>Health advisory timing:</strong> Issue respiratory alerts at earliest signal of AQI month-over-month spike to mitigate disease burden.</li>
              <li><strong>Policy intervention:</strong> Prioritize emission controls in clusters (Uttar Pradesh, Delhi NCR, Bihar) identified via bubble mapping and critical days metric.</li>
            </ol>
          </div>
        </div>

        <aside>
          <div class="card">
            <h3 style="margin-top:0">Recruiter Highlights</h3>
            <ul style="color:#dbeaf0">
              <li>End-to-end ownership: data ingestion → model → dashboard deployment.</li>
              <li>Practical business outcomes: demand scoring and product recommendations for commercialization teams.</li>
              <li>Technical skills: Python (pandas), Power BI (DAX, visuals), geospatial mapping, stakeholder storytelling.</li>
              <li>Collaboration-ready artefacts: PBIX, cleaned CSVs and analysis notebook available.</li>
            </ul>

            <h3 style="margin-top:12px">Tech Stack</h3>
            <div style="display:flex;flex-direction:column;gap:6px">
              <div class="pill">Power BI</div>
              <div class="pill">Python (pandas, numpy)</div>
              <div class="pill">Dataful & Public Datasets</div>
              <div class="pill">Excel & Manual Market Research</div>
            </div>

            <h3 style="margin-top:12px">Files Included</h3>
            <ul style="color:#dbeaf0">
              <li>Interactive Power BI report (PBIX)</li>
              <li>ETL & preprocessing notebook (Python)</li>
              <li>Cleaned datasets & mapping tables</li>
              <li>Stakeholder-ready summary PPT (optional)</li>
            </ul>

          </div>
        </aside>
      </section>

      <section>
        <h2 class="section">Project Snippets & Reusable Code</h2>
        <div class="card">
          <p style="color:var(--muted)">Below is an example snippet used for seasonal spike detection in the preprocessing notebook.</p>
          <pre class="code"># pseudocode (Python)
# load df with columns: date, state, aqi
# resample monthly and compute month-over-month percent change

# df_month = df.set_index('date').groupby('state').resample('M').mean().reset_index()
# df_month['mom_pct'] = df_month.groupby('state')['aqi'].pct_change()*100
# df_month['spike_flag'] = df_month['mom_pct'] &gt;= 20  # threshold for alerts
          </pre>
        </div>
      </section>

    </main>

    <footer>
      <div>Prepared by — Data Analyst Portfolio • Includes visualization and decision insights ready for interviews</div>
    </footer>
  </div>
</body>
</html>

