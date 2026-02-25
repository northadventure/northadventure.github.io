---
layout: default
---

<div id="time-message"></div>
<script>
  const hour = new Date().getHours();
  let message = "";
  if (hour < 12 && hour >= 6) {
    message = "Good Morning!";
  } else if (hour < 18 && hour >= 12) {
    message = "Good Afternoon!";
  } else {
    message = "Good Evening!";
  }
  document.getElementById("time-message").innerText = message;
</script>

I am a **Ph.D. candidate** in the **Interdiscimplinary Program in Artificial Intelligence** at **Seoul National University**.
I have been a member of the **[Biointelligence Lab](https://bi.snu.ac.kr/)** since 2020, under the supervision of **[Prof. Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html)**.

### Research Focus
My research focuses on **Reinforcement Learning (RL)**, with specific expertise applied across following domains:

* 🤖 **Robotic Locomotion & Manipulation**
* 🎨 **Visual Arts**
* ⚔️ **Multi-agent Military Combat & Tactics**
* 🧠 **Cognitive Insights for RL Enhancement**

I am currently focusing on my dissertation, proposing a generalized framework for desired-state-based reinforcement learning to broaden the scope of application and the practical utility of RL.

### Education

<h4 class="education">
  <i class="material-icons md-18">account_balance</i>
  <a href="http://en.snu.ac.kr/" target="_blank">Seoul National University</a>, Republic of Korea
  <sup>2022.09. - Present</sup>
</h4>

- Ph.D. candidate in [Interdiscimplinary Program in Artificial Intelligence](https://gsai.snu.ac.kr/)
- Cumulative GPA: 3.68 / 4.3 (3.88 / 4.5)
- Advisor: **[Prof. Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html)**

<h4 class="education">
  <i class="material-icons md-18">account_balance</i>
  <!-- <i class="material-icons md-18">handyman</i> -->
  <a href="http://en.snu.ac.kr/" target="_blank">Seoul National University</a>, Republic of Korea
  <sup>2020.03. - 2022.08.</sup>
</h4>

- M.S. student in [Interdisciplinary Program in Cognitive Science](https://cogsci.snu.ac.kr/)
- Cumulative GPA: 4.12 / 4.3 (4.32 / 4.5)
- Advisor: **[Prof. Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html)**

<h4 class="education">
  <i class="material-icons md-18">school</i>
  <a href="https://www.khu.ac.kr/eng/user/main/view.do" target="_blank">Kyunghee University</a>, Republic of Korea
  <sup>2016.03 - 2020.02</sup>
</h4>

- B.S. in [Computer Science and Engineering](https://ce.khu.ac.kr/ce/user/main/view.do)
- Cumulative GPA: 3.68 / 4.3 (3.97 / 4.5)


<div class="publications-list" markdown="1">

### Publications
- **Exponential Increase in Rewards Boosts Reinforcement Learning** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
(Under review)

- **Climb with SHERPA: Heuristic-Guided Reinforcement Learning via Segmented Experience Relay** <br/>
Minji Kim, **Ganghun Lee**, Minsu Lee, Byoung-Tak Zhang <br/>
RA-L 2026

- **Recency-Biased Sampling for Up-to-Date Adaptation of Reinforcement Learning** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2025 (<span style="color: #0056b3; font-weight: bold;">Best paper award</span>)
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE12577574" target="_blank">[pdf]</a>

- **Truncated Gaussian Policy for Debiased Continuous Control** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
AAAI 2025 (<span style="color: #0056b3; font-weight: bold;">Oral presentation</span>)
<a class="code" href="https://ojs.aaai.org/index.php/AAAI/article/view/33988" target="_blank">[pdf]</a>

- **Heuristic Action Cycle Reinforcement Learning** <br/>
Minji Kim, **Ganghun Lee**, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2025
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE12577576" target="_blank">[pdf]</a>

- **Truncated Gaussian Policy Gradient for Bounded Continuous Action Space** <br/>
**Ganghun Lee**, Minji Kim, Byoung-Tak Zhang <br/>
KCC 2024
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11861958" target="_blank">[pdf]</a>

- **Bottleneck-Aware Linear Augmentation for Robotic Imitation Learning** <br/>
Minji Kim, **Ganghun Lee**, Hyunseo Kim, Minsu Lee, Byoung-Tak Zhang <br/>
KCC 2024
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11862161" target="_blank">[pdf]</a>

- **Neural Collage Transfer: Artistic Reconstruction via Material Manipulation** <br/>
**Ganghun Lee**, Minji Kim, Yunsu Lee, Minsu Lee, Byoung-Tak Zhang <br/>
ICCV 2023
<a class="code" href="https://openaccess.thecvf.com/content/ICCV2023/papers/Lee_Neural_Collage_Transfer_Artistic_Reconstruction_via_Material_Manipulation_ICCV_2023_paper.pdf" target="_blank">[pdf]</a>
<a class="code" href="https://github.com/northadventure/CollageRL" target="_blank">[github]</a>

- **Defiant Policy Learning for Efficient Exploration in Reinforcement Learning** <br/>
**Ganghun Lee**, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2023
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11705331" target="_blank">[pdf]</a>

- **H2RL: Transferring Heuristic Knowledge to a Reinforcement Learning Agent for Solving the Online 3D Bin Packing Problem** <br/>
Minji Kim<sup>†</sup>, **Ganghun Lee**<sup>†</sup>, Minsu Lee, Byoung-Tak Zhang <br/>
ICRA 2023 Workshop (<span style="color: #0056b3; font-weight: bold;">Spotlight</span>)
<a class="code" href="https://transferabilityinrobotics.github.io/icra2023/spotlight/TRW08_abstract.pdf" target="_blank">[pdf]</a>

- **Multi-Agent Reinforcement Learning for Cover Tactics in SMAC Environment** <br/>
Yesol Park, **Ganghun Lee**, Yunsu Lee, Junseok Park, Byoung-Tak Zhang <br/>
KSC 2023
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11705319" target="_blank">[pdf]</a>

- **From Scratch to Sketch: Deep Decoupled Hierarchical Reinforcement Learning for Robotic Sketching Agent** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
ICRA 2022
<a class="code" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9811858" target="_blank">[pdf]</a>

- **Reinforcement Learning with Heuristics for Buffer-Utilized Random Bin Packing Problem** <br/>
Minji Kim, **Ganghun Lee**, Byoung-Tak Zhang <br/>
Journal of Logistics Science & Technology (JLST) 2022 (<span style="color: #0056b3; font-weight: bold;">Best paper award</span>)
<a class="code" href="https://koreascience.kr/article/JAKO202331061232757.page" target="_blank">[pdf]</a>

- **Deep Reinforcement Learning for Stroke-Conditioned Auto-Painting** <br/>
**Ganghun Lee**, Minsu Lee, Byoung-Tak Zhang <br/>
KCC 2022
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11113528" target="_blank">[pdf]</a>

- **Reset-free Multi-agent Reinforcement Learning Using Reversibility Estimation** <br/>
Minji Kim, **Ganghun Lee**, Byoung-Tak Zhang <br/>
KCC 2022
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11113610" target="_blank">[pdf]</a>

- **Toddler-Guidance Learning: Impacts of Critical Period on Multimodal AI Agents** <br/>
Junseok Park, Kwanyoung Park, Hyunseok Oh, **Ganghun Lee**, Minsu Lee, Youngki Lee, Byoung-Tak Zhang <br/>
ICMI 2021
<a class="code" href="https://dl.acm.org/doi/pdf/10.1145/3462244.3479932" target="_blank">[pdf]</a>

- **Response Analysis of Deep Neural Networks to Optical Illusion Video** <br/>
**Ganghun Lee**, Kibeom Kim, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2021
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11035857" target="_blank">[pdf]</a>

- **Diverged Episodic Memory-based Self-Supervised Policy Learning** <br/>
**Ganghun Lee**, Kibeom Kim, Dong-sig Han, Byoung-Tak Zhang <br/>
KCC 2021, KIISE 2023 (<span style="color: #0056b3; font-weight: bold;">Best paper award</span>)
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11214553" target="_blank">[pdf]</a>

- **Model-Based Curriculum Reinforcement Learning for Continuous Line Drwaing** <br/>
**Ganghun Lee**, Minji Kim, Byoung-Tak Zhang <br/>
KCC 2021
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10583172" target="_blank">[pdf]</a>

- **Deep Reinforcement Learning for Image-Based Target Trajectory Decomposition** <br/>
**Ganghun Lee**, Byoung Tak Zhang <br/>
The Korea Institute of Military Science and Technology (KIMST 2021)

- **Reset-free Competitive reinforcement learning to learn robotic manipulation skills** <br/>
Minji Kim, **Ganghun Lee**, Kibeom Kim, Minsu Lee, Byoung-Tak Zhang <br/>
KCC 2021
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10583176" target="_blank">[pdf]</a>

- **Reward-based Contrastive Learning for Generalization in Deep Reinforcement Learning** <br/>
Inwoo Hwang, HoJoon Song, Dong-sig Han, **Ganghun Lee**, Byoung-Tak Zhang <br/>
KCC 2021
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10583178" target="_blank">[pdf]</a>

- **Evolved Intrinsic Motivation for Fully Autonomous Reinforce Learning** <br/>
**Ganghun Lee**, Byoung-Tak Zhang <br/>
KSC 2020
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10529765" target="_blank">[pdf]</a>

- **Multi-robot Map Merging with Pose Estimation and Image Generation based on Neural Network** <br/>
Jaein Kim, Hyundo Lee, **Ganghun Lee**, Yoonsung Kim, Dong-sig Han, Byoung-Tak Zhang <br/>
KSC 2020
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10529744" target="_blank">[pdf]</a>

- **Query-Based Zero-Shot Detection** <br/>
HoJoon Song<sup>†</sup>, **Ganghun Lee**<sup>†</sup>, Byoung-Tak Zhang <br/>
KCC 2020
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09874614" target="_blank">[pdf]</a>

- **Resolving Data Interoperability in Ubiquitous Health Profile Using Semi-Structured Storage and Processing** <br/>
Fahad Ahmed Satti, Wajahat Ali Khan, **Ganghun Lee**, Asad Masood Khattak, Sungyoung Lee <br/>
ACM/SIGAPP SAC 2019
<a class="code" href="https://dl.acm.org/doi/pdf/10.1145/3297280.3297354" target="_blank">[pdf]</a>

- **Student to Teacher: Repeated Model Compression Through Reproducing Over the Shoulder Learning** <br/>
**Ganghun Lee**, Sungho Bae <br/>
KSC 2019 Undergraduate Session (**Best paper award**)
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09302009" target="_blank">[pdf]</a>

- **A New YouTube View Count Prediction Method using DeepAudio-Video Multimodal Learning** <br/>
Haeyeon Park, **Ganghun Lee**, Yeonwoo Jang, Hyeongseok Kim, Sungho Bae <br/>
KCC 2019 Undergraduate Session
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE08763702" target="_blank">[pdf]</a>

- **Design and Implementation of OTP-based Digital Door Lock System** <br/>
**Ganghun Lee**, Seongbeom Hong, Jinsung Cho <br/>
KSC 2017 Undergraduate Session
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE07322784" target="_blank">[pdf]</a>

</div>

### Experiences
<div class="experiences">

  <h4 class="exp-title">
    <i class="material-icons md-18">military_tech</i>
    Professional Research Personnel, Republic of Korea
    <sup> 2024.09. - 2027.08. (expected) </sup>
  </h4>
  <div class="exp-details" style="margin-left: 25px; margin-top: -15px; margin-bottom: 20px;">
    - <a class="code" href="https://bi.snu.ac.kr/" target="_blank">Biointelligence Lab</a>, Seoul National University<sup> 2024.09. - 2026.08. (expected) </sup><br/>
    <div style="margin-top: 5px; color: #d9534f; font-weight: 500;">
      <em>* Seeking at least 1-year research/industry position for the final year of service (Sep 2026 – Aug 2027).</em>
    </div>
  </div>

  <h4 class="exp-title">
    <!-- <i class="material-icons md-18">location_searching</i> -->
    <!-- <i class="material-icons md-18">center_focus_weak</i> -->
    <i class="material-icons md-18">gps_fixed</i>
    <!-- <i class="material-icons md-18">track_changes</i> -->
    <!-- <i class="material-icons md-18">radar</i> -->
    National Defense R&D Project 
    <span style="font-weight: 400; font-size: 14px;">with</span>
    <a href="https://www.hyundai-rotem.co.kr/ko/main/index.do" target="_blank">Hyundai Rotem</a>
    <sup> 2023 - Present </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Co-Lead Student Researcher</div>
    <div style="flex: 0 0 100%;">- RL-based multi-agent tactical algorithm development for tanks</div>
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">flight</i>
    National Defense R&D Project 
    <span style="font-weight: 400; font-size: 14px;">with</span>
    <a href="https://www.koreaaero.com/KO/" target="_blank">Korea Aerospace Industries (KAI)</a>
    <sup> 2024 - 2025 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Lead Student Researcher</div>
    <div style="flex: 0 0 100%;">- RL-based multi-agent mission execution and tactical engagement for aircraft</div>
    <!-- <div style="flex: 0 0 100%;">- RL-based multi-agent tactical algorithm development for aircraft</div> -->
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">science</i>
    Government-Funded Project (NRF)
    <sup> 2021 - 2025 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Student Researcher</div>
    <div style="flex: 0 0 100%;">- Participated in RL-focused research initiatives</div>
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">precision_manufacturing</i>
    Early Team Member at <a href="https://tommoro.ai/" target="_blank">Tommoro Robotics</a>
    <sup> 2022 - 2023 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Robot AI Scientist</div>
    <div style="flex: 0 0 100%;">- Sim2Real logistics project using robotic arms</div>
  </div>

  <h4 class="exp-title">
    <!-- <i class="material-icons md-18">model_training</i> -->
    <i class="material-icons md-18">schema</i>
    Research Intern at <a href="https://surromind.ai/" target="_blank">Surromind</a>
    <sup> 2021 - 2023 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- AI Engineer</div>
    <div style="flex: 0 0 100%;">- MLOps platform development</div>
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">local_laundry_service</i>
    Industry–Academia Collaborative Research Project
    <span style="font-weight: 400; font-size: 14px;">with</span>
    <a href="https://www.lge.co.kr/home" target="_blank">LG Electronics</a>
    <sup> 2020 - 2021 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Student Researcher</div>
    <div style="flex: 0 0 100%;">- Laundry appliance user behavior analysis</div>
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">scatter_plot</i>
    National Defense R&D Project (BMRR)
    <sup> 2020 - 2021 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Student Researcher</div>
    <div style="flex: 0 0 100%;">- 6D pose estimation model development</div>
  </div>

  <h4 class="exp-title">
    <i class="material-icons md-18">child_care</i>
    Government-Funded Project (BabyMind)
    <sup> 2020 - 2021 </sup>
  </h4>
  <div class="exp-details">
    <div style="flex: 0 0 100%;">- Student Researcher</div>
    <div style="flex: 0 0 100%;">- NeurIPS 2020 workshop organization</div>
  </div>

</div>

### Awards & Scholarships
- **Grand Prize at 2025 Demo Competition**, Seoul National University, 2025
- **AAAI 2025 Oral Presentation**, 2025
- **KSC 2025 Best Paper Award**, 2025
- **ICRA 2023 Workshop Spotlight Presentation**, 2023
- **Best Paper Award**, Journal of Logistics Science & Technology, 2022
- **KCC 2021 Best Paper Award**, 2021
- **Academic Excellence Scholarship**, Seoul National University, 2020, 2021
- **KSC 2019 Undergraduate Paper Award** (Encouragement Award), 2019
- **KTB Startup Competition** (Encouragement Award), 2019
- **TOPCIT Excellence Scholarship**, Kyunghee University, 2019
- **Leadership & Activity Scholarship**, Kyunghee University, 2019
- **Programming Contest** (Encouragement Award), Kyunghee University, 2018
- **Academic Excellence Scholarship**, Kyunghee University, 2016, 2017, 2019

