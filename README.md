# Data-Driven Set-Theoretic Model Predictive Control

This repository contains the codes for "Data-Driven Robust Backward Reachable Sets for Set-Theoretic Model Predictive Control"
by Mehran Attar and Walter Lucia

## Problem Statement
Given the input-state trajectories $\mathcal{D}=(x,u)$ collected for the linear model $x_{k+1} = Ax_k + Bu_k + w_k$ with $x_k \in \mathcal{X} \subset \mathbb{R}^n$ and $u_k \in \mathcal{U}\subset \mathbb{R}^m$ and $w_k \in \mathcal{W} \subset \mathbb{R}^n$, with unknown system matrices $(A,B):$

1. Design a data-driven algorithm computing an inner approximation of the ROSC sets $\mathcal{T}^{j} = {x \in \mathcal{X}: \exists u \in \mathcal{U}: x^+ \in \mathcal{T}^{j-1}, \forall w \in \mathcal{W} \}$
	
2. Design a Data-Driven Set-Theoretic MPC (D-ST-MPC) controller for the linear system enjoying the same properties of ST-MPC. 

## Files Description


## Running
1- Download [CORA 2022](https://tumcps.github.io/CORA/) and [MPT](https://www.mpt3.org/)

2- Add CORA and MPT folder and subfolders to the Matlab path.

3- Add the repo folder and subfolders to the Matlab path.
