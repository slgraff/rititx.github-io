<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Section</title>
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

<style>
  .about-section {
    text-align: center;
    padding: 50px 0;
  }
  .about-section h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  .about-section img {
    width: 200px; /* Adjust the size as needed */
    height: 200px;
    border-radius: 50%; /* Makes the image round */
    margin-bottom: 20px;
  }
  .about-section p {
    color: #333;
  }

  /* Additional CSS for Projects Section */
.projects-section h2 {
  margin-bottom: 40px;
  font-size: 2.5rem;
}
.card {
  box-shadow: 0 0 10px rgba(0,0,0,0.1); /* Adds a subtle shadow around the card */
}
.card-img-top {
  max-height: 180px; /* Adjust this value to fit the image properly in the card */
  object-fit: cover; /* This makes sure the image covers the area properly */
}
.card-body {
  padding: 15px;
}
.card-title {
  font-size: 1.25rem;
}
.card-text {
  margin-bottom: 15px;
}

/* Additional CSS for Skills Section */
.skills-section h2 {
  margin-bottom: 40px;
  font-size: 2.5rem;
}
.skills-section .card {
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}
.skills-section .card-img-top {
  padding: 20px; /* Add padding around your images if needed */
  background-color: #f8f9fa; /* Adjust the background color if your images have transparent areas */
  height: 180px; /* Fixed height for consistency */
  object-fit: contain; /* This will make sure the image is scaled properly within the container */
}
.skills-section .card-body {
  padding: 15px;
}
.skills-section .card-title {
  font-size: 1.25rem;
  margin-bottom: 15px;
}
.skills-section .btn-outline-primary {
  color: #007bff;
  border-color: #007bff;
}
.skills-section .btn-outline-primary:hover {
  color: #fff;
  background-color: #007bff;
  border-color: #007bff;
}

/* Additional CSS for Contact Section */
.contact-section {
  padding: 50px 0;
}
.contact-section h2 {
  font-size: 2.5rem;
  margin-bottom: 40px;
}
.contact-section p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}
.social-icon {
  width: 50px; /* Size of your icons */
  margin-bottom: 10px;
}
/* Hover effect for icons */
.social-icon:hover {
  opacity: 0.7;
}
/* Style for links in the Contact section */
.contact-section a {
  color: #fff;
  text-decoration: none; /* Removes underline from links */
  display: inline-block; /* Allows for margin on the bottom */
  margin-bottom: 10px;
}
.contact-section a:hover {
  color: #ddd; /* Color when hovering over the link */
}

/* CSS for Sticky Navbar */
.navbar {
  box-shadow: 0 2px 5px rgba(0,0,0,0.2); /* Adds a shadow for depth */
}

/* Ensure padding is added to body to avoid content being hidden behind the navbar */
body { 
  padding-top: 56px; /* Adjust this value based on the height of your navbar */
}

/* Smooth scroll */
html {
  scroll-behavior: smooth;
}

/* Style for navigation bar links */
.navbar-nav .nav-link {
  color: white;
}

.navbar-nav .nav-link:hover {
  color: #f8f9fa; /* Slightly lighter white when hovering over links */
}

/* Media query for responsive navbar collapsing */
@media (max-width: 992px) {
  .navbar-collapse {
    background-color: #343a40; /* Same as navbar color for seamless look */
  }
}


</style>

</head>
<body>

<section id='about' class="about-section">
  <div class="container">
    <h2>About</h2>
    <img src="images/about/1.jpg" alt="About Me">
    <p>​Ritika Bagga is a skilled and experienced Data Analyst with a proven track record of leveraging data to drive business growth and optimization.In her role as a self-employed Data Consultant, Ritika helps clients harness the power of data to improve their performance, optimize business processes, and achieve their strategic goals.

