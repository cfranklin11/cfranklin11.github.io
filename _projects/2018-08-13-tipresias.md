---
title: 'Tipresias'
excerpt: "From what I had learned the first time around, I was able to write cleaner application code and create a roughly-equivalent model that was much simpler and faster to train. The current iteration is a stacked ensemble with an XGBoost regressor, ELO model, and ARIMA model all feeding into an Extremely-Randomized Trees meta-estimator."
categories:
  - python
  - machinelearning
  - docker
  - react
  - javascript
  - graphql
  - serverless
featured_image: 'img/posts/tipresias.png'
project_links:
  - project_link: 'https://github.com/tipresias/tipresias'
    button_icon: 'github'
    button_text: 'Visit Repo'
  - project_link: 'http://www.tipresias.net'
    button_icon: 'cog'
    button_text: 'Visit Site'
---

The successor to Footy Tipper. I decided to start over from scratch, because:
1. I needed a better name.
2. Footy Tipper was more than a little refactoring away from being maintainable or extendible.

From what I had learned the first time around, I was able to write cleaner application code and create a roughly-equivalent model that was much simpler and faster to train. The current iteration is a stacked ensemble with an XGBoost regressor, ELO model, and ARIMA model all feeding into an Extremely-Randomized Trees meta-estimator. As a special bonus, there's an extra XGBoost regressor for predicting win probabilities in order to participate in the Monash University [probabilistic tipping competition](http://probabilistic-footy.monash.edu/~footy/about.shtml). As an extra special bonus bonus, there's now a mostly-functional website at [tipresias.net](tipresias.net) that will display tips and track model performance.