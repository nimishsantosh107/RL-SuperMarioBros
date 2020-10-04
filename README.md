## RL-SuperMarioBros

Reinforcement learning algorithms implemented to play SuperMario.


#### Dueling Double DQN with Prioritized Replay
| Notes | GIFs |
| --- | --- |
| <ins>**undated**</ins> <br> No improvement | **NIL** | 
| <ins>**02-08-2020**</ins> <li>switched to `SmoothL1Loss`<li>Too many episodes / Stuck for long (low `epsilon_min`)<li>Increase `epsilon_min (0.01)` - should reduce episodes<li>Got unstuck after rare exploration<li>almost beat level |**4748**<br> ![1-1-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/02-08-2020-1-1-v0.gif) |
| <ins>**03-08-2020**</ins> <li>Increased `epsilon_min (0.09)` used less episodes<li>beat level after more exploration | **2603**<br> ![1-4-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/03-08-2020-1-4-v0-a.gif) <br>*3545**<br> ![1-4-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/03-08-2020-1-4-v0-b.gif)|

