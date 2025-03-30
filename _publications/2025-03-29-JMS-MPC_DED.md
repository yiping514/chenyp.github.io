---
title: "Real-Time Decision-Making for Digital Twin in Additive Manufacturing with Model Predictive Control using Time-Series Deep Neural Networks"
collection: publications
category: manuscripts
permalink: /publications/2025-03-29-JMS-MPC_DED
excerpt: "<img src='https://yiping514.github.io/chenyp.github.io/images/JMS_MPC_DED.jpg'>"
date: 2025-03-29
venue: 'Journal of Manufacturing Systems'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://yiping514.github.io/chenyp.github.io/files/2025_JMS_MPC_DED.pdf'
citation: 'Chen, Y.-P., Karkaria, V., Tsai, Y.-K., Rolark, F., Quispe, D., Gao, R. X., Cao, J., & Chen, W., &quot;Real-time decision-making for Digital Twin in additive manufacturing with Model Predictive Control using time-series deep neural networks.&quot; <i>Journal of Manufacturing Systems<i>, 80(2025): 412-424.'
---

Digital Twin-a virtual replica of a physical system enabling real-time monitoring, model updating, prediction, and decision-making-combined with recent advances in machine learning (ML), offers new opportunities for proactive control strategies in autonomous manufacturing. However, achieving real-time decision-making with Digital Twins requires efficient optimization driven by accurate predictions of highly nonlinear manufacturing systems. This paper presents a simultaneous multi-step Model Predictive Control (MPC) framework for real-time decision-making, using a multi-variate deep neural network (DNN), named Time-Series Dense Encoder (TiDE), as the surrogate model. Different from the models in conventional MPC which only provide one-step ahead prediction, TiDE is capable of predicting future states within the prediction horizon in one shot (multi-step), significantly accelerating MPC. Using Directed Energy Deposition (DED) additive manufacturing (AM) as a case study, we demonstrate the effectiveness of the proposed MPC in achieving melt pool temperature tracking to ensure part quality, while reducing porosity defects by regulating laser power to maintain melt pool depth constraints. In this work, we first show that TiDE is capable of accurately predicting melt pool temperature and depth. Second, we demonstrate that the proposed MPC achieves precise temperature tracking while satisfying melt pool depth constraints within a targeted dilution range (10%-30%), reducing potential porosity defects. Compared to Proportional-Integral-Derivative (PID) controller, MPC results in smoother and less fluctuating laser power profiles with competitive or superior melt pool temperature control performance. This demonstrates MPC's proactive control capabilities, leveraging time-series prediction and real-time optimization, positioning it as a powerful tool for future Digital Twin applications and real-time process optimization in manufacturing.

Keywords: _Digital Twin, Additive manufacturing, Model Predictive Control, Time-seriesDeep neural network, Directed energy deposition_

<img src="https://yiping514.github.io/chenyp.github.io/images/JMS_MPC_DED.jpg" alt="Proposed method for the simultaneous multistep MPC for DED.">
