# F1 Flux — Mitigating Predictive Bias in Formula 1 Pit Stop Data

Conducted as part of Femetronics
Date: December 2025

## Overview

F1 Flux is a Femetronics programme where a group of women used Python and machine learning to investigate predictive bias in Formula 1 pit stop data. Using disaggregation, we reduced the bias gap between top-tier and lower-tier teams by up to 92%.

## The Problem

Top-tier F1 teams produce cleaner, more consistent data due to greater resources. When a single AI model is trained on all team data together, it quietly learns to favour the teams with better data — disadvantaging smaller teams in predictions.

## Our Approach

- Built Decision Tree Regressor models using F1 pit stop data from 2018–2024
- Measured bias using Mean Absolute Error (MAE) as a fairness metric
- Applied disaggregation — training separate specialised models for each team tier
- Reduced predictive bias by 65.3% to 92.17% across all three projects

## Project Structure
Project A
Project B
Project C

## Results

| Project | Initial Bias | Final Bias | Bias Reduction |
|---------|-------------|------------|----------------|
| A       | 0.0014      | 0.0005     | 65.3%          |
| B       | 0.00305     | 0.00024    | 92.17%         |
| C       | 0.0025      | 0.0004     | 83.8%          |

## Team

**Project Leads & AI Mentors**
- Haniyya — AI Lead Mentor, Project Planner & Manager
- Gizem — AI Lead Mentor, Project Planner & Manager

**Participants**
- Iman — Project A
- Participant A — Project A
- Salma — Project B
- Neha — Project C

Full Report
https://drive.google.com/file/d/1mkNKJlHaRcZWsNHnspg0_X6kXM201ZNX/view?usp=sharing
