## RL-SuperMarioBros

Reinforcement learning algorithms implemented to play SuperMario. Will be used as a practical baseline to compare different algorithms & techniques.

### Dueling Double DQN
| Notes | GIFs |
| --- | :---: |
| <ins>**21-10-2020**</ins> <br> <ul><li> `epsilon_min (0.01)`<li> Very slow learning <li> Score increased rarely post this episode </ul> | **Episode: 4298**<br> ![1-1-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/21-10-2020-1-1-v0.gif)|

### Dueling Double DQN with Prioritized Replay
| Notes | GIFs |
| --- | :---: |
| <ins>**17-08-2020**</ins> <br> <ul><li>Algorithm tested <li>Agent didn't learn</ul> | **NIL** | 
| <ins>**02-10-2020**</ins> <ul><li>Switched to `SmoothL1Loss`<li>Too many episodes / Stuck for long (low `epsilon_min`)<li>Increase `epsilon_min (0.01)` - should reduce episodes<li>Got unstuck after rare exploration<li>almost beat level</ul> |**Episode: 4748**<br> ![1-1-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/02-10-2020-1-1-v0.gif) |
| <ins>**03-10-2020**</ins> <ul><li>Increased `epsilon_min (0.09)` used less episodes<li>beat level after more exploration</ul> | **Episode: 2603**<br> ![1-4-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/03-10-2020-1-4-v0-a.gif) <br>**Episode: 3545**<br> ![1-4-v0](https://github.com/nimishsantosh107/RL-SuperMarioBros/raw/master/videos/03-10-2020-1-4-v0-b.gif)|


