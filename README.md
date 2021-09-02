# Arabic-MTL-NMT
A repo for the project "Arabic Multitask Learning Neural Machine Translation"

|      Experiment          |           Discription           |   val     |    test     |
|    -------------         |     -----------------------     |  ------------ | ------------    |
| [1]stanrad translaton (seed=42)  |      6 layers, 50 epochs/70 epochs. [notebook](https://bit.ly/3wxSeRd)   |   30.18/30.32     |   30.56/30.71     |
| [2]stanrad translaton (seed=42)  |      6 layers, 50 epochs [notebook](https://bit.ly/3wtO7Wo)       |     30.22       |   30.76       |
| [1]mixing with (1,0.3) mixing ratio (seed=42) | 6 layers, 40 epochs / 10 epochs fintuning. [notebook](https://bit.ly/3hzsUGh)   |   30.22/31.06  |  30.44/31.63|  
| [2]mixing with (1,0.3) mixing ratio (seed=42) | 6 layers, 40 epochs / 10 epochs fintuning. [notebook](https://bit.ly/3r44O9D)-[notebook](https://bit.ly/3mW5KwH)  |   30.22/31.19 -31.51/32.00 |  30.52/31.49 - 32.43/32.76  |
| [1]mixing with (1,0.5) mixing ratio (seed=42) | 6 layers, 40 epochs / 10 epochs fintuning.          |     30.20/30.80     |   30.7/31.70     |
| [2]mixing with (1,0.5) mixing ratio (seed=42) |     6 layers, 40 epochs / 10 epochs fintuning. |     30.34/31.03 |   30.85/31.55      |
| [3]mixing with (1,0.5) mixing ratio [seed=42]     |     6 layers, 70 epochs. [notebook](https://bit.ly/3gLWsj3)      |     32.05 |   32.33 |
| [1]mixing with (1,0.8) mixing ratio (seed=42)   |     6 layers, 40 epochs / 10 epochs fintuning.           |     29.96/30.48       |   30.45/31.18    |
| [2]mixing with (1,0.8) mixing ratio (seed=42)     |     6 layers, 40 epochs / 10 epochs fintuning.      |     30.02/30.84 |   30.53/31.32    |
| [1]mixing with (1,1) mixing ratio (seed=42)   |     6 layers, 70 epochs / 10 epochs fintuning.           |    ?????      |   ???????    |
| [2]mixing with (1,1) mixing ratio      |     6 layers, 70 epochs / 10 epochs fintuning. [notebook](https://bit.ly/3zCUIQN)     |    31.87/32.00    |    32.08/32.85   |

You can find the notebook for finetuning tasks [here](https://colab.research.google.com/drive/1C0xC56U1VmDhcE02rGbGb4b2SvypGZmS?usp=sharing) 




