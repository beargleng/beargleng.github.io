---
title: "The Intrinsic Timing Relationship Between Tropical Cyclone Maximum Intensification Rate and Lifetime Maximum Intensity"
collection: publications
category: manuscripts
permalink: /publication/2025-05-05-mir-lmi-timing
excerpt: "The intensification rate (IR) equation, derived from a time-dependent simplified energetically based dynamical system (EBDS), links tropical cyclone (TC) intensity, IR, and their evolutions, suggesting a connection between the timing of TC lifetime maximum intensity (LMI) and the maximum intensification rate (MIR). This study demonstrates that the IR equation predicts MIR typically preceding LMI within 36 hr, as confirmed by numerical simulation and analysis of best track data. It was observed that the majority of global TCs reached LMIs within 36 hr after MIR from 1982 to 2023. This consistency between observational data, numerical simulations, and analytical results highlights the EBDS-based IR equation's ability to capture the timing relationship between MIR and LMI. This intrinsic link highlights the importance of understanding the timing of MIR in the evolution of TCs."
date: 2025-05-05
venue: "Geophysical Research Letters"
slidesurl: "https://academicpages.github.io/files/slides1.pdf"
paperurl: "https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1029/2024GL113158"
citation: "Xiong, Q., & Wu, Q. (2025). The intrinsic timing relationship between tropical cyclone maximum intensification rate and lifetime maximum intensity. Geophysical Research Letters, 52, e2024GL113158."
---
## Summary

The severity of tropical cyclone (TC) related hazards is closely linked to the intensity that a storm ultimately attains, and lifetime maximum intensity (LMI) is a key metric for characterizing TC intensity. Previous studies have mainly focused on the maximum intensity that TCs may potentially reach, whereas the timing of reaching LMI has received less attention. Based on an intensification rate (IR) equation derived from a time dependent simplified energetically based dynamical system (EBDS), this study shows that the maximum intensification rate (MIR) typically occurs within 36 hours before LMI. This conclusion is supported by both numerical simulations and observational best-track dataset.

<figure>
  <img src="/images/publications/mir-lmi/fig1.png" alt="Timing difference between MIR and LMI as a function of MPI and initial intensity" style="width:100%; max-width:850px;">
  <figcaption><strong>Figure 1.</strong> Timing difference between the maximum intensification rate and lifetime maximum intensity as a function of maximum potential intensity and initial intensity. (a) Analytical solution; (b) numerical solution.</figcaption>
</figure>

By nondimensionalizing and solving the time dependent TC IR equation, this study obtains a theoretical relationship between the timing of MIR and LMI:

$$
\Delta t = \frac{\Delta t^*}{\kappa V_{\mathrm{MPI}}}
$$

where \(\Delta t^*\) is a nondimensional constant, $\kappa$ is an environmental parameter that can be treated as approximately constant, and \(V_{\mathrm{MPI}}\) is the maximum potential intensity. This relationship indicates that the timing difference between MIR and LMI is inversely proportional to the maximum potential intensity, suggesting that a larger MPI generally corresponds to a shorter MIR–LMI time interval.

<figure>
  <img src="/images/publications/mir-lmi/fig2.png" alt="WRF idealized simulations of TC intensity evolution and MIR-LMI timing difference" style="width:100%; max-width:850px;">
  <figcaption><strong>Figure 2.</strong> (a) TC intensity evolution in idealized WRF simulations, with thin lines indicating individual experiments and thick lines indicating ensemble means for each group. (b) Boxplots of the timing difference between the maximum intensification rate and lifetime maximum intensity for each group of experiments.</figcaption>
</figure>

The theoretical results are further evaluated using idealized WRF simulations. Four sea surface temperature conditions are used to regulate the maximum potential intensity (MPI) of simulated TCs, with 10 independent experiments conducted for each group. The simulations show that the timing difference between MIR and LMI decreases as sea surface temperature, and thus maximum potential intensity, increases. The simulated MIR–LMI timing difference is generally within approximately 36 hours.

<figure>
  <img src="/images/publications/mir-lmi/fig3.png" alt="Frequency distributions of the timing difference between MIR and LMI for global tropical cyclones from 1982 to 2023" style="width:100%; max-width:850px;">
  <figcaption><strong>Figure 3.</strong> Frequency distributions of the timing difference between the maximum intensification rate and lifetime maximum intensity for global tropical cyclones during 1982–2023. (a–c) MIR timing is defined as the ending time of the intensification event. (d–f) MIR timing is defined as the midpoint time of the intensification event.</figcaption>
</figure>

Statistical analyses of observational best-track dataset show that the timing difference between MIR and LMI for global TCs during 1982–2023 is mostly within 36 hours. This feature is broadly consistent across different ocean basins and TC intensity categories. The agreement among theoretical analysis, numerical simulations, and observations suggests that the time-dependent energetically based dynamical system effectively captures the intrinsic timing relationship between MIR and LMI. This intrinsic link highlights the importance of understanding the timing of MIR for interpreting TC intensity evolution.

---

## 本文简介

热带气旋造成的灾害程度与其达到的强度密切相关，而生命史最大强度是衡量热带气旋强度的关键指标。现有研究多关注热带气旋可能达到的最大强度，却较少探讨其达到最大强度的具体时间。本研究基于时间依赖的基于能量的简单动力学系统推导的增强率方程发现，最大增强率通常出现在生命史最大强度前 36 小时内。这一结论得到了数值模拟和观测数据的双重验证。

本研究通过无量纲化方法求解了时间依赖的热带气旋增强率方程，并得到了理论上最大增强率与生命史最大强度之间的函数关系：

$$
\Delta t = \frac{\Delta t^*}{\kappa V_{\mathrm{MPI}}}
$$

其中，\(\Delta t^*\) 是无量纲常数，\(\kappa\) 是一个可近似看作常值的环境参数，\(V_{\mathrm{MPI}}\) 是热带气旋最大潜在强度。该方程表明，热带气旋最大增强率与生命史最大强度之间的时间差与最大潜在强度成反比关系，即更高的最大潜在强度通常对应更短的 MIR–LMI 时间间隔。

本研究进一步使用 WRF 理想实验对理论结果进行了验证。四组不同的海温状态用于控制热带气旋最大潜在强度的大小，每组实验包含 10 次独立运行。结果表明，模式理想台风的最大增强率与生命史最大强度之间的时间差与海温大小，也即最大潜在强度大小，呈反比关系，并且该时间差大致位于 36 小时以内。

观测数据的统计结果显示，1982–2023 年全球热带气旋的最大增强率与生命史最大强度之间的时间差主要分布在 36 小时以内，并且这一特征在不同海盆和不同强度等级的热带气旋中均较为稳定。观测数据、数值模拟与理论分析结果的一致性表明，时间依赖的基于能量的简单动力学系统能够有效捕捉热带气旋最大增强率与生命史最大强度之间的内在时间关系。这一内在关系凸显了理解最大增强率发生时刻对于把握热带气旋强度演变规律的重要性。

