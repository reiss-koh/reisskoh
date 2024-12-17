---
# Leave the homepage title empty to use the site title
title: "Woosung (Reiss) Koh"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: 📚 Publications
      text: "*First Author(s), ^Advisor(s)"
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: '🧐 Currently Working On'
      subtitle: ''
      text: |-
        I am primarily working on methods to improve **Language Model Reasoning** and **Generalization**!
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🌟 Why I Do Research'
      subtitle: ''
      text: |-
        Numerous experiences inspire me to do research. Here are two representative examples.

        **(1)** Out of the blue, at the beginning of the COVID-19 pandemic, I began suffering from chronic orofacial pain. It was excruciating pain, 24/7. I had to go to the emergency room twice and faced significant physio-psychological challenges. Despite consulting multiple major institutions and clinical departments, I was unable to receive a definitive diagnosis. 
        
        Naturally, I took matters into my own hands—I read numerous research papers and other online resources to try to find a diagnosis, while continuing to search for clinicians who could help me. Eventually, through numerous interventions, my chronic pain was (mostly) resolved after 1.5 years. I am happy to share that I now have it completely under control. In addition, most of my pain-induced psychological challenges have been fully resolved, and I believe I am now arguably healthier than ever before. 
        
        Through this journey, I came to realize that my well-being—and that of others—rests on the shoulders of technological advancement. I believe I wouldn’t be where I am today without the support of science and society, and it is my responsibility to give back what I have received.

        **(2)** During my mandatory national service (which lasted 21 months), I had the pleasure of working at a social welfare center. This period significantly overlapped with the chronic pain I described in **(1)**. Some of my time was spent with marginalized elderly individuals and those with physical or cognitive disabilities, but most of it was dedicated to working with primary school children.

        Among these children, there was one girl who had a developmental disability. Unfortunately, she struggled to socialize with her neurotypical peers and was sometimes excluded. Despite the senior caregivers’ best efforts, she continued to face difficulties thriving in that environment. Eventually, she transferred to a more specialized facility, though she would occasionally visit us.

        This experience of feeling helpless while caring for underprivileged individuals and groups inspires me to find ways to enrich and empower the lives of others. I believe that advancing science is one of the best ways I can make a meaningful, positive impact. I hope to see a future where humanity’s progress fosters wide-spread inclusiveness.
    design:
      columns: '1'

  - block: markdown
    content:
      title: '🌎 Background'
      subtitle: ''
      text: |-
        I was born in Seoul, Korea but lived abroad with my family during my grade-school years, attending numerous institutions such as the American International School of Dhaka (AISD) and ACS Jakarta. During my high-school years I was a semi-professional e-sports player where I assumed the in-game leader (IGL) position throughout. A well renowned teamate I shared a majority of my career with is *f0rsakeN*. I seldom participated in academic endevours during my middle- and high-school years, but the skills and values I have gained performing near the highest-level were far more valuable than anything regular schooling could have taught me. Notably: leadership, emotional intelligence, perfecting a craft to the frontier, and going beyond existing state-of-the-art. Near the end of my high-school years I realized that I would be rejected from relevant universities at this rate, and began studying. Since then, I have dedicated my life to academia. Regarding leisure, when I was younger, I played a lot of badminton and was fairly fluent in the clarinet. 
    design:
      columns: '1'

  # - block: markdown
  #   content:
  #     title: '🎨 Leisure and Hobbies'
  #     subtitle: ''
  #     text: |-
  #       🐹 First, I enjoy watching videos of cute animals. If you look at my *for you page* it is mostly guinea pigs, hamsters, rabbits, and so forth. Guinea pigs are my favorite! 🏋 A few times a week I go to the gym for weight training. When I was younger I played a lot of badminton, while dabbling with table tennis, tennis, soccer, swimming, and golf. 🛫 Occasionally, I like to travel around with friends and family! I have been to Korea, Japan (Osaka, Kyoto, Nara, Tokyo), Thailand (Bangkok), Indonesia (Jakarta, Bali), Malaysia (Kuala Lumpur, Genting Highlands), Singapore, Bangladesh (Dhaka, Cox's Bazar), Hong Kong, and Canada (Vancouver). 🥂 I typically do not drink — good white wine and champagne are exceptions. 🍣 I also love sea food — e.g. sushi/sashimi (tuna, salmon, uni, fish roe), abalone, crab. I especially love grilling fresh clams! 📺 I occasionally enjoy watching sit coms. 🎼 I usually am always listening to music. When I was younger I briefly played the clarinet, drums, piano, violin, and guitar (in that order of fluency).
  #   design:
  #     columns: '1'
---