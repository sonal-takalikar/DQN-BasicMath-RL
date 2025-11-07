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
- Baseline average reward: 0.29
- Experiments with gamma, learning rate, and epsilon decay included

## License
MIT License

## Attribution
DQN architecture based on Mnih et al. (2015) and PyTorch tutorials.
