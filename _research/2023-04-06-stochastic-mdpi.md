---
title: "Parallel Stochastic Computing Architecture for Computationally Intensive Applications"
collection: research 
permalink: /research/2023-04-06-stochastic-mdpi
excerpt:'<div style="text-align: center;">
  <img src="../images/mdpi_stochastic/mdpi_sto_arch.png" alt="arch" style="display: inline-block; margin: 10px;">
  <img src="../images/mdpi_stochastic/mdpi_sto_lfsr.png" alt="board" style="display: inline-block; margin: 10px;">
</div>'


date: 2023-04-06
venue: 'Electronics'
paperurl: 'https://doi.org/10.3390/electronics12071749'
citation: '<strong>Kim, J.</strong>; Jeong, W.S.; Jeong, Y.; Lee, S.E. Parallel Stochastic Computing Architecture for Computationally Intensive Applications. Electronics 2023, 12, 1749.'
---
Stochastic computing requires random number generators to generate stochastic sequences that represent probability values. In the case of an 8-bit operation, a 256-bit length of a stochastic sequence is required, which results in latency issues. In this paper, a stochastic computing architecture is proposed to address the latency issue by employing parallel linear feedback shift registers (LFSRs). The proposed architecture reduces the latency in the stochastic sequence generation process without losing accuracy. In addition, the proposed architecture achieves area efficiency by reducing 69% of flip-flops and 70.4% of LUTs compared to architecture employing shared LFSRs, and 74% of flip-flops and 58% of LUTs compared to the architecture applying multiple LFSRs with the same computational time.

