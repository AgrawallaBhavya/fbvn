# Bilinear Value Network
---
## Installation
-  install mujoco_py==1.50, see instructions at https://github.com/openai/mujoco-py/tree/1.50.1.1
-  pip install gymnasium_robotics[mujoco_py]
-  running the setup below should be sufficient after this, the nescessary changes have been made to the code
- `pip install -e . `
- Copy [`.jaynes.yml`](https://github.com/geyang/jaynes-starter-kit/blob/master/04_slurm_configuration/.jaynes.yml) into the project directory
- `git init`

## Run baselines
```
cd experiments/001_baselines
python fetch.py
```

## Run BVN
```
cd experiments/002_bvn
python fetch.py
```
