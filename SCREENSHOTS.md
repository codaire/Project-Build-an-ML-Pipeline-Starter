# NYC Airbnb ML Pipeline – W&B Project Screenshots

This document showcases key views from the Weights & Biases (W&B) project dashboard used to track and manage the NYC Airbnb ML pipeline experiments.

---

## 1. Project Overview

The `nyc_airbnb` project overview in W&B, showing project visibility settings, contributor count, total runs (15), and total compute time (2 minutes).

![W&B Project Overview](images/wandb_project_overview.png)

---

## 2. Workspace – Feature Importance Runs

The personal workspace view displaying 15 visualized runs with a **feature_importance** media panel. Runs such as `deft-jazz-15`, `ethereal-terrain-9`, and `fiery-valley-8` are shown side by side for comparison.

![W&B Workspace Feature Importance](images/wandb_workspace_feature_importance.png)

---

## 3. Artifacts – Random Forest Export

The Artifacts panel showing the `random_forest_export` artifact at **Version 3 (prod)**. This version was created on March 18th, 2026, contains 7 files totalling 61.0 MB, and is tagged as the production model. The upstream artifact is `trainval_data.csv:v0`.

![W&B Artifacts Random Forest Export](images/wandb_artifacts_random_forest.png)

---

## Notes

- All screenshots were captured on **March 18, 2026**.
- The W&B project is hosted under the `fightingweight-western-governors-university` entity.
- The production model artifact (`random_forest_export:v3`) was created by run `ethereal-terrain-9`.
