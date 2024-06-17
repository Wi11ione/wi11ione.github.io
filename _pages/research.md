---
permalink: /research/
title: "Research Experience"
author_profile: true
redirect_from: 
  - "/nmp/"
  - "/nmp.html"
---

<style>
.research-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.research-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  border: 1px solid #ddd;
  border-radius: 5px;
  overflow: hidden;
  width: 100%;
  text-decoration: none;
  color: inherit;
  margin-bottom: 20px;
  transition: transform 0.3s ease;
  height: 200px; /* 固定框的高度 */
}

.research-item:hover {
  transform: scale(1.05);
}

.research-image {
  width: 50%;
  height: 100%; /* 固定图片的高度 */
  object-fit: cover; /* 确保图片在框内保持合适的比例 */
  object-position: top; /* 确保图片从顶部开始显示 */
}

.research-text {
  flex: 1;
  padding: 20px;
  width: 50%;
}

.research-item h4,
.research-item a {
  text-decoration: none;
}

.research-item:hover h4,
.research-item:hover a {
  text-decoration: none;
}
</style>

<script>
function selectRandomImage(images) {
  return images[Math.floor(Math.random() * images.length)];
}

document.addEventListener("DOMContentLoaded", function() {
  const imageSelections = {
    'risk-guided-policy-optimization': [
      '/images/PriorRiskEstimationModel1.png',
      '/images/PriorRiskEstimationModel2.png',
      '/images/PriorRiskEstimationModel3.png'
    ],
    'adversarial-traffic-participant-behavior': [
      '/images/PriorTrafficModel_Framework1.png',
      '/images/PriorTrafficModel_Framework2.png',
      '/images/PriorTrafficModel_Framework3.png'
    ],
    'safety-critical-scenario-generation': [
      '/images/paper1-framework1.png',
      '/images/paper1-framework2.png',
      '/images/paper1-framework3.png'
    ],
    'scenario-diversity': [
      '/images/DiversityImprovement1.png',
      '/images/DiversityImprovement2.png',
      '/images/DiversityImprovement3.png'
    ],
    'naturalistic-driving-data': [
      '/images/paper1-framework1.png',
      '/images/paper1-framework2.png',
      '/images/paper1-framework3.png'
    ],
    'safety-analysis': [
      '/images/paper4-framework1.png',
      '/images/paper4-framework2.png',
      '/images/paper4-framework3.png'
    ],
    'safety-boundary-identification': [
      '/images/SafetyBoundaryIndentification_Illustration1.png',
      '/images/SafetyBoundaryIndentification_Illustration2.png',
      '/images/SafetyBoundaryIndentification_Illustration3.png'
    ],
    'data-closed-loop': [
      '/images/paper2-framework1.png',
      '/images/paper2-framework2.png',
      '/images/paper2-framework3.png'
    ],
    'continual-reinforcement-learning': [
      '/images/SelfEvolveMechanisim_Framework1.png',
      '/images/SelfEvolveMechanisim_Framework2.png',
      '/images/SelfEvolveMechanisim_Framework3.png'
    ],
    'mixed-reality-simulation': [
      '/images/paper1-framework1.png',
      '/images/paper1-framework2.png',
      '/images/paper1-framework3.png'
    ],
    'new-generation-chassis': [
      '/images/paper1-framework1.png',
      '/images/paper1-framework2.png',
      '/images/paper1-framework3.png'
    ],
    'active-lane-changing-system': [
      '/images/paper1-framework1.png',
      '/images/paper1-framework2.png',
      '/images/paper1-framework3.png'
    ]
  };

  document.querySelectorAll('.research-item img').forEach(function(img) {
    const key = img.dataset.key;
    if (imageSelections[key]) {
      img.src = selectRandomImage(imageSelections[key]);
    }
  });
});
</script>

# Institute of Intelligent Vehicles, Tongji University, 2022.9-Present

---

## Self-Evolving Learning-Based Autonomous Driving Systems: Safety-Critical Scenario Generation
supported by the National Key R&D Program of China under Grant No2022YFB2502900, directed by Prof. Yanjun Huang

---

