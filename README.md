# 🧠 Emotion-Aware RL for Sustainable Fitness Coaching

Modern fitness recommendation systems often ignore user emotions, leading to burnout, monotony, and dropouts. This project presents a **multi-modal, emotion-aware Deep Q-Network (DQN) framework** for sustainable, personalized fitness coaching.

---

## 📌 Key Features

- **💪 Dual-Persona Modeling**  
  - **Physical Persona** – captures fitness level, endurance, and workout preferences  
  - **Emotional Persona** – models emotional sensitivity, motivation, and mood dynamics

- **📈 Emotion-Aware Simulation**  
  A user simulator generates realistic physical and emotional reactions to coaching actions, including affective feedback (RTWS, EMA).

- **🎯 Reward Shaping**  
  A custom reward function blends short-term emotional responses with long-term wellness trends to guide the learning process.

- **🤖 Deep Q-Network (DQN)**  
  A neural network-based agent learns an optimal coaching policy by interacting with the simulated environment using Q-learning.

---

## 🏗️ System Architecture

![Emotion-Aware RL Architecture](https://github.com/anandaru/Emotion_Aware_RL/blob/main/arch.png)  


---

## 📊 Dataset

We use the **SNPERS dataset** (18,101 user fitness records) and enrich it with **synthetic emotional labels** to simulate user mood, stress, and engagement over time.

---

## 🧪 Results

| Metric                  | Emotion-Aware DQN | Non-Emotional RL | Static Plan |
|-------------------------|-------------------|------------------|-------------|
| User Engagement (↑)     | ✅ High            | ⚠️ Medium         | ❌ Low       |
| Emotional Satisfaction  | ✅ Positive Trend  | ⚠️ Fluctuating    | ❌ Declining |
| Fitness Improvement     | ✅ Maintained      | ✅ Maintained     | ✅ Baseline  |

The emotion-aware DQN agent adapts to how users **feel** and **perform**, enabling better long-term consistency.

---

## 🌱 Why It Matters

📅 Personalization isn't just about physical needs—it's also about emotional sustainability.  
🧠 This framework shows that **emotionally intelligent coaching** keeps users motivated and consistent.

---

## 🚀 Future Directions

- 🔬 Validate with real users using wearables + mood surveys  
- 🗣️ Add natural language generation for empathetic feedback  
- 👥 Integrate social factors (e.g., group workouts)  
- 📱 Extend to domains like mental health, education, and lifestyle coaching

---

## 📚 Reference

[1] Yang et al., *SNPERS: A Physical Exercise Recommendation System Integrating Statistical Principles and Natural Language Processing 
🔗 [SNPERS](https://www.researchgate.net/publication/366623718_SNPERS_A_Physical_Exercise_Recommendation_System_Integrating_Statistical_Principles_and_Natural_Language_Processing
