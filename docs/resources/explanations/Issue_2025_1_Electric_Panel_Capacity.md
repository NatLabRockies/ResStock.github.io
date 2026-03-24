---
layout: default
title: ResStock 2025 Release 1 Electric Panel Capacity
parent: Resources
nav_order: 16
---

# Issue Report: ResStock 2025 Release 1 Electric Panel Capacity
## Summary of Issue
Electric panel results are new in the ResStock 2025 Release 1 dataset. After the dataset release, the ResStock team found an error in the electric panel results for a few of the measures in the ResStock 2025 Release 1 AMY2018 and AMY2012 datasets.

In short, some of the upgraded measures energy loads are being counted as a new load, when they should not be. This causes electric panel capacity constraints to increase in some measures, when  the electric panel capacity should actually decrease because the new upgraded load is more efficient than the baseline load. This issue currently impacts the following three measures only in the ResStock 2025 Release 1 dataset: 
•	Natural Gas Furnace 95% AFUE
•	Propane Furnace 95% AFUE or Fuel Oil Furnace 88% AFUE
•	Reference Space Heating and Air Conditioning Upgrade Circa 2025

Only when the column **applicability** has a value of “True” does this issue occur. For the Natural Gas Furnace 95% AFUE measure, the issue impacts about 75% of all samples across the dataset. For the Propane Furnace 95% AFUE or Fuel Oil Furnace 88% AFUE, the issue impacts about 6% of all samples across the dataset. Finally, for the Reference Space Heating and Air Conditioning Upgrade Circa 2025 measure, the issue impacts about 75% of all samples across the dataset.

This issue impacts the following annual result columns:
- out.params.panel_load_total_load.2023_nec_existing_dwelling_load_based..w 
- out.params.panel_load_occupied_capacity.2023_nec_existing_dwelling_load_based..a
- out.params.panel_load_headroom_capacity.2023_nec_existing_dwelling_load_based..a
- out.params.panel_load_cooling..w
- out.params.panel_load_heating.w
- out.params.panel_load_total_load_savings.2023_nec_existing_dwelling_load_based..w
- out.params.panel_load_occupied_capacity_savings.2023_nec_existing_dwelling_load_based..a
- out.params.panel_constraint_capacity.2023_nec_existing_dwelling_load_based
- out.params.panel_constraint_overall.2023_nec_existing_dwelling_load_based

The electric panel space calculations are not impacted at all. This issue is only relevant for any capacity-related results.

**Right now, the ResStock team recommends avoiding using these columns in these measures while a work around is determined and this issue is investigated more in depth.**