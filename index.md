# Home
# About
# Skills
# Contacts

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
    <style>
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
        
    </style>
    </secction>    
 
<section id="about"></section>
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

</style>
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





