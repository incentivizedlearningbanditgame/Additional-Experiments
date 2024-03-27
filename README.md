The three experiments compare our algorithm IPA to a UCB baseline and to the Principal's epsilon Greedy algorithm proposed in Dogan et al., Repeated Principal-Agent Games with Unobserved Agent Rewards and Perfect-Knowledge Agents. We ran the simulations on a 5 arms bandit instance, 40 000 time steps and we changed the exploration parameter m in the latter. As it can be observed on two of the experiments, for too small values of m (respectively m=30 and m=100), the algorithm underexplores and fails to converge. If m is chosen too big (2000 in our example), the algorithm explores too much and incurs an important regret.
