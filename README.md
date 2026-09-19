# Neural Networks Project
## Grokking at the Edge of Numerical Stability (ICLR 2025)

Paper: https://arxiv.org/abs/2501.04697
Authors code: https://github.com/LucasPrietoAl/grokking-at-the-edge-of-numerical-stability

## Team
- Chinyere Ifeanyi
- Lamiya Ahmed
- Blessing Omotade
- William Ikejiri
- Brayden Marshall

## Files
| File | What it does |
|------|-------------|
| config.py | All settings live here, nobody hardcodes values elsewhere 
| data.py | Modular arithmetic data and MNIST subset 
| models.py | MLP and one layer transformer 
| losses.py | StableMax implementation 
| optim.py | Orthogonal gradient implementation 
| train.py | Shared training loop 
| plots.py | Reads results/ and writes figures 

## Rules
- Never push directly to main. Create your own branch first.
- Every experiment runs on at least 3 seeds and results are averaged.
- Do not commit anything into results/ or figures/.
