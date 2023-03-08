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
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: Linux
  #         description: 100%
  #         icon: linux
  #         icon_pack: fab
  #       - name: Python
  #         description: 100%
  #         icon: python
  #         icon_pack: fab
  #       - name: Go
  #         description: 75%
  #         icon: python
  #         icon_pack: fab
  - block: experience
    id: experience
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
        - title: Scientific Software Developer
          company: Mestrelab Research S.L.
          company_url: 'https://mestrelab.com/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2019-11-11'
          date_end: ''
          description: '
            * Implementation of micro-services in Python and Go.
   
            * Implementation of streaming services using NATS.
  
            * Development of high performance software for Surface Plasmon Resonance (SPR) analysis.'
        - title: 'Post-doctoral researcher'
          company: 'Polytechnic Institute of Cávado and Ave (IPCA)'
          company_url: 'https://ipca.pt/'
          location: 'Barcelos (Portugal)'
          date_start: '2018-10-13'
          date_end: '2019-11-10'
          description: 'Post-doctoral researcher in High Performance Computing and Big Data applied to Genomics. Languages and frameworks used: C/C++, Java, MPI and Spark'
        - title: 'Post-doctoral researcher and Software Developer'
          company: 'Technological Institute for Industrial Mathematics (ITMATI)'
          company_url: 'http://www.itmati.com/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2018-02-01'
          date_end: '2018-10-12'
          description: '
            * Software development in Python, C++ and Fortran.

            * Development of prediction models for time series data.'
        - title: 'Data Scientist'
          company: 'DXC Technology'
          company_url: 'http://www.dxc.technology/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2017-09-01'
          date_end: '2018-01-31'
          description: 'Development of Big Data software to perform ETL processes by using Apache Spark.'
        - title: 'Researcher and PhD student'
          company: 'Centro de Investigación en Tecnoloxías da Información (CiTIUS)'
          company_url: 'https://citius.usc.es/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2014-01-14'
          date_end: '2017-08-31'
          description: 'My research is based in:

          * Big Data applications performance with Hadoop and Spark.

          * High Performance Computing applied to Natural Language Processing and Genomics.

          * Genomics alignment by using Big Data and HPC technologies.
          '
        - title: 'Software Developer'
          company: 'Applied Mathematics Department (University of Santiago de Compostela)'
          company_url: 'http://www.usc.es/dmafm/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2013-02-01'
          date_end: '2014-01-13'
          description: '
          * Development of gas networks simulator and optimizator by using Fortran language.

          * In charge of the development of a graphical interface for its use with the simulator and optimizator tool based in the open source project Quantum Gis (QGis). This interface is made with Pyhton and Qt (PyQt).

          * Code development for mathematical problems.

          * Development of paralell applications with OpenMp and MPI.

          * Implementation of the software simulator and optimizator software as SaaS (Software as a Service).

          * Administration of the Linux server where the gas simulator and optimizator software resides.
          '
        - title: 'Projects technician & systems administrator'
          company: 'Galicia Supercomputing Centre (CESGA)'
          company_url: 'https://www.cesga.es/'
          location: 'Santiago de Compostela (Spain)'
          date_start: '2008-04-14'
          date_end: '2013-02-01'
          description: '
          * Linux servers administration (dom0 Xen servers and also virtual machines).

          * Development of web platforms based on Java and PHP.

          * Maintenance and development of an e-Learning platform based in the Chamilo Open Source platform, Aula Cesga.

          * Managing videoconferences through BigBlueButton.

          * Scripts programming using Python and Bash.
          '
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: recent
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Take a look at all publications [here](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please, fill in your data.
      # Contact (add or remove contact options as necessary)
      # email: test@example.org
      # phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: Feliciano Barrera 9B - Bajo
        city: Santiago de Compostela
        region: A Coruña
        postcode: '15706'
        country: Spain
        country_code: ES
      directions: Just ring the bell
      office_hours:
        - 'Monday to Friday 08:00 to 13:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/ChemaRianxo'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
