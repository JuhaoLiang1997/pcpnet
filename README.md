# PortraitNet
Reproduction of paper: "[PCPNET Learning Local Shape Properties from Raw Point Clouds](https://arxiv.org/abs/1710.04954)"

## Quick Start
1. Download datasets
```
python pclouds/download_pclouds.py
python models/download_models.py
```
2. Model evaluation: `python eval_pcpnet.py`
3. Model Training: `python train_pcpnet.py`
4. Result Visualization in `visualizatino.ipynb`
5. Run the command: `python train.py`


## Implemented Features
- [x] train code
- [x] test visualization
- [x] wandb
- [ ] multi-gpu parallel training


# Acknowledgement
- [pcpnet](https://github.com/paulguerrero/pcpnet)