With a diverse background spanning data analysis, HR management, and business consulting, Ritika brings a unique and well-rounded perspective to her work.
Ritika's expertise extends beyond data analysis, as she is also adept in payroll management, compliance, and driving strategic HR initiatives. Her ability to translate complex data insights into actionable business strategies is a key strength that has made her a valuable asset to her clients.
In addition to her professional accomplishments, Ritika is an avid learner and educator. 

</p>
    <p>Ritika's passion for data and analytics is at the heart of her work, and she is dedicated to helping organizations transform their processes and achieve sustainable growth. With her analytical prowess, strategic mindset, and collaborative approach, Ritika is poised to make a significant impact on the organizations she serves.
</p>
  </div>
</section>


<!-- Projects Section -->
<section id="projects" class="projects-section bg-light" id="projects">
  <div class="container">
    <h2 class="text-center">Projects</h2>
    <div class="row">
      <!-- Project 1 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="images/projects/1.jpg" class="card-img-top" alt="Project 1">
          <div class="card-body">
            <h5 class="card-title">Project 1: Sales Data Analysis and Visualization</h5>
            <p class="card-text"> In this project, I analyzed a comprehensive sales dataset for an e-commerce company to uncover key insights and trends. Using Python libraries such as Pandas and NumPy for data cleaning and manipulation, I created interactive dashboards with Tableau to visualize sales performance, customer behavior, and product trends. The visualizations helped stakeholders identify high-performing products, optimize marketing strategies, and improve overall business performance.</p>
            <a href="#" class="btn btn-primary">Blog Post</a>
            <a href="#" class="btn btn-secondary">Source Code</a>
          </div>
        </div>
      </div>
      <!-- Project 2 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="images/projects/2.jpg" class="card-img-top" alt="Project 2">
          <div class="card-body">
            <h5 class="card-title">Project 2: Customer Segmentation Using K-Means Clustering</h5>
            <p class="card-text"> 

This project focused on segmenting customers into distinct groups based on their purchasing behavior using K-Means clustering. I utilized Python libraries such as Scikit-learn and Matplotlib to preprocess the data, perform clustering analysis, and visualize the results. The segmentation provided valuable insights into customer demographics and purchasing patterns, enabling the marketing team to tailor personalized campaigns and improve customer retention strategies.</p>
            <a href="#" class="btn btn-primary">Blog Post</a>
            <a href="#" class="btn btn-secondary">Source Code</a>
          </div>
        </div>
      </div>
      <!-- Project 3 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="images/projects/3.jpg" class="card-img-top" alt="Project 3">
          <div class="card-body">
            <h5 class="card-title">Project 3: Financial Time Series Forecasting</h5>
            <p class="card-text">In this project, I developed a financial forecasting model to predict stock prices using historical data. Leveraging the yfinance library, I collected and analyzed stock data for SPY. I applied time series analysis techniques and used Facebook's Prophet library for forecasting. The model's performance was evaluated through cross-validation and visualized using Plotly. This project provided actionable insights for investment decisions and risk management.

These projects demonstrate my ability to analyze complex datasets, derive meaningful insights, and create visualizations that support data-driven decision-making.</p>
            <a href="#" class="btn btn-primary">Blog Post</a>
            <a href="#" class="btn btn-secondary">Source Code</a>
          </div>
        </div>
      </div>
    </div>

  </div>
</section>


<!-- Skills Section -->
<section id="skills" class="skills-section bg-white" id="skills">
  <div class="container">
    <h2 class="text-center">Skills</h2>
    <div class="row">
      <!-- Skill 1 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card">
          <img src="images/skills/1.png" class="card-img-top" alt="Python">
          <div class="card-body">
            <h5 class="card-title">Python</h5>
            <p class="card-text">Ritika Bagga is a highly skilled Python programmer with a robust set of capabilities tailored for data analysis. Her proficiency in Python is demonstrated through various projects and applications, highlighting her technical prowess and analytical acumen.

