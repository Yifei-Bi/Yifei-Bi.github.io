---
permalink: /
title: "Bi Yifei's personal website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

In 2024, I graduated from the University of Liverpool with a First-Class Bachelor of Science degree. I completed my graduation project under the supervision of [Prof. YueYong](https://www.xjtlu.edu.cn/zh/study/departments/academic-departments/computer-science-and-software-engineering/department-staff/academic-staff/staff/yong-yue) and[Prof.Zhu Xiaohui](https://www.xjtlu.edu.cn/zh/study/departments/academic-departments/computer-science-and-software-engineering/department-staff/academic-staff/staff/xiaohui-zhu).   

### My current research interests are:
1. Reinforcement learning.
2. LLM Agent
3. RLHF


Paper：
==============================
### Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study  
Weihao Tan, Ziluo Ding, Wentao Zhang, Boyu Li, Bohan Zhou, Junpeng Yue, Haochong Xia, Jiechuan Jiang, Longtao Zheng, Xinrun Xu, Yifei Bi, Pengjie Gu, Xinrun Wang, Börje F. Karlsson, Bo An, Zongqing Lu  
##### | ICLR 2024 Workshop on LLM Agents | [Paper](https://openreview.net/forum?id=pmcFzuUxsP&referrer=%5Bthe%20profile%20of%20Bo%20An%5D(%2Fprofile%3Fid%3D~Bo_An2))  

### Cradle: Empowering Foundation Agents Towards General Computer Control  
Weihao Tan*, Wentao Zhang*, Xinrun Xu*, Haochong Xia, Ziluo Ding, Boyu Li, Bohan Zhou, Junpeng Yue, Jiechuan Jiang, Yewen Li, Ruyi An, Molei Qin, Chuqiao Zong, Longtao Zheng, Yujie Wu, Xiaoqiang Chai, Yifei Bi, Tianbao Xie, Pengjie Gu, Xiyun Li, Ceyao Zhang, Long Tian, Chaojie Wang, Xinrun Wang†, Börje F. Karlsson†, Bo An, Shuicheng Yan, Zongqing Lu  
##### | Under review NeurIPS 2024 Dataset and benchmark Track | [Paper](https://arxiv.org/abs/2403.03186) | [Project](https://baai-agents.github.io/Cradle/)  

  
**Project Introduction:**  
Existing LLM Agents primarily interact with games or software through APIs, limiting their applicability to software without available APIs and reducing their overall practicality. To address this issue, we developed a universal LLM Agent that takes the computer screen (and potentially audio) as input and produces keyboard and mouse operation commands as output, enabling the Agent to interact with various software applications. Our Agent has successfully performed interactions and completed tasks in ten different software and games, including *Red Dead Redemption 2*, Meitu, and Google.  

**Work Responsibilities:**  
1. Designed and implemented the Skill Library code within the Agent, which is used to execute operation commands.  
2. Utilized APIs for large models such as GPT-4-o and GPT-4-turbo to research task completion and performance.  
3. Optimized prompts using CoT (Chain of Thought) and Few-shot techniques, and assisted image recognition with Grounding DINO.  

### SwiftReact: Integrating Reinforcement Learning and Large Language Models for Enhanced Real-time Feedback  
Yifei Bi, Chengzhi Liu, Yuxuan Huang, Chong Zhang, Kexiang Shuai, Hanling Wang, Zihong Luo, Haochen Xue, Linhua Dong, Xiaohui Zhu, Yong Yue, Jieming Ma  
##### | Submitted to COLING | [Project](https://github.com/Shuaikx/SC2_Agent)  

**Project Introduction:**  
Current LLMs typically rely on API calls to generate responses, but the time required for these API calls makes it challenging to apply LLMs in real-time feedback scenarios, such as autonomous driving. To address this issue, we proposed the SwiftReact framework, which leverages the real-time feedback capabilities of reinforcement learning (RL) through a Reward Model, combined with the interpretability and strategic overview provided by LLMs. This framework enables the application of LLMs in real-time feedback scenarios and has been deployed in the real-time strategy game StarCraft II.  

**Work Responsibilities:**  
Trained two converging RL algorithms, PPO and DQN, in StarCraft II.  
Developed the SwiftReact framework:  
Step 1: Environment Information Conversion: Analyzed and organized relevant game information, transforming it into a format more easily understood by LLMs to prevent hallucinations and errors in prior knowledge.  
  
Step 2: Strategy Generation: Combined the information from the first step with the Memory module, enabling LLMs to generate targeted strategies based on the available information.  
  
Step 3: Reward Model: Developed an LLM-specific reward function based on the generated strategies, and combined it with the RL reward function according to different weights to form a new Reward Model, which the RL then uses to execute corresponding commands.   




