---
title: 'Public Health Data Science with MATLAB'
tags:
 - data science
 - public health
 - MATLAB
 - tutorial
authors:
 - name: Juan H Klopper
         orcid: 0000-0002-7325-1906
         affiliation: 1
affiliations:
 - name: Milken Institute School of Public Health, The George Washington University
         index: 1
date: August 21, 2024
bibliography: paper.bib
---

# Summary

Public health research is essential for identifying, preventing, and managing health issues that affect populations [@jutte_administrative_2011]. It plays a critical role in understanding the distribution and determinants of health and diseases, which in turn informs the development of policies and interventions that improve public health outcomes [@bernier_public_2011]. Through research, public health professionals can identify risk factors, evaluate the effectiveness of interventions, and guide evidence-based decision-making to protect and promote the health of communities [@brownson_building_2018].

For domain experts, the ability to work with and analyze data is particularly important [@maier-hein_surgical_2022]. The growing availability of health data from electronic health records to large-scale surveys—offers opportunities to uncover patterns, predict trends, and optimize resource allocation [@de_mauro_beyond_2016]. By equipping themselves with data science skills, public health students and experts can leverage these data sources to generate insights that are crucial for tackling complex health challenges, such as chronic diseases, pandemics, and health disparities.

Proficiency in statistical tools and software is invaluable, as it allows researchers to perform advanced analyses, develop models, and visualize data, thereby enhancing the quality and impact of their research in public health. The MATLAB language and software environment allows domain experts full access to working with data, either using code or by using a variety of built-in tools that import, wrangle, analyze, and report on finding with the click of a button. This makes MATLAB an ideal tool for the domain expert to contribute to data analysis and research in public health.

The open educational resource built using MATLAB and presented here is structured as follows.

1. Arithmetic, variables, and data containers
2. Storing data as vectors and matrices
3. Data types and exploratory data analysis
4. Working with data in spreadsheets
5. Data wrangling
6. Common statistical tests and models

The audience for this open educational tool are any student of Public Health, early career researcher in Public Health, any expert in Public Health already in employment, and for any instructor at a School of Public Health that wishes to introduce the use of MATLAB to their students.

Since its creation, the material in this course has been used by over 100 past students of the author. The course material consists off a full set of elaborate documents (one for each chapter), available on GitHub in PDF and in MLX (MATLAB Live Script) format [@klopper_juankloppermatlab4datascience_2024]. The latter are interactive documents. Students can use these notebooks to experiment with the code in the course. The GitHub repository also contains the data file used in the course. There is also a five-hour instructional video for the course [@data_science_for_public_health_matlab_2024]. 

# Statement of Need

The availability of data and the need to use this data to find solutions to public health problems is increasing. The recent COVID-19 pandemic serves as outstanding example. The tools to manage and analyze data and to present findings have matured over time. There is an increased expectation that public health experts, scientists, and researchers not only understand their domain, but also have a working understanding of applied computer science and statistics to achieve their goals.

Many Schools of Public Health throughout the United States (US) and elsewhere in the World offer technical courses in computer languages and software for Health Data Science. These courses are dominated by SAS [@noauthor_sas_nodate], Python [@noauthor_welcome_2024], and R [@noauthor_r_nodate]. None of the 10 leading Schools in the US offer any courses in MATLAB. MATLAB, however, remains a leading language in Data Science today. This is especially true in technical and engineering fields. The job market for graduates of Schools of Public Health is robust, with opportunities in many job markets. To enable students to expand their opportunities for employment in companies and organizations with health-related technical and engineering positions, the free and open educational resource presented in this paper aims to achieve the following.

1. Provide a learning resource to all students of Public Health and instructors at Schools of Public Health
2. Review important topics in biostatistics
3. Learn critical skills in the creation, wrangling, analysis, and presentation of data using a coding and low-coding approach with the MATLAB language and built-in tools
4. Learn to use code and low-code approaches to solve problems in Public Health

# References