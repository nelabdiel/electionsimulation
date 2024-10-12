# When to declare victory in an election?

**Objective**: The goal of this project is to model when Candidate A can confidently declare victory in an election based on real-time vote tallies, using Bayesian statistics with a Gamma prior. The model estimates the probability that Candidate A will win, given a dynamic tally of votes, and determines the point at which Candidate A can announce victory with 95% confidence.

Key Approach:
- Simulate votes using a true proportion for Candidate A.
- Use a Gamma prior to model the uncertainty in the vote distribution.
- Update the posterior as votes are counted.
- Compute the credible interval for the vote share and check when the lower bound exceeds 50%, indicating a majority.
- Announce victory once Candidate A's win is 95% certain.