Data Manipulation: Ritika is adept at using libraries such as Pandas and NumPy for data manipulation and analysis. She efficiently handles large datasets, performing operations like filtering, grouping, and aggregating data to extract meaningful insights.

Data Cleaning: She possesses strong skills in data cleaning, ensuring that datasets are free from inconsistencies, missing values, and errors. Ritika uses techniques to preprocess data, making it suitable for analysis and modeling.

Data Visualization: Ritika excels in data visualization, utilizing libraries like Matplotlib, Seaborn, and Plotly to create informative and visually appealing charts and graphs. Her visualizations help in understanding complex data patterns and communicating insights effectively.

Web Scraping: She is proficient in web scraping using libraries such as BeautifulSoup and Scrapy. Ritika can extract data from websites, preprocess it, and integrate it into her analysis, demonstrating her ability to gather and utilize external data sources.

Project Management: Her Python skills extend to managing data analysis projects from start to finish. Ritika ensures proper documentation, version control using Git, and collaborative development practices.

Ritika Bagga's Python expertise is a cornerstone of her data analysis skill set, enabling her to tackle complex data challenges and deliver insightful, data-driven solutions.</p>
            <a href="#" class="btn btn-outline-primary">Link to course or bootcamp</a>
          </div>
        </div>
      </div>
      <!-- Skill 2 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card">
          <img src="images/skills/2.png" class="card-img-top" alt="Data Visualization">
          <div class="card-body">
            <h5 class="card-title">Data Visualization</h5>
            <p class="card-text">Ritika Bagga is a proficient data visualization specialist with a strong skill set that encompasses various aspects of the field. Here are some key points about her skills:

Data Interpretation: Ritika excels at interpreting complex data sets and transforming them into clear, insightful visualizations that tell a story. Her ability to identify key trends and patterns is a significant asset.

Interactive Dashboards: She is skilled in creating interactive dashboards that allow users to explore data dynamically. These dashboards are often equipped with filters, drill-down capabilities, and other interactive elements to enhance user engagement.

Data Cleaning and Preparation: Ritika has a strong background in data cleaning and preparation, ensuring that the data used in visualizations is accurate and reliable. She is proficient in using tools like SQL, Python, and Excel for data manipulation.

Communication: Her communication skills are excellent, enabling her to convey complex data insights to both technical and non-technical stakeholders effectively.

Project Management: Ritika has experience managing data visualization projects from conception to completion, including requirement gathering, design, implementation, and iteration based on feedback.

Overall, Ritika Bagga's combination of technical proficiency, design sensibility, and analytical acumen makes her a valuable asset in the field of data visualization.</p>
            <a href="#" class="btn btn-outline-primary">Link to course or bootcamp</a>
          </div>
        </div>
      </div>
      <!-- Skill 3 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card">
          <img src="images/skills/3.png" class="card-img-top" alt="SQL">
          <div class="card-body">
            <h5 class="card-title">SQL</h5>
            <p class="card-text">
Ritika Bagga's proficiency in SQL is evident in her project portfolio, showcasing a comprehensive skill set that highlights her ability to manage and manipulate data efficiently. Here are her SQL skills:

Database Design and Management: Ritika has experience in designing, creating, and managing relational databases. She is proficient in defining schemas, establishing relationships, and ensuring data integrity through normalization and the use of constraints.

Complex Queries: She excels at writing complex SQL queries to retrieve and manipulate data. Her skills include the use of subqueries, joins (INNER, LEFT, RIGHT, FULL), and set operations (UNION, INTERSECT, EXCEPT) to perform advanced data retrieval tasks.

Data Manipulation: Ritika is adept at using Data Manipulation Language (DML) commands such as SELECT, INSERT, UPDATE, and DELETE. She ensures efficient data operations while maintaining data integrity and consistency.

Data Analysis: Ritika uses SQL for data analysis tasks, including aggregations, window functions (like RANK, ROW_NUMBER, and PARTITION BY), and complex calculations to derive meaningful insights from data.

