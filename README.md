# rlgym-tools
Extra tools for RLGym.

Contains environment alternatives for [Stable-Baselines3](https://stable-baselines3.readthedocs.io/en/master/), [RLlib](https://docs.ray.io/en/master/rllib.html) and [PettingZoo](https://www.pettingzoo.ml/), replay to RLGym GameState converter, and advanced reward functions. 

Check out the [RLGym wiki](https://rlgym.github.io/) for more info: 

## Installation
`pip install rlgym-tools`

## Installation steps on local Win10
- create a conda env with python 3.9
- install torch version fitting your system
- might need to install mkl related libs
- pip install rlgym-tools
- if giving error such as "ImportError: DLL load failed while importing win32file: The specified module could not be found.", then copy pythoncom38.dll and pywintypes38.dll from /path/to/conda/env/Lib/site-packages/pywin32_system32 into C:\Windows\System32. Probably there is a better way (e.g., via some environment variables (LD_LIBRARY_PATH ?) to point to conda dir).