### Results achieved 2022.9-2024.4
<div class="research-grid">
  <a class="research-item" href="{{ site.url }}/research/self-evolving-learning/safety-critical-scenario-generation/risk-guided-policy-optimization/">
    <img src="" alt="Risk-Guided Policy Optimization" class="research-image" data-key="risk-guided-policy-optimization">
    <div class="research-text">
      <h4>We proposed a risk-guided policy optimization method for safety-critical scenario generation, which generates more diverse and plausible scenarios more efficiently.</h4>
    </div>
  </a>
  
  <a class="research-item" href="{{ site.url }}/research/self-evolving-learning/safety-critical-scenario-generation/adversarial-traffic-participant-behavior/">
    <img src="" alt="Adversarial Traffic Participant Behavior" class="research-image" data-key="adversarial-traffic-participant-behavior">
    <div class="research-text">
      <h4>We proposed an adversarial traffic participant behavior model combining traffic prior and reinforcement learning, which solves the limitation that adversarial scenario generation can only be applied to specific working conditions.</h4>
    </div>
  </a>

  <a class="research-item" href="{{ site.url }}/research/self-evolving-learning/safety-critical-scenario-generation/safety-critical-scenario-generation/">
    <img src="" alt="Safety-Critical Scenario Generation" class="research-image" data-key="safety-critical-scenario-generation">
    <div class="research-text">
      <h4>We proposed a safety-critical scenario generation method combining dynamic and static scenario parameters, which greatly improves the efficiency of scenario generation.</h4>
    </div>
  </a>
</div>

---

### Work in progress 2024.3-Present
<div class="research-grid">
  <a class="research-item" href="{{ site.url }}/research/self-evolving-learning/safety-critical-scenario-generation/scenario-diversity/">
    <img src="" alt="Scenario Diversity" class="research-image" data-key="scenario-diversity">
    <div class="research-text">
      <h4>We are working on quantifying the diversity of scenarios and improving the diversity in safety-critical scenario generation for a comprehensive evaluation of autonomous vehicles.</h4>
    </div>
  </a>
  
  <a class="research-item" href="{{ site.url }}/research/self-evolving-learning/safety-critical-scenario-generation/naturalistic-driving-data/">
    <img src="" alt="Naturalistic Driving Data" class="research-image" data-key="naturalistic-driving-data">
    <div class="research-text">
      <h4>We are working on combining naturalistic driving data with adversarial scenario generation to improve the naturalness and plausibility of the generated scenario.</h4>
    </div>
  </a>
</div>

---

## Adaptive Evolution and Evaluation of Secure and Confident Intelligent Systems: Safety Evaluation of Autonomous Vehicles in Complex Environments
supported by the National Natural Science Foundation of China under Grant U23B2061, directed by Prof. Yanjun Huang

---

### Results achieved 2023.1-2024.5
<div class="research-grid">
  <a class="research-item" href="{{ site.url }}/research/adaptive-evolution/safety-evaluation/safety-analysis/">
    <img src="" alt="Safety Analysis" class="research-image" data-key="safety-analysis">
    <div class="research-text">
      <h4>We proposed an approach for the safety analysis of autonomous vehicles from complex safety-critical scenario data, which can intuitively reveal the distribution and characteristics of safety-critical scenarios for any given algorithm.</h4>
    </div>
  </a>
  
  <a class="research-item" href="{{ site.url }}/research/adaptive-evolution/safety-evaluation/safety-boundary-identification/">
    <img src="" alt="Safety Boundary Identification" class="research-image" data-key="safety-boundary-identification">
    <div class="research-text">
      <h4>We proposed a safety boundary online identification method that learns from the test data under a long-tailed environment.</h4>
    </div>
  </a>
</div>

---

## Self-Evolutionary Methods and Applications for Intelligent Systems in Complex Environments: Close-loop Self-Evolve Mechanism for Autonomous Vehicle Based on Mixed Reality Testing
supported by Fundamental Research Funds for the Central Universities, Ministry of Education of China, directed by Prof. Yanjun Huang

---

### Results achieved 2022.9-2023.9
<div class="research-grid">
  <a class="research-item" href="{{ site.url }}/research/self-evolutionary-methods/applications/data-closed-loop/">
