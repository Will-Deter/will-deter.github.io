---
layout: post
title:  "Novel, Agent-Based TSP Solution Approximation Method"
date:   2022-12-26 00:00:00 -0500
categories: projects
---

### Abstract
The travelling salesperson problem is a famous example of the NP-hard class of problems.  Efficient algorithms to approximate solutions are highly valued if they can achieve relatively small errors at low computational cost. In this project, a TSP approximation method inspired by cleaning up is developed. A pair of agents cooperate to clean up (visit) a set of messes (cities).  A simple genetic algorithm (SGA) is used to evolve agents' processing of information about their positions as well as the topology of the mess network.  The objective is to create a team of agents whose rulesets may inexpensively approximate solutions as the largest cost of computation is "paid upfront" through the training process.