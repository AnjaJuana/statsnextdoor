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
            <p>Bij Statistician Next Door bied ik professionele statistische adviesdiensten aan een breed scala aan klanten. Mijn doel is om met elke klant samen te werken om hun specifieke problemen te identificeren en op maat gemaakte diensten te leveren. Of u nu een bedrijf, onderzoeker, of student bent, ik kan u helpen door advies te geven over uw statistische vraagstukken en/of de data-analyse voor u uit te voeren. Mijn diensten omvatten:</p>
            <ul>
                <li><b>Bedrijven:</b> Met behulp van data-analyse kan ik u helpen uw huidige prestaties te begrijpen, toekomstige uitkomsten te voorspellen en uw besluitvorming te ondersteunen met geavanceerde statistische technieken en datavisualisatietools.</li>
                <li><b>Onderzoekers:</b> Ik kan helpen bij het formuleren van een duidelijke en haalbare onderzoeksvraag, het selecteren van geschikte statistische methoden en het uitvoeren van data-analyse. Daarnaast kan ik u ondersteunen bij het interpreteren van de resultaten, het rapporteren van bevindingen en het communiceren van de implicaties van uw onderzoek.</li>
                <li><b>Studenten:</b> Ik kan u begeleiden in de programmeertaal R en concepten en toepassingen van statistiek uitleggen via online begeleiding. Ik lever echter geen oplossingen voor beoordeelde opdrachten.</li>
                <li><b>Aangepaste diensten:</b> Neem contact met mij op met uw statistisch probleem, en misschien kan ik u helpen.</li>
            </ul>
            <p>Ik gebruik de programmeertaal R voor alle statistische analyses en kan u ook adviseren over uw eigen analyses in R.</p>
            <p>Neem vandaag nog contact met mij op, en laat mij u helpen met uw data-analysevraagstukken.</p>
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
  
  
  - block: collection
    id: projects
    content:
      title: Featured projects
      subtitle: ''
      text: 'Advanced statistical models in medicine'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - project
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card

  
  
  - block: markdown
    id: prices
    content:
      title: 'Prijzen'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>De tarieven zijn afhankelijk van het soort werk en de omvang van het project. Na ontvangst van de details van uw project stuur ik binnen enkele werkdagen een offerte en een tijdlijn.</p>
        </div>
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <div class="md_style">
            <p>Om gebruik te maken van mijn diensten, stuurt u een samenvatting van uw project of probleem per e-mail op info "at" statisticiannextdoor.com. Vermeld hierbij in het bijzonder de volgende informatie: </p>
            <ul>
                <li>Korte samenvatting van het project</li>
                <li>Projectdoel: wat verwacht u als uitkomst van dit project?</li>
                <li>Type analyse, indien al bekend</li>
                <li>Tijdlijn: is er een specifieke deadline waar u naartoe werkt?</li>
            </ul>
            <p><b>Stuur geen data via e-mail!</b></p>
            <p>Binnen een paar werkdagen ontvangt u een op maat gemaakt voorstel met een prijs- en tijdsindicatie.</p>
            <p>Zodra u akkoord geeft, kunnen we onze samenwerking starten.</p>
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
              Toon Impressum
            </button>
          </div>         
          <!-- Hidden Impressum content -->
          <div id="impressum-content" style="display:none; font-size: 0.8em;">
            <ul style="list-style-type: none; padding: 0; margin: 0;">
                <li><b>Naam:</b> Dr. Anja Juana Rüten-Budde</li>
                <li><b>Adres:</b> Roseggerstraße 23, 8700 Leoben, Oostenrijk</li>
                <li><b>E-mail:</b> info "at" statisticiannextdoor.com</li>
            </ul>
            <p>Eenmanszaak volgens § 6 lid 1 Z 27 UStG (Kleinondernemersregeling)</p>
          </div>
        </div>
        <!-- JavaScript function for toggle -->
        <script>
          function toggleImpressum() {
            var content = document.getElementById("impressum-content");
            var button = document.getElementById("toggle-button");
            if (content.style.display === "none") {
              content.style.display = "block";
              button.textContent = "Verberg Impressum";  // Change to "Hide"
            } else {
              content.style.display = "none";
              button.textContent = "Toon Impressum";  // Change to "Show"
            }
          }
        </script>
        

#    design:
      columns: '1'
---

<!-- email as picture:  <img src="/images/email_white.png" class="inline-image" style="width: 38%; height: auto; display: inline-block; vertical-align: middle; margin: 0; padding: 0;"> -->

