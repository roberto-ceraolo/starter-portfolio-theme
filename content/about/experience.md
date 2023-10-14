---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: AI Research Intern
    company: Schlumberger-Doll Research (SDR)
    company_url: ''
    company_logo: slb-logo
    location: Cambridge, MA
    date_start: '2022-07-19'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * As part of the Maths and Analytics team, currently researching Deep Learning methods to extract knowledge from well logs, 1D signals from measurements of the Earth Subsurface.
        * Contributed to the creation and deployment of a Vector Search Retrieval tool for well logs, by using Variational Autoen- coders and clustering methods to handle high data dimensionality.
        * Ran experiments on GPU cluster, and introduced new features to the tool, after proving their value from results.
        * Reduced data dimension and and RAM usage by 100%, loading time by 1000%.

  
  - title: Teaching Assistant
    company: University of Lausanne (UNIL)
    company_url: ''
    company_logo: unil-logo
    location: Lausanne
    date_start: '2022-09-01'
    date_end: '2023-05-31'
    description: |2-
        Responsibilities included:
        
        * Preparing materials and hosting the labs for the courses "Data Mining and Machine Learning" and "Cloud and Advanced Analytics"
        * Learnt to use the tools and technologies used in the industry, such as Docker, Kubernetes, Spark, Hadoop, AWS, Azure, etc.
        * Learnt to explain complex concepts to students in a simple and understandable way


  - title: Business Analyst Intern
    company: Barclays Technology 
    company_url: ''
    company_logo: barclays-logo
    location: Knustford, UK
    date_start: '2020-06-01'
    date_end: '2020-08-15'
    description: Proposed a new idea to make the classification of technical incidents more efficient through Machine Learning. Outlined a Data Pipeline, choosing several features of interest to be used with a classification algorithm.

design:
  columns: '1'
---
