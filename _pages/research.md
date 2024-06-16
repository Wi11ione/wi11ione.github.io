---
permalink: /research/
title: "Research Experience"
author_profile: true
redirect_from: 
  - "/nmp/"
  - "/nmp.html"
---

## Institute of Intelligent Vehicles, [Tongji University](https://www.tongji.edu.cn/eng/), 2022.9-Present
* **Key Technologies for Self-Evolving Learning-Based Autonomous Driving Systems**, supported by the National Key R&D Program of China under Grant No2022YFB2502900, directed by [Prof. Yanjun Huang](https://www.researchgate.net/profile/Yanjun-Huang-4)
  * **Results achieved** 2022.9-2024.4
    * Proposed a risk-guided policy optimization method for safety-critical scenario generation, which generates more diverse and plausible scenarios more efficiently.
    * Proposed an adversarial traffic participant behavior model combining traffic prior and reinforcement learning, which solves the limitation that adversarial scenario generation can only be applied to specific working conditions.
    * Proposed a safety-critical scenario generation method combining dynamic and static scenario parameters, which greatly improves the efficiency of scenario generation.
  * **Work in progress** 2024.3-Present
    * Quantifying the diversity of scenarios and improving the diversity in safety-critical scenario generation for a comprehensive evaluation of autonomous vehicles.
    * Working on combining naturalistic driving data with adversarial scenario generation to improve the naturalness and plausibility of the generated scenario.

* **Adaptive Evolution and Evaluation of Secure and Confident Intelligent Systems**, supported by the National Natural Science Foundation of China under Grant U23B2061, directed by [Prof. Yanjun Huang](https://www.researchgate.net/profile/Yanjun-Huang-4)
  * **Results achieved** 2023.1-2024.5
    * Proposed an approach for the safety analysis of autonomous vehicles from complex safety-critical scenario data, which can intuitively reveal the distribution and characteristics of safety-critical scenarios for any given algorithm.
    * Proposed a safety boundary online identification method that learns from the test data under a long-tailed environment.

* **Self-Evolutionary Methods and Applications for Intelligent Systems in Complex Environments**, supported by Fundamental Research Funds for the Central Universities, Ministry of Education of China, directed by [Prof. Yanjun Huang](https://www.researchgate.net/profile/Yanjun-Huang-4)
  * **Results achieved** 2022.9-2023.9
    * Reviewed the research related to data-closed loop and proposed a self-evolution mechanism for autonomous driving algorithm.
  * **Work in progress** 2023.10-Present
    * Working on applying continual reinforcement learning methods to improve the self-evolution of autonomous driving algorithms under safety-critical scenarios.
    * Participated in constructing a mixed-reality simulation platform for autonomous vehicles by combining vehicle hardware in the loop and virtual traffic scenarios.

## State Key Laboratory of Automotive Simulation and Control, [Jilin University](https://www.jlu.edu.cn/#), 2019.3-2021.6
* **Design of New Generation Chassis Vehicle Traveling System and Analysis of Its Dynamic Performance**, directed by [Prof.Hsin Guan](http://auto.jlu.edu.cn/info/1306/1784.htm) and [Prof.Pingping Lu](http://auto.jlu.edu.cn/info/1318/3892.htm)
  * **Results achieved** 2020.9-2021.6
    * Designed a new traveling system with four-wheel independent drive and four-wheel independent steering.
    * Modeling of the vehicle dynamics and the distribution algorithm of steering angles and torques of four wheels
    * Vehicle dynamics simulation and its performance analysis based on Matlab/Simulink and Carsim
 
* **Design of Active Lane-Changing System for Intelligent Vehicle and Its Hardware-in-the-Loop Testing**, directed by [Prof.Bing Zhu](http://auto.jlu.edu.cn/info/1134/2305.htm)
  * **Results achieved** 2019.3-2020.9
    * Designed a lane change decision-making algorithm combining risk and efficiency and a lane-changing trajectory planning & control algorithm considering driving comfort and stability
    * Designed a lane detection hardware-in-the-loop test platform


## Research Experience

<div class="research-grid">
  <div class="research-item">
    <a href="{{ site.url }}/research/key-technologies/">
      <img src="/images/paper1-framework.png" alt="Key Technologies for Self-Evolving Learning-Based Autonomous Driving Systems">
      <h3>Key Technologies for Self-Evolving Learning-Based Autonomous Driving Systems</h3>
    </a>
  </div>
  
  <div class="research-item">
    <a href="{{ site.url }}/research/adaptive-evolution/">
      <img src="path_to_image.jpg" alt="Adaptive Evolution and Evaluation of Secure and Confident Intelligent Systems">
      <h3>Adaptive Evolution and Evaluation of Secure and Confident Intelligent Systems</h3>
    </a>
  </div>
  
  <div class="research-item">
    <a href="{{ site.url }}/research/self-evolutionary-methods/">
      <img src="path_to_image.jpg" alt="Self-Evolutionary Methods and Applications for Intelligent Systems in Complex Environments">
      <h3>Self-Evolutionary Methods and Applications for Intelligent Systems in Complex Environments</h3>
    </a>
  </div>
  
  <div class="research-item">
    <a href="{{ site.url }}/research/new-generation-chassis/">
      <img src="path_to_image.jpg" alt="Design of New Generation Chassis Vehicle Traveling System and Analysis of Its Dynamic Performance">
      <h3>Design of New Generation Chassis Vehicle Traveling System and Analysis of Its Dynamic Performance</h3>
    </a>
  </div>
  
  <div class="research-item">
    <a href="{{ site.url }}/research/active-lane-changing-system/">
      <img src="path_to_image.jpg" alt="Design of Active Lane-Changing System for Intelligent Vehicle and Its Hardware-in-the-Loop Testing">
      <h3>Design of Active Lane-Changing System for Intelligent Vehicle and Its Hardware-in-the-Loop Testing</h3>
    </a>
  </div>
</div>

<style>
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.research-item {
  text-align: center;
  border: 1px solid #ddd;
  padding: 20px;
  border-radius: 10px;
  transition: transform 0.3s;
}

.research-item img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
}

.research-item h3 {
  margin-top: 15px;
}

.research-item:hover {
  transform: scale(1.05);
}
</style>