By highlighting these skills on her project portfolio website, Ritika Bagga effectively demonstrates her comprehensive expertise in SQL, showcasing her ability to handle a wide range of database-related tasks with proficiency and precision.</p>
            <a href="#" class="btn btn-outline-primary">Link to course or bootcamp</a>
          </div>
        </div>
      </div>
      <!-- Skill 4 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card">
          <img src="images/skills/4.png" class="card-img-top" alt="Data Storytelling">
          <div class="card-body">
            <h5 class="card-title">Data Storytelling</h5>
            <p class="card-text">Ritika Bagga excels in data storytelling, a critical component of her data analysis expertise. Her ability to convey data-driven insights in a compelling and understandable manner is showcased through the following skills:

Narrative Construction: Ritika masterfully constructs narratives that transform complex data sets into engaging stories. She identifies the key message and tailors her narrative to highlight the most significant findings, making the data relatable and impactful.

Visualization Techniques: Ritika uses effective visualization techniques to support her narratives. She selects the most appropriate charts, graphs, and visuals that best represent the data, ensuring clarity and enhancing the story's impact.

Context and Insights: She provides context to the data, explaining the background, methodology, and significance of the findings. Ritika's insights go beyond mere data presentation, offering interpretations and implications that guide decision-making.

Emotional Engagement: Ritika employs storytelling techniques that evoke emotions, making her data presentations more memorable and persuasive. She uses real-world examples, anecdotes, and scenarios that resonate with her audience.

Clear Communication: Her ability to communicate complex data insights clearly and concisely is a hallmark of her storytelling. Ritika uses simple language, avoids jargon, and explains technical terms when necessary, ensuring her message is understood by all.

Interactivity: Ritika often incorporates interactive elements into her data stories, such as interactive dashboards and visualizations, allowing her audience to explore the data further and engage with the story on a deeper level.

By showcasing these data storytelling skills on her project portfolio website, Ritika Bagga demonstrates her ability to not only analyze data but also to craft compelling stories that drive understanding and action.</p>
            <a href="#" class="btn btn-outline-primary">Link to course or bootcamp</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Me Section -->
<section id="contact" class="contact-section text-center text-white bg-dark">
  <div class="container">
    <h2>Contact Me</h2>
    <div class="row">
      <div class="col-lg-6">
        <p><i class="fas fa-envelope"></i> ritika1@yahoo.com</p>
      </div>
      <div class="col-lg-6">
        <p><i class="fas fa-phone"></i> 214-864-3320</p>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-2 col-md-4 mb-4">
        <a href="https://linkedin.com/in/yourusername" target="_blank">
          <img src="icons/linkedin.png" alt="LinkedIn" class="social-icon">
          LinkedIn
        </a>
      </div>
      <div class="col-lg-2 col-md-4 mb-4">
        <a href="https://twitter.com/yourusername" target="_blank">
          <img src="icons/twitter.png" alt="Twitter" class="social-icon">
          Twitter
        </a>
      </div>
      <div class="col-lg-2 col-md-4 mb-4">
        <a href="https://github.com/yourusername" target="_blank">
          <img src="icons/github.png" alt="GitHub" class="social-icon">
          GitHub
        </a>
      </div>
      <div class="col-lg-2 col-md-4 mb-4">
        <a href="https://medium.com/@yourusername" target="_blank">
          <img src="icons/medium.png" alt="Medium" class="social-icon">
          Medium
        </a>
      </div>
      <div class="col-lg-2 col-md-4 mb-4">
        <a href="https://youtube.com/c/yourchannel" target="_blank">
          <img src="icons/youtube.png" alt="YouTube" class="social-icon">
          YouTube
        </a>
      </div>
    </div>
  </div>
</section>

<!-- Sticky Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#home">Portfolio</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#skills">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>


<!-- Bootstrap JS and dependencies (jQuery and Popper) -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.9.5/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
