---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id : experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Consultant
          company: EXL
          company_url: 'https://www.exlservice.com/'
          location: Gurugram
          date_start: '2021-09-21'
          date_end: ''
          description: |2-
              Project: BTI (Bank Transactions Insights)

              Responsibilities:

              * Developed location based search algorithm for merchants in consumer bank data
              * Developed spent categorisation features for detecting the patterns in customer spending behaviour
              * Implemented a new search-alogorithm in elasticsearch
              * Optimised the production code to process huge dataset
              * Undertook development of production code from third-party vendor to in-house development
              * Conducted KT sessions to develop in-house capabilities of the team to contribute in development code

              Achievements:

              * Accuracy and coverage of merchant identification improved marginally
              * Hyper-personalised customer marketing can be done by detecting customer personas
              * Code development and deployment time reduced significantly
              * Code runtime and memory footprint reduced.

        - title: Research Analyst & Software Engineer
          company: Optirisk Systems
          company_url: 'https://optirisk-systems.com/'
          location:  Remote
          date_start: '2018-12-10'
          date_end: '2021-09-13'
          description: |2-
              Project: Strategies based on SSD

              Responsibilities:

              * Identifying requirements of Indian, US and UK stakeholders to build investment & trading solutions
              * Co-ordinating with internal team across the globe for smooth running of strategies and development of internal systems
              * Designed stop-loss for risk management of portfolios
              * Developed strategies for NIFTY 50 & SP500
              * Deployment and maintenance of live strategies on cloud and developed systems for PnL reports for stakeholders
              * Server and database maintenence for live trading on NIFTY, HANGSENG and SP500 across 3 timezones
              * Developed and deployed backend systems for data scrapping, market alerts and market data & sentiment data
              * Conducted seminars and talks to explain strategies and how & why they work
              * Conducted knowledge transfer session for new recruits for quick and smooth orientation

              Achievements:

              * New strategy went live for NIFTY Futures trading which generated 34% profit in 8 months
              * Completed 2 years of trading on HANGSENG which generated 40% profit
              * Completed 2 years of trading on HANGSENG which generated 40% profit
              * Implemented stop-loss which improved returns of strategy from 14% to 70%
              * Conducted seminar on TradeTron which improved strategy subscription from 12 to 100+
              * Implmented new automated strategies on TradeTron, Exante and Interactive Brokers
        
        - title: Data Scientist Engineer
          company: Crisp Analytics
          company_url: 'https://www.lumiq.ai/'
          location:   Noida
          date_start: '2017-11-10'
          date_end: '2018-12-10'
          description: |2-
              Project: TVS Credit - Risk Control (4 months) 

              Responsibilities:

              * Developed model using behavioural analysis to identify delinquent customers
              * Designed comprehensive data model for project development
              * Performed data validation on client data to rectify gaps in staging and core data
              * Selected and created variables using weight of evidence and information value
              * Identified target customers with high probability of NPA and delinquency

              Achievements:

              * Increased efficiency of existing model by 50% for prediction of delinquent customers
              * Reduced the cost of customer follow ups of risk control unit

              <br>

              Project: MyBox - Identity Information on Blockchain (6 months) 

              Responsibilities:

              * Worked on monetising and secure sharing of personal identification information
              * Performed feasibility analysis of backend and Ethereum blockchain development
              * Implemented ERC20 tokens for development of crypto-currency
              * Encryption and safekeeping of KYC data using state of art RSA encryption algorithms

              Achievements:

              * Process of sharing information became more transparent and hassle-free

        - title: Data Analyst
          company: Snapmint
          company_url: 'https://snapmint.com/'
          location:  Mumbai
          date_start: '2016-09-01'
          date_end: '2017-11-01'
          description: |2-
              Project: Snapmint( Smart lending platform)

              Responsibilities:

              * Developed generalised linear model in H20 to detect the key factors in bounces.
              * Performed rejection analysis to increase loan disbursement to false negative customers
              * Automated the customer verification (KYC) using algorithms like soundex, jaro-winkler
              * Collaborated with cross functional teams for smooth business functioning
              * Designed dashboard and MIS reports for reporting of business performance


              Achievements:

              * Designed and developed policy for credit appraisal of customers
              * Turn around time in verification and under-writing process was reduced significantly

      
    design:
      columns: '2'
  - block: features
    id : skills
    content:
      title: Skills

      items:
        - name: R
          description:
          icon: r-project
          icon_pack: fab
        - name: Python
          description: Python/Flask
          icon: python
          icon_pack: fab
        - name: Data Science
          description: Neural Networks
          icon: chart-line
          icon_pack: fas
        - name: Linux
          description: 
          icon: linux
          icon_pack: fab
        - name: Git
          description: 
          icon: git
          icon_pack: fab
        - name: Database
          description: SQL/NoSQL
          icon: database
          icon_pack: fas
        - name: Blockchain
          description: Hyperledger/Ethereum
          icon: link
          icon_pack: fas
        - name: Business Intelligence
          description: Tableau/Data Studio
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Backend Development
          description: Ruby/Python
          icon: code
          icon_pack: fas

  - block: experience
    id: research
    content:
      title: Research Project
      subtitle: 'Prediction of Efficacy of Oligo-Peptides using QSAR and ANN'
      text: |2-
        Methodology:
        * Did research to predict IC50 values of peptides using Artificial Neural Network & QSAR
        * Used Sttugart Neural Network Simulator (SNNS) and R for modelling
        * Used neural networks with 1 and 2 hidden layers with quick propagation algorithm

        Achievement:
        * Second prize in International Conference on Artificial Intelligence held at NMIMS, Shirpur


  - block: experience
    id: publication
    content:
      title: Featured Publications
      subtitle: '[Prediction of Efficacy of Oligo-Peptides using QSAR and ANN](https://www.tsijournals.com/articles/prediction-of-efficacy-of-oligopeptides-using-qsar-and-ann.html)'
      text: Artificial Neural Network (ANN) is statistical learning models inspired by biological neural networks. The research work presented here mainly focused on use of ANN for quantitative structure activity relationship modeling of peptides. Some peptides can work as anti-depressing agents, as they reduce the activity of Angiotensin I Converting Enzyme (ACE), which converts Angiotensin I to Angiotensin II (a vasoconstrictor). In this work, we have used LogIC50 as the property to show the activity of peptides against ACE. The networks are prepared using the principle artificial neural network using SNNS (Stuttgart Neural Network Simulator). The best obtained network for di-peptides has architecture of 24-8-3-1 and the average absolute average errors obtained are 0.34, 0.42 and 0.58 for training, validation and test set respectively.
  
  - block: experience
    id: awards
    content:
      title: Awards & Achievements
      subtitle: ''
      text: |2-
        Courses:
        * Successfully completed Introduction to Data Science in Python, Data Analysis Tools, Data Management and Visualisation & Customer Analytics from Coursera

        Academic:
        * Among top 0.5% in All India Engineering Entrance Exam (AIEEE), 2009
        * Awarded the KVPY Scholarship by IISC, Bangalore for excellence in KVPY Exam, 2008
        * Awarded Merit certificate for excellence in Mathematics by CBSE, in class X, 2007

  - block: experience
    id: research
    content:
      title: Other Interests
      subtitle: ''
      text: |2-
        * Guitar, Online Gaming, Philosophy, Origami, Cooking, Coding
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: dhruvrana27@gmail.com
      phone: 
      appointment_url: 'https://calendly.com'
      address:
        street: BPTP Astaire Gardens
        city: Gurugram
        region: Harayana
        postcode: '122103'
        country: India
        country_code: IN
    design:
      columns: '2'
---
