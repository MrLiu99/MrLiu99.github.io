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

Hi, I am **Xu Liu** (刘旭), a third-year Ph.D. student at the College of Computer Science, Nankai University, advised by <a href='https://ics.nankai.edu.cn/12509/list.htm'>Prof. Tao Li</a>. I am affiliated with the <a href='https://ics.nankai.edu.cn/'>Nankai Intelligent Computing System Lab</a> and the <a href='https://www.hl-it.cn/'>Haihe Lab of ITAI</a>.

My research interests include **edge computing** and **heterogeneous multi-agent systems**, with a focus on computation offloading,  adaptive model routing and multi-objective optimization. I have published 10 papers in international journals and conferences, with <a href='https://scholar.google.com/citations?hl=en&user=2v307vU77j8C'><span id='total_cit'></span> Google Scholar citations 147</a> 

Welcome to reach out to me for communication and cooperation!


# 📖 Educations

- *2024.09 - 2028.06 (expected)*, College of Computer Science, Nankai University. Ph.D. in Computer Technology. Research fields: heterogeneous multi-agent systems and adaptive model routing.

- *2021.09 - 2024.06*, School of Computer Science and Software Engineering, Tiangong University. M.Eng. in Software Engineering. Research fields: cloud-edge collaboration and task scheduling.

- *2017.09 - 2021.06*, School of Electrical Engineering and Automation, Qilu University of Technology. B.Eng. in Automation.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


<style>
.pub-tag {
  display: inline-block;
  margin-left: 4px;
  padding: 1px 6px;
  border-radius: 3px;
  color: #ffffff;
  font-size: 0.72em;
  font-weight: 700;
  line-height: 1.35;
  vertical-align: 1px;
  white-space: nowrap;
}

/* CCF-A、SCI-I */
.red {
  background-color: #d9534f;
}

/* CCF-B、SCI-II */
.blue {
  background-color: #337ab7;
}

/* CCF-C、SCI-III、SCI-IV、Non 等 */
.green {
  background-color: #5a9216;
}
</style>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMC 2025</div><img src='images/aeds.png' alt="AEDS framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AEDS: An Affinity-driven Efficient DRL-based Task Scheduling Framework for Edge Computing](https://doi.org/10.1109/TMC.2025.3608263)

**Xu Liu**, Zhaolong Jian, Xueshuo Xie, Qiankun Dong, Mulin Li, Xiaoyu Zhang, Tao Li

*IEEE Transactions on Mobile Computing (TMC), 2025.* **CCF A**


<ul style="list-style: none; padding-left: 0; margin-top: 8px;">
  <li style="margin-bottom: 6px;">▸ AEDS uses affinity-guided edge cluster selection to reduce the scheduling search space and improve decision efficiency.</li>
  <li>▸ AEDS combines offline pre-training, online fine-tuning, and task migration to adapt to dynamic edge environments.</li>
</ul>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS 2023</div><img src='images/uav.png' alt="UAV-assisted computation offloading framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-objective Deep Reinforcement Learning for Computation Offloading in UAV-assisted Multi-access Edge Computing](https://doi.org/10.1016/j.ins.2023.119154)

**Xu Liu**, Zheng-Yi Chai, Ya-Lun Li, Yan-Yang Cheng, Yue Zeng

*Information Sciences, 2023.* **SCI Q1**


<ul style="list-style: none; padding-left: 0; margin-top: 8px;">
  <li style="margin-bottom: 6px;">▸ MODRL-COP jointly optimizes task latency and energy consumption in UAV-assisted edge computing.</li>
  <li>▸ MODRL-COP combines multi-objective optimization with deep reinforcement learning to generate flexible offloading policies.</li>
</ul>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNSM 2025</div><img src='images/iiot.png' alt="Industrial IoT task offloading framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Evolutionary Multi-Objective Deep Reinforcement Learning for Task Offloading in Industrial Internet of Things](https://doi.org/10.1109/TNSM.2025.3585148)

**Xu Liu**, Zheng-Yi Chai, Yan-Yang Cheng, Ya-Lun Li, Tao Li

*IEEE Transactions on Network and Service Management (TNSM), 2025.* **SCI Q2**


<ul style="list-style: none; padding-left: 0; margin-top: 8px;">
  <li style="margin-bottom: 6px;">▸ EMDRL-ITOP jointly optimizes task latency, energy consumption, and service cost in Industrial IoT environments.</li>
  <li>▸ EMDRL-ITOP integrates evolutionary optimization with deep reinforcement learning to improve policy exploration and solution quality.</li>
</ul>

</div>
</div>

# 📚 Full Publication List

### 2025

