---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>   

# 💬About me

Hi, I am Dingyi Jiang. Presently, I am an Artificial Intelligence major bachelor and will graduate in 2024 summer, where I am in <a href='http://cic.tju.edu.cn/english/home.htm'>the College of Intelligence and Computing, Tianjin University</a>(天津大学智能与计算学部). I have several AI-related projects and internships. Notably, I participated in an exchange program during 2023 at <a href='https://cse.hkust.edu.hk/'>the Department of Computer Science and Technology at HKUST</a>(香港科技大学计算机科学与技术学院). I won two scholarships during my undergraduate years。\
<img src="images/TJU.png" width = "100" height = "100" alt="" align=center />
<img src="images/HKUST.png" width = "230" height = "170" alt="" align=center />  

# 💬I will be a fast-track Ph.D. with <a href='https://sites.google.com/site/borriewang/'>Boyu Wang</a> at <a href='https://www.uwo.ca/'>the University of Western Ontario</a> in fall, 2024. Currently, my research interests including transfer learning algorithms and LLM.

# 📖 Education
- *2021.09 - now*,  Undergraduate, Tianjin University, Artificial Intelligence
- *2023.01 - 2023.06*, Exchange Student, HKUST, Computer Science
- *2019.09 - 2021.06*, Undergraduate, Tianjin University, Applied Chemistry (Changed Major)


