---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## 👩🏻‍🎓 About Me

I am a Ph.D. candidate at the College of Computer Science and Artificial Intelligence, Fudan University, advised by Prof. Min Yang, Prof. Yuan Zhang and Prof. Lei Zhang. I was also a visiting Ph.D. student at Johns Hopkins University, advised by Prof. Yinzhi Cao.

My research is on vulnerability governance for open-source software, covering the full lifecycle: **discovery, exploitation and verification, and patching**. Methodologically, I combine static/dynamic program analysis with large language models — program analysis enumerates and prunes the candidate search space, the model performs semantic reasoning and code synthesis within that constrained space, and every result is confirmed by real execution.

Before Fudan, I received my B.Eng. from Xidian University in 2022.

## 🎓 Education

- **Fudan University**, Ph.D. in Cyberspace Security, Sep 2022 – Present
  * Advisors: Prof. Min Yang, Prof. Yuan Zhang, Prof. Lei Zhang
- **Johns Hopkins University**, Visiting Ph.D. Student, Oct 2025 – Aug 2026
  * Advisor: Prof. Yinzhi Cao
- **Xidian University**, B.Eng. in Cyberspace Security, Sep 2018 – Jun 2022

## 🔍 Research Interests

- Vulnerability Detection and Exploitation
- LLM for Security
- Software Supply Chain Security
- Program Analysis

## 📄 Publications

1. **Speak Your Dialect: Detecting Java Object Injection Gadget Chains in Third-party (De)serialization Frameworks.**  
 **Bofei Chen**, Lei Zhang, Haoran Zhao, Min Yang, Yinzhi Cao.  
To appear in the Proceedings of the IEEE Symposium on Security and Privacy (**IEEE S&P**), 2027.

2. **Patch-Guided Vulnerability Detection: Extracting Java API Security Rules via Attack-Defense Cross-Analysis.**  
 **Bofei Chen**, Shuang Liao, Lei Zhang, Chibin Zhang, Mathias Payer, Yuan Zhang.  
In Proceedings of the 35th **USENIX Security Symposium**, 2026. *(Acceptance rate: 14.0%)*

3. **Efficient Detection of Java Deserialization Gadget Chains via Bottom-up Gadget Search and Dataflow-aided Payload Construction.** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10646692)] [[Code](https://github.com/fdu-sec/JDD)] [![GitHub stars](https://img.shields.io/github/stars/fdu-sec/JDD?style=social)](https://github.com/fdu-sec/JDD)  
 **Bofei Chen**, Lei Zhang, Xinyou Huang, Yinzhi Cao, Yuan Zhang, Min Yang.  
In Proceedings of the 45th IEEE Symposium on Security and Privacy (**IEEE S&P**), 2024. *(Acceptance rate: 14.9%)*

4. **JDD: In-depth Mining of Java Deserialization Gadget Chains via Bottom-up Gadget Search and Dataflow-aided Payload Construction.** [[Briefing](https://blackhat.com/asia-25/briefings/schedule/#jdd-in-depth-mining-of-java-deserialization-gadget-chains-via-bottom-up-gadget-search-and-dataflow-aided-payload-construction-44141)]  
 **Bofei Chen**, Lei Zhang, Xinyou Huang, Yinzhi Cao, Yuan Zhang, Min Yang.  
**Black Hat Asia**, 2025. *(Top-scoring submission; officially selected as a reference example for Black Hat 2026)*

5. **LLMPort: Cross-file Patch Porting via Task Decomposition and Self-correction.** [[Paper](https://yuanxzhang.github.io/paper/LLMPort-ase25.pdf)]  
 **Bofei Chen**, Lei Zhang, Peng Deng, Nan Wang, Haoyu Xu, Mingda Guo, Yuan Zhang, Min Yang.  
In Proceedings of the 40th IEEE/ACM International Conference on Automated Software Engineering (**ASE**), 2025.

6. **Exploring Static Taint Analysis in LLMs: A Dynamic Benchmarking Framework for Measurement and Enhancement.** [[Paper](https://yuanxzhang.github.io/paper/LLMTaint-ase25.pdf)]  
Haoran Zhao, Lei Zhang, Keke Lian, Fute Sun, **Bofei Chen**, Yongheng Liu, Zhiyu Wu, Yuan Zhang, Min Yang.  
In Proceedings of the 40th IEEE/ACM International Conference on Automated Software Engineering (**ASE**), 2025.

7. **AgentCyberRange: Benchmarking Frontier AI Systems in Realistic Cyber Ranges.** [[Paper](https://arxiv.org/pdf/2606.14295)]  
Fengyu Liu, Jiarun Dai, Yihe Fan, Wuyuao Mai, Ziao Li, **Bofei Chen**, et al.  
**arXiv** preprint, 2026.

## 🛡️ Zero-day Vulnerabilities

I have discovered over 100 zero-day vulnerabilities in widely deployed open-source projects (1K+ GitHub stars) and in commercial products maintained by organizations including the Apache Software Foundation, Red Hat, Spring, Ant Group and Weibo. A selected list:

| CVE | Project | Type |
| --- | --- | --- |
| [CVE-2024-52046](https://github.com/advisories/GHSA-76h9-2vwh-w278) | [Apache MINA](https://mvnrepository.com/artifact/org.apache.mina/mina-core) (Rank 2 in Network App Frameworks on Maven) | RCE; CVSS 10.0 |
| [CVE-2023-29234](https://github.com/advisories/GHSA-6x49-w35h-wqrj) | [Apache Dubbo](https://github.com/apache/dubbo) | RCE; CVSS 9.8 |
| CVE-2025-14238 | [jBPM (Red Hat)](https://github.com/kiegroup/jbpm) | RCE; upstream of Red Hat products; acknowledged as high risk |
| [CVE-2024-7885](https://github.com/advisories/GHSA-9623-mqmm-5rcf) | [Undertow (Red Hat)](https://github.com/undertow-io/undertow) | Information Leak; CVSS 7.5 |
| CVE-2026-57611 | [Apache Commons JEXL](https://github.com/apache/commons-jexl), [Apache Hive](https://github.com/apache/hive) | RCE |
| [CVE-2026-41856](https://spring.io/security/cve-2026-41856/) | [Spring for GraphQL](https://github.com/spring-projects/spring-graphql) | Authorization Bypass; CVSS 7.5 |
| [CVE-2026-40967](https://spring.io/security/cve-2026-40967) | [Spring AI](https://github.com/spring-projects/spring-ai) | Expression Injection; CVSS 8.6 |

## 🏅 Honors and Awards

- 2025: First-Class Academic Scholarship for Doctoral Students, Fudan University
- 2024: Outstanding Doctoral Candidate Scholarship, Fudan University
- 2023 & 2024: Academic Scholarship for Doctoral Students, Fudan University
- 2023: National First Prize, 2nd "Huawei Cup" China Graduate Cybersecurity Innovation Competition (Challenge Track)
- 2022: Outstanding Graduate of Shaanxi Province (ranked 1st at the School of Cyber Engineering, Xidian University)
- 2022: 4th "Gratitude to Modern Chinese Scientists" Scholarship
- 2021: National Scholarship
- 2020: National First Prize, 14th National College Information Security Contest
- 2019: Provincial First Prize, National College Mathematics Competition

## 🎤 Academic Services

- **Reviewer**: ACM TOPS 2024
- **Shadow Reviewer**: ACM CCS 2024, IEEE S&P 2023

## 🎋 Misc

I play the Chinese bamboo flute and was a member of the Xidian University Folk Music Ensemble during my undergraduate years. I also enjoy Chinese folk dance.
