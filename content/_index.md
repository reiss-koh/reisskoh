---
# Leave the homepage title empty to use the site title
title: ""
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
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: '🌟 Why I Do Research'
      subtitle: ''
      text: |-
        Two experiences inspire me to do research.

        **(1)** Out of the blue, at the beginning of the COVID-19 pandemic, I began suffering from chronic pain. It was excruciating pain, 24/7. I had to go to the emergency room twice and faced significant physio-psychological challenges. Despite consulting multiple clinical departments and major institutions, I was unable to receive a definitive diagnosis. 
        
        Naturally, I took matters into my own hands—I read numerous research papers and other online resources to try to find a diagnosis, while continuing to search for clinicians who could help me. Eventually, through modern science, my chronic pain was (mostly) resolved after 1.5 years after numerous interventions. I am happy to share that I now have it completely under control and am no longer afraid of it. In addition, most of my pain-induced psychological challenges have been fully resolved, and I believe I am now arguably healthier than before. 
        
        Through this journey, I came to realize that my well-being—and that of others—rests on the shoulders of technological advancement. I believe I wouldn’t be where I am today without the support of science and society, and I feel it is my responsibility to give back what I have received.

        **(2)** During my mandatory national service (which lasted 18 months), I had the pleasure of working at a social welfare center. This period significantly overlapped with the chronic pain I described in **(1)**. Some of my time was spent with marginalized elderly individuals and those with physical or cognitive disabilities, but most of it was dedicated to working with primary school children.

        Among these children, there was one girl who had a developmental disability. Unfortunately, she struggled to socialize with her neurotypical peers and was sometimes excluded. Despite the senior caregivers’ best efforts, she continued to face difficulties thriving in that environment. Eventually, she transferred to a more specialized facility, though she would occasionally visit us.

        This experience of feeling helpless while caring for underprivileged individuals and groups has fueled my desire to find ways to enrich and empower the lives of others. I believe that advancing science and technology is one of the best ways I can make a meaningful, positive impact. I hope to see a future where humanity’s progress fosters wide-spread inclusiveness.
    design:
      columns: '1'
---