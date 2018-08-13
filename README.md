# Using genetic algorithm for neural network classifier for LHCb experiment

## After use generic algorithm for feature selection
Feature selection is done in repository https://github.com/PiotrWNowak/Genetic_algorithm_feature_selection .

In model_training.py we run model for whole set of events (1.7*10^6).
<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_2.png">
</p>

<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_1.png">
</p>

### Comparise results model trained with and without feature selection.
<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_8.png">
</p>

After we make sure that the model has best performance in model_analysys.py and model_analysys.ipynb we do rest of analysys.


## Final model analysis

<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_9.png">
</p>

### For threshold = 0.5
<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_5.png">
</p>

<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_4.png">
</p>

### Threshold was changed to get 96% true positive rate (sensitivity)

<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_3.png">
</p>

<p align="center">
  <img src="https://github.com/PiotrWNowak/LHCb_trigger_genetic_algorithm/raw/master/images/Figure_6.png">
</p>


## Author

**Piotr Nowak**
