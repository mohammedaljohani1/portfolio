<html lang="en">
<head>
<style>
    .header {
  line-height: 80px;
  width: 100%;
  transition: line-height 0.2s linear, box-shadow 0.2s linear;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 100;
  background: rgba(245, 245, 245, 0.97);
}

.header.small {
  line-height: 50px;
  box-shadow: 0px 1px 3px 0px rgba(50, 50, 50, 0.8);
}

.header.small > .container > #logo {
  height: 40px;
}

#logo {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: red;
  float: left;
  height: 40px;
  width: 170px;
  margin-left: 5px;
}

ul.nav {
  float: right;
  list-style: none;
  margin: 0;
  padding: 0;
}

ul.nav li {
  float: left;
  position: relative;
}

ul.nav li a {
  transition: color 0.2s linear;
  font-size: 18px;
}

ul.nav li:hover a {
  color: red;
}

ul.nav li a {
  padding: 21px;
  color: initial;
  text-decoration: initial;
}
    .accordion {
        cursor: pointer;
        padding: 18px;
        width: 100%;
        border: 1px solid #000;
        border-bottom: none;
        text-align: left;
        outline: none;
        font-size: 15px;
        transition: 0.4s;
        max-width: 500px;
    }
    .accordion:last-child{
        border-bottom: 1px solid #000;
    }
    .accordion-header {
        display: flex;
        padding: 16px;
        cursor: pointer;
        
    }
    .accordion-icon {
        width: 16px;
        color: #C00;
    }
    .accordion-title {
        flex: 1;
    }
    .accordion-content {
        padding: 16px;
    }
    .accordion-content {
        display: none;
    }
    .active, .accordion:hover {
        background-color: #ccc;
    }
/* Style the counter */
        .view-btn {
          display: flex;
          justify-content: center;
          align-items: center;
          flex-direction: column;
        }
        /* Styles for website counter container */
        .view-btn {
          background-color: #1267e7;
          height: 50px;
          width: 180px;
          font-weight: 900;
          font-size: 27px;
          margin-top: 10px;
          color: white;
          border-radius: 10px;
          box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
        }
/* skills section styling */


.skills .skills-content .left .text{
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
}
.skills .skills-content .left p{
    text-align: justify;
}
.skills .skills-content .left a{
    display: inline-block;
    background: crimson;
    color: #fff;
    font-size: 18px;
    font-weight: 500;
    padding: 8px 16px;
    margin-top: 20px;
    border-radius: 6px;
    border: 2px solid crimson;
    transition: all 0.3s ease;
}
.skills .skills-content .left a:hover{
    color: crimson;
    background: none;
}
.skills .skills-content .right .bars{
    margin-bottom: 15px;
}
.skills .skills-content .right .info{
    display: flex;
    margin-bottom: 5px;
    align-items: center;
    justify-content: space-between;
}
.skills .skills-content .right span{
    font-weight: 500;
    font-size: 18px;
}
.skills .skills-content .right .line{
    height: 5px;
    width: 100%;
    background: lightgrey;
    position: relative;
}
.skills .skills-content .right .line::before{
    content: "";
    position: absolute;
    height: 100%;
    left: 0;
    top: 0;
    background: crimson;
}
.skills-content .right .html::before{
    width: 100%;
}
.skills-content .right .css::before{
    width: 80%;
}
.skills-content .right .py::before{
    width: 70%;
}
.skills-content .right .cc::before{
    width: 50%;
}
.skills-content .right .opensource::before{
    width: 75%;
}
.skills-content .right .adpi::before{
    width: 80%;
}
.skills-content .right .ai::before{
    width: 25%;
}
.skills-content .right .bld::before{
    width: 50%;
}

