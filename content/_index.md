---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: About Me
      text: |-
        I am a software engineer with a focus on bioinformatics and data engineering. My undergraduate degree was in Medical Bioscience BSc, with a wet-lab focus on oncology and neurodegenerative disease. My thesis evaluated machine learning architectures for classifying cardiac MRI data. 

        Prior to university, I worked at a 5 person BioTech startup in Berlin where I first started to work as an engineer. Throughout undergrad I worked part-time or during the summer as a engineer, largely with genomics data. At the Chan-Zuckerberg Biohub I focused on LIMS tooling and transcriptomics. At insitro, I continue to develop transcriptomics infrastructure as well as working on clinical data.

        In my free time I swim & train Muay Thai. Born in NYC, grew up in London, lived in Berlin & San Francisco. Currently based out of NYC!
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        - title: Software Engineer - Compute Core / ClinData
          company: insitro
          company_url: 'https://insitro.com/'
          location: South San Francisco, California, US (remote)
          date_start: '2023-05-30'
          description: Develop cloud compute infrastructure (K8s, Terraform, AWS) to support software across insitro’s scientific and computational domains. Build full-stack scientific data explorers. Engineer data structures to consolidate data infrastructure and support omics analysis and ML at scale. Produced analyses and reports for target screening with scientific teams. Stood up image viewing infrastructure and tooling for clinical datasets.
        - title: Lead Data Engineer - Quantitive Cell Science Data Science Team
          company: Chan Zuckerberg Biohub
          company_url: 'https://www.czbiohub.org/'
          location: San Francisco, California, US
          date_start: '2021-12-01'
          date_end: '2023-05-01'
          description: Lead and built a project called Datahub, which aims to structure data to support research. Biomedical research is complex, with highly heterogeneous metadata depending on the sample, modality, or goal. Datahub leverages graph databases to represent highly interconnected metadata. A website and API allows users to easily upload, track, and analyze ongoing research. To support Datahub, I also developed infrastructure and analysis pipelines for the mass spectrometry and genomics platforms. Communicated with leadership, and users, and coordinated software engineers to develop automation. Researched using graph theory to interrogate multiomic data being generated at the Biohub under the guidance of the quantitive cell science data science team and Dr Angela Oliveira Pisco. Furthermore worked to analyse and interpret transcriptomics and spatial transcriptomcis datasets.
        - title: Bioinformatics and Data Analyst - Population Genomics Group
          company: Illumina
          company_url: 'https://www.illumina.com/'
          location: Cambridge, UK
          date_start: '2021-06-01'
          date_end: '2021-09-01'
          description: Worked as a bioinformatician for Illumina’s EMEA office, within their Population Genomics (PopGen) group reporting to Dr Ole Schulz-Trieglaff. Contributed to methods for merging and saving terabytes of variant called files (VCFs). Developed test software for triaging bugs and identifying algorithmic slowdowns. Worked for the DRAGEN platform in C++ and Python locally and in Illumina’s HPC environment.
        - title: Machine Learning Researcher - Darrel P Francis Lab
          company: National Heart and Lung Institute
          company_url: 'https://www.imperial.ac.uk/nhli/'
          location: London, UK
          date_start: '2020-10-01'
          date_end: '2021-03-01'
          description: Developed machine learning models under the guidance of Professor Darrel Francis and Dr. James Howard in the Cardiology Department of Hammersmith Hospital, with the end goal of producing a CMRI (cardiac magnetic resonance imaging) pipeline for automated diagnostic of cardiovascular diseases. Developed a classifier that identified the ‘view’ of CMRIs, and retrospectively assessed model performance using several metrics. Investigated a potential novel transformer methodology for image data.
        - title: Bioinformatics Engineer
          company: Global Gene Corp
          company_url: 'https://anuva.bio/'
          location: Cambridge, UK
          date_start: '2020-06-01'
          date_end: '2020-10-01'
          description: GGC collects bespoke exome data from underrepresented populations for investigations into disease genotypes, towards a 1 Million Genome Project. Developed an exome analysis pipeline in nextflow for variant calling and evaluated called variants using bioinformatics tools and Exomiser on a HPC. Also created a PostgreSQL database for storage of the Exomiser analysis, an API backend, and a ReactJS frontend. My project enabled geneticists to review and autogenerate reports on likely causative variants for the subject’s disease phenotype.
        - title: Researcher
          company: Imperial College London
          company_url: ''
          location: London, UK
          date_start: '2019-07-01'
          date_end: '2020-04-01'
          description: This project was an investigation into the effect of adiponectin on ß-Amyloid secretion in PDK1- Knockdown HEK293 cells, as a potential molecular target for treating Alzheimers. I worked with a group of four other researchers to develop knockdown cells with CRISPR, and evaluate the impact of adiponectin on the ß-Amyloid secretion pathway through protein and genomic expression.
        - title: Software Engineer
          company: Automat
          company_url: 'https://automat.berlin/'
          location: Berlin, Germany (remote)
          date_start: '2019-07-01'
          date_end: '2020-04-01'
          description: Automat develops turnkey software solutions. Worked within Automat’s ‘Workshop Mode’ and was responsible for the infrastructure behind the communication software pricing API and a web-scraping tool. Developed and deployed this all on AWS. Worked with Docker, SQL, and Serverless.
        - title: Researcher
          company: Imperial College London
          company_url: ''
          location: London, UK
          date_start: '2018-10-01'
          date_end: '2019-03-01'
          description: Studied the inhibition of paclitaxel-induced apoptosis by epinephrine in a breast cancer cell line using cell viability assays, western blot, and qPCR alongside cell culture techniques.
        - title: R&D Engineer
          company: i2x
          company_url: 'https://i2x.ai/en/home/'
          location: Berlin, Germany
          date_start: '2018-03-01'
          date_end: '2018-07-01'
          description: Researched and developed a hardware device for i2x's call assistance service. Developed audio streaming software in python and Arduino, to stream data to i2x’s ML infrastructure, and visualise analytics.
        - title: R&D Engineer
          company: Leonyte Biosystems
          company_url: ''
          location: Berlin, Germany
          date_start: '2017-09-01'
          date_end: '2018-03-01'
          description: Leonyte was an early stage startup aiming to provide real-time testing for pathogens in food. Worked with the engineering team to develop a prototype portable bacterial detection device. This involved reading data sheets from National Instruments, writing summaries, and constructing several prototypes. Visualized biological and system data for presentation and troubleshooting. Smoothed signals and fine-tuned detection algorithms to improve pathogen detection. Helped with administration related to inventory, monthly invoicing, and SCRUM.
    design:
      columns: '2'
    
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false

  - block: portfolio
    id: projects
    content:
      title: Public Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: Machine Learning
        - name: Software Engineering
          tag: Software Engineering
        - name: Bioinformatics
          tag: Bioinformatics
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'MOOCs'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/8PLQZGBNL6G6
          date_end: ''
          date_start: '2018-05-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Build a Modern Computer from First Principles From Nand to Tetris (Project-Centered Course)
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/82TT9YXZN8DV
          date_end: ''
          date_start: '2018-03-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Computational Neuroscience
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/LGLK2YSJZHT6
          date_end: ''
          date_start: '2018-03-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: DeepLearning.ai
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/Z47WCQXKHKL7
          date_end: ''
          date_start: '2017-11-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: The Brain and Space
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/CCMUXJE84VL5
          date_end: ''
          date_start: '2017-08-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Philosophy and the Sciences Introduction to the Philosophy of Cognitive Sciences
          url: ''
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: samuelrohandsouza@gmail.com
      address:
        city: New York City
        region: NY
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
