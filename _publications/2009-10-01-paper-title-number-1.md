---
title: "Inferring Diffusion Networks without Timestamps (UNDER REVIEW)"
collection: publications
permalink: /publication/paper_1
excerpt: ''
date: 2018-10-01
venue: 'ICDE 2019 (UNDER REVIEW)'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: ''
---
Authors: Hao Huang, Qian Yan, Yunjia Zhang, Yueming Sun, Wei Lu, Yunjun Gao

Abstract: To infer the structures of diffusion networks, most existing approaches require not only the final infection statuses of network nodes, but also the timestamps that pinpoint the exact time when infections of the nodes occur. Nonetheless, in many natural diffusion processes such as the spread of epidemics, monitoring the exact infection timestamps is often difficult and expensive. In this work, we investigate the problem of inferring the diffusion network structures without infection timestamps, using only the final infection statuses of nodes. Instead of utilizing the sequence of timestamps to determine the potential parent-child influence relationships between the nodes, we design a probabilistic generative model of the final infection statuses to quantitatively measure the likelihood of potential structures of the objective diffusion network, taking into account network complexity. Then, for each node in the network, we can infer an appropriate number of most probable parent nodes. Furthermore, in order to reduce redundant computation during the inference, we preclude a few insignificant candidate parent nodes from being considered in the inference, if their infections have very weak correlations with the infections of the corresponding child nodes. Extensive experiments on both synthetic and real-world networks are conducted, and the results verify the effectiveness and efficiency of our approach.
