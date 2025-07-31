# LRMs Adaptive Thinking Papers😎

This repo includes papers about the adaptive thinking of reasoning LLMs. Adaptive thinking is benificial for long-CoT  large reasoning models to save cost and improve effeciency.

## Survey
* **Towards concise and adaptive thinking in large reasoning models: A survey⭐⭐⭐**
  * Jason Zhu, Hongyu Li.
  * https://arxiv.org/abs/2507.09662


## Analysis of Overthinking and Underthinking

* **Does thinking more always help? Understanding test-time scaling in reasoning models⭐**
  * ***Simple Note📕: Using `wait` to increase the thinking length will cause the performance decrease after specific point.***
  * Soumya Suvra Ghosal, Souradip Chakraborty, Avinash Reddy, Yifu Lu, Mengdi Wang, Dinesh Manocha, Furong Huang, Mohammad Ghavamzadeh, Amrit Singh Bedi.
  * https://arxiv.org/abs/2506.04210

* **ALPHAONE: Reasoning Models Thinking Slow and Fast at Test Time⭐**
  * ***Simple Note📕: A test-time method that defines an 'α moment' to scale the thinking phase, encouraging slow thinking before it (by adding `Wait,`) and forcing fast thinking after it (by replacing `Wait,` with `</think>`).***
  * Junyu Zhang, Haoran Geng, Peihao Li, Runpei Dong, Han Wang, Xuying Ning, Xialin He, Yutong Bai, Huan Zhang, Jitendra Malik, Saurabh Gupta.
  * https://arxiv.org/abs/2505.24863
  
*  **Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs**  
   * Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie.
   * https://arxiv.org/abs/2505.00127

* **Reasoning models can be effective without thinking⭐**
  * ***Simple Note📕: Using `<think>Okay, I think I have finished thinking.</think>` to skip thinking process***
  * Wenjie Ma, Jingxuan He, Charlie Snell, Tyler Griggs, Sewon Min, Matei Zaharia.
  * https://arxiv.org/abs/2504.09858

## RL-based Solution

* **Think how to think: Mitigating overthinking with autonomous difficulty cognition in large reasoning models⭐**
  * ***Simple Note📕: Using SFT for autonomous difficulty cognition***
  * Yongjiang Liu, Haoxi Li, Xiaosong Ma, Jie Zhang, Song Guo
  * https://arxiv.org/abs/2507.02663

* **Exploring and Exploiting the Inherent Efficiency within Large Reasoning Models for Self-Guided Efficiency Enhancement⭐**
  * ***Simple Note📕: Proposes two methods: 1) training-free 'Efficiency Steering' via a vector from efficient/verbose paths, and 2) 'Self-Rewarded Efficiency RL' to reward brevity.***
  * Weixiang Zhao, Jiahe Guo, Yang Deng, Xingyu Sui, Yulin Hu, Yanyan Zhao, Wanxiang Che, Bing Qin, Tat-Seng Chua, Ting Liu.
  * https://arxiv.org/abs/2506.15647

* **Optimizing Length Compression in Large Reasoning Models⭐**
  * ***Simple Note📕: A GRPO-based method that uses a dual-reward system: a 'Length Reward' for overall conciseness and a 'Compress Reward' to specifically prune 'invalid thinking' after the correct answer is found.***
  * Zhengxiang Cheng, Dongping Chen, Mingyang Fu, Tianyi Zhou.
  * https://arxiv.org/abs/2506.14755

* **ARM: Adaptive Reasoning Model**
  * Siye Wu, Jian Xie, Yikai Zhang, Aili Chen, Kai Zhang, Yu Su, Yanghua Xiao.
  * https://arxiv.org/abs/2505.20258

* **Adaptive Deep Reasoning: Triggering Deep Thinking When Needed**
  * Yunhao Wang, Yuhao Zhang, Tinghao Yu, Can Xu, Feng Zhang, Fengzong Lian.
  * https://arxiv.org/abs/2505.20101

