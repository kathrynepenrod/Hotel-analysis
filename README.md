<div align="center">
  <img width="200" height="200" alt="Hotel Analytics Logo" src="https://github.com/user-attachments/assets/fed75f82-aa6b-46d2-a7b0-bf46e0277566" />
  <h1>Hotel Operations: Exploratory Data Analysis</h1>
  <p><em>An exploratory data analysis (EDA) project examining hotel operational metrics to uncover actionable insights regarding guest demands, parking space optimization, and revenue trends.</em></p>
</div>

<hr>

<h2>Project Overview</h2>
<p>Understanding guest behavior and operational overhead is critical for hospitality management. This project dives into hotel booking and operational datasets to evaluate key performance indicators (KPIs), resource allocation, and financial trends.</p>

<h3>Key Areas of Investigation:</h3>
<ul>
  <li><strong>Infrastructure & Capacity:</strong> Analyzing parking lot space requirements relative to seasonal booking volumes and vehicle space demands.</li>
  <li><strong>Revenue Dynamics:</strong> Investigating Average Daily Rate (ADR) trends, revenue fluctuations, and pricing correlations.</li>
  <li><strong>Operational Trends:</strong> Uncovering behavioral patterns in cancellations, lead times, and special requests to improve forecasting accuracy.</li>
</ul>

<hr>

<h2>Tech Stack</h2>
<ul>
  <li><strong>Language:</strong> Python</li>
  <li><strong>Libraries:</strong> 
    <ul>
      <li><code>pandas</code>, <code>numpy</code> (Data cleaning & manipulation)</li>
      <li><code>matplotlib</code>, <code>seaborn</code> (Data visualization & exploratory plotting)</li>
      <li><code>scipy</code> (Statistical analysis)</li>
    </ul>
  </li>
</ul>

<hr>

<h2>Key Findings and Conclusions</h2>

<h3>Guest Trends and Behavioral Patterns</h3>
<ul>
  <li><strong>Geographic Differences:</strong> Travelers from different regions exhibit distinct booking patterns. For instance, visitors from Poland tend to be more family-oriented, while Portugal leads in both previous cancellations and successfully completed bookings.</li>
  <li><strong>Guest Categories:</strong> Corporate travelers frequently submit special requests but rarely travel with children. Conversely, groups typically book well in advance and experience multiple booking modifications.</li>
  <li><strong>Cancellation Drivers:</strong> Non-refundable bookings unexpectedly correlate with higher cancellation rates. Overall cancellation and no-show risks increase when lead times are long, guests have a history of prior cancellations, or daily rates are high. No-shows frequently involve families with children and babies, likely driven by unforeseen travel disruptions.</li>
</ul>

<h3>Parking Lot Capacity Recommendations</h3>
<ul>
  <li><strong>Capacity Benchmarks:</strong> Because exact lot dimensions vary, evaluation requires counting available spaces against the following operational thresholds:
    <ul>
      <li><strong>50 or more spaces:</strong> Current capacity is sufficient.</li>
      <li><strong>35 to 50 spaces:</strong> Expansion is recommended but not immediately critical.</li>
      <li><strong>Fewer than 35 spaces:</strong> Expansion is necessary.</li>
    </ul>
  </li>
  <li><strong>Application:</strong> These thresholds apply across both regular operations and corporate events, assuming event guests are logged into the system.</li>
</ul>

<h3>Revenue and ADR Dynamics</h3>
<ul>
  <li><strong>Completed vs. Cancelled Stays:</strong> Comparing the ADR of completed versus cancelled stays differentiates secured revenue from potential revenue lost while helping to calculate retained cancellation fees.</li>
  <li><strong>Deposit Impact:</strong> Analyzing cancelled bookings shows that non-refundable deposits retain a portion of revenue upon cancellation, whereas refundable and no-deposit bookings isolate true financial loss.</li>
</ul>

<hr>

<h2>Repository Structure</h2>
<pre><code>
├── data/                  # Raw and cleaned datasets (excluded from version control)
├── notebooks/             # Jupyter notebooks for exploratory data analysis
├── visualizations/        # Exported charts and summary plots
└── README.md              # Project documentation
</code></pre>

<hr>
