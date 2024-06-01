---
date: "2023-10-24"
design:
  spacing: 6rem
sections:

- block: hero
  id: hero
  content:
    text: |
     <p class="mt-6 leading-8" style="font-size:1.6rem; color:black">Neurophysiology | Appetite Regulation | Endocrinology</p>
    title: <h1 class="font-bold tracking-tight" style="font-size:4rem; color:black">Christelinda Laureijs</h1>
  design:
    background:
      image:
        filename: Rat-hero-small.svg
        filters:
          brightness: 1
        #text_color_light: true
        #size: cover
        parallax: false
    #css_class: dark
    spacing:
      margin:
      - 0
      - 0
      - 0
      - 0
      padding:
      - 20
      - 0
      - 20
      - 0
      
      
- block: markdown
  id: intro
  content:
    title: I am a researcher, R coder, and artist
    text: | 
      I am a master's student working under the supervision of Dr. Karen Crosby at Mount Allison University. My work focuses on the effect of insulin on neurons in the dorsomedial hypothalamus (DMH), which is a brain region critical for appetite regulation.
  design:
    background:
      image:
        filename: Green-neuron.svg
        parallax: true
        position: right
        
        
- block: markdown
  id: projects
  content:
      title: Projects
  design:
    background:
      color: white
      text_color_light: false
    spacing:
      padding: ["25px", "0", "0px", "0"]
  
- block: markdown
  id: honours
  content:
      text: |
        <h3>Does insulin act in the DMH?</h3>
        For my honours project, I asked if insulin binds to DMH neurons, and if so, how that may affect their activity. I compared synaptic transmission (a measure of communication between neurons) and action potentials (a measure of neuronal excitability) before and after exposing DMH neurons to insulin.
        <a href="https://github.com/christelinda-laureijs/honours-thesis" target="_blank" title="Explore the GitHub project!"><img src="Methods-schematic.png"></a>
        I found that insulin <b>decreases</b> both excitatory synaptic transmission and neuronal excitability in DMH neurons. If you're interested in reading more, you can explore <a href="https://github.com/christelinda-laureijs/honours-thesis" target="_blank" title="Explore the GitHub project!">the project page on GitHub</a>!
  design:
    background:
      image:
        filename: Insulin.svg
        parallax: false
        position: left

- block: markdown
  id: art
  content:
      text: |
        <h3>Cranky Bee Art</h3>
        A few years ago, I started an online business featuring my watercolour art and nature photography. It grew quickly and little did I know that this fun side project would soon become a...
        
        
        Visit <a href="https://crankybeeart.com/" target="_blank" title="Click here to visit the Cranky Bee Art website!">Cranky Bee Art</a>!

- block: markdown
  id: artpicture
  content:
    text: 
  design:
    background:
      image:
        filename: 20240531-Watercolour-banner.svg
        parallax: true
        position: center

- block: markdown
  id: coding
  content:
      text: |
        <h3>R coding projects</h3>
        
        I always have some sort of coding project on the go. My most recent projects have included creating an RMarkdown/LaTeX thesis template, coding a website (this one!) and developing scripts to analyze the recordings that we collect in the lab.
        
        I'm trying to create a script to identify local peaks in a recording.

  design:
    background:
      image:
        filename: Rat-Laptop.svg
        size: cover
        parallax: false
      

- block: markdown
  id: contact
  content:
      title: Contact
      text: |
        Let's connect! If you have ideas for collaboration, knowledge of useful R scripts or packages, or ideas for what card I should paint next, I would love to hear from you.
        
        cslaureijs@gmail.com
        
        <img src="avatar-round-png.png" alt="Photo of Christelinda Laureijs" width="300" height="300" style="display: block; margin-left: auto; margin-right: auto; width: 50%">


title: Home
type: landing
---