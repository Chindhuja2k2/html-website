# html-website
<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
body {
  font-family: Ariel, Helvetica, sans-serif;
  margin: 0;
}
.header {
  padding: 80px;
  text-align: center;
  background: pink;
  color: black;
}
.header h1 {
  font-size: 40px;
}
.navbar {
  overflow: hidden;
  background-color: #333;
  position: sticky;
  position: sticky;
  top: 0;
}
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
.navbar a.right {
  float: right;
}
.navbar a:hover{
  background-color:pink;
  color: blue;
}
.navbar a.active {
  background-color: #111;
  color: white;
}
.row {  
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.side {
  -ms-flex: 30%;
  flex: 30%;
  background-color: pink;
  padding: 20px;
}
.main {  
  -ms-flex: 70%;
  flex: 70%;
  background-color: pink;
  padding: 20px;
}
.img {
  background-color: pink;
  width: 100%;
  padding: 20px;
}
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}
@media screen and (max-width: 700px) {
  .row {  
    flex-direction: column;
  }
  @media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}
input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}
input[type=submit]:hover {
  background-color: #45a049;
}
.container {
  border-radius: 5px;
  background-color: white;
  padding: 10px;
}
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
    }
    }
   html {
  box-sizing: border-box;
}
 {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.about-section {
  padding: 50px;
  text-align: left;
  background-color: #474e5d;
  color: white;
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
 
</style>
</head>
<body>

<div class="header">
  <h1>"Set Your Businesss Up With Modern Pay Roll,Benifits And HR"</h1>
  <p><b><mark> TRY FOR FREE NOW !  >>></mark></b></p>
</div>

<div class="navbar">
  <a href="#" class="active">HOME</a>
  <a href="#">PAYROLL</a>
  <a href="#">BENEFITS</a>
  <a href="#">PRICING</a>
  <a href="#">JOIN US</a>
  <a href="#" class="right"><MARK>SIGN IN>></MARK></a>
</div>

<div class="row">
  <div class="side">
    <h3><center>"'OUR PLANS WHERE FIT TO BUILT YOUR UNIQUE NEEDS.STREAMLINE ONBOARDING,BENFITS,PAYROLL,PTOAND MORE WITH OUR SIMPE INITIATIVE PLATFORMS"'</center></h3>
    <center><h3>*free 14 days demo</h3>
    <h3>*no credit cards</h3>
    <h3>*no setups</h3></center>
    <center><img src="tripupp1.jpg"></center>
    <p><center>@ your email address<MARK>GET STARTED</MARK></center></p>
    <h2> HR manage your people with ease</h2>

<div class="container">
  <div style="text-align:center">
    <h2>ADD A CANDIDATE</h2>
    <p>A COMPLETE HR PLATFORM SAVES UR TIME</p>
  </div>
 <center><div class="row">
    <div class="column">
      <img src="tripupp2.jpg">
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="name"> Name</label>
        <input type="text" id="name" name="name" placeholder="Your name..">
        <label for=" job title">JOB TITLE</label>
        <input type="text" id=" job title" name="job title" placeholder="Your job title..">
        <label for="department">DEPARTMENT</label>
        <input type="text" id="department" name="department" placeholder="Your depatment..">
        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="australia">Australia</option>
          <option value="canada">Canada</option>
          <option value="usa">USA</option>
          <option value="india">INDIA</option>
          <option value="japan">JAPAN</option>
          <option value="german">GERMAN</option>
          <option value="france">FRANCE</option>
          <option value="italy">ITALY</option>
          <option value="swedon">SWEDON</option>
          <option value="china">CHINA</option>
          <option value="uk">UK</option>
          <option value="srilanka">SRILANKA</option>
        </select>
        <label for="subject">ABOUT YOU</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</div></center>
<div class="about-section">
  <h2>PAY ROLL-payroll thats easy to use and seriously smart</h2>
  <center><img src="F:\DOLAR.jpg">
  <p>unlimited pay roles,clear pricing,no surprices</p>
  <img src="F:\ribbon_logo.jpg">
  <p>automatically filesnyour pay roll taxes</p>
  <img src="F:\mail_logo.jpg">
  <p>everything you need,syncd with pay roll</p>
  <img src="F:\calender_logo.jpg">
  <p>compliance,accuracy and peaceof mind</p>
</div>
<div class="main">
    <h2>BENEFITS finally,employee benefits for every business</h2>
    <CENTER><h3>'Tripupp streamlines your workflow by automatically connecting HR,Benefits,payrolls and scheduling ,together in one platform.this means less time spent on low priority tasks so your team can focus on moe important things' </h3>
    <img src="F:\heart_logo.jpg">
    <p>our benefits are designd to be accesible for all</p>
    <img src="F:\gloves_logo.jpg">
    <p>A healthy team canbetter support your business and your bottimline</p>
    <img src="F:\firstaid_logo.jpg">
    <p>Become a business where talented people want to work and stick around </p>
    <br>
    <h2>Why Us?</h2></center>
    <h3>HIGH AND RETAIN TOP TALENT</h3>
    <h5>we make onboarding new employees ridiculously easy.on dayone,they are ready to go.And retaining them is easier too,with advanced HR tools like compensation reporting</h5>
    <br>
    <h3>STAY COMPLAINT</h3>
    <h5>keping a businesss complaint is made easier with zenefits.we automate manyof the compliance tasks and government filings for you</h5>
    <br>
    <h3>IMPROVE PRODUCTIVITY</h3>
    <h5>many of our features like self onboarding,selecting benfits and signing documents happen completely online,which means your employees will spend more times focused on their core functins</h5>
    <br>
    <h3>IMPROVE EMPLOYEE EXPERIENCE</h3>
    <h5> we improve your employees overall experience.from a mobile app that streamlines onboarding and requesting time off,to a modern experience that lets employees signfor benefits online</h5>
  <br><center><h3>we are here to help.Ask us anything orschedule a demo call</h3>
 <h2><MARK>TALK TO ADVISOR<MARK></h2><center>
 </div>
<div class="footer">
  <h2>Get your team</h2>
  <h2>Working with</h2
  <h2> Us!</h2>
  <h1><MARK>Get STARTED</MARK></h1>
</div>
<h2 style="text-align:center">founde"scorner</h2>
<center><div class="row">
  <div class="column">
    <div class="card">
      <img src="ceo.jpg" alt="ceo" style="width:100%">
      <div class="container">
        <h2>Kumar Amrendra </h2>
        <p> CEO & Founder</p>
        <p>Experienced Sales professional with a demonstrated history of working in the information technology and services industry. Skilled in Sales, Management, Pre-sales, Business Development, and Telecommunications. Strong sales professional with a PGDBM (MBA) focused in Marketing/Marketing Management, General from IIMT, Greater Noida.</p>
        <p>kumar@tripupp.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div></center>
</body>
</html>
