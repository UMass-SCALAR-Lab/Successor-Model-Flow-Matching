# Successor-Model-Flow-Matching
This repo implements TD flow algorithms on a demonstrative continuous state, continuous action domain.

The repo containts implementations of various TD flow algorithms proposed in _Farebrother, J., Pirotta, M., Tirinzoni, A., Munos, R., Lazaric, A., & Touati, A. (2025). Temporal Difference Flows. arXiv preprint arXiv:2503.09817._

We will add the diffusion-based successor modeling as next step.

## How to run the code?
1. Create a virtual environment and install pytorch, numpy, matplotlib, and tqdm.
2. Setup ipython kernel for the virtual environment.
3. Run the notebook `mc_cfm.ipynb` (Implements MC-CFM) and `complete_td_flow_matching.ipynb` (Implements MC-CFM, TD-CFM, TD-CFM(C), TD^2-CFM).

Please reach out to **svdeshmukh@cs.umass.edu** for any questions or feedback.
