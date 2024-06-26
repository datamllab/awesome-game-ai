# Awesome-Game-AI
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but incomplete, list of game AI resources on **multi-agent** learning.

If you want to contribute to this list, please feel free to send a pull request. Also you can contact [daochen.zha@rice.edu](mailto:daochen.zha@rice.edu), or [khlai@rice.edu](mailto:khlai@rice.edu).

:loudspeaker: News: Please check out our open-sourced [Large Time Series Model (LTSM)](https://github.com/daochenzha/ltsm)!

:loudspeaker: Have you heard of data-centric AI? Please check out our [data-centric AI survey](https://arxiv.org/abs/2303.10158) and [awesome data-centric AI resources](https://github.com/daochenzha/data-centric-AI)!

## What is Game AI?

Game AI is focusing on predicting which actions should be taken, based on the current conditions. Generally, most games incorporate some sort of AI, which are usually characters or players in the game. For some popular games such as [Starcraft](https://en.wikipedia.org/wiki/StarCraft) and [Dota 2](https://en.wikipedia.org/wiki/Dota_2), developers have spent years to design and refine the AI to enhance the experience.

## Single-Agent vs. Multi-Agent
Numerous studies and achievements have been made to game AI in single-agent environments, where there is a single player in the games. For instance, [Deep Q-learning](https://www.nature.com/articles/nature14236) is successfully applied to Atari Games. Other examples include [Super Mario](https://github.com/aleju/mario-ai), [Minecraft](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewPaper/14630), and [Flappy Bird](https://github.com/yenchenlin/DeepLearningFlappyBird).

Multi-agent environments are more challenging since each player has to reason about the other players' moves. Modern reinforcement learning techniques have boosted multi-agent game AI. In 2015, [AlphaGo](https://en.wikipedia.org/wiki/AlphaGo), for the first time beat a human professional Go player on a full-sized 19×19 board. In 2017, [AlphaZero](https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go) taught itself from scratch and learned to master the games of chess, shogi, and Go. In more recent years, researchers have made efforts to poker games, such as [Libratus](https://science.sciencemag.org/content/359/6374/418), [DeepStack](https://science.sciencemag.org/content/356/6337/508) and [DouZero](https://github.com/kwai/DouZero), achieving expert-level performance in Texas Hold'em and Chinese Poker game Dou Dizhu. Now researchers keep progressing and achieve human-level AI on [Dota 2](https://openai.com/five/) and [Starcraft 2](https://deepmind.com/blog/article/alphastar-mastering-real-time-strategy-game-starcraft-ii) with deep reinforcement learning.

## Perfect Information vs. Imperfect Information
Perfect information means that each player has access to the same information of the game, e.g., Go, Chess, and Gomoku. Imperfect information refers to the situation where players can not observe the full state of the game. For example, in card games, a player can not observe the hands of the other players. Imperfect information games are usually considered more challenging with more possibilities.

## What is included?
This repository gathers some awesome resources for Game AI on multi-agent learning for both perfect and imperfect information games, including but not limited to, open-source projects, review papers, research papers, conferences, and competitions. The resources are categorized by games, and the papers are sorted by years.


## Table of Contents

* [Open-Source Projects](#open-source-projects)
  * [Unified Toolkits](#unified-toolkits)
  * [Texas Hold'em](#texas-holdem-projects)
  * [Dou Dizhu](#dou-dizhu-projects)
  * [Starcraft](#starcraft-projects)
  * [Go](#go-projects)
  * [Gomoku](#gomoku-projects)
  * [Chess](#chess-projects)
  * [Chinese Chess](#chinese-chess-projects)
* [Review and General Papers](#review-and-general-papers)
* [Research Papers](#research-papers)
  * [Betting Games](#betting-games)
  * [Dou Dizhu](#dou-dizhu)
  * [Mahjong](#mahjong)
  * [Bridge](#bridge)
  * [Go](#go)
  * [Starcraft](#starcraft)
* [Conferences and Workshops](#conferences-and-workshops)
* [Competitions](#competitions)
* [Related Lists](#related-lists)

## Open-Source Projects

### Unified Toolkits
  * RLCard: A Toolkit for Reinforcement Learning in Card Games [[paper](https://arxiv.org/abs/1910.04376)] [[code](https://github.com/datamllab/rlcard)].
  * OpenSpiel: A Framework for Reinforcement Learning in Games [[paper](https://arxiv.org/abs/1908.09453)] [[code](https://github.com/deepmind/open_spiel)].
  * Unity ML-Agents Toolkit [[paper](https://arxiv.org/abs/1809.02627)] [[code](https://github.com/Unity-Technologies/ml-agents)].
  * Alpha Zero General [[code](https://github.com/suragnair/alpha-zero-general)].

### Texas Hold'em Projects
  * DeepStack-Leduc [[paper](https://arxiv.org/abs/1701.01724)] [[code](https://github.com/lifrordi/DeepStack-Leduc)].
  * DeepHoldem [[code](https://github.com/happypepper/DeepHoldem)].
  * OpenAI Gym No Limit Texas Hold 'em Environment for Reinforcement Learning [[code](https://github.com/wenkesj/holdem)].
  * PyPokerEngine [[code](https://github.com/ishikota/PyPokerEngine)].
  * Deep mind pokerbot for pokerstars and partypoker [[code](https://github.com/dickreuter/Poker)].

  
### Dou Dizhu Projects
  * PerfectDou: Dominating DouDizhu with Perfect Information Distillation [[code](https://github.com/Netease-Games-AI-Lab-Guangzhou/PerfectDou)].
  * DouZero: Mastering DouDizhu with Self-Play Deep Reinforcement Learning [[code](https://github.com/kwai/DouZero)].
  * Doudizhu AI using reinforcement learning [[code](https://github.com/skyduy/doudizhu-rl)].
  * Dou Di Zhu with Combinational Q-Learning [[paper](https://github.com/qq456cvb/doudizhu-C)] [[code](https://github.com/qq456cvb/doudizhu-C)].
  * DouDiZhu [[code](https://github.com/songbaoming/DouDiZhu)].
  * 斗地主AI设计与实现 [[code](https://github.com/ZhouWeikuan/DouDiZhu)].

### Starcraft Projects
* StarCraft II Learning Environment [[paper](https://arxiv.org/abs/1708.04782)] [[code](https://github.com/deepmind/pysc2)].
* Gym StarCraft [[code](https://github.com/alibaba/gym-starcraft)].
* StartCraft II Reinforcement Learning Examples [[code](https://github.com/chris-chris/pysc2-examples)].
* A Guide to DeepMind's StarCraft AI Environment [[code](https://github.com/llSourcell/A-Guide-to-DeepMinds-StarCraft-AI-Environment)].
* A reimplementation of Alphastar based on DI-engine with trained models [[code](https://github.com/opendilab/DI-star)].

### Go Projects
* ELF: a platform for game research with AlphaGoZero/AlphaZero reimplementation [[code](https://github.com/pytorch/ELF)] [[paper](https://arxiv.org/pdf/1902.04522.pdf)].

### Gomoku Projects
* AlphaZero-Gomoku [[code](https://github.com/junxiaosong/AlphaZero_Gomoku)].
* gobang [[code](https://github.com/lihongxun945/gobang)].

### Chess Projects
* Chess-Alpha-Zero [[code](https://github.com/Zeta36/chess-alpha-zero)].
* Deep Pink [[code](https://github.com/erikbern/deep-pink)].
* Simple chess AI [[code](https://github.com/lhartikk/simple-chess-ai)].

### Chinese Chess Projects
* CCZero (中国象棋Zero) [[code](https://github.com/NeymarL/ChineseChess-AlphaZero)].

### Mahjong Projects
* pymahjong (Japanese Riichi Mahjong) [[code](https://github.com/Agony5757/mahjong/tree/master/pymahjong)].
* Mortal [[code](https://github.com/Equim-chan/Mortal)].

## Review and General Papers
* Deep reinforcement learning from self-play in imperfect-information games, arXiv 2016 [[paper](https://arxiv.org/pdf/1603.01121.pdf)].
* Multi-agent Reinforcement Learning: An Overview, 2010 [[paper](https://link.springer.com/chapter/10.1007/978-3-642-14435-6_7)].
* An overview of cooperative and competitive multiagent learning, LAMAS 2005 [[paper](https://dl.acm.org/citation.cfm?id=2180576)].
* Multi-agent reinforcement learning: a critical survey, 2003 [[paper](http://jmvidal.cse.sc.edu/library/shoham03a.pdf)].

## Research Papers
### Betting Games
Betting games are one of the most popular form of Poker games. The list includes [Goofspiel](https://en.wikipedia.org/wiki/Goofspiel), [Kuhn Poker](https://en.wikipedia.org/wiki/Kuhn_poker), [Leduc Poker](http://poker.cs.ualberta.ca/publications/UAI05.pdf), and [Texas Hold'em](https://en.wikipedia.org/wiki/Texas_hold_%27em).

* Neural Replicator Dynamics, arXiv 2019 [[paper](https://arxiv.org/abs/1906.00190)].
* Computing Approximate Equilibria in Sequential Adversarial Games by Exploitability Descent, IJCAI 2019 [[paper](https://www.ijcai.org/proceedings/2019/0066.pdf)].
* Solving Imperfect-Information Games via Discounted Regret Minimization, AAAI 2019 [[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4007)].
* Deep Counterfactual Regret Minimization, ICML, 2019 [[paper](http://proceedings.mlr.press/v97/brown19b/brown19b.pdf)].
* Actor-Critic Policy Optimization in Partially Observable Multiagent Environments, NeurIPS 2018 [[paper](https://papers.nips.cc/paper/7602-actor-critic-policy-optimization-in-partially-observable-multiagent-environments.pdf)].
* Safe and Nested Subgame Solving for Imperfect-Information Games, NeurIPS, 2018 [[paper](http://papers.nips.cc/paper/6671-safe-and-nested-subgame-solving-for-imperfect-information-games.pdf)].
* DeepStack: Expert-Level Artificial Intelligence in Heads-Up No-Limit Poker, Science 2017 [[paper](https://arxiv.org/pdf/1701.01724.pdf)].
* A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning, NeurIPS 2017 [[paper](https://pdfs.semanticscholar.org/fbe9/950202a7fcc756369a38cb1ef4b9b994ae88.pdf)].
* Poker-CNN: A pattern learning strategy for making draws and bets in poker games using convolutional networks [[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12172/11606)].
* Deep Reinforcement Learning from Self-Play in Imperfect-Information Games, arXiv 2016 [[paper](https://arxiv.org/abs/1603.01121)].
* Fictitious Self-Play in Extensive-Form Games, ICML 2015 [[paper](http://proceedings.mlr.press/v37/heinrich15.pdf)].
* Solving Heads-up Limit Texas Hold’em, IJCAI 2015 [[paper](https://poker.cs.ualberta.ca/publications/2015-ijcai-cfrplus.pdf)].
* Regret Minimization in Games with Incomplete Information, NeurIPS 2007 [[paper](https://poker.cs.ualberta.ca/publications/NIPS07-cfr.pdf)].

### Dou Dizhu

* PerfectDou: Dominating DouDizhu with Perfect Information Distillation, NeurIPS 2022 [[paper](https://arxiv.org/abs/2203.16406)] [[code](https://github.com/Netease-Games-AI-Lab-Guangzhou/PerfectDou)].
* DouZero: Mastering DouDizhu with Self-Play Deep Reinforcement Learning, ICML 2021 [[paper](https://arxiv.org/abs/2106.06135)] [[code](https://github.com/kwai/DouZero)].
* DeltaDou: Expert-level Doudizhu AI through Self-play, IJCAI 2019 [[paper](https://www.ijcai.org/proceedings/2019/0176.pdf)].
* Combinational Q-Learning for Dou Di Zhu, arXiv 2019 [[paper](https://arxiv.org/abs/1901.08925)] [[code](https://github.com/qq456cvb/doudizhu-C)].
* Determinization and information set Monte Carlo Tree Search for the card game Dou Di Zhu, CIG 2011 [[paper](https://ieeexplore.ieee.org/document/6031993)].

### Mahjong

* Variational oracle guiding for reinforcement learning, ICLR 2022 [[paper](https://openreview.net/forum?id=pjqqxepwoMy)]
* Suphx: Mastering Mahjong with Deep Reinforcement Learning, arXiv 2020 [[paper](https://arxiv.org/abs/2003.13590)].
* Method for Constructing Artificial Intelligence Player with Abstraction to Markov Decision Processes in Multiplayer Game of Mahjong, arXiv 2019 [[paper](https://arxiv.org/abs/1904.07491)].
* Building a Computer Mahjong Player Based on Monte Carlo Simulation and Opponent Models, IEEE CIG 2017 [[paper](https://ieeexplore.ieee.org/document/7317929)].

### Bridge

* Boosting a Bridge Artificial Intelligence, ICTAI 2017 [[paper](https://ieeexplore.ieee.org/document/8372096)].

### Go
* Mastering the game of Go without human knowledge, Nature 2017 [[paper](https://www.nature.com/articles/nature24270)].
* Mastering the game of Go with deep neural networks and tree search, Nature 2016 [[paper](https://www.nature.com/articles/nature16961)].
* Temporal-difference search in computer Go, Machine Learning, 2012 [[paper](https://link.springer.com/article/10.1007/s10994-012-5280-0)].
* Monte-Carlo tree search and rapid action value estimation in computer Go, Artificial Intelligence, 2011 [[paper](https://www.ics.uci.edu/~dechter/courses/ics-295/winter-2018/papers/mcts-gelly-silver.pdf)].
* Computing “elo ratings” of move patterns in the game of go, ICGA Journal, 2007 [[paper](https://hal.inria.fr/file/index/docid/149859/filename/MMGoPatterns.pdf)].

### Starcraft
* Grandmaster level in StarCraft II using multi-agent reinforcement learning, Nature 2019 [[paper](https://www.nature.com/articles/s41586-019-1724-z)].
* On Reinforcement Learning for Full-length Game of StarCraft, AAAI 2019 [[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4394)].
* Stabilising experience replay for deep multi-agent reinforcement learning, ICML 2017 [[paper](https://dl.acm.org/citation.cfm?id=3305500)].
* Cooperative reinforcement learning for multiple units combat in starCraft, SSCI 2017 [[paper](https://ieeexplore.ieee.org/abstract/document/8280949)].
* Learning macromanagement in starcraft from replays using deep learning, CIG 2017 [[paper](https://ieeexplore.ieee.org/abstract/document/8080430)].
* Applying reinforcement learning to small scale combat in the real-time strategy game StarCraft: Broodwar, CIG 2012 [[paper](https://ieeexplore.ieee.org/abstract/document/6374183)].

## Conferences and Workshops
* [IEEE Conference on Computational Intelligence and Games (CIG)](http://www.ieee-cig.org/)
* [AAAI Workshop on Reinforcement Learning in Games](http://aaai-rlg.mlanctot.info/)
* [Bridging Game Theory and Deep Learning](https://nips.cc/Conferences/2019/Schedule?showEvent=13158)
* [IJCAI 2018 Computer Games Workshop](https://www.lamsade.dauphine.fr/~cazenave/cgw2018/cgw2018.html)
* [IEEE Conference on Games (CoG)](http://ieee-cog.org/2020/)

## Competitions
* [International Computer Games Association (ICGA)](http://icga.org/)
* [Annual Computer Poker Competition](http://www.computerpokercompetition.org/)

## Related Lists
* [Awesome StarCraft AI](https://github.com/SKTBrain/awesome-starcraftAI)
* [Awesome Deep Reinforcement Learning](https://github.com/tigerneil/awesome-deep-rl)
