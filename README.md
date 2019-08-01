# Paper Implementations

Welcome to my centralized repository for all my paper implementations! Every implementation is in its own repository, but they are included as submodules here for easy access.

To maximize clarity and reproducibility, we make use of various resources:

- Code Style: `black` `flake8` `flake8-bugbears` `isort` `pre-commit`
- Documentation: `flake8-docstring` `typing`
- Customization: `configargparse`
- Unit Tests: `pytest` `travis-ci`
- Visualization: `tensorboard` `wandb`

For more details, check [**this template repository**](https://github.com/seungjaeryanlee/implementations-template) or any implementation.

### Setup

If you wish to download all implementations, clone this repository and update all submodules.

```bash
git clone https://github.com/seungjaeryanlee/implementations.git
git submodule update --init --recursive
```

Note that every submodule has HEAD detached, so if you wish to modify code and push it to GitHub, you first need to checkout to master.

```bash
cd template/  # For example
git checkout master
```

### Finished Implementations ⌛

1. [**[NFQ]** Neural Fitted Q Iteration - First Experiences with a Data Efficient Neural Reinforcement Learning Method](https://github.com/seungjaeryanlee/implementations-nfq)

### Ongoing Implementations ⏳

- [**[DQN]** Human-level control through Deep Reinforcement Learning](https://github.com/seungjaeryanlee/implementations-dqn)

### Planned Implementations 🔜

- [**[DDQN]** Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/abs/1509.06461)
- [**[DuDQN]** Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581)
- [**[PER]** Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
