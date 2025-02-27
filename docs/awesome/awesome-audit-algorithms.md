<div class="github-widget" data-repo="erwanlemerrer/awesome-audit-algorithms"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Audit Algorithms [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

用于审计黑盒算法的精选算法列表.
如今，许多算法（推荐、评分、分类）都在第三方提供商处运行，而用户或机构对他们如何处理数据没有任何见解. 因此，此列表中的审核算法适用于此设置，创造了“黑盒”设置，其中一位审核员希望对这些远程算法有所了解.

<img src="https://raw.githubusercontent.com/erwanlemerrer/awesome-audit-algorithms/blob/main/resources/audit.png" width="600" alt="banner" class="center">

&gt; 用户查询远程算法（例如，通过可用的 API），以推断有关该算法的信息.


## Papers
### 2022
- [Look at the Variance! Efficient Black-box Explanations with Sobol-based Sensitivity Analysis](https://proceedings.neurips.cc/paper/2021/file/da94cbeff56cfda50785df477941308b-Paper.pdf) - (NeurIPS) *Sobol 指数提供了一种有效的方法来捕获图像区域之间的高阶交互以及它们通过方差透镜对（黑盒）神经网络预测的贡献.*
- [Your Echos are Heard: Tracking, Profiling, and Ad Targeting in the Amazon Smart Speaker Ecosystem](https://arxiv.org/pdf/2204.10920.pdf) - (arxiv) *推断 Amazon Echo 系统和广告定位算法之间的联系.*
### 2021
- [Auditing Black-Box Prediction Models for Data Minimization Compliance](https://www.cs.bu.edu/faculty/crovella/paper-archive/minimization-audit-Neurips21.pdf) - (NeurIPS) *使用有限数量的查询测量预测模型满足的数据最小化水平.*
- [Setting the Record Straighter on Shadow Banning](https://arxiv.org/abs/2012.05101) - (INFOCOM)  [(Code)](https://gitlab.enseeiht.fr/bmorgan/infocom-2021) *考虑 Twitter 中禁止影子的可能性（即适度黑盒算法），并测量几个假设的概率.*
- [FairLens: Auditing black-box clinical decision support systems](https://www.sciencedirect.com/science/article/pii/S030645732100145X?casa_token=oyjFKij269MAAAAA:w_ohScpMPNMnkDdzBqAIod5QfBgQlq5Ht9mMRSOydZpOgNG-i1yuqEmBjWN__38gOGmjNL7dVT0) -（信息处理和管理）*通过比较不同的多标签分类差异度量，提供检测和解释临床 DSS 中潜在公平问题的管道.*
- [Auditing Algorithmic Bias on Twitter](https://dl.acm.org/doi/abs/10.1145/3447535.3462491) - （网络科学）.
- [Bayesian Algorithm Execution: Estimating Computable Properties of Black-box Functions Using Mutual Information](https://proceedings.mlr.press/v139/neiswanger21a.html) - (ICML) *一种预算受限和贝叶斯优化程序，用于从黑盒算法中提取属性.*
### 2020
- [Black-Box Ripper: Copying black-box models using generative evolutionary algorithms](https://proceedings.neurips.cc/paper/2020/file/e8d66338fab3727e34a9179ed8804f64-Paper.pdf) - (NeurIPS) *复制黑盒神经模型的功能，但对查询数量没有限制（通过教师/学生方案和进化搜索）.*
- [Auditing radicalization pathways on YouTube](https://dl.acm.org/doi/pdf/10.1145/3351095.3372879) - (FAT*) *研究激进频道彼此之间的可达性，在静态频道推荐上使用随机游走.*
- [Adversarial Model Extraction on Graph Neural Networks](https://arxiv.org/abs/1912.07721) -（AAAI 图深度学习研讨会：方法和应用）*介绍 GNN 模型提取并为此提供初步方法.*
- [Remote Explainability faces the bouncer problem](https://rdcu.be/b6qB4) -（自然机器智能第 2 卷，第 529-539 页）  [(Code)](https://github.com/erwanlemerrer/bouncer_problem) *表明不可能（有一个请求）或难以发现在于远程 AI 决策的解释.*
- [GeoDA: a geometric framework for black-box adversarial attacks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rahmati_GeoDA_A_Geometric_Framework_for_Black-Box_Adversarial_Attacks_CVPR_2020_paper.pdf) - (CVPR)  [(Code)](https://github.com/thisisalirah/GeoDA) *在纯黑盒设置中制作对抗性示例以欺骗模型（无渐变，仅推断类）.*
- [The Imitation Game: Algorithm Selectionby Exploiting Black-Box Recommender](https://github.com/erwanlemerrer/erwanlemerrer.github.io/raw/master/files/imitation_blackbox_recommenders_netys-2020.pdf) - （网）  [(Code)](https://github.com/gdamaskinos/RecRank) *通过模仿远程和训练有素的决策来参数化本地推荐算法.*
- [Auditing News Curation Systems:A Case Study Examining Algorithmic and Editorial Logic in Apple News](https://ojs.aaai.org/index.php/ICWSM/article/view/7277) - (ICWSM) *将 Apple News 作为社会技术新闻策展系统的审计研究（趋势故事部分）.*
- [Auditing Algorithms:  On Lessons Learned and the Risks of DataMinimization](https://dl.acm.org/doi/pdf/10.1145/3375627.3375852) - (AIES) *由 Telefónica 开发的幸福感推荐应用程序的实际审计（主要基于偏见）.*
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805) - (arxiv) *执行训练数据提取攻击，通过查询语言模型来恢复单个训练示例.*
### 2019
- [Adversarial Frontier Stitching for Remote Neural Network Watermarking](https://arxiv.org/abs/1711.01894) - （神经计算与应用） [(Alternative implementation)](https://github.com/dunky11/adversarial-frontier-stitching) *检查远程机器学习模型是否为“泄露”模型：通过对远程模型的标准 API 请求，提取（或不提取）一个零位水印，该水印被插入到水印有价值的模型（例如，大型深度神经网络）中.*
- [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) - （CVPR）*询问对手可以在多大程度上窃取此类“受害者”模型的功能，仅基于黑盒交互：图像输入，预测输出.*
- [Opening Up the Black Box:Auditing Google's Top Stories Algorithm](https://par.nsf.gov/servlets/purl/10101277) - (Flairs-32) *对 Google 的热门故事面板进行审核，该面板提供了对其算法选择的见解，用于选择和排名新闻出版商*
- [Making targeted black-box evasion attacks effective andefficient](https://arxiv.org/pdf/1906.03397.pdf) - (arXiv) *调查对手如何最佳地使用其查询预算来针对深度神经网络进行有针对性的规避攻击.*
- [Online Learning for Measuring Incentive Compatibility in Ad Auctions](https://research.fb.com/wp-content/uploads/2019/05/Online-Learning-for-Measuring-Incentive-Compatibility-in-Ad-Auctions.pdf) - （WWW）*衡量黑盒拍卖平台的激励兼容-（IC）机制（遗憾）.* 
- [TamperNN: Efficient Tampering Detection of Deployed Neural Nets](https://arxiv.org/abs/1903.00317) - （ISSRE）*制作输入的算法可以检测远程执行的分类器模型的篡改.*
- [Neural Network Model Extraction Attacks in Edge Devicesby Hearing Architectural Hints](https://arxiv.org/pdf/1903.03916.pdf) - (arxiv) *通过总线Snooping获取内存访问事件，LSTM-CTC模型层序识别，根据内存访问模式进行层拓扑连接，数据量约束下层维估计，证明可以准确恢复与攻击起点类似的网络架构*
- [Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data](https://ieeexplore.ieee.org/abstract/document/8851798) - (ICNN) *可用于攻击和提取黑盒模型知识的复合方法，即使它完全隐藏了它的 softmax 输出.*
- [Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment](https://dl.acm.org/citation.cfm?id=3354261)  - (CCS) *在对手设置中的模型反演方法基于训练一个反演模型，该模型作为原始模型的反演. 在不完全了解原始训练数据的情况下，仍然可以通过在从更通用的数据分布中提取的辅助样本上训练反演模型来进行准确的反演.*
### 2018
- [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) - (ICLR) [(Code)](https://github.com/coallaoh/WhitenBlackBox) *通过分析其对某些输入的响应模式来推断远程神经网络模型的内部超参数（例如层数、非线性激活类型）.*
- [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) -（神经计算）*反向工程远程分类器模型（例如，用于逃避验证码测试）.*
- [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf)  - (arXiv) *通过训练无监督的隐式生成模型来搜索黑盒模型中的偏差. 然后通过扰动数据流形上的数据样本来定量地总结黑盒模型的行为. *
- [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) - (NIPS) *通过观察一些随机步行通勤时间来反转图表.*
- [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) - (CAEPIA) *确定返回的预测背后是哪种机器学习模型.* 
- [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) - (arXiv) *通过使用查询的定时攻击窃取/近似模型.*
- [Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data](https://arxiv.org/abs/1806.05476) - （IJCNN）  [(Code)](https://github.com/jeiks/Stealing_DL_Models) *通过使用随机自然图像（ImageNet 和 Microsoft-COCO）查询黑盒模型 (CNN) 知识来窃取它们.*
- [Auditing the Personalization and Composition ofPolitically-Related Search Engine Results Pages](https://dl.acm.org/doi/10.1145/3178876.3186143) - (WWW) *一个 Chrome 扩展，用于调查参与者并收集搜索引擎结果页面 (SERP) 和自动完成建议，用于研究个性化和组合.* 
### 2017
- [Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) - (CSCW) *旨在确定在同行排名服务中使用了哪些中心性指标.*
- [The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) -（复杂网络）*为推荐给用户的项目提出一个偏差检测框架.*
- [Membership Inference Attacks Against Machine Learning Models](http://ieeexplore.ieee.org/document/7958568/) - (Symposium on Security and Privacy) *给定一个机器学习模型和一个记录，确定这个记录是否被用作模型训练数据集的一部分.*
- [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) - （亚洲 CCS）*了解远程服务对对抗性分类攻击的脆弱性.*
### 2016
- [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) - (dat Workshop) *测量TaskRabbit的搜索算法排名.* 
- [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) - （Usenix 安全）  [(Code)](https://github.com/ftramer/Steal-ML) *旨在提取远程服务使用的机器学习模型.*
- [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) - (arXiv)  [(Code)](https://github.com/marcotcr/lime-experiments) *通过围绕数据实例进行采样来解释黑盒分类器模型.*
- [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) -（安全和隐私）*消毒剂和过滤器的黑盒分析.*
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) - （安全和隐私）*引入衡量输入对观察系统输出的影响程度的措施.*
### 2015
- [Peeking Beneath the Hood of Uber](https://dl.acm.org/citation.cfm?id=2815681) - (IMC) *推断 Uber 飙升价格算法的实现细节.*
### 2014
- [XRay: Enhancing the Web's Transparency with Differential Correlation](https://www.usenix.org/node/184394) - （USENIX 安全性）*审核用于定位特定广告、推荐或价格的用户配置文件数据.*
### 2013
- [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) - (WWW) *开发了一种衡量网络搜索结果个性化的方法.*
### 2012
- [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html)  - (JMLR) *凸分类器的规避方法. 考虑规避复杂性.*
### 2008
- [Privacy Oracle: a System for Finding Application Leakswith Black Box Differential Testing](https://dl.acm.org/citation.cfm?id=1455806) - (CCS) *Privacy Oracle：一个发现应用程序在传输到远程服务器时泄露个人信息的系统.*
### 2005
- [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) - (KDD) *远程线性分类器的逆向工程，使用成员查询.*
