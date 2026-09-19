---
title: 'New publication: Mean-state warming loads Germany’s extreme summer heat burden'
date: 2026-09-17
permalink: /posts/2026/09/mean-state-warming-germany-heat-burden/
tags:
  - publication
  - extreme heat
  - climate risk
  - Germany
  - global warming levels
  - environmental research letters
---

Our new paper, **“Mean-state warming loads Germany’s extreme summer heat burden,”** is now published in *Environmental Research Letters*.

The study examines how anthropogenic mean-state warming has already increased Germany’s extreme summer heat burden, and how that burden changes as global warming progresses toward +1.5 °C and +2.0 °C above pre-industrial levels.

A central aim of the work was to separate the contribution of the warming background climate from the day-to-day weather sequence that makes individual summers extreme.

## An observation-based framework

To do this, we developed **OMS — Observation-based Mean-Shift**, a counterfactual framework that preserves the observed sequence of daily weather while shifting only the seasonal mean temperature.

The idea is simple: instead of replacing an observed summer with a model-generated analogue, OMS keeps the actual daily variability of that summer intact and asks how the same weather sequence would have unfolded under a different background climate.

This makes it possible to translate observed summers into:

- pre-industrial conditions,
- the observed climate state,
- a +1.5 °C world, and
- a +2.0 °C world.

Because the day-to-day weather sequence is preserved, OMS isolates the **mean-state contribution** to heat burden rather than attempting a full event-attribution analysis.

## Germany warms faster than the global mean in summer

Using E-OBS observations together with HadCRUT5 global mean surface temperature, we estimate that Germany’s summer mean temperature increases by approximately **2.63 °C for every 1 °C of global warming**, with a 95% confidence interval of 1.62–3.62 °C.

This strong regional amplification is consistent with previous evidence that western and central European summers warm faster than the global mean.

We tested the stability of this relationship using alternative global temperature datasets and different smoothing choices, and obtained broadly consistent estimates.

## Measuring extreme-heat burden

To connect warming to an exposure-relevant quantity, we define **Extreme Heat Burden (EHD)** as the cumulative temperature exceedance above a fixed national summer 95th-percentile threshold.

This metric captures both:

- how often very hot days occur, and
- how far temperatures exceed the threshold.

We applied OMS to three recent high-impact German summers:

- **2018**
- **2019**
- **2022**

These summers were selected using a Heat Severity Index based on seasonal mean temperature anomaly, the number of hot days, and the intensity of exceedances.

## Heat burden rises strongly with warming

Across all three summers, the results show a clear increase in extreme-heat burden from pre-industrial conditions to the observed climate.

The burden increases further as the climate is translated to +1.5 °C and +2.0 °C global-warming levels.

Importantly, the increase occurs even though the observed daily weather sequence is unchanged. This means that mean-state warming alone is sufficient to substantially increase the cumulative heat burden associated with an already extreme summer.

The study therefore separates two components of heat risk:

1. the weather pattern that creates an extreme summer, and
2. the warmer climatic background on which that weather pattern now occurs.

## The burden is not distributed evenly across Germany

We also examine heat burden across Germany’s federal states.

The anthropogenic contribution is positive across the country, but its magnitude varies substantially between states and between individual summers.

For example, different regions emerge as hotspots in 2018, 2019, and 2022, illustrating how circulation and local conditions influence where the strongest burden occurs even when the national mean-state signal is coherent.

We additionally examine the burden on a per-capita basis and use Lorenz curves and Gini coefficients to assess how unevenly anthropogenic heat exposure is distributed across the population.

The per-capita analysis reveals clearer inequalities than the state-level totals alone, highlighting the importance of looking beyond national averages when considering adaptation and heat-risk planning.

## Why this matters

Expressing heat burden in terms of **global-warming levels** makes the results directly interpretable for climate-risk assessment.

Instead of asking only whether a particular heatwave was influenced by climate change, OMS asks:

> How much heat burden does the same observed weather sequence produce under different levels of background warming?

This provides a transparent way to compare:

- the anthropogenic contribution already realized today,
- the additional burden associated with +1.5 °C warming, and
- the further increase associated with +2.0 °C warming.

The framework is observation-anchored, reproducible, and portable to other regions where suitable temperature observations and global temperature records are available.

## Open and reproducible research

The analysis uses publicly available observational datasets, including E-OBS and HadCRUT5.

The code used to reproduce the OMS workflow — including the estimation of the regional warming sensitivity, temperature translation, extreme-heat burden calculation, and uncertainty analysis — is publicly available on GitHub and archived on Zenodo.

**Paper:**  
[Mean-state warming loads Germany’s extreme summer heat burden](https://doi.org/10.1088/1748-9326/aea4c9)

**Reference implementation:**  
[OMS heat burden Germany on Zenodo](https://zenodo.org/records/21005081)

**Citation:**  
Samakinwa, E., Scheiber, L., Cohrs, J.-C., Pfeifer, S., and Rechid, D. (2026). *Mean-state warming loads Germany’s extreme summer heat burden*. Environmental Research Letters, **21**, 184012.
