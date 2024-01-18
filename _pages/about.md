---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

About me
======
Jiguang WANG is a Ph.D. student in traffic and transportation engineering at The University of Hong Kong. He received his bachelor’s degrees in logistics engineering from Shanghai Maritime University in 2020 and earned his master’s degree in Management Science and Engineering from Tsinghua University in 2023. His research interests mainly include the fields of Data-driven optimization, Operations research, Urban mobility, Integer programming.


Education
======
* The University of Hong Kong, Department of Civil Engineering, PhD. Transportation Engineering, 2023-Present
  
     Supervisor: Dr. Jintao Ke, University of Hong Kong         

* Tsinghua University, Tsinghua Berkeley Shenzhen Institute, M.S. Management Science and Engineering, 2023
  
     Supervisor: Prof. Wai Kin (Victor) Chan, Tsinghua University 

* Shanghai Maritime University, School of Logistics Engineering, B.S. logistics engineering, 2020 

Work experience
======
* Jul. to Oct. 2021: Algorithm Engineer Intern
  * Huawei 2012 Laboratory 
  * Duties included: Conduct research on traffic pattern identification and prediction.


Publications
======
{% for post in site.publications reversed %}
{% endfor %}
