# Notes on time series data processing tools
- Motivation and application:

  Reliability data modeling for performance/lifetime projection
  
- Major topics

  Hidden Markov Model (HMM), Kalman Filter (KF), TBA.
  
  Both HMM and KF assume that there is an observation layer and an unknown true-state layer.
  
## Hidden Markov Model (HMM) 

The system transitions from one state to the next with certain point-value probability (transition probability matrix). A real state is observed as a certain observation state with certain point-value probability (emission probability matrix).

1. Viterbi algorithm (MLE)
  - **Given**: System dynamics (transition matrix & emission probabilities) and a series of observations.
  - **Determine**: Most probable state series.
  
2. Baum-Welch algorithm (Expectation maximization)
  - **Given**: A series of observations.
  - **Determine**: System dynamics (transition matrix & emission probabilities).
```
Alternately optimize path and dynamics
```
## Kalman filter

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
