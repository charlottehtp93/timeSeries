# Notes on time series data processing tools
- Motivation and application:

  Reliability data modeling for performance/lifetime projection
  
- Major topics

  Hidden Markov Model (HMM), Kalman filer, TBA
  
## Hidden Markov Model (HMM) - _Real system states are hidden_

1. Viterbi algorithm
  - **Given**: System dynamics (transition probabilities & emission probabilities) and a series of observations.
  - **Determine**: Most probable state series.
  
2. Baum-Welch algorithm
  - **Given**: A series of observations.
  - **Determine**: System dynamics (transition probabilities & emission probabilities).
  
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
