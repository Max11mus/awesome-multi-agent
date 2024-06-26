# Awesome Multi-Agent Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Multi-Agent Learning is a very exciting research area, which has strong connections with single-agent RL, multi-agent systems, game theory, evolutionary computation, communication framework and adaptation.

This repo contains a set of research papers as well as related information. The papers are sorted by time. Any suggestions and pull requests are welcome.

## Overview
 - [Tutorials](#tutorials)
 - [Research Papers](#papers)
    - RL in multi-agent
    - Imitation Learning and Inverse RL
    - Offline Learning
    - Communication
    - Adaptation
    - Multi-Agent Influence
    - Others
 - [Environment](#environment)

## Tutorials
- **SJTU Multi-Agent Reinforcement Learning Tutorial** [[website]](http://wnzhang.net/tutorials/marl2018/index.html)
  - J. Wang, W. Zhang at SJTU 2018 
-  **Multiagent Learning: Foundations and Recent Trends** [[website]](http://www.cs.utexas.edu/~larg/ijcai17_tutorial/)
    - S. Albrecht, P. Stone, **IJCAI 2017**
- **COMP310: Multi Agent System** [[website]](https://cgi.csc.liv.ac.uk/~trp/COMP310.html)    
  - T. Payne, 2017-2018
- **CompSci 285: Multi-Agent Systems** [[website]](https://www.seas.harvard.edu/courses/cs285/CS_285/Course_Home.html)   
  - D. Parkes, 2013
- **CS 224M : Multi Agent Systems** [[website]](http://web.stanford.edu/class/cs224m/)
  - Y. Shoham, 2013-14
- **Videos for "An Introduction to Multiagent Systems (Second Edition)"** [[website]](http://www.cs.ox.ac.uk/people/michael.wooldridge/pubs/imas/videos/)   
  - M. Wooldridge, John Wiley & Sons, 2009


## Papers
### RL in multi-agent
- **Coach-Player Multi-Agent Reinforcement Learning for Dynamic Team Composition** [[paper]](https://arxiv.org/abs/2105.08692)
  - B. Liu, Q. Liu, P. Stone, A. Garg, Y. Zhu, A. Anandkumar, **ICML 2021**
- **Randomized Entity-wise Factorization for Multi-Agent Reinforcement Learning** [[paper]](https://arxiv.org/abs/2006.04222)
  - S. Iqbal, C. A. Schroeder de Witt, B. Peng, W. Böhmer, S. Whiteson, F. Sha, **ICML 2021**
- **Deep Implicit Coordination Graphs for Multi-Agent Reinforcement Learning** [[paper]](https://arxiv.org/abs/2006.11438)
  - S. Li, J. K. Gupta, P. Morales, R. Allen, M. J. Kochenderfer, **AAMAS 2021**
- **Multi-Agent Game Abstraction via Graph Attention Neural Network** [[paper]](https://arxiv.org/abs/1911.10715)
  - Y. Liu, W. Wang, Y. Hu, J. Hao, X. Chen, Y. Gao, **AAAI 2020**
- **Actor-Attention-Critic for Multi-Agent Reinforcement Learning** [[paper]](https://arxiv.org/abs/1810.02912) [[code]](https://github.com/shariqiqbal2810/MAAC)
  - S. Iqbal, F. Sha, **ICML 2019**
- **QTRAN: Learning to Factorize with Transformation for Cooperative Multi-Agent Reinforcement Learning** [[paper]](https://arxiv.org/abs/1905.05408)
  - K. Son, D. Kim, W. J. Kang, D. E. Hostallero, Y. Yi, **ICML 2019**
- **QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning** [[arxiv]](https://arxiv.org/abs/1803.11485)
  - T. Rashid, M. Samvelyan, C. Witt, **ICML 2018**
- **Emergent Complexity via Multi-agent Competition** [[website]](https://arxiv.org/abs/1710.03748)[[Code]](https://github.com/openai/multiagent-competition)
  - T. Bansal, J. Pachocki, S. Sidor, **ICLR 2018**
- **Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments** [[paper]](https://arxiv.org/abs/1706.02275)[[code1]](https://github.com/openai/multiagent-particle-envs)[[code2]](https://github.com/openai/maddpg)
  - R. Lowe, Y. Wu, A. Tamar, **NeurIPS 2017**

### Competition Scenario
- **Emergent complexity through multi-agent competition** [[paper]](https://arxiv.org/pdf/1710.03748.pdf)
    - T. Bansal, J. Pachocki, S. Sidor, I. Sutskever, I. Mordatch, **ICLR 2018**

### Imitation Learning and Inverse RL
- **Multi-Agent Adversarial Inverse Reinforcement Learning** [[paper]](https://arxiv.org/abs/1907.13220)
  - L. Yu, J. Song, S. Ermon, **ICML 2019**
- **Multi-Agent Generative Adversarial Imitation Learning** [[paper]](https://arxiv.org/pdf/1807.09936.pdf)
  - J. Song, H. Ren, D. Sadigh, S. Ermon, **NeurIPS 2018**

### Offline Learning
-  **Offline Pre-trained Multi-Agent Decision Transformer** [[paper]](https://arxiv.org/abs/2112.02845)
    - L. Meng, M. Wen, Y. Yang, C. Le, X. Li, W. Zhang, Y. Wen, H. Zhang, J. Wang, B. Xu

### Communication
- **Multi-Agent Graph-Attention Communication and Teaming** [[paper]](https://dl.acm.org/doi/abs/10.5555/3463952.3464065) [[code]](https://github.com/MAGIC-AAMAS/MAGIC)
  - Y. Niu, R. Paleja, M. Gombolay, **AAMAS 2021**
- **TarMAC: Targeted Multi-Agent Communication** [[paper]](https://proceedings.mlr.press/v97/das19a.html)
  - A. Das, T. Gervet, J. Romoff, D. Batra, D. Parikh, M. Rabbat, J. Pineau, **ICML 2019**
- **Learning when to Communicate at Scale in Multiagent Cooperative and Competitive Tasks** [[paper]](https://arxiv.org/abs/1812.09755)
  - A. Singh, T. Jain, S. Sukhbaatar, **ICLR 2019**
- **Learning Attentional Communication for Multi-Agent Cooperation** [[paper]](https://arxiv.org/abs/1805.07733)
  - J. Jiang, Z. Lu, **NeurIPS 2018**
- **Learning to Communicate with Deep Multi-Agent Reinforcement Learning** [[paper]](https://proceedings.neurips.cc/paper/2016/hash/c7635bfd99248a2cdef8249ef7bfbef4-Abstract.html)
- **Learning Multiagent Communication with Backpropagation** [[paper]](https://arxiv.org/abs/1605.07736)
  - S. Sukhbaatar, A. Szlam, R. Fergus, **NeurIPS 2016**

### Adaptation
- **Meta-CPR: Generalize to Unseen Large Number of Agents with Communication Pattern Recognition Module** [[paper]](https://arxiv.org/abs/2112.07222)
  - W. C. Tseng, W. Wei, D. C. Juan, M. Sun, **pre-print**
- **A Policy Gradient Algorithm for Learning to Learn in Multiagent Reinforcement Learning** [[paper]](https://arxiv.org/abs/2011.00382)
    - D. Kim, M. Liu, M. Riemer, C. Sun, M. Abdulhai, G. Habibi, S. Lopez-Cot, G. Tesauro, J. P. How, **ICML 2021**
- **Evolutionary Population Curriculum for Scaling Multi-Agent Reinforcement Learning** [[paper]](https://arxiv.org/abs/2003.10423)
  - Q. Long, Z. Zhou, A. Gupta, F. Fang, Y. Wu, X. Wang, **ICLR 2020**
- **From Few to More: Largescale Dynamic Multiagent Curriculum Learning** [[paper]](https://arxiv.org/abs/1909.02790)
  - W. Wang, T. Yang, Y. Liu, J. Hao, X. Hao, Y. Hu, Y. Chen, C. Fan, Y. Gao, **AAAI 2020**
- **DiCE: The Infinitely Differentiable Monte Carlo Estimator** [[paper]](https://arxiv.org/abs/1802.05098)
    - J. Foerster, G. Farquhar, M. Al-Shedivat, T. Rocktäschel, E. P. Xing, S. Whiteson, **ICML 2018**
- **Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments** [[paper]](https://arxiv.org/pdf/1710.03641.pdf)
  - M. Al-Shedivat, T. Bansal, Y. Burda, I. Sutskever, I. Mordatch, P. Abbeel, **ICLR 2018**

### Multi-Agent Influence
- **Learning Latent Representations to Influence Multi-Agent Interaction** [[website]](https://sites.google.com/view/latent-strategies/) [[paper]](https://arxiv.org/abs/2011.06619)
  - A. Xie, D. P. Losey, R. Tolsma, C. Finn, D. Sadigh, **CoRL 2020**
- **Social Influence as Intrinsic Motivation for Multi-Agent Deep Reinforcement Learning** [[paper]](https://arxiv.org/abs/1810.08647)
  - N. Jaques, A. Lazaridou, E. Hughes, C. Gulcehre, P. A. Ortega, DJ Strouse, J. Z. Leibo, N. de Freitas, **ICML 2019**

### Application
- **Distributed Heuristic Multi-Agent Path Finding with Communication** [[paper]](https://arxiv.org/abs/2106.11365)
  - Z. Ma, Y. Luo, H. Ma, **ICRA 2021**

### Others
- **Adaptable Agent Populations Using a Generative Model of Policies** [[paper]](https://arxiv.org/abs/2107.07506)
    - K. Derek, P. Isola, **NeurIPS 2021**
- **Emergent Tool Use From Multi-Agent Autocurricula** [[paper]](https://arxiv.org/abs/1909.07528)
    - B. Baker, I. Kanitscheider, T. Markov, Y. Wu, G. Powell, B. McGrew, I. Mordatch, **ICLR 2020**


## Environment
<!-- - **Neural MMO** [[code]](https://neuralmmo.github.io/build/html/rst/userguide.html)
- **SMAC** [[code]](https://github.com/oxwhirl/smac)
- **Grid-World** [[code]](https://github.com/ArnaudFickinger/gym-multigrid)
- **Unity ML Agent** [[code]](https://github.com/Unity-Technologies/ml-agents)
- **Hanabi Learning Environment** [[code]](https://github.com/deepmind/hanabi-learning-environment)
- **MAgent** [[code]](https://github.com/geek-ai/MAgent) 
- **multiagent-particle-envs** [[code]](https://github.com/openai/multiagent-particle-envs)
- **multiagent-competition** [[code]](https://github.com/openai/multiagent-competition)
- **Multiagent emergence** [[code]](https://github.com/openai/multi-agent-emergence-environments) -->

<!-- | Name                                                                             | Value            |
|----------------------------------------------------------------------------------|------------------|
| <img src="https://neuralmmo.github.io/build/html/_images/splash.png" width=200/> | <img width=500/> | -->


<table >
  <tr>
    <td width="23%">
    <img src="https://neuralmmo.github.io/build/html/_images/splash.png" width="100%"/>
    </td>
    <td width="23%">
    <img src="https://user-images.githubusercontent.com/17878413/97562396-e8b12380-1a24-11eb-92ba-c9a05ec3630b.png" width="100%">
    </td>
    <td width="23%">
    <img src="https://raw.githubusercontent.com/ArnaudFickinger/gym-multigrid/master/figures/soccer_2.png" width="100%">
    </td>
    <td width="23%">
    <img src="https://raw.githubusercontent.com/Unity-Technologies/ml-agents/main/docs/images/soccer.png" width="100%">
    </td>
  </tr>
  <tr>
    <th>
    <a href="https://neuralmmo.github.io/build/html/rst/userguide.html">Neural MMO</a>
    </th>
    <th>
    <a href="https://github.com/oxwhirl/smac">SMAC</a>
    </th>
    <th>
    <a href="https://github.com/ArnaudFickinger/gym-multigrid">Grid-World</a>
    </th>
    <th>
    <a href="https://github.com/Unity-Technologies/ml-agents">Unity MLAgent</a>
    </th>
  </tr>

  <tr>
    <td width="23%">
    <img src="https://www.endtoend.ai/assets/blog/rl-weekly/7/hanabi.png" width="100%"/>
    </td>
    <td width="23%">
    <img src="https://camo.githubusercontent.com/ea0905ab13f984ec6480dc701e5bffc5c626eb6e94e3e7eea1b20e7c10a507af/68747470733a2f2f6b6970736f72612e6769746875622e696f2f7265736f75726365732f6d6167656e742d67726170682d312e676966" width="100%">
    </td>
    <td width="23%">
    <img src="https://openai.com/content/images/2017/06/chase_gif_final.gif" width="100%">
    </td>
    <td width="23%">
    <img src="https://i1.read01.com/LlXZ7awAJjZcpwhY1UdURns/0.jpg" width="100%">
    </td>
  </tr>
  <tr>
    <th>
    <a href="https://github.com/deepmind/hanabi-learning-environment">Hanabi Learning Environment</a>
    </th>
    <th>
    <a href="https://github.com/geek-ai/MAgent">MAgent</a>
    </th>
    <th>
    <a href="https://github.com/openai/multiagent-particle-envs">multiagent-particle-envs</a>
    </th>
    <th>
    <a href="multiagent-competition">multiagent-competition</a>
    </th>
  </tr>
  
  <tr>
    <td width="23%">
    <img src="https://vitalab.github.io/article/images/autocurricula/env.png" width="100%"/>
    </td>
  </tr>
  <tr>
    <th>
    <a href="https://github.com/openai/multi-agent-emergence-environments">Multiagent emergence</a>
    </th>

  </tr>

</table>