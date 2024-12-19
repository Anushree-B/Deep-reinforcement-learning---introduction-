# Deep-reinforcement-learning---introduction-
An introductory guide to Deep Reinforcement Learning (DRL).

---

## Table of Contents
1. [Definition](#definition)
2. [Example](#example)
3. [Core Components](#core-components)
4. [DRL Architecture](#drl-architecture)
5. [DRL Algorithms](#drl-algorithms)
6. [Applications](#applications)

---

## 1. Definition
Deep Reinforcement Learning (DRL) combines **reinforcement learning** with **deep neural networks (DNNs)** to solve multi-level problems by trial and error. DRL uses multiple layers of artificial neural networks to replicate the decision-making processes of the human brain.

---

## 2. Example: PAC-MAN Game
### State
- Position of PAC-MAN, GHOST, and COINS  

### Actions
- Moving **UP**, **DOWN**, **FRONT**, or **BACK**  

### Environment
- **Positive reward**: Collecting a coin  
- **Negative reward**: Encountering a ghost  

---

## 3. Core Components
### Agent
- Decision maker  
- Acts based on its policy  
- Gains experience over time  

### Environment
- External system providing feedback (reward or punishment)  

### State
- Represents the current situation and influences the agent's decisions  

### Action
- Alters the system's state, guided by the agent's policy  

### Policy
- Guides the agent’s decisions, aiming to find the optimal strategy  

### Value Function
- Estimates the expected reward from a state under a policy  

### Model
- Simulates environment dynamics for planning and prediction  

### Exploration vs. Exploitation
- **Exploration**: Discovering new actions for knowledge  
- **Exploitation**: Using known actions to maximize immediate rewards  

---

## 4. DRL Architecture
The DRL system consists of:  
1. **State Observation**  
2. **Agent**: Guided by a neural network  
3. **Environment Interaction**: Provides rewards based on actions  

Flow:  
**Observed State → Agent → Action → Environment → Reward**  

---

## 5. DRL Algorithms
### Deep Q-Learning
- Replaces the Q-table with a neural network  
- Approximates Q-values for actions in each state  

#### Steps:
1. Initialize network weights  
2. Choose an action  
3. Update network weights  

### Policy Gradient Methods
- Directly learns the best strategy (policy) for the agent  
- Adjusts the policy to maximize expected rewards  

#### Steps:
1. Initialize policy network  
2. Choose an action and observe the outcome  
3. Calculate gradients  
4. Update policy network weights  

### Model-Based vs. Model-Free Algorithms
1. **Model-Based**: Suitable for static environments; builds a model of the environment.  
2. **Model-Free**: Applies to dynamic environments; directly interacts with the environment without prior knowledge.  

---

## 6. Applications
### Entertainment and Gaming
- Used to develop intelligent game AI  
- Examples: Chess, Go, Dota 2  

### Robotics and Autonomous Systems
- Skills like navigation and object identification  
- Autonomous vehicles, drones  

### Healthcare
- Individualized treatment plans  
- Disease detection and robotic surgery  

---

## Thank You!  