* **AdaCtrl: Towards Adaptive and Controllable Reasoning via Difficulty-Aware Budgeting⭐**
  * ***Simple Note📕: A two-stage method that first SFTs the model on `[Easy]` and `[Hard]` tags for length control, then uses difficulty-aware RL to train for adaptive, self-assessed reasoning budgeting.***
  * Shijue Huang, Hongru Wang, Wanjun Zhong, Zhaochen Su, Jiazhan Feng, Bowen Cao, Yi R. Fung.
  * https://arxiv.org/abs/2505.18822

* **Learn to Reason Efficiently with Adaptive Length-based Reward Shaping**
  * Wei Liu, Ruochen Zhou, Yiyun Deng, Yuzhen Huang, Junteng Liu, Yuntian Deng, Yizhe Zhang, Junxian He.
  * https://arxiv.org/abs/2505.15612

* **When to continue thinking: Adaptive thinking mode switching for efficient reasoning**
  * ***Simple Note📕: Based on group accuracy for mode selection***
  * Xiaoyun Zhang, Jingqing Ruan, Xing Ma, Yawen Zhu, Haodong Zhao, Hao Li, Jiansong Chen, Ke Zeng, Xunliang Cai.
  * https://arxiv.org/abs/2505.15400

* **Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning**
  * Jinghui Lu, Haiyang Yu, Siliang Xu, Shiwei Ran, Guozhi Tang, Siqi Wang, Bin Shan, Teng Fu, Hao Feng, Jingqun Tang, Han Wang, Can Huang.
  * https://arxiv.org/abs/2505.15154

* **Think Only When You Need with Large Hybrid-Reasoning Models**
  * Lingjie Jiang, Xun Wu, Shaohan Huang, Qingxiu Dong, Zewen Chi, Li Dong, Xingxing Zhang, Tengchao Lv, Lei Cui, Furu Wei.
  * https://arxiv.org/abs/2505.14631

* **AdaptThink: Reasoning models can learn when to think⭐** 
  * ***Simple Note📕: Using instruct model for short-CoT***
  * Jiajie Zhang, Nianyi Lin, Lei Hou, Ling Feng, Juanzi Li.
  * https://arxiv.org/abs/2505.13417

* **Thinkless: LLM learns when to think⭐**
  * ***Simple Note📕: Using Nothinking for short-CoT; SFT for warm-up; Using DeGRPO to treat control token differently***
  * Gongfan Fang, Xinyin Ma, Xinchao Wang.
  * https://arxiv.org/abs/2505.13379

* **AdaCoT: Pareto-optimal adaptive chain-of-thought triggering via reinforcement learning**
  * Chenwei Lou, Zewei Sun, Xinnian Liang, Meng Qu, Wei Shen, Wenqi Wang, Yuntao Li, Qingping Yang, Shuangzhi Wu.
  * https://arxiv.org/abs/2505.11896

* **Learning when to think: Shaping adaptive reasoning in R1-style models via multi-stage RL**
  * Songjun Tu, Jiahao Lin, Qichao Zhang, Xiangyu Tian, Linjing Li, Xiangyuan Lan, Dongbin Zhao.
  * https://arxiv.org/abs/2505.10832

* **Ada-R1: Hybrid-CoT via bi-level adaptive reasoning optimization**
  * ***Simple Note📕: Collect data to conduct DPO. Based on group accuracy and length to gather preference pairs.***
  * Haotian Luo, Haiying He, Yibo Wang, Jinluan Yang, Rui Liu, Naiqiang Tan, Xiaochun Cao, Dacheng Tao, Li Shen.
  * https://arxiv.org/abs/2504.21659

## Early Exit

* **Think or not? Exploring thinking efficiency in large reasoning models via an information-theoretic lens⭐**
  * ***Simple Note📕: First analysis the infomation bias and information gain. Then use Entropy as threshold to perform dynamic early exit. Great Performance.***
  * Xixian Yong, Xiao Zhou, Yingying Zhang, Jinlin Li, Yefeng Zheng, Xian Wu.
  * https://arxiv.org/abs/2505.18237

