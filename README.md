# Deep Q-Learning for Atari BasicMath

DQN implementation for the BasicMath Atari environment using PyTorch.

## Requirements
- Python 3.8+
- PyTorch
- Gymnasium[atari]
- ale-py

## Installation
```bash
pip install torch gymnasium[atari] ale-py gymnasium[accept-rom-license]
```

## Usage
Run the Jupyter notebook `DQN_BasicMath.ipynb` in Google Colab or locally.

## Results
- **Baseline** (800 episodes): Average reward 0.29
- **Experiment 1** (gamma=0.8): Average reward 0.00
- **Experiment 2** (LR=0.001): Average reward 0.00  
- **Experiment 3** (decay=0.98): Average reward 0.01

Conclusion: Baseline hyperparameters performed best. Lower gamma and higher learning rate both hurt performance.

## License
MIT License

## Attribution
DQN architecture based on Mnih et al. (2015) and PyTorch tutorials.
