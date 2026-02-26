---
layout: post
toc: true
title: "科研成果"
categories: junk
tags: [markdown, css, html]
author:
  - 夏元俊
---

## 期刊论文
[1] Xia Yuanjun, Tan Zhiyuan, Li Meng, Zhang Pengfei, Yu Lele, Dong Shi, Liu Yining*. Communication-Efficient and Byzantine-Tolerant Federated Learning for Mobile Edge Computing[J], IEEE Transactions on Mobile Computing（返修中）
[2] Xia Yuanjun, Zhang Pengfei*, Zhang Zuoli, Meng Weizhi, Li Meng, Dong Shi, Liu Yining*. Verifiable and Byzantine-Robust Differential Private Federated Learning [J], IEEE Transactions on Dependable and Secure Computing（返修中）
[3] Xia Yuanjun, Liu Yining*, Dong Shi, Li Meng, Guo Cheng. SVCA: Secure and Verifiable Chained Aggregation for Privacy-Preserving Federated Learning[J], IEEE Internet of Things Journal, 11(10): 18351-18365, 2024 （2024年中科院一区TOP，CCF C）
[4] Xia Yuanjun, Liu Yining, Cheng Jingxue, Liang Yangfan, Khan Fazlullah*, Alturki Ryan, Wang Xiaopei. TEVA: Training-Efficient and Verifiable Aggregation for Federated Learning for Consumer Electronics in Industry 5.0[J]. IEEE Transactions on Consumer Electronics, 71(2):4248-4264, 2025. （中科院二区）
[5] 夏元俊,黎利辉,任舒扬,余乐乐,刘忆宁*.面向VANETs身份持续认证的隐私保护联邦学习方案[J].电讯技术,65(07):1007-1015,2025.（北大中文核心）
[6] Dong Shi, Xia Yuanjun*, Wang Tao. Network Abnormal Traffic Detection Framework Based on Deep Reinforcement Learning [J], IEEE Wireless Communication, 31(3): 185-193, 2024. （2024年中科院一区TOP，通信作者）
[7] Dong Shi*, Xia Yuanjun, Peng Tao. Network abnormal traffic detection model based on semi-supervised deep reinforcement learning[J]. IEEE Transactions on Network and Service Management, 18(4): 4197-4212, 2021. (中科院二区，CCF C, 导师第一，谷歌学术引用量 223)
[8] Dong Shi*, Xia Yuanjun. Network traffic identification in packet sampling environment[J]. Digital Communications and Networks, 9(4):957-970, 2023. (中科院一区, 导师第一)
[9] Dong Shi*, Xia Yuanjun, Kamruzzaman Joarder. Quantum Particle Swarm Optimization for Task Offloading in Mobile Edge Computing [J]. IEEE Transactions on Industrial Informatics, 19(8): 9113-9122, 2023.（中科院一区，CCF C, 导师第一，谷歌学术引用量 92）
[10] Dong Shi*, Xia Yuanjun, Peng Tao. Traffic identification model based on generative adversarial deep convolutional network[J]. Annals of Telecommunications, 77(9): 573-587, 2022. (中科院四区, 导师第一)
[11] Dong Shi, Su Huadong, Xia Yuanjun, Zhu Fei*, Hu Xinrong, Wang Bangcao. A Comprehensive Survey on Authentication and Attack Detection Schemes That Threaten It in Vehicular Ad-Hoc Networks[J]. IEEE Transactions on Intelligent Transportation Systems, 24(12): 13573-13602, 2023. （2023年中科院一区TOP，CCF B）
[12] Liang Yangfan, Liu Gao, Zhang Xianchao, Chen Yiming, Chen Jingxue, Xia Yuanjun, Liu Yining. Fully Anonymous Broadcast Signcryption for Secure Health Data Transmission in WBANs[J]. IEEE Transactions on Mobile Computing, 25(2):1729-1743, 2026. （中科院一区TOP，CCF A）
[13] Dong Shi, Shu Longhui, Xia Qingyu, Kamruzzaman Joarder, Xia Yuanjun, Peng Tao. Device Identification Method for Internet of Things Based on Spatial-Temporal Feature Residuals[J]. IEEE Transactions on Services Computing, 17(6):3400-3416, 2024. （中科院一区TOP，CCF A）
[14] Zhao Zhiqiang, Hu Xuexian, Liu Yining, Wei Jianghong, Xia Yuanjun, Liang Yangfan. SECP-AKE: Secure and efficient certificateless-password-based authenticated key exchange protocol for smart healthcare systems[J]. IEEE Transactions on Services Computing, 17(6):3400-3416, 2024. （中科院三区，CCF B）

## 会议论文
[1] Xia Yuanjun, Dong Shi*, Peng Tao, Wang Tao. Wireless Network Abnormal Traffic Detection Method Based on Deep Transfer Reinforcement Learning[C]. 2021 17th International Conference on Mobility, Sensing and Networking (MSN), 528-535, 2021. (CCF C)

<!-- 保留你原有的布局样式，确保正文拓宽+侧边栏左移生效 -->
<style>
  /* 1. 双栏布局容器：取消最大宽度限制，占满页面 */
  .resume-layout {
    display: flex;
    gap: 0 !important; /* 取消侧边栏和正文间隙 */
    max-width: 100% !important; /* 布局占满整个页面宽度 */
    margin: 0 !important; /* 取消默认居中边距 */
    padding: 0 !important;
  }

  /* 2. 侧边栏：移到页面最左侧，宽度不变 */
  .sidebar {
    width: 280px !important; /* 保留原侧边栏宽度，可按需改 */
    flex-shrink: 0 !important;
    margin-left: 0 !important; /* 贴紧页面最左侧 */
    padding: 20px 15px !important; /* 内边距，内容不贴边 */
  }

  /* 3. 正文区域：彻底拓宽，占满剩余所有宽度 */
  .content {
    flex: 1 !important; /* 占满侧边栏右侧所有空间 */
    max-width: calc(100% - 280px) !important; /* 宽度=页面总宽-侧边栏宽 */
    width: calc(100% - 280px) !important;
    padding: 20px 30px !important; /* 正文内边距，避免贴边 */
    margin: 0 !important; /* 取消默认边距 */
  }

  /* 4. 响应式适配：手机端恢复原布局，避免错乱 */
  @media (max-width: 768px) {
    .resume-layout {
      flex-direction: column !important;
    }
    .sidebar {
      width: 100% !important;
      margin-left: 0 !important;
    }
    .content {
      max-width: 100% !important;
      width: 100% !important;
      margin-left: 0 !important;
    }
  }

  /* 新增：优化论文列表排版，更符合学术简历风格 */
  .post-content p {
    line-height: 1.8 !important; /* 行高更舒展，便于阅读长论文条目 */
    margin-bottom: 12px !important; /* 每条论文间留间距 */
  }
  .post-content h2 {
    border-bottom: 2px solid #0066cc !important; /* 标题下划线，和链接色一致 */
    padding-bottom: 8px !important;
    margin: 30px 0 20px 0 !important;
  }
</style>
