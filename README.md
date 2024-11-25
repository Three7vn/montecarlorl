# montecarlorl
Simulation of blackjack which uses Monte Carlo algorithms to estimate action-value functions Q(s,a) and optimise decision-making policies through first-visit and constant-a reinforcement learning techniques.



The Game of Blackjack:

The player starts with two cards and can decide to 'request a card' (hit) or 'stand'.
The goal is to have a hand total closer to 21 than the dealer without exceeding it.

States include:
Players current hand total.
Dealer's face-up card.
Whether the player has a usable ace.

Monte Carlo Methods (MCM):
MC Prediction: Calculates the action-value function Q(s,a) by averaging the rewards for each state-action pair over multiple episodes (games).

MC Control: Refines the policy using constant-a updates, making decisions increasingly optimal over time.

Game Analysis:
Summarises total rewards, number of wins, losses, and draws.
Visualises outcomes to provide insights into player performance.