* **Dynamic Early Exit in Reasoning Models⭐**
    * ***Simple Note📕: A training-free method that monitors for reasoning transition tokens (e.g., `Wait`), induces a trial answer, and performs an early exit if the model's confidence in that answer is high.***
    * Chenxu Yang, Qingyi Si, Yongjie Duan, Zheliang Zhu, Chenyu Zhu, Qiaowei Li, Zheng Lin, Li Cao, Weiping Wang.
    * https://arxiv.org/abs/2504.15895
  
* **Reasoning Models Know When They're Right: Probing Hidden States for Self-Verification⭐**
  * ***Simple Note📕: Trains an MLP probe on the model's last-layer hidden states to verify the correctness of intermediate answers, enabling early-exit to reduce overthinking.***
  * Anqi Zhang, Yulin Chen, Jane Pan, Chen Zhao, Aurojit Panda, Jinyang Li, He He.
  * https://arxiv.org/abs/2504.05419

## Outside Switcher-based Solution

* **Steering LLM Thinking with Budget Guidance⭐**
  * ***Simple Note📕: A fine-tuning-free method using a lightweight predictor that models the remaining reasoning length as a Gamma distribution to guide the LLM's generation towards a target budget.***
  * Junyan Li, Wenshuo Zhao, Chuang Gan, Yang Zhang.
  * https://arxiv.org/abs/2506.13752

* **Long or short CoT? Investigating instance-level switch of large reasoning models⭐**
  * ***Simple Note📕: Using R1-7B as switcher, prompt engineering or SFT for selection***
  * Ruiqi Zhang, Changyi Xiao, Yixin Cao.
  * https://arxiv.org/abs/2506.04182

* **ThinkSwitcher: When to think hard, when to think fast⭐**
  * ***Simple Note📕: Using MLP as switcher, group accuracy as label***
  * Guosheng Liang, Longguang Zhong, Ziyi Yang, Xiaojun Quan.
  * https://arxiv.org/abs/2505.14183

## Latent Reasoning Thinking

* **On Reasoning Strength Planning in Large Reasoning Models⭐**
  * ***Simple Note📕: Finds that LRMs pre-plan reasoning length via a directional vector in activations (found by the difference in means of hard/easy questions), which can be steered to control reasoning token count.***
  * Leheng Sheng, An Zhang, Zijian Wu, Weixiang Zhao, Changshuo Shen, Yi Zhang, Xiang Wang, Tat-Seng Chua.
  * https://arxiv.org/abs/2506.08390

* **Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space⭐**
  * ***Simple Note📕: A training-free method that uses a probability-weighted mixture of token embeddings to create 'concept tokens', enabling reasoning in a continuous space to explore multiple paths implicitly.***
  * Zhen Zhang, Xuehai He, Weixiang Yan, Shuohang Wang, Yelong Shen, Ao Shen, Chenyang Zhao, Xin Eric Wang.
  * https://arxiv.org/abs/2505.15778

## Other Methods
* **Flexible Realignment of Language Models**
  * Wenhong Zhu, Ruobing Xie, Weinan Zhang, Rui Wang.
  * https://arxiv.org/pdf/2506.12704

* **Overclocking LLM reasoning: Monitoring and controlling thinking path lengths in LLMs**
  * ***Simple Note📕: training a regressor to identify the reasoning progress, and can make an intervention to make LRM think shorter.***
  * Roy Eisenstadt, Itamar Zimerman, Lior Wolf
  * https://arxiv.org/abs/2506.07240

## Long-CoT Compression

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Trae1ounG/Awesome-LLM-Adaptive-Thinking&type=Date)](https://star-history.com/#Trae1ounG/Awesome-LLM-Adaptive-Thinking&Date)