# 💻 Internships 
- *2023.06 - 2023.12*, LLM Intern, [Frontis](https://frontis.cn/), China.
  1. Responsible for large model fine-tuning (supervised fine-tuning) and pretraining using the Slurm cluster.
  2. Conduct data analysis and data cleaning for Llama large model SFT and pretraining, including manual sampling, multi-threaded character-level processing, and quality and coherence evaluation using the Bert model.
  3. Perform benchmark evaluations and ranking for large models.
    
- *2021.06 - 2021.09*, AI Intern, [AI Cyber](https://www.aicyber.com/), China.
  1. Provide deep learning experiments and slides for Tianjin college students. My projects included *CNN, HMM, quality assessment in speech synthesis, and the prosodic* and *intonation of Chinese in speech synthesis*.
  2. During this period,l became proficient in the operation of Linux on the server and the running of code on  GPU using Python.


<p>
# 📖 Study Performance
<a href='https://peterjiangdingyi.github.io/transcripts.github.io/main.html'>Click Here to Visit My Overall GPA.</a>

Because my first two years at Tianjin University were studying applied chemistry and after that, I changed major, so my transcripts contain lots of non-computer-related courses. Therefore, I put my core GPA which just contains computer-related courses together here.

|NO.|Courses|Credit|Grade(100)|Grade(4.0)|
|:--:|:------------------------------------------:|:------:|:---------:|:---------:|
|1|Data Structure|3.0|91|4.0|
|2|Programming practice|1.5|94|4.0|
|3|Programming Principles|3.0|90|4.0|
|4|Data Mining|2.0|92|4.0|
|5|Operating System Principle|3.0|94|4.0|
|6|Algorithm Design and Analysis|3.0|88|3.7|
|7|Probability Theory and Mathematic Statistics|3.0|87|3.7|
|8|Discrete Mathematics|4.0|65|2.7|
|9|Linear Algebra and Application|3.5|69|2.7|
|10|Advanced Mathematics|5.0|83|3.3|
|11|Mathematical Model(flip)|3.0|97|4.0|
|12|Mathematical Foundations of Artificial Intelligence|3.0|88|3.7|
|13|Principles of Database|2.0|95|4.0|
|14|Natural Language Processing|2.0|93|4.0|
|15|Machine Learning|2.0|81|3.0|
|16|Knowledge Engineering|2.0|97|4.0|
|17|Knowledge Graph|1.5|93|4.0|
|18|Neural Networks and Deep Learning|1.5|81.3|3.3|
|19|Speech Information Processing|2.0|88|3.7|
|20|Introduction to Computer Systems |2.0|87|3.7|
|21|Selected topics in advanced mathematics competitionof college students|2.0|93|4.0|
|22|Introduction to cognitive science|2.0|91|4.0|
|23|Introduction to Computer Systems|3.0|93|4.0|
|24|Digital Logic and Digital System|3.0|94|4.0|
|25|Python Programming and Application|2.5|86|3.7|
|26|Computer Networks|2.0|80|3.0|
|27|The Comprehensive Practice of Computer System|1.5|90|4.0|
|28|Comprehensive practice of machine learning|1.5|92.8|4.0|
|29|Comprehensive Practice Course for KnowledgeEngineering|1.5|87.4|3.7|
||**Weighted Average**||**87.31**|**3.67**|

**TOEFL Score**

<img src="images/toefl.png" width = "900" height = "170" alt="" align=center /> 
</p>

# 📝 Rescearchs 

- *2022.04 - 2023.05* Acted as Leader in Municipal College Students Innovation and Entrepreneurship Training Program， *Intelligent Visualization of the Attributes of the Global Burden of Disease*, supervised by Professor <a href='http://geoanalytics.tju.edu.cn/jieli'>Jie Li</a> and <a href='https://www.ai.pku.edu.cn/info/1140/2160.htm'>Dr. Liang Zhou</a>.
  
  In this project, We conducted a Graph Neural Network to analyze the similarity between diseases worldwide.
  1. By utilizing meta-path-related GNN to identify the correlation between diseases, converting the heterogeneous graph into an isomorphic graph, and then applying deepwalk to the isomorphic graph to obtain the representation of t-SNE dimensionality reduction visualization, a verification function can be provided.
  2. Research visualization result:

        -<a href='https://peterjiangdingyi.github.io/ghdx.github.io/DCD.html'>Graph Constructed by Meta-Path </a> \
           <img src="images/diseases.png" width = "500" height = "250" alt="" align=center />
     
        -<a href='https://peterjiangdingyi.github.io/ghdx.github.io/embed.html'>The similarity between diseases worldwide </a> \
           <img src="images/Similarity.png" width = "500" height = "250" alt="" align=center />  
    4. The edges of the project:
         (1) By using all kinds of meta-path, we can construct any arbitrary pattern to analyze topological information on the burden of diseases.
         (2) By using GNN, we can utilize the homogeneous graph derived from metapath to form embeddings to accurately analyze the similarity of diseases.
    
- *2022.04 - 2023.05* Acted as Researcher in Intelligent Fire Control Project, supervised by Professor <a href='http://cic.tju.edu.cn/faculty/yangliu/index.html'>Liu Yang</a>.
  1. In collaboration with <a href='http://www.farwide-electric.com/'>Shenzhen farwide-electric Co., Ltd (深圳弘远电气有限公司)</a>, a research project has been undertaken to explore the potential of Al in the field of hazardous fire protection, This project seeks to utilize Al technology to detect high voltage in order to preemptively control fires
  2. In this undertaking, l was responsible for the comprehensive upkeep of the system which encompasses an Al algorithm (such as SVM) and a Flask web framework, This necessitates a thorough understanding of the intricate interplay between the two components as well as the ability to identify and rectify any issues that may arise. Furthermore, I must guarantee its optimal performance (accuracy uplifted from 85% to 90%).
     
- *2023.04 - 2023.05* HKUST COMP 4901v Final Project, *Transformer-based Semantic Segmentation on 3D Point Clouds for Autonomous Driving*, supervised by Professor <a href='https://www.danxurgb.net/'> Dan XU</a>, and groupmates Martin R. Inauen, Mikhail Tsirlin.
  1. We reproduced the effort of the paper <a href='https://arxiv.org/abs/2012.09164'> Point Transformer</a> and delved into the potential of self-attention networks for self-driven related 3D point cloud processing. Our study involves understanding and using self-attention layers specifically for point clouds, which serve as fundamental building blocks for constructing self-attention networks deployed in semantic scene segmentation.
  2. <a href='https://peterjiangdingyi.github.io/transcripts.github.io/COMP4901v_Research.html'>CLICK Here to Browse Our Research Paper </a> \
             <img src="images/point.png" width = "500" height = "250" alt="" align=center /> 

     
# 🎖 Honors and Awards
- *2023.04* MCM/ICM Honorable Nomination. \
<img src="images/MA.jpg" width = "250" height = "270" alt="" align=center />  
- Coursera Deeplearning online course (Andrew Y Ngon) certification.\
<img src="images/standford_online.jpg" width = "250" height = "200" alt="" align=center />  

  
# 🔥 News
- *2023.06*: &nbsp;🔥 Start a Large Language Model internship at Frontis Ltd., Beijing!
- *2023.05*: &nbsp;🔥Complete my one-semester exchange program at HKUST!
- *2023.05*: &nbsp; Finish our college Innovative project *Intelligent Visualization of the Attributes of the Global Burden of Disease*, which has been recognized with a municipal award!
- *2023.05*: &nbsp; Achieved a full score on the final project presentation *Improvement of the state-of-the-art graph neural transformer model* for the postgraduate course *Advanced Deep Learning Architectures and their Applications* with groupmate Martin Rektoris, instructed by Dr. Qifeng Chen at HKUST!
- *2023.01*: &nbsp; Begin my exchange program at HKUST. I enrolled in AI-related courses, including the undergraduate course *Large-Scale Deep Perception, Localization, and Planning for Autonomous Vehicles* and the Postgraduate course *Advanced Deep Learning Architectures and their Applications*, *Computer Vision*.
- *2022.12*: &nbsp;🔥 Received a nomination to attend an academic exchange program at HKUST. It is an exceptional privilege to be one of the two nominees from Tianjin University!
- *2022.09*: &nbsp; Become a  research assistant of the "Intelligent Fire Protection" project led by Prof. Liu Yang at Tianjin University. In this project, I am responsible for developing AI algorithms.
- *2022.04*: &nbsp; Appointed as the leader of the "Intelligent Visualization of the Attributes of the Global Burden of Disease" innovative project, which is supervised by Dr. Jie Li.
- *2022.04*: &nbsp; Joined the Visualization Lab at Tianjin University, which is under the supervision of Dr. Jie Li.


  
