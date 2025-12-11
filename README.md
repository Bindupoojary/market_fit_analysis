<div class="container">
  <header>
    <div class="logo"><h1>AQ</h1></div>
    <div class="title">
      <h1 class="project">Air Quality, Health Impact & Market Demand Analysis</h1>
      <p class="lead">Integrated Power BI analysis connecting environmental, public health, and market signals.</p>
    </div>
  </header>

  <section class="overview">
    <h2>Project Summary</h2>
    <p>This dashboard provides a unified analytical system combining AQI severity trends, respiratory disease incidence, pollutant dominance, and market intelligence for air purifier demand across India.</p>
  </section>

  <section class="insights">
    <h2>Key Insights</h2>
    <ul>
      <li>Identified high-priority states using a composite risk and demand score.</li>
      <li>Mapped pollutant dominance and recommended filter technologies per region.</li>
      <li>Benchmarked air purifier competitors by features, pricing, and coverage.</li>
      <li>Detected seasonal respiratory outbreaks correlated with AQI spikes.</li>
    </ul>
  </section>

  <section class="gallery">
    <h2>Dashboard Preview</h2>
    <p>View the live interactive dashboard here:<br>
      <a href="https://app.powerbi.com/view?r=eyJrIjoiZjIzY2Y2YjUtODRlYS00OWEyLWE1YmQtYTNiYmQyOGQzYTJmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" target="_blank" style="color:#14b8a6;font-weight:600;">🔗 Live Power BI Dashboard</a>
    </p>

    <div class="images">
      <img src="/mnt/data/8c5ad604-1fbc-4488-8139-d6b5b1497c71.png" alt="AQI Dashboard – Overview 1" />
      <img src="/mnt/data/505e6cc5-16ce-4190-a408-0ac072f8a47f.png" alt="AQI Dashboard – Overview 2" />
      <img src="/mnt/data/0e528358-518b-41a3-a825-b6806f647d37.png" alt="AQI Dashboard – Trends" />
      <img src="/mnt/data/7b204dd3-2254-4b32-8cc0-de93ac13ec3a.png" alt="AQI Dashboard – Trends 2" />
      <img src="/mnt/data/1a837dee-7aa0-4a70-9c09-eb882d959049.png" alt="Respiratory Health – Disease Cases" />
      <img src="/mnt/data/8e840021-b442-46de-af06-9f6ec275da1f.png" alt="Respiratory Health – Trend" />
      <img src="/mnt/data/fd1fc076-e3b8-462b-9f96-eb399d16f2c7.png" alt="Market Demand – Priority Scoring" />
      <img src="/mnt/data/849683e3-14b3-4a4d-915d-10ca38033c15.png" alt="Market Demand – Competitor Pricing" />
      <img src="/mnt/data/042c3108-7335-4a7d-a0d1-031f0182ed9c.png" alt="Market Demand – Filter Recommendations" />
    </div>
  </section>

  <section class="analysis">
    <h2>Analytical Approach</h2>
    <h3>Data Preparation</h3>
    <p>Cleaned AQI, pollutant composition, EV metrics, income datasets, and health data using Python (pandas). Normalized time-series and handled missing values using seasonal interpolation.</p>

    <h3>Modeling</h3>
    <ul>
      <li>Priority Scoring Model combining AQI, disease cases, income, and demand triggers.</li>
      <li>Seasonal spike detection using MoM % change thresholds.</li>
      <li>Pollutant-to-filter mapping model based on pollutant dominance.</li>
    </ul>
  </section>

  <section class="recommendations">
    <h2>Recommendations</h2>
    <ol>
      <li>Target mid‑range purifiers in states with severe AQI but sufficient income capacity.</li>
      <li>Use HEPA + Activated Carbon filters in PM-dominant states; chemical scrubbers in SO₂-heavy regions.</li>
      <li>Roll out seasonal health advisories aligned with pollution-driven disease cycles.</li>
      <li>Focus policy interventions on top high-risk clusters like Delhi NCR and Uttar Pradesh.</li>
    </ol>
  </section>

  <section class="views">
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
    <p>This view equips policymakers and environmental agencies with the data to pinpoint pollution hotspots, assess long-term severity, and plan state-level mitigation strategies.</p>

    <h3>2. Health Impact & Respiratory Disease View</h3>
    <p>This module overlays air quality indicators with health outcomes to understand how environmental degradation influences public health. Key insights include:</p>
    <ul>
      <li><strong>Disease case trends</strong> by month showing seasonal outbreak patterns aligned with pollution peaks.</li>
      <li><strong>Disease-wise breakdown</strong> including influenza, H1N1, Nipah, and upper respiratory infections.</li>
      <li><strong>State-wise respiratory disease distribution</strong> identifying medically vulnerable zones.</li>
      <li><strong>AQI vs respiratory case correlation table</strong> quantifying exposure–impact relationships.</li>
      <li><strong>Total deaths vs reported cases</strong> offering severity understanding for healthcare planning.</li>
    </ul>
    <p>The health view demonstrates clear evidence that states with persistent high AQI—such as Delhi, Haryana, and Bihar—also exhibit elevated respiratory disease burdens. This strengthens the case for targeted health advisories, medical resource allocation, and stricter pollution control measures.</p>

    <h3>3. Executive Market Demand & Opportunity View</h3>
    <p>This view is tailored for business, product, and strategy teams to evaluate the commercial landscape for air purifiers. It consolidates:</p>
    <ul>
      <li><strong>Priority score by state</strong> combining AQI severity, income, disease load, and market triggers.</li>
      <li><strong>Competitive analysis</strong> of major purifier brands on pricing, CADR, feature stack, and coverage range.</li>
      <li><strong>Feature gap scoring</strong> to identify strengths and weaknesses of competitors.</li>
      <li><strong>State-wise pollutant mapping</strong> and <strong>recommended filter types</strong> based on pollutant dominance.</li>
      <li><strong>Income vs AQI scatter correlation</strong> to identify high-demand/high-affordability consumer segments.</li>
    </ul>
    <p>This enables companies to identify regions with the highest sales potential, choose the right product tier for each state, and craft marketing campaigns aligned with seasonal pollution spikes.</p>

    <h2>Overall Project Outcomes</h2>
    <ul>
      <li><strong>Holistic Risk Identification:</strong> Integrated AQI–health–economic signals revealed 8–12 states requiring urgent policy and business attention.</li>
      <li><strong>Actionable Market Intelligence:</strong> Mid-range air purifiers emerged as optimal for most Indian states due to price–feature balance.</li>
      <li><strong>Filter Technology Mapping:</strong> Provided pollutant-specific filter recommendations enabling companies to localize product variants.</li>
      <li><strong>Seasonal Intervention Strategy:</strong> Identified winter and early monsoon as the most critical windows for both health advisories and purifier sales surges.</li>
      <li><strong>High-Value Decision Framework:</strong> Produced a multi-layer system usable by government bodies, healthcare organizations, and consumer brands.</li>
    </ul>
  </section>

</div>
