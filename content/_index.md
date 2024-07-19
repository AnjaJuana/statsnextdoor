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
            <p><b>I am not accepting clients at this moment. Furthermore, the email address listed on this site is currently inactive and not monitored.</b></p>
            <p>At Statistician Next Door, I offer professional statistical consulting services to a variety of clients. My goal is to collaborate with each client to identify their specific needs and provide tailored services in an accessible way. Whether you are a company, a researcher, or a student, I can help you with your data analysis needs. My services include:</p>
            <ul>
                <li><b>Companies:</b> I can help you understand your current performance, predict your future outcomes, and support your decision making by using advanced statistical techniques and data visualization tools.</li>
                <li><b>Researchers:</b> I can help you define a clear and feasible research question, choose the appropriate statistical methods, and perform the data analysis. I can also help you interpret the results, report the findings, and communicate the implications of your research.</li>
                <li><b>Students:</b> I can tutor you in the programming language R and explain concepts and applications of statistics through online tutoring. I will not provide solutions for graded assignments.</li>
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
#      button:
#        text: Download CV
#        url: uploads/resume.pdf
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
            <p><b>I am not accepting clients at this moment. Furthermore, the email address listed on this site is currently inactive and not monitored.</b></p>
            <p>To request my service, please email me a summary of your project or problem at 
                <a href="mailto:yourname@yourdomain.com"> 
                    <img src="/images/email_adress.png " alt="Email us at yourname@yourdomain.com" class="inline-image"> 
                </a>. The more details you provide, the more precise my pricing estimate will be. 
            </p>
            <p>Do not send any data by email!</p>
            <p>Please mention if there is a specific deadline you are working towards. </p>
            <p>Within a few business days, you will receive a tailored offer with a price and timeline indication.</p>
            <p> Once you give the green light, we can move forward with our collaboration.</p>
        </div>
    design:
      background:
        color: '#F7F7F7'

#    design:
      columns: '1'
---