/* contact section styling */
.contact .title::after{
    content: "get in touch with him";
}
.contact .contact-content .column{
    width: calc(50% - 30px);
}
.contact .contact-content .text{
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
}
.contact .contact-content .left p{
    text-align: justify;
}
.contact .contact-content .left .icons{
    margin: 10px 0;
}
.contact .contact-content .row{
    display: flex;
    height: 65px;
    align-items: center;
}
.contact .contact-content .row .info{
    margin-left: 30px;
}
.contact .contact-content .row i{
    font-size: 25px;
    color: crimson;
}
.contact .contact-content .info .head{
    font-weight: 500;
}
.contact .contact-content .info .sub-title{
    color: #333;
}
.contact .right form .fields{
    display: flex;
}
.contact .right form .field,
.contact .right form .fields .field{
    height: 45px;
    width: 100%;
    margin-bottom: 15px;
}
.contact .right form .textarea{
    height: 80px;
    width: 100%;
}
.contact .right form .name{
    margin-right: 10px;
}
.contact .right form .email{
    margin-left: 10px;  
}
.contact .right form .field input,
.contact .right form .textarea textarea{
    height: 100%;
    width: 100%;
    border: 1px solid lightgrey;
    border-radius: 6px;
    outline: none;
    padding: 0 15px;
    font-size: 17px;
    font-family: 'Poppins', sans-serif;
    transition: all 0.3s ease;
}
.contact .right form .field input:focus,
.contact .right form .textarea textarea:focus{
    border-color: #b3b3b3;
}
.contact .right form .textarea textarea{
    padding-top: 10px;
    resize: none;
}
.contact .right form .button{
    height: 47px;
    width: 170px;
}
.contact .right form .button button{
    width: 100%;
    height: 100%;
    border: 2px solid crimson;
    background: crimson;
    color: #fff;
    outline: none;
    font-size: 20px;
    font-weight: 500;
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.3s ease;
}
.contact .right form .button button:hover{
    color: crimson;
    background: none;
}


</style>
</head>
<body>
	<nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#" class="hire about-img" style="padding: 20px; border-radius: 10px;">Mohammmed <span>Alijohani</span></a></div>
            <ul class="menu about-img" style="padding: 20px; border-radius: 10px;">
                <li><a href="#home" class="menu-btn hire">Home</a></li>
		    <li><a href="#about" class="menu-btn hire">About</a></li>
                <li><a href="#skills" class="menu-btn hire">Skills</a></li>
                <li><a href="#work-experience" class="menu-btn hire">Work Experience</a></li>
		 <li><a href="#education" class="menu-btn hire">Education</a></li>
                <li><a href="#contact" class="menu-btn hire">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>
	<section id="blank"></section>
	<section id=counter>
    <div>Portfolio Views:</div>
    <div class="view-btn"></div>
    <script>
      var counterContainer = document.querySelector(".view-btn");
      var viewCount = localStorage.getItem("portfolio_view");

      // Check if portfolio view exists in local storage
      if (viewCount) {
        viewCount = Number(viewCount) + 1;
        localStorage.setItem("portfolio_view", viewCount);
      } else {
        viewCount = 1;
        localStorage.setItem("portfolio_view", 1);
      }
      counterContainer.innerHTML = "Views: " + viewCount;
    </script>
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About Me</h2>
            <div class="about-content">
                <div class="column right about-img" style="padding: 20px; border-radius: 10px;">
                    <div class="text">He is a Passionate <span class="typing-2"></span></div>
                    <p>A self-taught programmer who is a Passionate contributor to communities, Open Source & Hackathons, Pursuing Knowledge to excel in future endeavors and helping people enhance their learnings by providing them with practical experience and Knowledge. He is currently the 162nd event ambassador at deeplearning.ai in the world and also a Mozilla Fest Facilitator. He is a founder, Organiser, and Speaker at Programmers Universal Group . He is an official volunteer at Google Developer Group Chandigarh, Progate, and Tensorflow User group Chandigarh. He is professionally a programmer, front-end Web developer, and an Artist. He is also a Youtuber where shares his knowledge with everyone. He is also an open-source contributor and Google Crowdsource Top contributor. He has also done many contributions to various communities. He was also selected as a share captain at Google Educator Group Ahmedabad and Pune. He was also in the list of top 10 Campus Ambassador at Developer Student Clubs Week of Wonders ( a week long national event )</p>
                    <a href="#" class="about-img">Download Resume</a>
                </div>
            </div>
        </div>
    </section>
	<!-- skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My creative skills & experiences.</div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, ratione error est recusandae consequatur, iusto illum deleniti quidem impedit, quos quaerat quis minima sequi. Cupiditate recusandae laudantium esse, harum animi aspernatur quisquam et delectus ipsum quam alias quaerat? Quasi hic quidem illum. Ad delectus natus aut hic explicabo minus quod.</p>
                    <a href="#" class="about-img">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>100%</span>
                        </div>
                        <div class="line html"></div>
			<div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>80%</span>
                        </div>
                        <div class="line css"></div>
		        <div class="bars">
                        <div class="info">
                            <span>Python</span>
                            <span>70%</span>
                        </div>
                        <div class="line py"></div>
			<div class="bars">
                        <div class="info">
                            <span>Git & Github</span>
                            <span>75%</span>
                        </div>
                        <div class="line opensource"></div>
		        <div class="bars">
                        <div class="info">
                            <span>BootStrap</span>
                            <span>100%</span>
                        </div>
                        <div class="line html"></div>
			<div class="bars">
                        <div class="info">
                            <span>Tailwind CSS</span>
                            <span>100%</span>
                        </div>
                        <div class="line html"></div>
			<div class="bars">
                        <div class="info">
                            <span>Adobe Photoshop & Illustrator</span>
                            <span>80%</span>
                        </div>
                        <div class="line adpi"></div>
			<div class="bars">
                        <div class="info">
                            <span>Cloud Computing</span>
                            <span>50%</span>
                        </div>
                        <div class="line cc"></div>
			<div class="bars">
                        <div class="info">
                            <span>Artificial Intelligence</span>
                            <span>25%</span>
                        </div>
                        <div class="line ai"></div>
			<div class="bars">
                        <div class="info">
                            <span>Blender</span>
                            <span>50%</span>
                        </div>
                        <div class="line bld"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
