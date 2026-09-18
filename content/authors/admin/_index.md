---
# Display name
title: Luis Angel Guerrero Hoyos

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Luis Angel
last_name: Guerrero Hoyos

# Status emoji
status:
  icon: 🛰

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: GIS Analyst | Civil-Geological Engineer

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Shannon and Wilson Inc
    url: https://www.shannonwilson.com/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:laghoyos@uw.edu'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/laghoyos
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/luis-angel-guerrero-hoyos-b3166912a/

interests:
  - GIS application development (ArcGIS Pro, arcpy)
  - Remote sensing (LiDAR, InSAR)
  - AI-assisted engineering tooling
  - Geotechnical engineering

education:
  - area: MSc Civil Engineering
    institution: University of Washington
    date_start: 2023-09-27
    date_end: 2025-05-31
    summary: |-
      GPA: 3.86/4.0
      
      Courses included:
      - Advanced Geomatics and Remote Sensing
      - Geospatial Data Analysis
      - Engineering Computing
      
      Thesis on Calibration of Physic-Based Model for Earthquake-induced Landslides Hazards using geospatial technologies. Supervised by Prof. <a rel="noreferrer" target="_new" href="https://www.ce.washington.edu/facultyfinder/joseph-wartman" style="text-decoration: none;">Joseph Wartman</a>.
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
  - area: BSc Geological Engineering
    institution: Universidad Nacional de Colombia
    date_start: 2013-02-04
    date_end: 2018-12-31
    summary: |-
      GPA: 4.2/5
      
      Courses included:
      - Introduction to Programming and Algorithms
      - Remote Sensing 
      - Geographic Information Systems (GIS)
work:
  - position: Staff Engineer
    company_name: Shannon and Wilson Inc
    company_url: https://www.shannonwilson.com/
    company_logo: sw.jpg
    date_start: 2025-07-01
    summary: |-
      Responsibilities include:
      - Act as GIS project lead across multiple concurrent client accounts, gathering stakeholder requirements and delivering production ArcGIS Pro applications, standardized map templates, and enterprise geodatabase/layer management (97 layers across 10 sites for one program).
      - Lead development of SWLC3D, a Python/arcpy LiDAR change-detection pipeline (PDAL, CloudCompare, ICP registration + M3C2 analysis) with automated QA validation, producing displacement-vector shapefiles and map-series deliverables for infrastructure and dam-monitoring programs; evaluated UAV LiDAR sensors (RIEGL miniVUX, YellowScan Venturer/Voyager, ROCK Ultra) for change detection over vegetated terrain.
      - Build Python/arcpy ETL automation (raster sampling, cross-section map-series export) and InSAR displacement-monitoring tools (Dolphin, PyGMTSAR), expanding the firm's remote-sensing service line.
      - Build browser-based engineering web applications (VIKTOR), including a seismic-displacement calculator and an in-app documentation viewer, and use Anthropic Claude/Claude Code to accelerate GIS tooling, documentation, and reporting automation.
      - Contribute to traditional geotechnical practice: boring logs, site investigation, and construction observation.
  - position: Owner & Coach
    company_name: Drizzle Ballers
    company_url: https://laghoyos.github.io/drizzle-ballers
    date_start: 2025-01-01
    summary: |-
      Founded and run a Seattle youth soccer coaching business; built and maintain the business website.
  - position: Research Assistant and Scientist
    company_name: University of Washington
    company_url: https://www.ce.washington.edu/
    company_logo: uw.svg
    date_start: 2023-08-01
    date_end: 2025-06-30
    summary: |-
      Responsibilities include:
      - Investigate the geospatial relationships between earthquake-induced landslides and their reactivations, building Python geoprocessing workflows (GeoPandas, Rasterio, GDAL) over satellite imagery (Sentinel-1 SAR), rasters (GeoTIFF, lidar), and vectors (GeoJSON, geopackage, shapefile).
      - Completed InSAR Processing and Analysis (ISCE+) training through EarthScope Consortium & NSF.
  - position: Geotechnical Intern
    company_name: Terracon Consultants Inc
    company_url: https://www.terracon.com/
    company_logo: terracon.jpeg
    date_start: 2024-06-01
    date_end: 2024-09-30
    summary: |-
      Responsibilities include:
      - Site reconnaissance and investigations, project scoping, budgeting, logging, geotechnical proposals and report preparation.
      - Geotechnical earthquake analysis: site response and liquefaction.
  - position: Monitoring Analyst
    company_name: Hexagon Geospatial
    company_url: https://hexagon.com/products/product-groups/monitoring-solutions/monitoring-radar
    company_logo: hexagon_geospatial_logo.jpeg
    date_start: 2021-07-01
    date_end: 2023-08-31
    summary: |-
      Responsibilities include:
      - Perform InSAR and geospatial data analysis and real-time geotechnical monitoring of pit slopes and tailing dams using ground-based interferometric radars, robotic total stations, and GNSS, while providing technical support and delivering daily, weekly, and monthly reports on unstable areas for decision-making.
  - position: Geological Engineer
    company_name: South32
    company_url: https://www.south32.net/what-we-do/our-locations/americas/cerro-matoso
    company_logo: south32.png
    date_start: 2019-01-01
    date_end: 2021-07-31
    summary: |
      Responsibilities include:
      - Manage and perform data entry of GIS databases for mineral resource estimation and decision-making, while planning and supervising drilling campaigns.
  - position: Research Assistant and Scientist
    company_name: Universidad Nacional de Colombia
    company_url: https://minas.medellin.unal.edu.co/
    company_logo: unal.jpg
    date_start: 2017-08-01
    date_end: 2018-03-31
    summary: |
      Responsibilities include:
      - Conduct photointerpretation, geotechnical mapping, and statistical modeling validation for landslide, debris flow, and flood hazard studies in Aburrá Valley, while proposing an early warning system for flash flows using RTI methodology.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: GIS & Remote Sensing
        description: 'ArcGIS Pro, arcpy, QGIS, LiDAR, InSAR'
        percent: 95
        icon: custom/data
      - name: Python
        description: 'arcpy, GDAL, geoprocessing automation'
        percent: 90
        icon: custom/code
      - name: SQL
        description: ''
        percent: 40
        icon: custom/sql
      - name: Data Analysis
        description: ''
        percent: 100
        icon: custom/data
      - name: GitHub
        description: ''
        percent: 100
        icon: custom/github
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Football
        description: ''
        percent: 100
        icon: custom/soccer
      - name: Traveling
        description: ''
        percent: 70
        icon: custom/airplane
      - name: Food
        description: ''
        percent: 70
        icon: custom/food
      - name: Music
        description: ''
        percent: 70
        icon: custom/music

