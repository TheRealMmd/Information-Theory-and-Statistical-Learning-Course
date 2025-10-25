# Information Theory & Statistical Learning — Coursework & Project

This repository contains my coursework and project materials for the **Information Theory & Statistical Learning** course.

## Repository Structure
- `Final/` — Final exam solutions and materials  
- `Problem set 1/` — Solutions and materials for Problem Set 1  
- `Problem set 2/` — Solutions and materials for Problem Set 2  
- `Problem set 3/` — Solutions and materials for Problem Set 3  
- `Problem set 4/` — Solutions and materials for Problem Set 4  
- `Project Report/` — Course project report (PDF) and related assets

## Course Project — *Information Flow in Deep Neural Networks Under Distributional Shifts*
**Goal.** Estimate and analyze mutual information between inputs and hidden representations in DNNs, and study how these estimates behave when the input distribution shifts.

**Background.** We build on the noisy-network framework and the Sample Propagation (SP) estimator for \(I(X;T_\ell)\) to make mutual information well-defined and trackable during training.

**Contributions.**
- **Robustness bounds:** Derived deviation bounds for the information estimator under **Total Variation (TV)** and **KL** shifts of the input distribution.  
- **Empirical study:** Tracked information flow across layers on standard models/datasets (e.g., MNIST variants) while applying controlled distributional shifts, highlighting layer-wise sensitivity and stability patterns.  
- **Discussion & outlook:** Directions toward Wasserstein-based bounds and distributionally robust training objectives.

**Read the report:** See `Project Report/Project Report.pdf`.

## Notes on the Coursework
The problem-set solutions reflect my understanding of topics in information theory and statistical learning (e.g., entropy and mutual information, data-processing inequalities, concentration and generalization, ERM/PAC/VC viewpoints). Materials are for educational use.

## Acknowledgments
Thanks to the course instructor and mentors for guidance and feedback.

## License
Unless stated otherwise inside a subfolder, the material is released under the MIT License.
