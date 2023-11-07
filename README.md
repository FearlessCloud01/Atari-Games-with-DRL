# Mastering Atari Games with Deep Reinforcement Learning

## Results

|                         Pong                          |             Breakout              |             Boxing             |
| :---------------------------------------------------: | :-------------------------------: | :----------------------------: |
| ![](Double-DQN/videos_modified/pong_modified_300.gif) | ![](DQN/videos/breakout_5000.gif) | ![](DQN/videos/boxing_500.gif) |

## Instructions to Run Code

```bash
conda create -n env # create new conda environment
conda activate env # activate the conda environment
pip install -r requirements.txt # install dependencies
jupyter notebook <path/to/notebook> # opens the required notebook in jupyter
# run all cells in the notebook
```

**Repository Structure:**

```bash
.
├── DQN
│   ├── DeepRL_boxing.ipynb
│   ├── DeepRL_breakout.ipynb
│   ├── DeepRL_pong.ipynb
│   ├── Param.py
│   ├── model.py
│   ├── models
│   │   ├── # saved model weights checkpoints for multiple games
│   ├── replay_memory.py
│   ├── utils.py
│   ├── videos
│   │   ├── # videos of agent playing multiple games
│   └── wrappers.py
├── Double-DQN
│   ├── DeepRL_boxing_modified.ipynb
│   ├── DeepRL_breakout_modified.ipynb
│   ├── DeepRL_pong_modified.ipynb
│   ├── Param_modif.py
│   ├── model.py
│   ├── models_modified
│   │   ├── # saved model weights checkpoints for multiple games
│   ├── replay_memory.py
│   ├── utils_modif.py
│   ├── videos_modified
│   │   ├── # videos of agent playing multiple games
│   └── wrappers.py
├── README.md
└── requirements.txt
```
