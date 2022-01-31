# Read if you're interested
<h1>To do:</h1>
<ul>
  <li>Home page.</li>
  <li>Blog page (CMS required).</li>
  <li>About page.</li>
  <li>Contact page.</li>
  <li>(Experimental)Track me page (page that tracks my stats on other platforms - THM, HTB, etc).</li>
</ul>

<h1>Frameworks and Services to be used:</h1>
<b>Frontend</b>
<ul>
  <li>React JS.</li>
</ul>

<b>Backend</b>
<ul>
  <li>ASP.NET Core.</li>
  <li>Specific framework in mind to serve as my CMS - https://github.com/piranhacms/piranha.core</li>
  <li>Server logging - https://github.com/serilog/serilog</li>
</ul>

<b>Hosting Provider</b>
<ul>
  <li>Azure Web App Service</li>
</ul>

<b>Site Backup Plan</b>
<ul>
  <li>Source code will be backed up to GitHub (free).</li>
  <li>Future wise > will experiment with Azure Backup Service.</li>
</ul>

<b>Web Traffic Management</b>
<ul>
  <li>Technically included as part of the Azure Web Service, using Azure will provide the ability to scale up/out as required.</li>
</ul>

<h1>Things the Backend will need to achieve:</h1>
<ol>
  <li>Send emails on the Contacts page.</li>
  <li>Be able to create new posts in the Blogs page. Includes the ability to edit and delete if required.</li>
  <li>Will need an Admin only login page to perform step 2.</li>
</ol>

<h2>Thought process for each page</h2>
<p><b>Home page</b> will be a simple page with static images and HTML stuff. Nothing too fancy. Maybe implement some overly complicated JavaScript animation here.</p>
<p><b>Blog page</b> will definitely take the most time with implementing correctly and securely. Have to learn the Piranha .Net Core framework here. Then build my project from scratch.</p>
<p><b>About page</b> will be identical to the Home page with regards to the frontend stuff. Nothing fancy here.</p>
<p><b>Contact page</b> will be almost identical as the Home page, except it will provide the option to download my professional work thingy-ma-jiggies.</p>
<p><b>Track me page</b> will be the second area which will take a lot of time for me. Will have to look for available APIs (if supported) to get my user profile activity event numbers. Otherwise, will have to use some Web Scraping method, process the data into a live graph, then display it to the page. Ultimate goal is to function as a dashboard except it will be accessible to any viewer.</p>

<h2>Branches that will be used:</h2>
<ul>
  <li>Production (main) >>> only tested and working commits are found here.</li>
  <li>Staging (testing) >>> only milestone related activity should be found here.</li>
  <li>Development (experimental) >>> most of the work is carried out here.</li>
</ul>

<h3>Post-deployment Tasks (once the site has been created, tested, and launched into production):</h3>
<ul>
  <li>Create a cost management plan (i.e./ monitor how much the site is costing me to run. Don't want to break da bank after all).</li>
  <li>Pentest my site just for giggles.</li>
  <li>Setup the link on Social Media. Fugg yeah</li>
</ul>
