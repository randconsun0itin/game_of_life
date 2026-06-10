
# **letter_trail buildkit**

high-fidelity simulation framework for reinforcement learning.

---

letter_trail provides flexible environment APIs for training agents in physics-based virtual worlds.

* deterministic simulation
* parallel environment support
* PyTorch / JAX integration
* JSON scene configurations

```bash
pip install letter_trail-buildkit
```

```python
from letter_trail import Env

env = Env("cartpole")
obs = env.reset()

for step in range(100):
    act = agent(obs)
    obs, reward, done, _ = env.step(act)
```

---

docs → [letter_trail-ai.dev/docs](https://letter_trail-ai.dev/docs)
papers → [research.letter_trail-ai.dev](https://research.letter_trail-ai.dev)
