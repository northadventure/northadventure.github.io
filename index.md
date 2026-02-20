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

My research focuses on **Reinforcement Learning (RL)**, with specific expertise applied across diverse domains, including optimization of
(i) robotic locomotion & manipulation, 
(ii) visual arts, 
(iii) multi-agent military combat & tactics, 
and (iv) enhancing RL capability through cognitive insights.

I am currently focusing on my dissertation, proposing a generalized framework for desired-state-based reinforcement learning to broaden the scope of application and the practical utility of RL.


### Education

<h4 class="education">
  <i class="material-icons md-18">account_balance</i>
  <a href="http://en.snu.ac.kr/">Seoul National University</a>, Republic of Korea
  <sup>2022.09. - Present</sup>
</h4>

- Ph.D. student in [Interdiscimplinary Program in Artificial Intelligence](https://gsai.snu.ac.kr/)
- Cumulative GPA: 3.68 / 4.3 (3.88 / 4.5)
- Advisor: **[Prof. Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html)**

<h4 class="education">
  <i class="material-icons md-18">account_balance</i>
  <a href="http://en.snu.ac.kr/">Seoul National University</a>, Republic of Korea
  <sup>2020.03. - 2022.08.</sup>
</h4>

- M.S. student in [Interdisciplinary Program in Cognitive Science](https://cogsci.snu.ac.kr/)
- Cumulative GPA: 4.12 / 4.3 (4.32 / 4.5)
- Advisor: **[Prof. Byoung-Tak Zhang](https://bi.snu.ac.kr/members/byoung-tak-zhang.html)**

<h4 class="education">
  <i class="material-icons md-18">school</i>
  <a href="https://www.khu.ac.kr/eng/user/main/view.do">Kyunghee University</a>, Republic of Korea
  <sup>2016.03 - 2020.02</sup>
</h4>

- B.S. in [Computer Science and Engineering](https://ce.khu.ac.kr/ce/user/main/view.do)
- Cumulative GPA: 3.68 / 4.3 (3.97 / 4.5)



### Publications

- **Recency-Biased Sampling for Up-to-Date Adaptation of Reinforcement Learning** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2025 (**Best paper award**)
<!-- <a class="code" href="NOT YET" target="_blank">[pdf]</a> -->

- **Truncated Gaussian Policy for Debiased Continuous Control** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
AAAI 2025 (**Oral presentation**)
<a class="code" href="https://ojs.aaai.org/index.php/AAAI/article/view/33988" target="_blank">[pdf]</a>

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
<a class="code" href="https://github.com/northadventure/CollageRL">[github]</a>

- **Defiant Policy Learning for Efficient Exploration in Reinforcement Learning** <br/>
**Ganghun Lee**, Minsu Lee, Byoung-Tak Zhang <br/>
KSC 2023
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11705331" target="_blank">[pdf]</a>

- **H2RL: Transferring Heuristic Knowledge to a Reinforcement Learning Agent for Solving the Online 3D Bin Packing Problem** <br/>
Minji Kim<sup>†</sup>, **Ganghun Lee**<sup>†</sup>, Minsu Lee, Byoung-Tak Zhang <br/>
ICRA 2023 Workshop (**Spotlight**)
<a class="code" href="https://transferabilityinrobotics.github.io/icra2023/spotlight/TRW08_abstract.pdf" target="_blank">[pdf]</a>

- **Reinforcement Learning with Heuristics for Buffer-Utilized Random Bin Packing Problem** <br/>
Minji Kim, **Ganghun Lee**, Byoung-Tak Zhang <br/>
Journal of Logistics Science & Technology (JLST) 2023 (**Best paper award**)
<a class="code" href="https://koreascience.kr/article/JAKO202331061232757.page" target="_blank">[pdf]</a>

- **Multi-Agent Reinforcement Learning for Cover Tactics in SMAC Environment** <br/>
Yesol Park, **Ganghun Lee**, Yunsu Lee, Junseok Park, Byoung-Tak Zhang <br/>
KSC 2023
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11705319" target="_blank">[pdf]</a>

- **From Scratch to Sketch: Deep Decoupled Hierarchical Reinforcement Learning for Robotic Sketching Agent** <br/>
**Ganghun Lee**, Minji Kim, Minsu Lee, Byoung-Tak Zhang <br/>
ICRA 2022
<a class="code" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9811858" target="_blank">[pdf]</a>

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
KCC 2021, KIISE 2023 (**Best paper award**)
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11214553" target="_blank">[pdf]</a>

- **Model-Based Curriculum Reinforcement Learning for Continuous Line Drwaing** <br/>
**Ganghun Lee**, Minji Kim, Byoung-Tak Zhang <br/>
KCC 2021
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10583172" target="_blank">[pdf]</a>

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
KSC 2019
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09302009" target="_blank">[pdf]</a>

- **A New YouTube View Count Prediction Method using DeepAudio-Video Multimodal Learning** <br/>
Haeyeon Park, **Ganghun Lee**, Yeonwoo Jang, Hyeongseok Kim, Sungho Bae <br/>
KCC 2019
<a class="code" href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE08763702" target="_blank">[pdf]</a>

- **Design and Implementation of OTP-based Digital Door Lock System** <br/>
**Ganghun Lee**, Seongbeom Hong, Jinsung Cho <br/>
KSC 2017
<a class="code" href="PDF_LINK" target="_blank">[pdf]</a>



### Experiences

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  Professional Research Personnel, Republic of Korea
  <sup> 2024.09. - 2027.08. (expected) </sup>
</h4>
- Biointelligence Lab, Seoul National University

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  <a href="https://www.hyundai-rotem.co.kr/ko/main/index.do">Hyundai Rotem</a>, Republic of Korea
  <sup> 2023 - Present </sup>
</h4>
- Participation in Industry–Academia Collaborative Research Project

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  <a href="https://www.koreaaero.com/KO/">Korea Aerospace Industries (KAI)</a>, Republic of Korea
  <sup> 2024 - 2025 </sup>
</h4>
- Participation in Industry–Academia Collaborative Research Project

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  <a href="https://tommoro.ai/">Tommoro Robotics</a>, Republic of Korea
  <sup> 2022 - 2023 </sup>
</h4>
- Robot AI Scientist

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  <a href="https://surromind.ai/">Surromind</a>, Republic of Korea
  <sup> 2021 - 2023 </sup>
</h4>
- AI Engineer

<h4 class="experiences">
  <i class="material-icons md-18">work</i>
  <a href="https://tommoro.ai/">LG Electronics</a>, Republic of Korea
  <sup> 2020 - 2021 </sup>
</h4>
- Participation in Industry–Academia Collaborative Research Project
