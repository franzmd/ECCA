# ECCA Calculator

A stateless, single-file web app for the **Electroconvulsive Therapy Cognitive Assessment (ECCA)** — a 30-point bedside screening tool for monitoring cognition during a course of ECT.

## What it does

- **Test tab** — interactive calculator for all 8 ECCA sections (Orientation, Subjective Memory, Informant Assessment, Registration, Attention, Autobiographical Memory, Fund of Knowledge, Delayed Recall) with phase-specific parallel forms for Pre / Mid / Post-ECT (word lists, Serial 7s start values, Trail B ranges, Months Backwards patterns).
- **Informant tab** — digital version of the ECCA Informant Sheet, chart-copyable.
- **Copy for Chart** — one tap produces a clean, paste-ready summary block for the EHR.

## Design principles

- **Stateless.** No database, no storage, no network calls. Nothing is saved; closing the page clears everything. No PHI is stored on the device.
- **Single file.** Plain HTML/CSS/JS, zero dependencies. Hosted on GitHub Pages; works offline once loaded; Add to Home Screen for an app-like experience.
- **Scoring:** Orientation 4 + Subjective 4 + Informant 4 + Registration 0 + Attention 3 + Autobiographical 6 + Fund of Knowledge 5 + Recall 4 = **30 points**.

## Important legal notice

The ECCA is a copyrighted instrument: **COPYRIGHT 2014, EMORY UNIVERSITY BRAIN HEALTH CENTER** (fuquacenter.org/ecca). This repository reproduces the instrument's content. It is provided for personal clinical use; **obtain permission from the Fuqua Center before distributing, publishing, or using it in research.**

Reference: Hermida D, et al. *Electroconvulsive therapy and cognition: validation of the ECCA.* Journal of Affective Disorders. 2020;269:36-42.

## Disclaimer

Screening/monitoring instrument only — not a diagnostic neuropsychological assessment. Not affiliated with Emory University or the Fuqua Center.
