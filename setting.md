# setting

```bash

git submodule update --init --recursive
.venv\Scripts\python.exe -m pip install -e .

```


```bash
git submodule update --recursive

```

# Test
```bash
.venv\Scripts\python.exe myosuite\utils\examine_env.py --env_name myoLegRoughTerrainWalk-v0
```

# Issues

## rendering wierd(solved)
https://github.com/google-deepmind/mujoco/issues/894

https://github.com/google-deepmind/mujoco/issues/639


Solution:
Set the labtop monitor as main monitor.
