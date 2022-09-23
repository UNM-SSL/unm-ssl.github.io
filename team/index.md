---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team
-- Donny: currently editing

The Scalable Systems Lab is a research laboratory in the Computer Science Department at the University of New Mexico. We collaborate closely with the UNM Center for Advanced Research Computing, the Scalable Computing Systems Department at Sandia National Laboratories, the Computer and Computational Sciences Division at Los Alamos National Laboratory, and research groups at a variety of corporations, for example Cray and Intel.

The Scalable Systems Lab (UNM-SSL) is home to a diverse group of students and professionals. Their research includes on HPC Mapping, Network Performance Tuning, Performance Prediction, and other systems related work.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Healer/Grad Student"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

{% include section.html %}

## Join

#### Post Doctoral Researcher

The SSL is currently searching for a postdoctoral fellow to mentor on leading research at our DOE-funded Center for Understandable, Performant Exascale Communication Systems. The specific research topics the postdoc will work on depend on the candidate’s background, but will generally be in the area of:
  1. Designing system software (both communication and runtime) for coupling multiple scientific codes together 
  1. Developing new and optimizing existing communication primitives for DOE production codes, and/or 
  1. Designing and implementing new benchmarks that are actually representative of the communication challenges faced by production codes. 

The postdoc will work closely with Prof. Bridges, other SSL members, and our collaborators at other institutions, including our many national lab collaborators. The fellowship also includes a paid 10-week residency at an NNSA national laboratory.

{% include link.html type="external" link="https://unm.csod.com/ux/ats/careersite/18/home/requisition/21893?c=unm" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nsf.svg"
  link1="https://www.nsf.gov/"
  tooltip1="National Science Foundation"

  image2="images/psaap.png"
  link2="https://psaap.llnl.gov/"
  tooltip2="NNSA PSAAP-III Program"

  image3="images/lanl.png"
  link3="https://www.lanl.gov/"
  tooltip3="Los Alamos National Laboratory"

  image4="images/sandia.svg"
  link4="https://www.sandia.gov/"
  tooltip4="Sandia National Laboratories"
%}
