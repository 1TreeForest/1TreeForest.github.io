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

I am a third-year Ph.D. candidate in Computer Science and Engineering at The Chinese University of Hong Kong, fortunately advised by [Prof. Wei Meng](https://www.cse.cuhk.edu.hk/~wei/). Before joining CUHK, I received my B.Eng. in Cyber Science and Engineering from Sichuan University.

My research interests include LLM for Security, Program Analysis, and Web Security. Most recently, I am working on LLM-driven vulnerability detection and automated repair in large-scale codebases. My work has been published at top-tier security conferences including IEEE S&P and ACM CCS.


# 🔥 News
- *2026.03*: One paper accepted to IEEE S&P 2026.
- *2025.10*: One paper received <span style="color:#A52422; font-weight:bold;">Distinguished Paper Award</span> at ACM CCS 2025.
- *2025.03*: One paper accepted by ACM CCS 2025.
- *2024.09*: One paper accepted to IEEE S&P 2025.
- *2024.04*: One paper accepted to IEEE S&P 2024.

# 📝 Publications

- **Web Application Vulnerability Repair via Context-Aware Fault Localization and Directed Differential Fuzzing**
  <br><u>Chenlin Wang</u>, Wei Meng.
  <br>*To appear in Proceedings of the 47th IEEE Symposium on Security and Privacy (S&P)*, May 2026.
  <br>Acceptance rate: 135/1,070 = 12.6%.

- **Predator: Directed Web Application Fuzzing for Efficient Vulnerability Validation** ([paper](papers/sp25-predator.pdf)) ([code](https://github.com/cuhk-seclab/Predator))
  <br><u>Chenlin Wang</u>, Wei Meng, Changhua Luo, Penghui Li.
  <br>*In Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025.
  <br>Acceptance rate: 257/1,740 = 14.8%.

- **BACScan: Automatic Black-Box Detection of Broken-Access-Control Vulnerabilities in Web Applications** ([paper](papers/ccs25-BACScan.pdf))
  <br>Fengyu Liu, Yuan Zhang, Enhao Li, Wei Meng, Youkun Shi, Qianheng Wang, <u>Chenlin Wang</u>, Zihan Lin, Min Yang.
  <br>*Proceedings of the 2025 ACM SIGSAC Conference on Computer and Communications Security (CCS)*, 2025.
  <br>Acceptance rate: 316/2,186 = 14.5%.
  <br>🏆 <span style="color:#A52422; font-weight:bold;">Distinguished Paper Award</span>

- **Holistic Concolic Execution for Dynamic Web Applications via Symbolic Interpreter Analysis** ([paper](papers/sp24-SymPHP.pdf)) ([code](https://github.com/secureweb/symphp))
  <br>Penghui Li, Wei Meng, Mingxue Zhang, <u>Chenlin Wang</u>, Changhua Luo.
  <br>*2024 IEEE Symposium on Security and Privacy (S&P)*, 2024.
  <br>Acceptance rate: 261/1,463 = 17.8%.

- **Spotlight on Video Piracy Websites: Familial Analysis Based on Multidimensional Features** ([paper](papers/ksem22-VPW.pdf))
  <br><u>Chenlin Wang</u>, Yonghao Yu, Ao Pu, Fan Shi, Cheng Huang.
  <br>*International Conference on Knowledge Science, Engineering and Management (KSEM)*, 2022.

# 🎖 Honors and Awards
- *2025.10* <span style="color:#A52422; font-weight:bold;">Distinguished Paper Award</span>, ACM CCS 2025
- *2025.05* IEEE S&P 2025 Student Travel Grant
- *2022.12* National Scholarship (2021-2022)
- *2022.01* Chinese Modern Scientist Scholarship
- *2022.08* The First Prize in National College Student Cyber Science and Engineering Contest
- *2022.08* Innovation and Entrepreneurship Award
- *2022.09* Outstanding Graduate
- *2021.12* National Scholarship (2020-2021)

# 📖 Educations
- *2023.08 - present*, Ph.D. in Computer Science and Engineering, The Chinese University of Hong Kong, Hong Kong.
- *2018.09 - 2023.06*, B.Eng. in Cyber Science and Engineering, Sichuan University, Chengdu, China.

# 💻 Services
**Conference External Reviewer:**
<br>The Web Conference (2024, 2025, 2026)
<br>ACM CCS (2023, 2024, 2025)
<br>USENIX Security (2025)
<br>IEEE S&P (2023, 2024)

**Journal External Reviewer:** Science of Computer Programming (2024)

**Teaching Assistant@CUHK:** CSCI 4130 (2025 Spring, 2026 Spring), ENGG 5105 (2024 Fall), CSCI 4140 (2024 Spring), CSCI 1130A (2023 Fall)