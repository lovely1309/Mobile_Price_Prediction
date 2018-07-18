# Mobile_Price_Prediction
### Objective
To predict actual price of mobile based on features but price range indicating how high the price is ,using machine learning.

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)
### Short description of the dataset:

| Feature name  |  Feature description                                  |  Type   |
|---------------|-------------------------------------------------------|---------|
| id            | ID                                                    | Numeric |
| battery_power | Total energy a battery can store in mAh               | Numeric |
| blue          | Has bluetooth or not                                  | Boolean |
| clock_speed   | Speed at which microprocessor executes instructions   | Numeric |
| dual_sim      | Has dual sim support or not                           | Boolean |
| fc            | Front Camera mega pixels                              | Numeric |
| four_g        | Has 4G or not                                         | Boolean |
| int_memory    | Internal Memory in Gigabytes                          | Numeric |
| m_dep         | Mobile Depth in cm                                    | Numeric |
| mobile_wt     | Weight of mobile phone                                | Numeric |
| n_cores       | Number of cores of processor                          | Numeric |
| pc            | Primary Camera mega pixels                            | Numeric |
| px_height     | Pixel Resolution Height                               | Numeric |
| px_width      | Pixel Resolution Width                                | Numeric |
| ram           | Random Access Memory in Megabytes                     | Numeric |
| sc_h          | Screen Height of mobile in cm                         | Numeric |
| sc_w          | Screen Width of mobile in cm                          | Numeric |
| talk_time     | Longest time that battery will last by a call         | Numeric |
| three_g       | Has 3G or not                                         | Boolean |
| touch_screen  | Has touch screen or not                               | Boolean |
| wifi          | Has wifi or not                                       | Numeric |
### Outcome metrics_score:

| Model name                   |Accuracy_score|
|------------------------------|--------------|
| Random forest with           | 0.87125      |
| AdaBoostClassifier           | 0.52125      | 
| Logistic regression          | 0.8125       |
| KNN classifier               | 0.9199       | 


