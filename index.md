---
layout: lesson
root: .
lastupdated: Month Day, Year
contributors: ["First Last", "First Last", "Pls Add Others"]
maintainers: ["First Last", "First Last"]
domain: Domain Name
topic: Topic
software:
dataurl:
status: Under Development
---

# Data Carpentry Genomics Workshop

=======

Data Carpentry workshops are for any researcher who has data they want to analyze , and no prior computational experience is required. This hands-on workshop teaches basic concepts, skills and tools for working more effectively with data.

The focus of this workshop will be on working with genomics data and data management and analysis for genomics research. We will cover metadata organization in spreadsheets, data organization, connecting to and using cloud computing, the command line for sequence quality control and bioinformatics workflows, and R for data analysis and visualization. We will not be teaching any particular bioinformatics tools, but the foundational skills that will allow you to conduct any analysis and analyze the output of a genomics pipeline.

Participants should bring their laptops and plan to participate actively. By the end of the workshop learners should be able to more effectively manage and analyze data and be able to apply the tools and approaches directly to their ongoing research.

Data Carpentry's aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain.

### Workshop structure

One dataset will be used throughout the workshop. We will start by introducing the dataset and the steps we'll go through for analysis. 

### Dataset

In this workshop we're using data from Blount et al 2012 paper from Dr. Richard Lenski's Long Term Evolution Experiment.  

- [Overview of the dataset](http://www.datacarpentry.org/introduction-genomics/01-intro-to-dataset.html)
- [Data for command line and data wrangling lessons]()
- [Data for R lesson]()

### Amazon instance for workshop

All the software and data used in the workshop is on an Amazon AMI.

If you want to run your instance of the server used for this workshop, launch a t2.medium instance with AMI **ami-6516b30e**, available under "Community AMIs" in the Amazon EC2 Managemant Console. 

### Preliminary schedule

**Day 1 Morning**

Module 1: [Workshop Introduction](http://www.datacarpentry.org/introduction-genomics)

- Overview of the workshop
- Introducing the dataset and questions
- Genomic data in the NCBI SRA database

Module 2: [Using cloud computing for genomics](https://github.com/datacarpentry/cloud-genomics)  

- understand what cloud computing is and why it's useful
- log in to remote computing resources

**Day 1 Afternoon**

Module 3: [Introduction to the command line](https://github.com/datacarpentry/shell-genomics)  

- command line 

**Day 2 Morning**

Module 5: [Data wrangling and processing](https://github.com/datacarpentry/wrangling-genomics)  

- running FastQC
- running Trimmomatic
- running FastQC to look at changes

**Day 2 Afternoon**

Module 6: [R for data analysis and visualization](https://github.com/datacarpentry/R-genomics)

- importing data in to R and using it for analysis and visualization


### Requirements

Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workfl\
ow.
*These lessons assume no prior knowledge of the skills or tools*, but working
through this lesson requires working copies of the software described.
To most effectively use these materials, please make sure to install everything
*before* working through this workshop.

<p><strong>Twitter</strong>: @datacarpentry