- [AEDS: An Affinity-driven Efficient DRL-based Task Scheduling Framework for Edge Computing](https://ieeexplore.ieee.org/document/11155212), **Xu Liu**, Zhaolong Jian, Xueshuo Xie, Qiankun Dong, Mulin Li, Xiaoyu Zhang, and Tao Li, **IEEE TMC 2025** <span class="pub-tag red">CCF-A</span>

- [SmartZone: Runtime Support for Secure and Efficient On-device Inference on ARM TrustZone](https://doi.org/10.1109/TC.2025.3557971), Zhaolong Jian, **Xu Liu**, Qiankun Dong, Longkai Cheng, Xueshuo Xie, and Tao Li, **IEEE TC 2025** <span class="pub-tag red">CCF-A</span>

- [Evolutionary Multi-Objective Deep Reinforcement Learning for Task Offloading in Industrial Internet of Things](https://doi.org/10.1109/TNSM.2025.3585148), **Xu Liu**, Zheng-Yi Chai, Yan-Yang Cheng, Ya-Lun Li, and Tao Li, **IEEE TNSM 2025** <span class="pub-tag blue">SCI-II</span>

- [Task Offloading for Industrial Internet of Things Based on Evolutionary Multiobjective Multitasking Optimization](https://doi.org/10.1016/j.swevo.2024.101786), Yan-Yang Cheng, Zheng-Yi Chai, Ya-Mei Xia, **Xu Liu**, and Gao-Min Yin, **Swarm and Evolutionary Computation 2025** <span class="pub-tag red">SCI-I</span>

- [Col-TEEs: Secure and Efficient Collaborative Inference Framework in Heterogeneous TEEs](https://doi.org/10.1109/ICPADS67057.2025.11322922), **Xu Liu**, Tao Li, Zhaolong Jian, Xueshuo Xie, Mulin Li, and Gang Wang, **IEEE ICPADS 2025** <span class="pub-tag green">CCF-C</span>


### 2024

- [Evolutionary Multitasking for Multiobjective Optimization Based on Hybrid Differential Evolution and Multiple Search Strategy](https://doi.org/10.1016/j.future.2024.04.032), Ya-Lun Li, Yan-Yang Cheng, Zheng-Yi Chai, **Xu Liu**, Haole Hou, and Guoqiang Chen, **Future Generation Computer Systems 2024** <span class="pub-tag blue">SCI-II</span>

- [A Task Offloading Algorithm Using Multi-Objective Optimization under Hybrid Mode in Mobile Edge Computing](https://doi.org/10.1007/s11036-023-02272-x), Haole Hou, Zheng-Yi Chai, **Xu Liu**, Ya-Lun Li, and Yue Zeng, **Mobile Networks and Applications 2024** <span class="pub-tag green">CCF-C</span>


### 2023

- [Multi-Objective Deep Reinforcement Learning for Computation Offloading in UAV-Assisted Multi-Access Edge Computing](https://doi.org/10.1016/j.ins.2023.119154), **Xu Liu**, Zheng-Yi Chai, Ya-Lun Li, Yan-Yang Cheng, and Yue Zeng, **Information Sciences 2023** <span class="pub-tag red">SCI-I</span>

- [A Computation Offloading Algorithm Based on Multi-Objective Evolutionary Optimization in Mobile Edge Computing](https://doi.org/10.1016/j.engappai.2023.105966), Zheng-Yi Chai, **Xu Liu**, and Ya-Lun Li, **Engineering Applications of Artificial Intelligence 2023** <span class="pub-tag red">SCI-I</span>

- [Temporal Data Scheduling in Internet of Vehicles Using an Improved Decomposition-Based Multi-Objective Evolutionary Algorithm](https://ieeexplore.ieee.org/document/10026658), Ya-Lun Li, Zheng-Yi Chai, Fei Tan, and **Xu Liu**, **IEEE TITS 2023** <span class="pub-tag red">SCI-I</span>


# 💡 Interesting Repositories

### [PowerTown: A Generative Multi-Agent Community Electricity Consumption Simulation System](https://github.com/MrLiu99/PowerTown)

*Open-source Project, 2026* &nbsp;|&nbsp; [**Code**](https://github.com/MrLiu99/PowerTown)

**PowerTown** is an LLM-driven simulation system for modeling heterogeneous residential electricity consumption behaviors and evaluating demand-response strategies. It equips resident agents with memory, reflection, and planning capabilities, and connects their daily activities with device-level electricity consumption.

<ul style="list-style: none; padding-left: 0; margin-top: 8px;">
  <li style="margin-bottom: 6px;">▸ Maps natural-language activities into structured electricity consumption events containing time, device, and power information.</li>
  <li style="margin-bottom: 6px;">▸ Supports synchronous coupling and asynchronous replay for comparing resident responses under different electricity pricing strategies.</li>
  <li>▸ Simulates a localized virtual community with heterogeneous resident identities, daily routines, and energy-use preferences.</li>
</ul>

# 🎖 Honors and Awards

- *2025.10* Second Prize in the 13th National College Student Digital Media Technology Works and Creativity Competition.
- *2025.10* Nankai University Gongneng Scholarship (Second Class).
- *2024.10* Nankai University Gongneng Scholarship.
- *2024.08* Second Prize in the 8th China College IC Competition.
- *2024.08* Third Prize in the 19th China Graduate Electronics Design Contest.
- *2024.05* Outstanding Master's Graduate of Tiangong University.
- *2023.11* Second Prize in the Graduate Academic Forum of Tiangong University.
- *2023.10* National Scholarship.
- *2023.10* Tiangong University Academic Scholarship (First Class).


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- *2024.03 - 2025.07*, Research Intern, Digital Health Center, Haihe Lab of ITAI. Research on cloud-edge collaborative inference.
- *2025.08 - Present*, Research Intern, Unmanned Systems Center, Haihe Lab of ITAI. Research on coordination in heterogeneous multi-agent systems.
