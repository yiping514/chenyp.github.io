---
title: "ARCO-BO: Adaptive Resource-aware COllaborative Bayesian Optimization for Heterogeneous Multi-Agent Design"
collection: publications
category: manuscripts
permalink: /publications/2026-03-09-JMD-ARCOBO
excerpt: "<img src='https://yiping514.github.io/chenyp.github.io/images/JMD_ARCOBO.png'>"
date: 2026-03-09
venue: 'Journal of Mechanical Design'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://yiping514.github.io/chenyp.github.io/files/2026_JMD_ARCOBO.pdf'
citation: 'Wang, Zihan, Chen, Yi-Ping, Dolar, Tuba, and Wei Chen. &quot;ARCO-BO: Adaptive Resource-aware COllaborative Bayesian Optimization for Heterogeneous Multi-Agent Design. &quot; <i>Journal of Mechanical Design<i> 148 (2026): 091703.'
---



Many real-world optimization problems in scientific discovery and engineering design optimization involve multiple design evaluation sources, such as simulators, experiments, or manufacturing sites, operate independently and evaluate different functions of the same underlying objective (quantity of interest). In this work, we refer to these design evaluation sources as agents. Such agents often differ in their objective function mappings, evaluation budgets, and accessible optimization variables, which complicates coordination and information sharing.
Bayesian Optimization (BO) is a widely used framework for expensive blackbox optimization, yet its standard single-agent formulation assumes centralized control and full data sharing. Recent collaborative BO methods relax these assumptions but still rely on uniform resources, fully shared input spaces, and closely aligned tasks, and these requirements are seldom met in real applications.

To address these limitations, we introduce Adaptive Resource-Aware Collaborative Bayesian Optimization (ARCO-BO), a framework that explicitly accounts for heterogeneity in multi-agent optimization. ARCO-BO integrates three key components: a similarity- and optimal-location-aware consensus mechanism for adaptive information sharing, a budget-aware asynchronous sampling strategy for resource coordination, and a partial input-space sharing scheme for heterogeneous optimization variables. Experiments on synthetic benchmarks and high-dimensional engineering optimization problems demonstrate that ARCO-BO consistently outperforms independent BO and existing consensus-based collaborative BO, achieving robust and efficient performance in complex heterogeneous multi-agent optimization settings.

Keywords: _Bayesian optimization, collaborative optimization,  resource-aware optimization, multi-agent systems, task similarity_

<img src="https://yiping514.github.io/chenyp.github.io/publications/JMD_ARCOBO.png" alt="The illustration of two agents collaborating with consensus.">





