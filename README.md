# Adaptive thinking papers 

This repo includes papers about the adaptive thinking of reasoning LLMs. Adaptive thinking is benificial for long-CoT  large reasoning models to save cost and improve effeciency.

## Analysis of Overthinking and Underthinking

* **Does thinking more always help? Understanding test-time scaling in reasoning models⭐**
  * <span style="color: red;">Simple Note: Using Nothinking for short-CoT; SFT for warm-up; Using 
  * Soumya Suvra Ghosal, Souradip Chakraborty, Avinash Reddy, Yifu Lu, Mengdi Wang, Dinesh Manocha, Furong Huang, Mohammad Ghavamzadeh, Amrit Singh Bedi.
  * https://arxiv.org/abs/2506.04210

*  **Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs**
  * Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie.
  * https://arxiv.org/abs/2505.00127

* **Reasoning models can be effective without thinking⭐**
  * <span style="color: red;">Simple Note: Using `<think>Okay, I think I have finished thinking.</think>` to skip thinking process</span>*
  * Wenjie Ma, Jingxuan He, Charlie Snell, Tyler Griggs, Sewon Min, Matei Zaharia.
  * https://arxiv.org/abs/2504.09858

## RL-based Solution

* **Think how to think: Mitigating overthinking with autonomous difficulty cognition in large reasoning models⭐**
  * *<span style="color: red;">Simple Note: Using SFT for autonomous difficulty cognition</span>*
  * Yongjiang Liu, Haoxi Li, Xiaosong Ma, Jie Zhang, Song Guo
  * https://arxiv.org/abs/2507.02663

* **Thinkless: LLM learns when to think⭐**
  * *<span style="color: red;">Simple Note: Using Nothinking for short-CoT; SFT for warm-up; Using DeGRPO to treat control token differently</span>*
  * Gongfan Fang, Xinyin Ma, Xinchao Wang.
  * https://arxiv.org/abs/2505.13379

* **AdaptThink: Reasoning models can learn when to think⭐** 
  * *<span style="color: red;">Simple Note: Using instruct model for short-CoT</span>*
  * Jiajie Zhang, Nianyi Lin, Lei Hou, Ling Feng, Juanzi Li.
  * https://arxiv.org/abs/2505.13417

* **AdaCoT: Pareto-optimal adaptive chain-of-thought triggering via reinforcement learning**
  * Chenwei Lou, Zewei Sun, Xinnian Liang, Meng Qu, Wei Shen, Wenqi Wang, Yuntao Li, Qingping Yang, Shuangzhi Wu.
  * https://arxiv.org/abs/2505.11896

* **Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning**
  * Jinghui Lu, Haiyang Yu, Siliang Xu, Shiwei Ran, Guozhi Tang, Siqi Wang, Bin Shan, Teng Fu, Hao Feng, Jingqun Tang, Han Wang, Can Huang.
  * https://arxiv.org/abs/2505.15154

* **AdaCtrl: Towards Adaptive and Controllable Reasoning via Difficulty-Aware Budgeting**
  * Shijue Huang, Hongru Wang, Wanjun Zhong, Zhaochen Su, Jiazhan Feng, Bowen Cao, Yi R. Fung.
  * https://arxiv.org/abs/2505.18822

* **Think Only When You Need with Large Hybrid-Reasoning Models**
  * Lingjie Jiang, Xun Wu, Shaohan Huang, Qingxiu Dong, Zewen Chi, Li Dong, Xingxing Zhang, Tengchao Lv, Lei Cui, Furu Wei.
  * https://arxiv.org/abs/2505.14631

* **When to continue thinking: Adaptive thinking mode switching for efficient reasoning**
  * *<span style="color: red;">Simple Note: Based on group accuracy for mode selection</span>*
  * Xiaoyun Zhang, Jingqing Ruan, Xing Ma, Yawen Zhu, Haodong Zhao, Hao Li, Jiansong Chen, Ke Zeng, Xunliang Cai.
  * https://arxiv.org/abs/2505.15400

* **Learning when to think: Shaping adaptive reasoning in R1-style models via multi-stage RL**
  * Songjun Tu, Jiahao Lin, Qichao Zhang, Xiangyu Tian, Linjing Li, Xiangyuan Lan, Dongbin Zhao.
  * https://arxiv.org/abs/2505.10832

* **Adaptive Deep Reasoning: Triggering Deep Thinking When Needed**
  * Yunhao Wang, Yuhao Zhang, Tinghao Yu, Can Xu, Feng Zhang, Fengzong Lian.
  * https://arxiv.org/abs/2505.20101

* **Learn to Reason Efficiently with Adaptive Length-based Reward Shaping**
  * Wei Liu, Ruochen Zhou, Yiyun Deng, Yuzhen Huang, Junteng Liu, Yuntian Deng, Yizhe Zhang, Junxian He.
  * https://arxiv.org/abs/2505.15612

* **ARM: Adaptive Reasoning Model**
  * Siye Wu, Jian Xie, Yikai Zhang, Aili Chen, Kai Zhang, Yu Su, Yanghua Xiao.
  * https://arxiv.org/abs/2505.20258

* **Ada-R1: Hybrid-CoT via bi-level adaptive reasoning optimization**
  * Haotian Luo, Haiying He, Yibo Wang, Jinluan Yang, Rui Liu, Naiqiang Tan, Xiaochun Cao, Dacheng Tao, Li Shen.
  * https://arxiv.org/abs/2504.21659




## Outside Switcher-based Solution

* **Long or short CoT? Investigating instance-level switch of large reasoning models⭐**
  * *<span style="color: red;">Simple Note: Using R1-7B as switcher, prompt engineering or SFT for selection</span>*
  * Ruiqi Zhang, Changyi Xiao, Yixin Cao.
  * https://arxiv.org/abs/2506.04182

* **ThinkSwitcher: When to think hard, when to think fast⭐**
  * *<span style="color: red;">Simple Note: Using MLP as switcher, group accuracy as label</span>*
  * Guosheng Liang, Longguang Zhong, Ziyi Yang, Xiaojun Quan.
  * https://arxiv.org/abs/2505.14183



## Long-CoT Compression

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Trae1ounG/Awesome-LLM-Adaptive-Thinking&type=Date)](https://star-history.com/#Trae1ounG/Awesome-LLM-Adaptive-Thinking&Date)