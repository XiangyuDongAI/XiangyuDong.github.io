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

<style>
.scrollable-box {
  overflow: auto;         
  max-width: 100%;        
  max-height: 200px;     
  scrollbar-width: thin;  
  padding: 8px;           

}

.scrollable-box ul {
  white-space: nowrap;
  margin: 0;
  padding-left: 25px; 
  display: inline-block;
}

.scrollable-box li {
  display: list-item;
  list-style-type: disc; 
  margin-bottom: 8px;
}

.scrollable-box a {
  color: #0066cc;
  text-decoration: underline;
}
</style>

<span class='anchor' id='about-me'></span>

I am an Embodied AI student researcher currently working at Northeastern University (Foshan), under the supervision of Professor [Xiaoguang Ma](http://www.ise.neu.edu.cn/2021/0909/c6131a202809/page.htm). Recently, I am focusing on research in Agentic UAVs. Prior to this, I received my Master's degree in Electronic Information from Zhejiang University of Technology in June 2024, where my work was dedicated to developing visual Simultaneous Localization and Mapping (vSLAM) algorithms for ground mobile robots to achieve visual navigation in dynamic scenes.

More about me: [Email](dxy1999ai@163.com) / [Google Scholar](https://scholar.google.com/citations?hl=en&user=uvRv17YAAAAJ&view_op=list_works&sortby=pubdate) / [Github](https://github.com/YourUsername) / [Curriculum Vitae](https://example.com/your-cv.pdf)

Feel free to contact me by email if you are interested in discussing or collaborating with me.

# 📚 Research Vision
My current research focuses on developing self-improving / self-evolving embodied navigation agents, and exploring their applications in aerial and ground robots. In the long run, my research vision is to build an embodied agent that can autonomously perceive, make decisions, and learn continuously like humans. To achieve this, I primarily focus on:
- Language-driven visual navigation (e.g., VLN and ObjectNav).
- Large foundation models (e.g., LLMs and VLMs) and their training techniques.
- Lifelong learning of LLM / VLM-powered agents.
- Vision-Language-Action models and their applications.

# 🔥 News
<div class="scrollable-box">
  <ul>
    <li> 2025.07: &nbsp;🎉🎉 Our work “<a href="https://arxiv.org/pdf/2507.13152" target="_blank">SE-VLN</a>” was unveiled on Arxiv! <a href="https://mp.weixin.qq.com/s/N45mBZE4OD5KmvyJka8N6g?scene=1&click_id=101" target="_blank">[视觉语言导航]</a></li>
    <li> 2025.06: &nbsp;🎉🎉 One national invention patent on <a href="https://kns.cnki.net/kcms2/article/abstract?v=pkeuivz917UQpMHd6x69ed_Qw1HzLZ-AkE2PaeUWZpFKFtQG3IacdRt0HQx8Nr7oY9ChzJVekWrUf3wQEZ7v10MSNaFDERyQKVNz9nTWaZiSEBiyqGXo_nVme1EWem3PiAzrK0RTmwocxQBlnxtkX7P2otC0BYiFZ9pORJa27TT1h9QsLoKYLA==&uniplatform=NZKPT&language=CHS" target="_blank">visual SLAM</a> was authorized!</li>
    <li> 2024.09: &nbsp;🎉🎉 One paper was accepted to Chinese Journal of Sensors and Actuators about visual SLAM!</li>
    <li> 2024.06: &nbsp;🎉🎉 I obtained my Master's degree from Zhejiang University of Technology!</li>
    <li> 2024.05: &nbsp;🎉🎉 I joined Professor Xiaoguang Ma's laboratory!</li>
    <li> 2024.03: &nbsp;🎉🎉 One paper was accepted to IEEE DDCLS 2024 about visual SLAM!</li>
    <li> 2023.05: &nbsp;🎉🎉 I gave an oral presentation on visual SLAM at IEEE DDCLS 2023!</li>
    <li> 2022.04: &nbsp;🎉🎉 One national invention patent on <a href="https://kns.cnki.net/kcms2/article/abstract?v=pkeuivz917XIPC1JzKS2rusJXnurxx2O3BZw5H2ecyZ7V-BYtJP0_2R4mg6Mc60sYOpnkNY_psG960fkV4nl-Y9Z-gXP7zVASRQIACLmgYLfaE9TRQXzusPt33_gd91HpdmInvY4vBNtR7xBi_ojRR3wnaE05-D-bVkTVy4RnLRZOebl6mcrew==&uniplatform=NZKPT&language=CHS" target="_blank">unmanned boats</a> was authorized!</li>
    <li> 2021.06: &nbsp;🎉🎉 I obtained my Bachelor's degree from Nantong University!</li>
    <li> 2021.05: &nbsp;🎉🎉 Our UAV project successfully passed the conclusion assessment!</li>
    <li> 2020.05: &nbsp;🎉🎉 Our unmanned boat project successfully passed the conclusion assessment!</li>
    <li> 2019.05: &nbsp;🎉🎉 Our unmanned boat work was selected for the Jiangsu Provincial College Students' Science and Technology Innovation Achievement Exhibition!</li>
    <li> 2019.05: &nbsp;🎉🎉 I presided over a National Undergraduate Training Program for Innovation and Entrepreneurship project on unmanned aerial vehicles (UAVs).</li>
    <li> 2019.05: &nbsp;🎉🎉 I participated in a National Undergraduate Training Program for Innovation and Entrepreneurship project on unmanned boats.</li>
    <li> 2018.10: &nbsp;🎉🎉 I joined the Intelligent Transportation Laboratory, supervised by Professor <a href="https://jttm.ntu.edu.cn/2020/0922/c5249a151941/page.htm" target="_blank">Shi Quan</a>!</li>
  </ul>
</div>

# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/se-vln.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SE-VLN: A Self-Evolving Vision-Language Navigation Framework Based on Multimodal Large Language Models](https://arxiv.org/abs/2507.13152)

__Xiangyu Dong *__, Haoran Zhao *, Jiang Gao, Haozhou Li, Xiaoguang Ma <sup>†</sup>, Yaoming Zhou <sup>†</sup>, Fuhai Chen, Juan Liu, Submitted to AAAI 2026.

[**Introduction**]((https://example.com/paper1)) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We drew inspiration from the evolution capabilities of natural agents, and proposed a self-evolving VLN framework (SE-VLN) to endow VLN agents with the ability to continuously evolve during testing. To the best of our knowledge, it was the first time that an multimodal LLM-powered self-evolving VLN framework was proposed.
</div>
</div>
- [Boosting LLM-Powered Agentic UAVs via Reflective Self-Learning for Language-Goal Aerial Navigation](https://example.com/paper1), Haoyu Tong, __Xiangyu Dong__, Xiaoguang Ma <sup>†</sup>, Submitted to IEEE RAL 2025.
- [PM-Nav: Prior-Map Guided Embodied Navigation in Functional Buildings](https://example.com/paper1), Jiang Gao *, __Xiangyu Dong *__, Haozhou Li, Haoran Zhao, Yaoming Zhou, Xiaoguang Ma <sup>†</sup>, Submitted to ICRA 2026.
- [MR-VLN: Towards Continual Vision-and-Language Navigation via Multimodal Memory and Retrieval](https://example.com/paper1), Haozhou Li, __Xiangyu Dong__, Xiaoguang Ma <sup>†</sup>, Submitted to ICRA 2026.
- [Dual Multi-modal Incremental Learning with Class-individual Memory](https://example.com/paper1), Fuhai Chen <sup>†</sup>, __Xiangyu Dong__, Xiaoguang Ma, Submitted to AAAI 2026. 
- [SEMA-VLN: A Self-Evolving Multi-Agent Vision-Language Navigation Framework Based on Foundation Models](https://example.com/paper1), __Xiangyu Dong__, Jiang Gao, Haozhou Li, Xiaoguang Ma <sup>†</sup>, Wei Meng, Zhengtao Hu, IEEE RAL, 2025, under review.

(co-first authors: *, corresponding authors: †)

# 🎖 Honors and Awards
- *2023*: Second-Class Academic Scholarship, Zhejiang University of Technology.
- *2022*: First-Class Academic Scholarship, Zhejiang University of Technology.
- *2022*: Second Prize in the East China Division, China Graduate Electronic Design Competition.
- *2021*: Freshman Scholarship, Zhejiang University of Technology.
- *2021*: Excellent Undergraduate Graduation Thesis, Nantong University.
- *2021*: Outstanding Student, School of Transportation and Civil Engineering, Nantong University.
- *2019*: First Prize in the East Division, National College Student Embedded Chip and System Design Competition.
- *2019*: Second Prize, Jiangsu Provincial "Internet +" College Student Innovation and Entrepreneurship Competition. 
- *2019*: Second Prize, Nantong University "Internet +" College Student Innovation and Entrepreneurship Competition. 

# 📖 Educations
- *2021.09 - 2024.06*: Master, College of Information Engineering, Zhejiang University of Technology, Hangzhou, China. 
- *2017.09 - 2021.06*: Bachelor, School of Transportation and Civil Engineering, Nantong University, Nantong, China. 

# 💬 Reports
- *2023.05*: “A Robust Visual SLAM Based on Key Point Instantaneous Rate Identification in Dynamic Environments”, 2023 IEEE 12th Data Driven Control and Learning Systems Conference (DDCLS). 

# 💻 Internships
- *2025.05 - Present*: [Tianmushan Laboratory](https://www.tmslab.cn/), co-supervisor: Professor [Yaoming Zhou](https://shi.buaa.edu.cn/zhouyaoming/zh_CN/index.htm).
- *2024.05 - Present*: [Northeastern University](http://www.fsgraduate.neu.edu.cn/), supervisor: Professor [Xiaoguang Ma](http://www.ise.neu.edu.cn/2021/1108/c6151a206223/page.htm).

# 🛠 Social Services
- Reviewer: The 40th Annual AAAI Conference on Artificial Intelligence (AAAI 2026).
