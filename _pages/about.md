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


I am studying for a doctorate at the University of the Chinese Academy of Sciences. <br/>
I am currently working on multilingual large language model training, multilingual machine translation, and zero-shot learning. If you are seeking any form of academic cooperation, please feel free to email me: lukaiwen20@mails.ucas.ac.cn <br/>
I graduated from Xinjiang University with a bachelor's degree and am currently studying for a PhD at the <a href="https://www.ucas.edu.cn/">University of Chinese Academy of Sciences (中国科学院大学)</a>, advised by <a href="https://people.ucas.edu.cn/~yangyating">Yating Yang (杨雅婷)</a>.<br/>
My research interest includes machine translation, large language models and low-resource language processing. I have published several papers at the top international AI conferences and periodical such as WWW, COLING and TALLIP.<br/>
 <a href='https://scholar.google.com.hk/citations?user=pfroRUEAAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。 


<span class='anchor' id='-xl'></span>

# 🎓 Educations
- *2016.09 - 2020.06*,  <a href="https://www.xju.edu.cn/"><img class="png" src="/images/xju32.png" width="15pt"></a> Xinjiang University, Bachelor.
- *2020.09 - Present*, <a href="https://www.ucas.edu.cn/"><img class="png" src="/images/ucas32.png" width="15pt"></a>University of Chinese Academy of Sciences, Ph.D. Candidate.
 
<span class='anchor' id='-lwzl'></span>


<span class='anchor' id='-xll'></span>

# 🔥 News
- *2025.01*: 🎉 Our paper has been accepted by WWW 2025
- *2024.12*: 🎉 Our paper has been accepted by COLING 2025
- *2024.09*: 🎉 Our paper has been accepted by CCMT 2024
- *2024.08*: 🎉 Our paper has been accepted by NLPCC 2024
- *2023.07*: 🎉 Our paper has been accepted by TALLIP

 
<span class='anchor' id='-lwzll'></span>



<h1 id="-publications">📝 Publications</h1>
<!-- # 📝 Publications -->
<!-- <h2 id="-speech-synthesis">🎙 Speech Synthesis</h2> -->



<div class="paper-box"><div class="paper-box-image"><div><div class="badge">WWW 2025</div><img src="images/www.svg" alt="sym" width="100%"></div></div>
<div class="paper-box-text">

  <p><a href="https://openreview.net/pdf?id=AegCFewVum">M<sup>2</sup>-VLP: Enhancing Multilingual Vision-Language Pre-Training via Multi-Grained Alignment</a> <br>
Ahtamjan Ahmat, Lei Wang, Yating Yang, Bo Ma, Rui Dong, <strong>Kaiwen Lu</strong>, Rong Ma, Xinyue Wang</p>
  <ul>
      <li>In this work, we propose a unified multi-grained contrastive learning paradigm.</li>
       <!-- <li><strong>Academic Impact</strong>: This work has won excellent posters from CIPS-LMG2024 and was reported by <a href="https://mp.weixin.qq.com/s/rZ8rcVA4OK5DcbDMnsMANg">CIPS</a>.</li> -->
    </ul>
  </div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">COLING 2025</div><img src="images/CONLIG2025.svg" alt="sym" width="100%"></div></div>
<div class="paper-box-text">

  <p><a href="https://aclanthology.org/2025.coling-main.559/">Low-Resource Language Expansion and Translation Capacity Enhancement for LLM: A Study on the Uyghur</a> <br>
<strong>Kaiwen Lu</strong>, Yating Yang , Fengyi Yang, Rui Dong, Bo Ma,Ahtamjan Ahmat, Abibilla Atawulla, Lei Wang, Xi Zhou</p>
  <ul>
      <li>In this work, we have expanded LLama's support for Uyghur and enhanced its translation capabilities</li>
       <li><strong>Academic Impact</strong>: This work has won excellent posters from CIPS-LMG2024 and was reported by <a href="https://mp.weixin.qq.com/s/rZ8rcVA4OK5DcbDMnsMANg">CIPS</a>.</li>
    </ul>
  </div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CCMT 2024</div><img src="images/ccmt.svg" alt="sym" width="100%"></div></div>
<div class="paper-box-text">

  <p><a href="http://sc.cipsc.org.cn/mt/conference/2024/schedule/">基于迭代领域知识蒸馏的 K 近邻检索增强机器翻译</a> <br>
 张驰锐, 杨雅婷, 陈奕都, <strong>鲁凯文</strong>, 董瑞, 马博, 王磊</p>
  <ul>
      <li>In this work, we propose a search-enhanced machine translation method based on domain knowledge distillation</li>
       <!-- <li><strong>Academic Impact</strong>: This work has won excellent posters from CIPS-LMG2024 and was reported by <a href="https://mp.weixin.qq.com/s/rZ8rcVA4OK5DcbDMnsMANg">CIPS</a>.</li> -->
    </ul>
  </div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">NLPCC 2024</div><img src="images/nlpcc.svg" alt="sym" width="100%"></div></div>
<div class="paper-box-text">

  <p><a href="https://link.springer.com/chapter/10.1007/978-981-97-9437-9_22">Pruning Residual Networks in MNMT to Improve Zero-shot Translation</a> <br>
<strong>Kaiwen Lu</strong>, Yating Yang , Rui Dong, Bo Ma, Lei Wang, Xi Zhou, Ahtamjan Ahmat</p>
  <ul>
      <li>In this work, we propose a residual network pruning method to improve the performance of zero-shot translation directions in multilingual machine translation.</li>
       <!-- <li><strong>Academic Impact</strong>: This work has won excellent posters from CIPS-LMG2024 and was reported by <a href="https://mp.weixin.qq.com/s/rZ8rcVA4OK5DcbDMnsMANg">CIPS</a>.</li> -->
    </ul>
  </div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">TALLIP</div><img src="images/tallip.svg" alt="sym" width="100%"></div></div>
<div class="paper-box-text">

  <p><a href="https://dl.acm.org/doi/10.1145/3610289">WAD-X: Improving Zero-shot Cross-lingual Transfer via Adapter-based Word Alignment</a> <br>
Yating Yang , Rui Dong, Bo Ma, Rui Dong, <strong>Kaiwen Lu</strong>, Lei Wang</p>
  <ul>
      <li>In this work, we train an adapter using word alignment data and use this adapter to improve the model's performance on cross-language tasks.</li>
       <!-- <li><strong>Academic Impact</strong>: This work has won excellent posters from CIPS-LMG2024 and was reported by <a href="https://mp.weixin.qq.com/s/rZ8rcVA4OK5DcbDMnsMANg">CIPS</a>.</li> -->
    </ul>
  </div>
</div>


<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2015.11* 获得 第十四届“挑战杯”全国大学生课外学术科技作品竞赛 `一等奖`  
- *2015.06* 获得 第十三届“挑战杯”四川大学生课外学术科技作品竞赛 `一等奖`
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  

<span class='anchor' id='-xshy'></span>

# 🏛️ Academic Conferences
- *2025.01.24*, The 31st International Conference on Computational Linguistics, Abu Dhabi, UAE, Oral
- *2024.11.03*, CCF International Conference on Natural Language Processing and Chinese Computing, Hangzhou, China, Poster
- *2023.10.19*, The 19th China Conference on Machine Translation, Jinan, China，Technical Director for Evaluation Task
- *2022.08.06*, The 18th China Conference on Machine Translation, Lhasa, China，Technical Director for Evaluation Task

<span class='anchor' id='-gzsx'></span>

# 💻 工作实习
- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉
