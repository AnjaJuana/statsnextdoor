---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
    
sections:
  - block: markdown
    content:
      title: 'Statistician Next Door' 
      subtitle: 'Statistical Consulting'
      text: |-
        <div class="md_style">
            <p>At Statistician Next Door, I offer professional statistical consulting services to a variety of clients. My goal is to collaborate with each client to identify their specific needs and provide tailored services. Whether you are a company, a researcher, or another professional, I can help by advising you on your statistical needs and/or performing the data analysis for you. My services include:</p>
            <ul>
                <li><b>Companies:</b> Through data analysis, I can help you understand your current performance, predict future outcomes, and support your decision-making using advanced statistical techniques and data visualization tools.</li>
                <li><b>Researchers:</b> I can assist in defining a clear and feasible research question, selecting appropriate statistical methods, and performing the data analysis. Additionally, I can help you interpret the results, report the findings, and communicate the implications of your research.</li>
                <li><b>Custom Services:</b> Please contact me with your statistical problem, and I might just be able to help you.</li>
            </ul>
            <p>I am using the R programming language for all statistical analysis and can advise you on your own analysis in R as well.</p>
            <p>Contact me today and let me help you with your data analysis needs.</p>
        </div>
    design:
      background:
        color: white
        

  - block: resume-biography-3 
    id: aboutme
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      background:
        color: '#F7F7F7'
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Anja_CV.pdf
#    design:
#      css_class: dark
#      background:
#        color: black
#        image:
#          # Add your image background to `assets/media/`.
#          filename: stacked-peaks.svg
##          filters:
#            brightness: 1.0
#          size: cover
#          position: center
#          parallax: false
          
  - block: markdown
    id: prices
    content:
      title: 'Prices'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>Rates depend on the type of work and the size of the project. After receiving the details of your project, I will send an offer and a timeline within a couple of business days. 
            </p>
        </div>
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>To request my service, please email me a summary of your project or problem at info "at" statisticiannextdoor.com. In particular, please include the following information: 
            </p>
            <ul>
                <li>Brief summary of project</li>
                <li>Project goal: what do you expect as outcome of this project?</li>
                <li>Type of analysis if already known</li>
                <li>Timeline: is there a specific deadline you are working towards?</li>
                <li>Budget for the project</li>
            </ul>
            <p><b>Do not send any data by email!</b></p>
            <p>Within a few business days, you will receive a tailored offer with a price and timeline indication.</p>
            <p> Once you give the green light, we can move forward with our collaboration.</p>
        </div>
    design:
      background:
        color: '#F7F7F7'
  - block: markdown
    content:
      title: ''
      subtitle: 'Statistical Consulting'
      text: |-
        <div>
          <!-- Centering the toggle button -->
          <div style="text-align: center;">  <!-- Centering div -->
            <button id="toggle-button" onclick="toggleImpressum()" style="background:none;border:none;color:black;text-decoration:none;cursor:pointer;">
              Show Impressum
            </button>
          </div>         
          <!-- Hidden Impressum content -->
          <div id="impressum-content" style="display:none; font-size: 0.8em;">
            <ul style="list-style-type: none; padding: 0; margin: 0;">
                <li><b>Name:</b> Dr. Anja Juana Rüten-Budde</li>
                <li><b>Address:</b> Roseggerstraße 23, 8700 Leoben, Austria</li>
                <li><b>Email:</b> info "at" statisticiannextdoor.com</li>
            </ul>
            <p>Einzelunternehmer gemäß § 6 Abs. 1 Z 27 UStG (Kleinunternehmerregelung)</p>
          </div>
        </div>
        <!-- JavaScript function for toggle -->
        <script>
          function toggleImpressum() {
            var content = document.getElementById("impressum-content");
            var button = document.getElementById("toggle-button");
            if (content.style.display === "none") {
              content.style.display = "block";
              button.textContent = "Hide Impressum";  // Change to "Hide"
            } else {
              content.style.display = "none";
              button.textContent = "Show Impressum";  // Change to "Show"
            }
          }
        </script>
        

#    design:
      columns: '1'
---

<!-- email as picture:  <img src="/images/email_white.png" class="inline-image" style="width: 38%; height: auto; display: inline-block; vertical-align: middle; margin: 0; padding: 0;"> -->

