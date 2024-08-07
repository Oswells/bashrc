# Make Shell Easy!
## How to make it work
Download the file ".myshell" to your linux host. 
Then execute the following commands in your terminal:
```shell
curl https://raw.githubusercontent.com/Oswells/bashrc/main/.myshell -o ~/.myshell && echo source ~/.myshell >> ~/.bashrc && source ~/.bashrc
```
Each time you change the file ".myshell", you should run ```source ~/.bashrc``` in your terminal.

## What it supports

| Command |                 Detail                  |
| :-----: | :-------------------------------------: |
|   env   | activate/deactivate a conda environment |
|  lenv   |    list existing conda environments     |
|  cenv   |       create a conda environment        |
|  denv   |       delete a conda environment        |
|  ctmux  |          create a tmux session          |
|  ltmux  |       list existing tmux sessions       |
|  atmux  |      attach/create a tmux session       |
|  ktmux  |           kill a tmux session           |
|   gpu   |      equals to 'gpustat -i 0.2 -p'      |
| nvidia  |         equals to 'nvidia-smi'          |
|   pid   |    equals to 'fuser -v /dev/nvidia*'    |
|   kpy   |    kill all python pids    |
