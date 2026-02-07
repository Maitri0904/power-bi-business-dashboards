<h1>🏏 T20 Cricket Data Analysis Project</h1>

<p>
This project focuses on analyzing <b>T20 Cricket player performance</b> using real match data.  
The goal is to use <b>data analytics and visualization</b> to select an ideal playing XI based purely on performance metrics rather than popularity.
</p>

<hr>

<h2>📸 Dashboard Preview</h2>

<p>
Below is the interactive Power BI dashboard developed as part of this project:
</p>

<img src="Screenshot 2026-02-07 182137.png" alt="T20 Player Analysis Dashboard" width="100%">

<hr>

<h2>📌 Project Workflow</h2>

<ol>
  <li><b>Data Source</b> – Raw match data collected in <b>JSON format</b> from <b>CricSheet</b>.</li>
  <li><b>Data Processing</b> – JSON files converted and cleaned using <b>Python</b>.</li>
  <li><b>Data Transformation</b> – Clean datasets exported as <b>CSV files</b>.</li>
  <li><b>Visualization</b> – Interactive dashboards created in <b>Power BI</b>.</li>
  <li><b>Final Goal</b> – Build a <b>data-driven T20 team selection system</b>.</li>
</ol>

<hr>

<h2>🙏 Data Source Acknowledgement</h2>

<p>
Cricket match data used in this project was sourced from <b>CricSheet</b>, an open data initiative providing detailed ball-by-ball cricket datasets for research and analytics purposes.  
This project uses the data strictly for <b>educational and analytical use</b>.
</p>

<hr>

<h2>🛠️ Tools & Technologies Used</h2>

<ul>
  <li>🐍 Python (Pandas, JSON handling, Data Cleaning)</li>
  <li>📊 Power BI (Data Visualization & Dashboard Design)</li>
  <li>📁 CSV (Processed Data Storage)</li>
  <li>🌐 JSON (Raw Cricket Match Data)</li>
</ul>

<hr>

<h2>📊 Key Performance Metrics Used</h2>

<h3>🏏 Batting Metrics</h3>
<ul>
  <li><b>Batting Average</b> – Consistency of a player</li>
  <li><b>Strike Rate</b> – Scoring speed (runs per 100 balls)</li>
  <li><b>Boundary %</b> – Percentage of runs scored via 4s and 6s</li>
  <li><b>Average Balls Faced</b> – Stability at crease</li>
</ul>

<h3>🎯 Bowling Metrics</h3>
<ul>
  <li><b>Economy Rate</b> – Runs conceded per over</li>
  <li><b>Bowling Strike Rate</b> – Balls taken per wicket</li>
  <li><b>Bowling Average</b> – Runs given per wicket</li>
  <li><b>Dot Ball %</b> – Pressure-building deliveries</li>
</ul>

<hr>

<h2>👥 Player Role Classification</h2>

<ul>
  <li><b>Power Hitters / Openers</b> – Fast scoring batsmen at the top</li>
  <li><b>Anchors</b> – Stable middle-order batsmen</li>
  <li><b>Finishers</b> – Aggressive lower-order batsmen</li>
  <li><b>All-Rounders</b> – Players contributing in both batting & bowling</li>
  <li><b>Specialist Fast Bowlers</b> – Wicket-taking pace bowlers</li>
</ul>

<hr>

<h2>📈 Dashboard Highlights</h2>

<ul>
  <li>Player comparison based on <b>Strike Rate vs Batting Average</b></li>
  <li>Bowler analysis using <b>Economy vs Bowling Strike Rate</b></li>
  <li>Role-wise performance breakdown</li>
  <li>Trend analysis across matches</li>
  <li>Interactive filters for role, stage, and match type</li>
</ul>

<hr>

<h2>🔍 Key Insights from Analysis</h2>

<ul>
  <li>⚡ Power hitters with <b>Strike Rate above 140</b> contribute most to quick starts.</li>
  <li>🧱 Anchors maintain innings stability with <b>higher batting averages</b>.</li>
  <li>🔥 Finishers show <b>highest boundary percentage</b> in death overs.</li>
  <li>🎯 All-rounders provide balance by maintaining <b>economy below 8</b> while scoring at 130+ strike rate.</li>
  <li>🚫 Bowlers with <b>high dot ball percentage</b> create pressure leading to wickets.</li>
</ul>

<hr>

<h2>🏆 Final Outcome</h2>

<p>
The project successfully demonstrates how <b>data analytics can be used for sports decision-making</b>.  
Instead of selecting players based on reputation, this model selects a <b>balanced T20 team using performance statistics</b>.
</p>

<hr>

<h2>📂 Project Structure</h2>

<pre>
/data
   ├── raw_json_files
   ├── cleaned_csv_files

/python_scripts
   ├── json_to_csv.py
   ├── data_cleaning.py

/powerbi_dashboard
   ├── T20_Player_Analysis.pbix
</pre>

<hr>

<h2>🚀 Future Improvements</h2>

<ul>
  <li>Integrate live match data APIs</li>
  <li>Add predictive modeling for player performance</li>
  <li>Build a web app for automated team selection</li>
</ul>

<hr>

<h2>🙌 Author</h2>

<p>
Created with passion for <b>Cricket Analytics & Data Science</b> ❤️  
</p>
