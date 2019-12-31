---
title: "Aerial Wirelesss Networks"
excerpt: "Decentralized Trajectory Control for Aerial Networks<br/><img src='/images/awn_schematic.png'>"
collection: portfolio
---

This project aims to implement a flexible aerial Radio Access Network (RAN) that can be rapidly deployed in previously unknown environments. This places a strong emphasis on the trajectory control of these Aerial Access Points, however a dynamic operating environment and limited prior knowledge of user mobility and traffic models makes tight closed-loop control an impractical luxury. While reasonable prior models may exist for fixed infrastructure networks, aerial networks are often considered for short-term temporary deployments such as post-disaster recovery where expecting prior models is unreasonable and online estimation of these models during operation is necessary. I’m using Reinforcement Learning (RL) to address these challenges. My current focus is on decentralized learning and opportunistic cooperation of multiple RL agents.

<img src='/images/sim_example_3d_3d.png'>

Noticing a lack of publicly available simulation tools that can be used for benchmarks, I also started developing [gently](https://github.com/uluturki/gently), an open-sourced aerial wireless network simulator with a reinforcement learning environment written in Python. Main feature of gently is the inclusion of domain specific Wireless Networks details such as line-of-sight, channel models, interference, and traffic models. It is a work in progress and I hope to release v1.0 with my dissertation.