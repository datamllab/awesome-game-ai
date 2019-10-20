# Awesome-Game-AI
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but incomplete, list of game AI resources.

If you want to contribute to this list, please feel free to send a pull request. Also you can contact [daochen.zha@tamu.edu](daochen.zha@tamu.edu), or [khlai037@tamu.edu](khlai037@tamu.edu).

## What is Game AI?

Game AI is focusing on predicting which actions should be taken, based on the current conditions. Generally, most games incorporate some sort of AI, which are usually characters or players in the game. For some popular games such as [Starcraft](https://en.wikipedia.org/wiki/StarCraft) and [Dota 2](https://en.wikipedia.org/wiki/Dota_2), developers have spent years to design and refine the AI to enhance the experience.

Modern reinforcement learning techniques have boosted the development of Game AI. In 2015, [AlphaGo](https://en.wikipedia.org/wiki/AlphaGo), for the first time beat a human professional Go player on a full-sized 19×19 board. In 2017, [AlphaZero](https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go) taught itself from scratch and learned to master the games of chess, shogi, and Go. In more recent years, researchers have made efforts to poker games, such as [Libratus](https://science.sciencemag.org/content/359/6374/418) and [DeepStack](https://science.sciencemag.org/content/356/6337/508), achieving expert-level performance in Texas Hold'em. Now researchers keep progressing and achieve human-level AI on [Dota 2](https://openai.com/five/) and [Starcraft 2](https://deepmind.com/blog/article/alphastar-mastering-real-time-strategy-game-starcraft-ii) with deep reinforcement learning.

## What is Included?

We provide some useful resources for getting started in Game AI, including open-source projects and research papers. The resources are categorized by games, and the papers are sorted by years. Currently, the list is incomplete, with main focus on imperfect information games. We need your help to add more awesome resources, such as perfect information games, game competitions, and links for tutorials.

## Table of Contents

* [Open-Source Projects](#open-source-projects)
  * [Unified Toolkits](#unified-toolkits)
  * [Texas Hold'em](#texas-holdem-projects)
  * [Dou Dizhu](#dou-dizhu-projects)
  * [Starcraft](#starcraft-projects)
  * [Gomoku](#gomoku-projects)
  * [Chess](#chess-projects)
  * [Chinese Chess](#chinese-chess-projects)
* [Research Papers](#research-papers)
  * [Betting Games](#betting-games)
  * [Dou Dizhu](#dou-dizhu)
  * [Mahjong](#mahjong)
  * [Bridge](#bridge)
  * [Go](#go)
* [Related Lists](#related-lists)

## Open-Source Projects

### Unified Toolkits
  * RLCard: A Toolkit for Reinforcement Learning in Card Games [[paper](https://arxiv.org/abs/1910.04376)] [[code](https://github.com/datamllab/rlcard)].
  * OpenSpiel: A Framework for Reinforcement Learning in Games [[paper](https://arxiv.org/abs/1908.09453)] [[code](https://github.com/deepmind/open_spiel)].
  * Alpha Zero General [[code](https://github.com/suragnair/alpha-zero-general)].

### Texas Hold'em Projects
  * DeepStack-Leduc [[paper](https://arxiv.org/abs/1701.01724)] [[code](https://github.com/lifrordi/DeepStack-Leduc)].
  * DeepHoldem [[code](https://github.com/happypepper/DeepHoldem)].
  * OpenAI Gym No Limit Texas Hold 'em Environment for Reinforcement Learning [[code](https://github.com/wenkesj/holdem)].
  * PyPokerEngine [[code](https://github.com/ishikota/PyPokerEngine)].
  * Deep mind pokerbot for pokerstars and partypoker [[code](https://github.com/dickreuter/Poker)].

  
### Dou Dizhu Projects
  * Doudizhu AI using reinforcement learning [[code](https://github.com/skyduy/doudizhu-rl)].

### Starcraft Projects
* StarCraft II Learning Environment [[paper](https://arxiv.org/abs/1708.04782)] [[code](https://github.com/deepmind/pysc2)].

### Gomoku Projects
* AlphaZero-Gomoku [[code](https://github.com/junxiaosong/AlphaZero_Gomoku)].

### Chess Projects
* Chess-Alpha-Zero [[code](https://github.com/Zeta36/chess-alpha-zero)].

### Chinese Chess Projects
* CCZero (中国象棋Zero) [[code](https://github.com/NeymarL/ChineseChess-AlphaZero)].

## Research Papers
### Betting Games
Betting games are one of the most popular form of Poker games. The list includes [Goofspiel](https://en.wikipedia.org/wiki/Goofspiel), [Kuhn Poker](https://en.wikipedia.org/wiki/Kuhn_poker), [Leduc Poker](http://poker.cs.ualberta.ca/publications/UAI05.pdf), and [Texas Hold'em](https://en.wikipedia.org/wiki/Texas_hold_%27em).

* Neural Replicator Dynamics, arXiv 2019 [[paper](https://arxiv.org/abs/1906.00190)].
* Computing Approximate Equilibria in Sequential Adversarial Games by Exploitability Descent, IJCAI 2019 [[paper](https://www.ijcai.org/proceedings/2019/0066.pdf)].
* Solving Imperfect-Information Games via Discounted Regret Minimization, AAAI 2019 [[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4007)].
* Deep Counterfactual Regret Minimization, ICML, 2019[[paper](http://proceedings.mlr.press/v97/brown19b/brown19b.pdf)].
* Actor-Critic Policy Optimization in Partially Observable Multiagent Environments, NeurIPS 2018 [[paper](https://papers.nips.cc/paper/7602-actor-critic-policy-optimization-in-partially-observable-multiagent-environments.pdf)].
* Safe and Nested Subgame Solving for Imperfect-Information Games, NeurIPS, 2018 [[paper](http://papers.nips.cc/paper/6671-safe-and-nested-subgame-solving-for-imperfect-information-games.pdf)].
* DeepStack: Expert-Level Artificial Intelligence in Heads-Up No-Limit Poker, Science 2017 [[paper](https://arxiv.org/pdf/1701.01724.pdf)].
* A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning, NeurIPS 2017 [[paper](https://pdfs.semanticscholar.org/fbe9/950202a7fcc756369a38cb1ef4b9b994ae88.pdf)].
* Deep Reinforcement Learning from Self-Play in Imperfect-Information Games, arXiv 2016 [[paper](https://arxiv.org/abs/1603.01121)].
* Fictitious Self-Play in Extensive-Form Games, ICML 2015 [[paper](http://proceedings.mlr.press/v37/heinrich15.pdf)].
* Solving Heads-up Limit Texas Hold’em, IJCAI 2015 [[paper](https://poker.cs.ualberta.ca/publications/2015-ijcai-cfrplus.pdf)].
* Regret Minimization in Games with Incomplete Information, NeurIPS 2007 [[paper](https://poker.cs.ualberta.ca/publications/NIPS07-cfr.pdf)].

### Dou Dizhu
[Dou Dizhu](https://en.wikipedia.org/wiki/Dou_dizhu) ([斗地主](https://baike.baidu.com/item/斗地主/177997?fr=aladdin)) is a very popular Chinese Poker game.

* DeltaDou: Expert-level Doudizhu AI through Self-play, IJCAI 2019 [[paper](https://www.ijcai.org/proceedings/2019/0176.pdf)].
* Combinational Q-Learning for Dou Di Zhu, arXiv 2019 [[paper](https://arxiv.org/abs/1901.08925)].
* Determinization and information set Monte Carlo Tree Search for the card game Dou Di Zhu, CIG 2011 [[paper](https://ieeexplore.ieee.org/document/6031993)].

### Mahjong
[Mahjong](https://en.wikipedia.org/wiki/Mahjong) ([麻将](https://baike.baidu.com/item/%E9%BA%BB%E5%B0%86/215?fr=aladdin)) is a tile-based game that was developed in China.

* Method for Constructing Artificial Intelligence Player with Abstraction to Markov Decision Processes in Multiplayer Game of Mahjong, arXiv 2019 [[paper](https://arxiv.org/abs/1904.07491)].

### Bridge
[Bridge](https://en.wikipedia.org/wiki/Contract_bridge) is a trick-taking card game played with 52 standard deck.

* Boosting a Bridge Artificial Intelligence, ICTAI 2017 [[paper](https://ieeexplore.ieee.org/document/8372096)].

### Go
* Mastering the game of Go with deep neural networks and tree search [[paper](https://www.nature.com/articles/nature16961)].
* Mastering the game of Go without human knowledge [[paper](https://www.nature.com/articles/nature24270)].

## Related Lists
* [Awesome StarCraft AI](https://github.com/SKTBrain/awesome-starcraftAI)
* [Awesome Deep Reinforcement Learning](https://github.com/tigerneil/awesome-deep-rl)
