# Bipedal-Walker

## Overview
The challenge for this coursework was to build an agent to efficiently learn to walk in Gym's BipedalWalker environment, for both the normal and hardcore versions. The terrain in the normal environment is flat, whereas the hardcore environment contains many obstacles that the agent must navigate. 

## LA3P + SAC
I trained my agents using Loss Adjusted Approximate Actor Prioritsed Experience Replay (LA3P) and Soft Actor Critic (SAC) [1], for both environments producing agents which learnt very quickly to walk. Convergence for the normal environment, was "outstanding", and my agent achieved "top-of-class" results in the hardcore version. My report details my approach and how it was applied differently to each environment.

For this coursework I received 86/100.

## Normal (Episode 1,400)
<p align="center">
  <img src="./jbtl68-agent-video,episode=1400,score=332.gif" width="300" />
</p>

## Hardcore (Episode 1,300)
<p align="center">
  <img src="./jbtl68-agent-hardcore-video,episode=1300,score=302.gif" width="300"/>
</p>

[1] Baturay Saglam et al. “Actor prioritized experience replay”. In: Journal of Artificial Intelligence Research 78 (2023), pp. 639–672.


