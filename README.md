<html lang="en">
  <body>
  <h1 style="font-stretch: expanded; color:white; font-weight:bold;" class="title">Module 24 Challenge - Project 4</h1>
  <img src="./banner.jpg" alt="lesson banner" tabindex="0" aria-label="lesson banner. Click to Enlarge." data-canonical-src="./banner.jpg" style="max-width: 100%;">
  <a href="http://www.freepik.com">image designed by upklyak / Freepik</a>
  <br>
  <br>
    <ul>
      <h2>Project 4 Overview</h2>
      <li> <strong>Find a problem worth solving, analyzing, or visualizing.</strong></li>
      <li> <strong>Use machine learning (ML)</strong></li>
      <li><strong>Use Scikit-learn and/or another machine learning library.</li>
      <li><strong>Must be powered by a dataset with at least 100 records</li>
      <li><strong>must use at least two of the following:</li>
      <ul>
          <li>Python Pandas</li>
          <li>Python Matplotlib</li>
          <li>HTML/CSS/Bootstrap</li>
          <li>JavaScript Plotly</li>
          <li>JavaScript Leaflet</li>
          <li>SQL Database</li>
          <li>MongoDB Database</li>
          <li>Google Cloud SQL</li>
          <li>Amazon AWS</li>
          <li>Tableau</li>
        </ul>
    </ul>
    <h2>Group Work</h2>
      <ul>
          <li>Project ideation</li>
          <li>Data fetching/API integration</li>
          <li>Data analysis</li>
          <li>Building the ML model</li>
          <li>Testing</li>
          <li>Creating documentation</li>
          <li>Creating the presentation</li>
      </ul>
    <h2>Project Description</h2>
      <p>We obtained the data from the County Health Rankings & Roadmaps (CHR&R), a program of the University of Wisconsin Population Health Institute.</p>  
      <p>We downloaded years 2013 through 2023. The data was cleaned and prepared using excel first and then with Pandas</p>
      <p> </p>
      <h3>Teen Birth Rate</h3>
      <p>In the "The Teen Birth Rate Predictions" notebook we converted all to a dataframe with Pandas, merged all dataframes, removed NaNs.</p>
      <p>We kept the columns 'FIPS', 'county', 'state', "Teen Birth Rate" per each year. FIPS stands for "Federal Information Processing Standard."</p> 
      <p>Using supervised machine learning with a linear regression model we attempted to predict the of Teen Birth Rate for the years 2025, 2026, and 2027.</p> 
      <p>This information would be helpful to identify counties and states where the need to educate and help prevent Teen pregnancy.</p>
      <p>Reading the .xlsx files and converting them to a dataframe took shy of 2 minutes so we implemented storing the data into a database.</p>
      <p>The process reading the converting the files to a dataframe shrunk to less than 3 seconds. </p>
      <p>The R-squared resulted in 0.9593332454137964 which is very accurate</p>
      <p> </p>
    <h3>Children in Poverty Rate</h3>
      <p>From the same dataset we also used the children in poverty rate from the years 2013 through 2023 and used the linear regression model to predict the years 2025 - 2027.</p>
      <p>The results were also very good with r-squared value of 0.9296094430298143</p>
      <p>Both, the teen birth rate, and the children in poverty numbers have been declining since 2013 which is positive, however there some states that are somewhat behind.</p>
    <h3>Visualizations</h3>
      <p>Using Tableau we created visualizations to help analyze the data.</p>
      <p>A link to a presentation explaining the ETL performed and the rest of the process is available in this repository as well.</p>
      <p>The visualizations link are contained in the presentation.</p>
      <p>Python, Tableau and Excel were used to complete the project and the Python library used can be found in the presentation. </p>
      <p> </p>
      <h3>Links</h3>
      <p>https://public.tableau.com/app/profile/spencer.duke/viz/Project4Map_16911688241540/Dashboard1</p>
      <p> </p>
      <p>https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation</p>
      <p> </p>
      <p>https://public.tableau.com/views/Project4_16914646659640/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link</p>
      <p> </p>
   <h2> <strong>Group members:</strong></h2>
      <ul>
        <li>David Calero</li>
        <li>Joshua Mayo</li>
        <li>Gustavo Bustillos</li>
        <li>Sperncer Duke</li>
    </ul>
  </body>
</html>