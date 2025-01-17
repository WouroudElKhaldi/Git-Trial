<style>
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
}

.container {
    display: flex ;
    max-width: 800px;
    margin: 20px;
    padding: 20px;
    background-color: #f5f5f5;
    box-shadow: 0 2px 10px rgba(166, 0, 255);
    border-radius: 10px;
    color : #333 ;
}

.profile-column {
    flex: 1;
    padding-right :  20px;
}

.content-column {
    flex : 2;
    background-color: #fff;
    box-shadow : 0 2px 10px rgba(166, 0, 255);
    border-radius : 10px;
    padding : 20px;
}


h1:hover {
    box-shadow: 0 0 10px rgba(166, 0, 255);
    transform : scale(1.05) ;
    transition: transform 0.2s ease-in-out;
    background : linear-gradient(to top, #a600ff, gray ) ;
    border-radius : 30% ;
    background-clip: text ;
    color: #fff;
}
h1 {
    font-size: 2.5rem ;
    text-align: center ;
    margin: 10px;
    padding: 10px;
}

h1, h2 {
    color: #a600ff;
    text-align: center;
}

img.profile-photo {
    display: block;
    margin: auto;
    border-radius: 50%;
    box-shadow: 0 0 10px rgba(166, 0, 255);
    transition: transform 0.3s ease-in-out;
}

img.profile-photo:hover {
    transform: scale(1.1);
}

h2.section-heading {
    margin-top: 30px;
    border-bottom: 2px solid #a600ff;
    padding-bottom: 5px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    margin-bottom: 10px;
}

.certificate-box {
    background-color: #f8f9fa;
    border: 1px solid #ccc;
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 5px;
    transition: transform 0.3s ease-in-out;
}

.certificate-box:hover {
    transform: scale(1.02);
    box-shadow: 0 0 10px rgba(166, 0, 255);
}

.contact-info {
    background-color: #a600ff;
    color: #fff;
    padding: 20px;
    border-radius: 5px;
    margin-top: 20px;
    margin-left: auto; 
    margin-right: auto;
    text-align: center; 
}

.language {
    display: inline-block;
    background-color: #f5f5f5;
    color: #333;
    padding: 5px 10px;
    margin-right: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.language:hover{
    box-shadow: 0 0 10px rgba(166, 0, 255);
    transform: scale(1.05);
    transition: transform 0.3s ease-in-out;
}

.section-heading {
    color: #a600ff;
    margin-top: 30px;
    border-bottom: 2px solid #a600ff;
    padding-bottom: 5px 0;
    background-color: #f5f5f5; 
}

.skills-list {
    display: flex;
    flex-wrap: wrap;
    margin-top: 10px;
}

.skill-badge {
    display: inline-block;
    background-color: #a600ff;
    color: #fff;
    padding: 5px 10px;
    margin: 7px;
    border-radius: 5px;
}
.skill-badge:hover {
    transform: scale(1.05);
    transition: transform 0.3s ease-in-out;
    box-shadow: 0 0 10px rgba(71, 71, 71)
}


.language-list {
    margin-top: 10px;
}

.cf-link:hover {
    color: #a600ff; 
}

.cf-link:active {
    color: #00cc00 ;
}

</style>
<body class="cv">
<div class="container">
  <div class="profile-column">
    <h1>Wouroud El Khaldi</h1>
    <h2>CV</h2>
    <img src="wourou.jpg" alt="Profile Photo" width="180" height="180" class="profile-photo"> 
    <div class="contact-info">
        <h2 style="color:black ; margin: 15px;">Personal Info</h2>
        <p><b>Name:</b> Wouroud Mahmoud El Khaldi</p>
        <p><b>Nationality:</b> Lebanese</p>
        <p><b>Date of Birth:</b> 1/12/2004</p>
        <p><b>Phone Number:</b> +96181877217</p>
        <p><b>Email:</b><a href="mailto:wouroudelkhaldi@gmail.com"  style="color:#e3cfdb">wouroudelkhaldi@gmail.com</a></p>
        <p><b>Location:</b> North Lebanon / Akkar / Bebnine</p>
    </div>
  </div>
  <div class="content-column">
    <h2 class="section-heading">Education</h2>
    <ul>
        <li><strong>2019</strong>: Brevet At - Dr. Yaacoub El Sarraf Official School</li>
        <li><strong>2022</strong>: SV/LS (Third Secondary Year) At - Miniara Official High School</li>
        <li><strong>2023</strong>: TS1 Informatics Management At - Al Saade Technical Institute</li>
    </ul>
    <h2 class="section-heading">Certificates</h2>
    <div class="certificate-box">
    <p><strong>META FRONT-END DEVELOPER PROFESSIONAL CERTIFICATE</strong></p>
    <ul>
        <li><strong>26/02/2023</strong>: Introduction to Front-End Development by <strong>Meta</strong> at <em>Coursera</em> <a href="https://coursera.org/verify/LAPUX5ZRNDGH" class="cf-link" >Verify here</a> </li>
        <li><strong>01/04/2023</strong>: Programming with JavaScript by <strong>Meta</strong> at <em>Coursera</em> <a href="https://coursera.org/verify/2524VWZNLZAC" class="cf-link">Verify here</a></li>
        <li><strong>08/04/2023</strong>: Version control by <strong>Meta</strong> at <em>Coursera</em> <a href="https://coursera.org/verify/ZTKX5WN9RQDK" class="cf-link">Verify here</a></li>
        <li><strong>/04/2023</strong>: HTML and CSS in depth by <strong>Meta</strong> at <em>Coursera</em> <a href="https://coursera.org/verify/EZJ58WJAMN83" class="cf-link">Verify here</a></li>
        <li><strong>23/06/2023</strong>: React Basic by <strong>Meta</strong> at <em>Coursera</em> <a href="https://coursera.org/verify/YDBDGHVNE5XY" class="cf-link">Verify here</a></li>
    </ul>
    </div>
    <h2 class="section-heading">Languages</h2>
    <ul class="language-list">
        <li class="language">Native Arabic</li>
        <li class="language">English: reading, writing, and speaking</li>
        <li class="language">French: reading, writing, and speaking</li>
    </ul>
    <h2 class="section-heading">Skills and Acknowledgments</h2>
    <div class="skills-list">
        <span class="skill-badge">Front-End web developer (and Designer)</span>
        <span class="skill-badge">Interacting with Microsoft apps (Word / Excel / PowerPoint / Access)</span>
        <span class="skill-badge">Interacting with IDEs (Visual Studio, Visual Studio Code, Pycharm)</span>
        <span class="skill-badge">Well-experienced in using computers</span>
        <span class="skill-badge">Basic knowledge of Algorithm, Data Structure, Computer Architecture, Database, and problem solving</span>
        <span class="skill-badge">Basic programming in JS language</span>
        <span class="skill-badge">Strong knowledge of Object-Oriented Programming (OOP) & Functional Programming (FP)</span>
        <span class="skill-badge">Strong knowledge of Version Control, especially using Git/GitHub</span>
        <span class="skill-badge">Proficient in Unix and Windows commands</span>
        <span class="skill-badge">Advanced HTML & CSS</span>
        <span class="skill-badge">Basic use of REACT library</span>
        <span class="skill-badge">Basic use of Bootstrap framework</span>
        <span class="skill-badge">UI/UX design</span>
    </div>
 
</div>
</body>