languages:
  - name: English
    percent: 100
  - name: Spanish
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: CEE Departmental Graduate Fellowship
    url: https://www.ce.washington.edu/current/abroad/valle
    date: '2023-08-01'
    awarder: University of Washington
    # icon: custom/uw
    summary: |-
      This fellowship award at the University of Washington underscores my expertise in geospatial data analysis, InSAR (Interferometric Synthetic Aperture Radar) techniques, and coding proficiency. My demonstrated skills in harnessing geospatial data and employing advanced remote sensing technologies like InSAR and LiDAR highlight my commitment to advancing knowledge in earth sciences and spatial analysis.
      
      <a href="https://laghoyos.github.io/website/uploads/resumes-letters/fellowship.pdf" target="_blank" rel="noopener" style="text-decoration: none;" class="inline-flex items-center px-4 py-2 text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg hover:bg-gray-100 hover:text-primary-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-primary-700 dark:bg-gray-800 dark:text-gray-300 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700">
      <svg class="w-3.5 h-3.5 me-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentcolor" viewBox="0 0 20 20">
        <path d="M14.707 7.793a1 1 0 00-1.414.0L11 10.086V1.5a1 1 0 00-2 0v8.586L6.707 7.793A1 1 0 105.293 9.207l4 4a1 1 0 001.416.0l4-4a1 1 0 00-.002-1.414z"></path>
        <path d="M18 12h-2.55l-2.975 2.975a3.5 3.5.0 01-4.95.0L4.55 12H2a2 2 0 00-2 2v4a2 2 0 002 2h16a2 2 0 002-2v-4a2 2 0 00-2-2zm-3 5a1 1 0 110-2 1 1 0 010 2z"></path>
      </svg> 
      See Certificate
      </a>
  - title: Radar Monitoring
    url: https://mining.arizona.edu/professional-development
    date: '2020-12-01'
    awarder: University of Arizona
    # icon: /assets/media/icons/custom/arizona.svg
    summary: |-
      Learned:
        - Ground-based Synthetic Aperture Radar (SAR).
        - Ground-based Real Aperture Radar (RAR) • Satellite-based InSAR.
        - Capabilities/limitations • Data interpretation • Real-world examples and case studies.
      
      <a href="https://laghoyos.github.io/website/uploads/resumes-letters/georadars.pdf" target="_blank" rel="noopener" style="text-decoration: none;" class="inline-flex items-center px-4 py-2 text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg hover:bg-gray-100 hover:text-primary-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-primary-700 dark:bg-gray-800 dark:text-gray-300 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700">
      <svg class="w-3.5 h-3.5 me-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentcolor" viewBox="0 0 20 20">
        <path d="M14.707 7.793a1 1 0 00-1.414.0L11 10.086V1.5a1 1 0 00-2 0v8.586L6.707 7.793A1 1 0 105.293 9.207l4 4a1 1 0 001.416.0l4-4a1 1 0 00-.002-1.414z"></path>
        <path d="M18 12h-2.55l-2.975 2.975a3.5 3.5.0 01-4.95.0L4.55 12H2a2 2 0 00-2 2v4a2 2 0 002 2h16a2 2 0 002-2v-4a2 2 0 00-2-2zm-3 5a1 1 0 110-2 1 1 0 010 2z"></path>
      </svg> 
      See Certificate
      </a>
  - title: InSAR Processing and Analysis (ISCE+)
    date: '2024-08-01'
    awarder: EarthScope Consortium & NSF
    summary: |-
      Training in InSAR processing and analysis using ISCE+, covering satellite SAR data preparation and displacement time-series analysis.


---

## About Me

I am a GIS Analyst and Civil-Geological Engineer with 7+ years of experience building ArcGIS Pro applications, Python/arcpy geoprocessing and ETL automation, and LiDAR change-detection tooling as GIS project lead across multiple concurrent client accounts — paired with a background in traditional geotechnical practice: field explorations, laboratory testing, report preparation, and construction observation. I increasingly rely on AI-assisted development (Anthropic Claude, Claude Code) to accelerate GIS tooling and documentation. I hold a MSc degree in Civil Engineering (Geotechnical) from the University of Washington and a BSc degree in Geological Engineering from the Universidad Nacional de Colombia, and am currently pursuing PE licensure. I excel in both autonomous and team-based learning environments, with outstanding interpersonal, written, and communication skills, and a creative, problem-solving mindset focused on geospatial analysis, data engineering, geotechnical engineering, and risk management. In addition to my academic and professional pursuits, I have a love for football, both as a player and a fan.
