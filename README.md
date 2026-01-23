# Repurchase Agreement (Repo) Market Spike Detection Simulator

## Overview
This repository contains the Python notebook used to simulate repo haircut rates for Treasury issues and Asset-Backed Securities (ABSs). It was created to supplement the research paper available at https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5572598. It uses these simulations to test a "spike detection" algorithm outlined in the research paper.

## Libraries Used
The primary libraries used in this codebase are the three standard Python data science libraries:
* `numpy`
* `pandas`
* `matplotlib`

## Credits

For simulating Brownian motion through Monte Carlo samples, the `brownian` function code from an article written by Warren Weckesser (available at https://scipy-cookbook.readthedocs.io/items/BrownianMotion.html) was used.