<!-- Work experience section start -->
<section id="work-experience">
  <h2>Work History</h2>
  <div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>09/2020 - 09/2022, IT Engineer, BENN Technologies, Inc., Los Angeles, CA, United States</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        <ol>
            <li>Resolved any virus and malware issues and managed Windows and Linux servers.</li>
            <li>Developed and maintained a Windows and Linux server for the company.</li>
            <li>Maintained various hardware and software and worked on the improvement of data security.</li>
            <li>Configured VPN, backed up and restored data, and managed relevant correspondence.</li>
            <li>Reduced unnecessary IT department expenses by 10%.</li>
            <li>Won the Employee of the Month Award twice for meeting all assigned goals and targets.</li>
        </ol>
    </div>
  </div>
  <div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>19/2018 - 09/20219 SECURITY PROFESSIONALS INC.Columbia, SC</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        <ol>
            <li>
                Refined and improved existing documentation system, resulting in reduced labor costs totaling $15,000 annually via increased workplace efficiency
            </li>
            <li>
                Consolidated multiple ticketing systems, improving communication and ticket turnover rate by 7%
            </li>
            <li>
                Investigated alerts created by IDS/IPS including malicious file uploads, compromised servers, SQL injections, and port scanning
            </li>
        </ol>
    </div>
  </div>
</section>
<!-- Education section start -->
<section id="education">
  <h2>Education</h2>
  <div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>09/2013 - 05/2017, Computer Science, Massachusetts Institute of Technology, Cambridge, MA, United States</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        <ol>
            <li>GPA: 3.96 (Top 3% of the Program)</li>
            <li>Clubs and Societies: Engineering Society, Math Society, TEDx Club</li>
        </ol>
    </div>
  </div>
  <div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>09/2009 - 05/2013, High School, European School Copenhagen, Copenhagen, Denmark</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
       <ol>
           <li>Graduated with Distinction (Grade 1 - A/excellent equivalent in all subjects)</li>
           <li>Extracurricular Activities: Computer Club, Engineering Society, Tennis Club</li>
       </ol>
    </div>
  </div>
</section>
<!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get in Touch</div>
                    <p></p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Mohammed Aljohan1</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">Newyork, USA</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">mohammedalojhan@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form action="https://formspree.io/f/mqkgooqj" method="POST">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" placeholder="Name" name="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" placeholder="Email" name="email_id" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" placeholder="Subject" name="subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="50" rows="20" placeholder="Message..." name="message" required></textarea>
                        </div>
                        <div class="button">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>
<script>
  const accordionHeader = document.getElementsByClassName('accordion-header');
  const accordionContent = document.getElementsByClassName('accordion-content');
  const accordionIcon = document.getElementsByClassName('accordion-icon');
for (let i = 0; i < accordionHeader.length; i++) {
  accordionHeader[i].addEventListener('click', function() {
    accordionContent[i].style.display = accordionContent[i].style.display =='block' ? 'none' : 'block';
    accordionIcon[i].innerHTML = accordionContent[i].style.display =='block' ? '-' : '+';  
  });
}

</script>
    
</body>
</html>
 
    

  



   
   




