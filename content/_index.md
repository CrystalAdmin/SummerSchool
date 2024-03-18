---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: MIDSEA Summer School 2024
      text: 🧱 Infectious Disease Modelling  🧱
      primary_action:
        text: Registration 
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Programme Schedule
        url: https://docs.hugoblox.com
      announcement:
        text: "MIDSEA Summer School 2024 Registration"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "200+"
          description: |
            Subscribers on  
            Mailing List
        - statistic: "9"
          description: |
            Online Seminars 
            since 2022
        - statistic: "2"
          description: |
            International Workshop  
            Organized
    
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Summer School Programme
          text: De La Salle Manila, Mahasarakham University, Mahidol Oxford Research Unit, National University of Singapore, Oxford University Clinical Research Unit and University of Phillippines are in the initial stages of planning a Summer School scheduled to take place from 19 to 29 June 2024 in Vietnam. 
          feature_icon: check
          features:
            - "Parallel Tracks of Different Topics for maximum exposure"
            - "Full-Board Accommodations with Networking of Modelling Practioners"
            
  
          # Upload image to `assets/media/` and reference the filename here
          image: Programme Schedule.jpeg
          #button:
          #  text: More Information
          #  url: https://hugoblox.com/templates/
        
        - title: Registration Fees
          text: Registration fees includes twin room accommodation, full board and course fees
          feature_icon: bolt
          features:
            - "Low Middle Income Countries Academics / Students / Gov Officials - USD 500"
            - "High Income Countries Academics / Students / Gov Officials - USD 1000"
            - "Private Sector - USD 3100"
          # Upload image to `assets/media/` and reference the filename here
          image: Registration Fees.png
          button:
            text: Register Now
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
 
  



---
