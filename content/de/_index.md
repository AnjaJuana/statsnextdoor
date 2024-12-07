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
            <p>Bei Statistician Next Door biete ich professionelle statistische Beratungsdienste für eine Vielzahl von Kunden an. Mein Ziel ist es, gemeinsam mit jedem Kunden seine spezifischen Bedürfnisse zu identifizieren und maßgeschneiderte Dienstleistungen anzubieten. Ob Sie ein Unternehmen, Forscher, oder Student sind, ich kann Ihnen helfen, indem ich Sie zu Ihren statistischen Anforderungen berate und/oder die Datenanalyse für Sie durchführe. Meine Dienstleistungen umfassen:</p>
            <ul>
                <li><b>Unternehmen:</b> Durch Datenanalysen helfe ich Ihnen, Ihre aktuelle Leistung zu verstehen, zukünftige Ergebnisse vorherzusagen und fundierte Entscheidungen mit fortschrittlichen statistischen Techniken und Datenvisualisierungs-Tools zu unterstützen.</li> 
                <li><b>Forscher:</b> Ich unterstütze Sie bei der Formulierung einer klaren und umsetzbaren Forschungsfrage, der Auswahl geeigneter statistischer Methoden und der Durchführung der Datenanalyse. Zusätzlich helfe ich Ihnen, die Ergebnisse zu interpretieren, die Befunde zu berichten und die Implikationen Ihrer Forschung zu kommunizieren.</li> 
                <li><b>Studierende:</b> Ich biete Nachhilfe im Programmieren mit der Programmiersprache R sowie Erklärungen zu Konzepten und Anwendungen der Statistik im Rahmen von Online-Tutoring an. Ich erstelle keine Lösungen für benotete Aufgaben.</li> 
                <li><b>Individuelle Dienstleistungen:</b> Kontaktieren Sie mich mit Ihrem statistischen Problem, und möglicherweise kann ich Ihnen helfen.</li>
            </ul>
            <p>Ich verwende die Programmiersprache R für alle statistischen Analysen und kann Sie auch bei Ihrer eigenen Analyse in R beraten.</p> 
            <p>Kontaktieren Sie mich noch heute, und lassen Sie mich Ihnen bei Ihren Datenanalyse-Anforderungen helfen.</p>
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
      # button:
      #  text: Download CV
      #  url: uploads/Anja_CV.pdf
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
      title: 'Preise'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>Die Preise hängen von der Art der Arbeit und dem Umfang des Projekts ab. Nachdem ich die Details Ihres Projekts erhalten habe, werde ich Ihnen innerhalb weniger Werktage ein Angebot und einen Zeitplan zusenden. 
            </p>
        </div>
  - block: markdown
    id: contact
    content:
      title: 'Kontakt'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>Um meine Dienstleistungen anzufordern, senden Sie bitte eine E-Mail mit einer Zusammenfassung Ihres Projekts oder Problems an info "at" statisticiannextdoor.com. Bitte fügen Sie insbesondere die folgenden Informationen bei: 
            </p>
            <ul>
                <li>Kurzbeschreibung des Projekts</li> 
                <li>Ziel des Projekts: Was erwarten Sie als Ergebnis dieses Projekts?</li> 
                <li>Art der Analyse, falls bereits bekannt</li> 
                <li>Zeitrahmen: Gibt es eine spezifische Frist, auf die Sie hinarbeiten?</li> 
            </ul>
            <p><b>Senden Sie keine Daten per E-Mail!</b></p> 
            <p>Innerhalb weniger Werktage erhalten Sie ein maßgeschneidertes Angebot mit einer Preis- und Zeitangabe.</p> 
            <p>Sobald Sie grünes Licht geben, können wir mit der Zusammenarbeit beginnen.</p>
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
              Impressum anzeigen
            </button>
          </div>         
          <!-- Hidden Impressum content -->
          <div id="impressum-content" style="display:none; font-size: 0.8em;">
            <ul style="list-style-type: none; padding: 0; margin: 0;">
                <li><b>Name:</b> Dr. Anja Juana Rüten-Budde</li>
                <li><b>Adresse:</b> Roseggerstraße 23, 8700 Leoben, Österreich</li>
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
              button.textContent = "Impressum verbergen";  // Change to "Hide"
            } else {
              content.style.display = "none";
              button.textContent = "Impressum anzeigen";  // Change to "Show"
            }
          }
        </script>
        

#    design:
      columns: '1'
---

<!-- email as picture:  <img src="/images/email_white.png" class="inline-image" style="width: 38%; height: auto; display: inline-block; vertical-align: middle; margin: 0; padding: 0;"> -->

