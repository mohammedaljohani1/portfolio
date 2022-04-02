# Home
# About
# Skills
# Contacts

<section id="about"></section>
<style>
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




```markdown
Syntax highlighted code block

# Home
## About
### contact

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mohammedaljohani1/portfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
