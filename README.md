# Monte Carlo Engine — Probability & Simulation

## Objective

I used simulation and probability to study convergence, conditional probability, medical screening, and financial risk.

## Methodology

- I simulated 10,000 fair coin flips and plotted the running proportion of heads.
- I simulated 10,000 Monty Hall games using stay and switch strategies.
- I applied Bayes’ Theorem and simulated a screening test for 100,000 people.
- I generated 10,000 possible daily portfolio returns using a Normal distribution.
- I calculated one-day Value at Risk and Expected Shortfall for a $1 million portfolio.
- I estimated pi at several sample sizes to examine how Monte Carlo error changes.
- I converted the risk calculations into a reusable function and checked its output against my manual results.

## Key Findings

The coin-flip proportion remained within one percentage point of 0.5 after approximately 6,455 flips.

In the Monty Hall simulation, switching won 6,694 of 10,000 games, compared with 3,306 wins from staying. Switching therefore won about twice as often.

In the medical-screening simulation, only 9.2% of positive tests came from people who were actually sick. The low disease prevalence allowed false positives from the much larger healthy population to outnumber true positives.

For the $1 million portfolio, the 95% one-day Value at Risk was $19,494. On the worst 5% of simulated days, the average loss measured by Expected Shortfall was $24,230. This demonstrates that Value at Risk is a threshold rather than a maximum possible loss.
