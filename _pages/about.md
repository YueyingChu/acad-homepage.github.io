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
Welcome to my academic homepage! Here you can find my [Curriculum Vitae](/_pages/Yueying_s_Resume.pdf), publications, and research interests.

I am currently a PhD candidate in Psychology at Zhejiang University, affiliated with the Center for Psychological Sciences and the Department of Psychology and Behavioral Sciences, where I am advised by Prof. [Peng Liu](https://person.zju.edu.cn/pengliu). Since 2025, I have also been a visiting PhD student at the Centre for Biomedical Ethics, National University of Singapore, supervised by Prof. [Brian D. Earp](https://www.brianearp.com) and Prof. [Julian Savulescu](https://medicine.nus.edu.sg/cbme/people_uri/julian-savulescu-bioethics/).

My current research focuses on human-LLM alignment: how large language models converge with, diverge from, or reshape human moral judgment, social evaluation, and responsibility attribution. During my PhD, I have long studied the social psychology and machine psychology of intelligent agents, including automated vehicles and large language models, with work spanning moral judgment, responsibility attribution, human-agent trust, and human-agent collaboration. Overall, my research trajectory has gradually moved from automated vehicles toward broader questions about LLMs and intelligent agents in society.

<h1 id="publications">Publications &amp; Preprints</h1>
<p class="publication-note"><sup>#</sup> These authors contributed equally to this work; <sup>*</sup> Corresponding author(s)</p>

<section class="research-direction">
  <div class="research-direction__intro">
    <h2>Human-LLM Alignment &amp; Expectations for Social AI</h2>
    <p>This line of work asks whether LLMs mirror, amplify, or diverge from human social and moral evaluations, and what people actually want from AI systems that take on social roles. Drawing on studies of blame bias against driverless cars, reactions to AI-generated creative work, and public preferences for how AI partners should behave across different relationships, it treats alignment as a psychological and relational problem: not only whether models produce accurate answers, but whether they judge, assign credit, and follow social norms in ways that people find appropriate for a machine rather than a human.</p>
  </div>

  <article class="pub-entry">
    <h3><a href="https://osf.io/preprints/psyarxiv/zt6vh_v1">People want human and AI social partners to follow different relational norms despite similar roles</a></h3>
    <p class="pub-authors">Madeline G. Reinecke, <strong>Yueying Chu</strong>, Ivar Rodríguez Hannikainen, Andreas Kappes, Sebastian Porsdam Mann, Ilina Singh, Julian Savulescu, and Brian D. Earp</p>
    <p class="pub-venue"><em>PsyArXiv</em> preprint, 2026.</p>
    <p class="pub-links"><a href="https://osf.io/preprints/psyarxiv/zt6vh_v1">Preprint</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1080/10447318.2025.2526593">Road Rage Against the Machine: Humans and LLMs Share a Blame Bias Against Driverless Cars</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong>, Peng Liu<sup>*</sup>, Julian Savulescu, and Brian D. Earp</p>
    <p class="pub-venue">In <em>International Journal of Human-Computer Interaction</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1080/10447318.2025.2526593">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.techsoc.2025.103055">Personalizing AI Art Boosts Credit, Not Beauty</a></h3>
    <p class="pub-authors">Maryam Ali Khan, Elzė Sigutė Mikalonytė, Sebastian Porsdam Mann, Peng Liu, <strong>Yueying Chu</strong>, Mario Attie-Picker, Mey Bahar Buyukbabani, Julian Savulescu<sup>*</sup>, Ivar R. Hannikainen, and Brian D. Earp<sup>*</sup></p>
    <p class="pub-venue">In <em>Technology in Society</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.techsoc.2025.103055">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://psycnet.apa.org/doi/10.1037/aca0000739">Machine Creativity: Aversion, Appreciation, or Indifference?</a></h3>
    <p class="pub-authors">Peng Liu<sup>*</sup>, <strong>Yueying Chu</strong>, Yandong Zhao, and Siming Zhai</p>
    <p class="pub-venue">In <em>Psychology of Aesthetics, Creativity, and the Arts</em>, 2025.</p>
    <p class="pub-links"><a href="https://psycnet.apa.org/doi/10.1037/aca0000739">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1111/nyas.15258">Credit and Blame for AI-Generated Content: Effects of Personalization in Four Countries</a></h3>
    <p class="pub-authors">Brian D. Earp<sup>#</sup>, Sebastian Porsdam Mann<sup>#</sup>, Peng Liu<sup>#, *</sup>, Ivar Hannikainen<sup>#, *</sup>, Maryam Ali Khan, <strong>Yueying Chu</strong>, and Julian Savulescu</p>
    <p class="pub-venue">In <em>Annals of the New York Academy of Sciences</em>, 2024.</p>
    <p class="pub-links"><a href="https://doi.org/10.1111/nyas.15258">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.xinn.2023.100449">Public aversion against ChatGPT in creative fields?</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong> and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>The Innovation</em>, 2023.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.xinn.2023.100449">DOI</a></p>
  </article>
</section>

<section class="research-direction">
  <div class="research-direction__intro">
    <h2>Intelligent Agent Moral Judgment &amp; Responsibility Attribution</h2>
    <p>This work examines how people judge intelligent agents when morally difficult decisions are involved. The studies compare expectations for humans and machines, showing that people may require similar outcomes from human and machine actors while evaluating them through different psychological standards. This thread provides the moral-psychology foundation for later work on LLMs and other intelligent agents.</p>
  </div>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.cognition.2024.106011">Morality on the road: Should machine drivers be more utilitarian than human drivers?</a></h3>
    <p class="pub-authors">Peng Liu<sup>*</sup>, <strong>Yueying Chu</strong>, Siming Zhai, Tingru Zhang<sup>*</sup>, and Edmond Awad</p>
    <p class="pub-venue">In <em>Cognition</em>, 2025.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.cognition.2024.106011">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.cognition.2023.105575">Machines and humans in sacrificial moral dilemmas: Required similarly but judged differently?</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong> and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>Cognition</em>, 2023.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.cognition.2023.105575">DOI</a></p>
  </article>
</section>

<section class="research-direction">
  <div class="research-direction__intro">
    <h2>Human-Agent Trust, Repair &amp; Collaboration</h2>
    <p>These studies focus on how humans coordinate with intelligent agents before and after errors occur. Across automated vehicles, eHMIs, anthropomorphic agents, and repair strategies such as apology, the work investigates when people trust agents, when trust breaks, and how design cues can support prosocial interaction and collaboration after failure.</p>
  </div>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1080/10447318.2026.2682916">Can External Human-Machine Interfaces Promote Human Drivers' Prosocial Intentions Toward Automated Vehicles in Mixed Traffic?</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong>, Jinglei Chen, Yunhao Cai, Zhigang Xu, and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>International Journal of Human-Computer Interaction</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1080/10447318.2026.2682916">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1177/03611981251355535">To Apologize or Not to Apologize? Trust Repair After Automated Vehicles' Mistakes</a></h3>
    <p class="pub-authors">Yunhao Cai<sup>#</sup>, <strong>Yueying Chu<sup>#</sup></strong>, Zhigang Xu, and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>Transportation Research Record</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1177/03611981251355535">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1080/10447318.2025.2607570">Can Anthropomorphic Intelligent Vehicle Agents Restore Trust in Automated Vehicles After Failures?</a></h3>
    <p class="pub-authors">Yunhao Cai<sup>#</sup>, <strong>Yueying Chu<sup>#</sup></strong>, Xiaofei Yu, Hao Tan, and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>International Journal of Human-Computer Interaction</em>, 2025.</p>
    <p class="pub-links"><a href="https://doi.org/10.1080/10447318.2025.2607570">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1109/THMS.2024.3434680">To Err is Automation: Can Trust be Repaired by the Automated Driving System After its Failure?</a></h3>
    <p class="pub-authors">Peng Liu, <strong>Yueying Chu</strong>, Guanqun Wang, and Zhigang Xu<sup>*</sup></p>
    <p class="pub-venue">In <em>IEEE Transactions on Human-Machine Systems</em>, 2024.</p>
    <p class="pub-links"><a href="https://doi.org/10.1109/THMS.2024.3434680">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1145/3744333.3747832">Examining Cross-Cultural Differences in Intelligent Vehicle Agents: Repair Strategies after Their Failures</a></h3>
    <p class="pub-authors">Lan Lan<sup>#</sup>, Yunhao Cai<sup>#</sup>, <strong>Yueying Chu</strong>, Wenting Tang, Yuchu Chen, and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>AutomotiveUI '25</em>, 2025. <strong>Best Paper Nominee</strong>.</p>
    <p class="pub-links"><a href="https://doi.org/10.1145/3744333.3747832">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1177/1071181322661390">What does that car mean? The influence of vehicle motion and symbolic patterns of LED signals on pedestrians' interpretation of a vehicle's intent</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong>, Deveshwar Hariharan, Seth Hollar, and Jing Feng<sup>*</sup></p>
    <p class="pub-venue">In <em>Proceedings of the Human Factors and Ergonomics Society Annual Meeting</em>, 2022.</p>
    <p class="pub-links"><a href="https://doi.org/10.1177/1071181322661390">DOI</a></p>
  </article>
</section>

<section class="research-direction">
  <div class="research-direction__intro">
    <h2>Automated Vehicle Safety, Acceptance &amp; Human Factors</h2>
    <p>This research examines the human side of driving automation, including how users understand imperfect automated systems, how misconceptions shape acceptance, and how human-factor risks contribute to automation-related crashes. It grounds later intelligent-agent work in concrete safety, risk perception, and technology acceptance problems.</p>
  </div>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.trf.2025.103447">Imperfect advanced driver assistance systems in the eyes of imperfect users</a></h3>
    <p class="pub-authors"><strong>Yueying Chu<sup>#</sup></strong>, Wenting Tang<sup>#</sup>, Shanguang Chen, and Peng Liu</p>
    <p class="pub-venue">In <em>Transportation Research Part F: Traffic Psychology and Behaviour</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.trf.2025.103447">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1080/00140139.2023.2210793">Automation complacency on the road.</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong> and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>Ergonomics</em>, 2023.</p>
    <p class="pub-links"><a href="https://doi.org/10.1080/00140139.2023.2210793">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1016/j.trf.2022.04.010">People with more misconceptions about automated vehicles might be more positive toward them.</a></h3>
    <p class="pub-authors">Peng Liu<sup>*</sup>, Manqing Du, Zhigang Xu, and <strong>Yueying Chu</strong></p>
    <p class="pub-venue">In <em>Transportation Research Part F: Traffic Psychology and Behaviour</em>, 2022.</p>
    <p class="pub-links"><a href="https://doi.org/10.1016/j.trf.2022.04.010">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1007/978-3-032-30798-9_17">Causation Analysis of Vehicle Driving Automation-Related Accidents</a></h3>
    <p class="pub-authors">Yunhao Cai, <strong>Yueying Chu</strong>, Yijing Zhang, Peng Liu, and Shanguang Chen</p>
    <p class="pub-venue">In <em>HCI in Mobility, Transport, and Automotive Systems</em>, 2026.</p>
    <p class="pub-links"><a href="https://doi.org/10.1007/978-3-032-30798-9_17">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.54941/ahfe1004419">Privacy Concern and Acceptability of Driver Monitoring System</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong>, Zihui Yuan, and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>AHFE 2023 Hawaii Edition</em>, 2023.</p>
    <p class="pub-links"><a href="https://doi.org/10.54941/ahfe1004419">DOI</a></p>
  </article>

  <article class="pub-entry">
    <h3><a href="https://doi.org/10.1007/978-3-031-35678-0_1">Human factor risks in driving automation crashes</a></h3>
    <p class="pub-authors"><strong>Yueying Chu</strong> and Peng Liu<sup>*</sup></p>
    <p class="pub-venue">In <em>HCI in Mobility, Transport and Automotive Systems</em>, 2023. <strong>Best Paper Award</strong>.</p>
    <p class="pub-links"><a href="https://doi.org/10.1007/978-3-031-35678-0_1">DOI</a></p>
  </article>
</section>

<h1 id="presentations-and-posters">Presentations &amp; Posters</h1>

<article class="pub-entry">
  <h3>To Apologize or Not to Apologize? Trust Repair After Automated Vehicles' Mistake</h3>
  <p class="pub-authors"><strong>Oral</strong>, January 2025</p>
  <p class="pub-venue">104th Transportation Research Board (TRB) Annual Meeting. January 5-9, 2025, Washington DC, USA.</p>
</article>

<article class="pub-entry">
  <h3>Can External Human-Machine Interfaces Promote Prosocial Intentions of Human Drivers Toward Automated Vehicles in Mixed Traffic?</h3>
  <p class="pub-authors"><strong>Poster</strong>, January 2025</p>
  <p class="pub-venue">104th Transportation Research Board (TRB) Annual Meeting. January 5-9, 2025, Washington DC, USA.</p>
</article>

<article class="pub-entry">
  <h3>Examining a dual-process model for explaining the effectiveness of trust repair in human-automation interaction</h3>
  <p class="pub-authors"><strong>Oral</strong>, August 2024</p>
  <p class="pub-venue">22nd Triennial Congress of the International Ergonomics Association (IEA) Jointly with INCOSE HSI2024 (3rd INCOSE International Conference on Human Systems Integration). August 25-29, 2024, ICC JEJU, Republic of Korea.</p>
</article>

<article class="pub-entry">
  <h3>Dynamic Trust Repair: Conceptual and Feasibility Analysis</h3>
  <p class="pub-authors"><strong>Oral</strong>, July 2024</p>
  <p class="pub-venue">15th International Conference on Applied Human Factors and Ergonomics (AHFE 2024) and the Affiliated Conferences. July 24-27, 2024, Université Côte d'Azur, Nice, France.</p>
</article>

<article class="pub-entry">
  <h3>Are large language models more rational than humans in ascribing responsibility?</h3>
  <p class="pub-authors"><strong>Oral</strong>, June 2024</p>
  <p class="pub-venue">Fourth International Workshop on Logics for New-Generation Artificial Intelligence. June 15-16, 2024, Hangzhou, China.</p>
</article>

<article class="pub-entry">
  <h3>Privacy Concern and Acceptability of Driver Monitoring System</h3>
  <p class="pub-authors"><strong>Oral</strong>, December 2023</p>
  <p class="pub-venue">2023 AHFE International Conference on Human Factors in Design, Engineering, and Computing (AHFE 2023 Hawaii Edition) Applications for Interservice and Industry. December 4-6, 2023, Waikiki Beach Marriott Resort &amp; Spa, Honolulu, Hawaii, USA.</p>
</article>

<article class="pub-entry">
  <h3>自动化自满概念：挑战与影响 (The concept of automation complacency: Challenges and implications).</h3>
  <p class="pub-authors"><strong>Oral</strong>, November 2023</p>
  <p class="pub-venue">浙江省心理学会学术年会 (Zhejiang Psychology Association Annual Meeting). November 24-26, 2023, Huzhou, China.</p>
</article>

<article class="pub-entry">
  <h3>Human Factor Risks in Driving Automation Crashes.</h3>
  <p class="pub-authors"><strong>Oral</strong>, July 2023</p>
  <p class="pub-venue">5th International Conference, MobiTAS 2023, held as part of the 25th HCI International Conference (HCII 2023). July 23–28, 2023, Copenhagen, Denmark.</p>
</article>

<h1 id="selected-honors-and-awards">Selected Honors &amp; Awards</h1>
- *2025* China Association for Science and Technology (CAST) Youth Talent Support Program for PhD Students (中国科协青年科技人才培育工程博士生专项计划)
- *2024* Zhejiang University Qiushi Xinxing Program (浙江大学求是新星培养计划)
- *2024.12* Zhejiang University Qiushi Feiying Program (NUS visiting student)
- *2022.06* Outstanding Graduates of Zhejiang University, 2022
- *2021.09* Zhejiang University Scholarship - First Prize (Top 3%) (2020-2021)
- *2020.09* Zhejiang Provincial Scholarship (2019-2020)

# Academic Service
- **Reviewer:** AI & Society, AI and Ethics, Cities, Computers in Human Behavior Reports, Ergonomics, Scientific Reports, Journal of Medical Ethics, AAAI 2026, etc.
- **Co-chair:** AHFE2024 Session 102: Interaction with Emerging Technologies II
- **Co-chair:** HCII2023 S012: Human and social sides of automated vehicles

# Education
- *2022.09 - Present*, PhD candidate, Zhejiang University, Hangzhou.
- *2025.03 - 2026.03*, Visiting PhD student, NUS, Singapore.
- *2018.09 - 2022.06*, B.S. in Psychology, Zhejiang University, Hangzhou.
