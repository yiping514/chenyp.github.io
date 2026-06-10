---
title: "Real-Time Decision-Making for Digital Twin in Additive Manufacturing with Model Predictive Control"
collection: talks
type: "Webinar Keynote"
permalink: /talks/2026-06-SME
venue: "SME Manufacturing Edge Webinar Series - Ideas Shaping Manufacturing's Future"
date: 2026-06-02
location: "Virtual"
---

[Link to SME Webinar](https://www.advancedmanufacturing.org/resources/webinars/)

<img src="https://yiping514.github.io/chenyp.github.io/images/SME_webinar.png" alt="talk photo">


Digital Twins integrated with recent advances in machine learning enable new opportunities for proactive control in autonomous manufacturing. Achieving real-time decision-making, however, requires fast optimization supported by accurate predictions of highly nonlinear process dynamics. In this talk, we present a simultaneous multi-step Model Predictive Control (MPC) framework that leverages a multivariate deep neural network, the Time-Series Dense Encoder (TiDE), as a surrogate model. Unlike conventional MPC approaches that rely on one-step-ahead predictions, TiDE directly forecasts the entire future state trajectory over the prediction horizon in a single pass, substantially improving computational efficiency for real-time control. Using Directed Energy Deposition (DED) additive manufacturing as a case study, we demonstrate that the proposed framework achieves precise melt pool temperature tracking to ensure part quality, while actively mitigating porosity defects by enforcing melt pool depth constraints through laser power regulation. Compared to a PID controller, the proposed MPC delivers superior temperature tracking performance while simultaneously satisfying process constraints. We further extend the framework to incorporate aleatoric uncertainty quantification, enabling robust decision-making under stochastic disturbances, as well as continual validation and adaptation to process drift. These capabilities highlight the proactive and adaptive nature of the proposed approach, integrating time-series prediction, uncertainty quantification, and real-time optimization, and positioning it as a powerful paradigm for next-generation Digital Twin–enabled manufacturing systems.

