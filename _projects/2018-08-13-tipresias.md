---
layout: post
title: 'Tipresias'
excerpt: "A machine-learning application for predicting AFL match results (i.e. 'footy tipping'), this project is composed of the following services: Django web application serving data to a React frontend via a GraphQL API, Kedro data-science project (Python & Jupyter notebooks) that runs in serverless functions, R application for fetching data."
---

{% include button.html color="#24292e" icon="github" text="tipresias" link="https://github.com/tipresias" %}{% include button.html text="tipresias.net" link="http://www.tipresias.net" %}

The successor to Footy Tipper. I decided to start over from scratch, because:
1. I needed a better name.
2. Footy Tipper was more than a little refactoring away from being maintainable or extendible.

From what I had learned the first time around, I was able to write cleaner application code and create a roughly-equivalent model that was much simpler and faster to train. The current iteration is a stacked ensemble with an XGBoost regressor, ELO model, and ARIMA model all feeding into an Extremely-Randomized Trees meta-estimator. As a special bonus, there's an extra XGBoost regressor for predicting win probabilities in order to participate in the Monash University [probabilistic tipping competition](http://probabilistic-footy.monash.edu/~footy/about.shtml). As an extra special bonus bonus, there's now a mostly-functional website at [http://www.tipresias.net](tipresias.net) that will display tips and track model performance.