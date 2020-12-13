## Introduction
Recent researches revealed that deep reinforcement learning(DRL) has potential to solove optimization problem like travelling salesman problem(TSP)\[[1](https://arxiv.org/pdf/1611.09940.pdf)\] ,vehicle routing problem(VRP) and their variants \[[2](https://papers.nips.cc/paper/8190-reinforcement-learning-for-solving-the-vehicle-routing-problem.pdf)\]\[[3](https://dl.acm.org/doi/pdf/10.1145/3394486.3403356)\]. These problems are NP-hard problems and usually solved using manuscript heuristics. It requires expertise in optimization field to design efficient heuristic algorithms. DRL has shown great potential to automatically learn heuristics, attracting more researchers to apply DRL to solve such problems.

Pick up and delivery problem is such a NP-hard problem. Its goal is to final optimal path to satisfy all demands on a map given a set of origins and destinations and several vehicles with limited capacity. This is illustrated below. One can set time windows for each demands to ensure orders are picked up during specific time windows, which is called pickup and delivery problem with time windows (PDPTW). Since the problem is very common in the reality like food delivery, ride hailing service and other transportatio systems, many literatures focus on developing efficient algotihtms to solve the problem. However, the more realistic setting is that the deamnds will appear dynamically, leading to much more sophisticated problem. The dynamic of transition is also hard to be captured using mathematical tools.
<p align="center">
  <img width="400" height="300" src=images/require.png>
  <img width="400" height="300" src=images/result.png>
</p>

Therefore, more and more researches begin to apply DRL to solve dynamic PPDTW. Amazon sets a reinforcement learning benchmarks for online pick up and delivery problem \[[4]((https://arxiv.org/pdf/1911.10641.pdf)\]. Other researches try to deploy DRL agents to dispathes cutomers\[[5](https://arxiv.org/pdf/1903.03882.pdf)\]\[[6](https://arxiv.org/abs/1911.11260)\]

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions forafafdafafsdfddfad
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/zhilee2019/FinalProjectDRL.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Reference
\[[1](https://arxiv.org/pdf/1611.09940.pdf)\] Bello, I., Pham, H., Le, Q. V., Norouzi, M., & Bengio, S. (2016). Neural combinatorial optimization with reinforcement learning. arXiv preprint arXiv:1611.09940.

\[[2](https://papers.nips.cc/paper/8190-reinforcement-learning-for-solving-the-vehicle-routing-problem.pdf)\]Nazari, M., Oroojlooy, A., Snyder, L., & Takác, M. (2018). Reinforcement learning for solving the vehicle routing problem. In Advances in Neural Information Processing Systems (pp. 9839-9849).

\[[3](https://dl.acm.org/doi/pdf/10.1145/3394486.3403356)\]Efficiently Solving the Practical Vehicle Routing Problem: A Novel Joint Learning Approach

\[[4](https://arxiv.org/pdf/1911.10641.pdf)\]Balaji, B., Bell-Masterson, J., Bilgin, E., Damianou, A., Garcia, P. M., Jain, A., ... & Ye, C. (2019). Orl: Reinforcement learning benchmarks for online stochastic optimization problems. arXiv preprint arXiv:1911.10641.

\[[5](https://arxiv.org/pdf/1903.03882.pdf)\]Al-Abbasi, A. O., Ghosh, A., & Aggarwal, V. (2019). Deeppool: Distributed model-free algorithm for ride-sharing using deep reinforcement learning. IEEE Transactions on Intelligent Transportation Systems, 20(12), 4714-4727.

\[[6](https://arxiv.org/abs/1911.11260)\] Holler, J., Vuorio, R., Qin, Z., Tang, X., Jiao, Y., Jin, T., ... & Ye, J. (2019, November). Deep Reinforcement Learning for Multi-Driver Vehicle Dispatching and Repositioning Problem. In 2019 IEEE International Conference on Data Mining (ICDM) (pp. 1090-1095). IEEE.
