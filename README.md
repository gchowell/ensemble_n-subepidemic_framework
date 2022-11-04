# ensemble_n-subepidemic_framework
A Matlab toolbox for fitting and forecasting epidemic trajectories using the ensemble n-subepidemic framework

It carries out the following tasks:

    fitting models to time series data,
    estimation of parameters with quantified uncertainty,
    plotting the fits of the top-ranked models,
    plotting the AICc values of the top-ranked models,
    generates forecasts of the top-ranked models
    gnerates ensemble forecasts based on the top-ranked models.

Additional features include:

    fitting models using different parameter estimation approaches (least-squares, maximum likelihood estimation),
    fitting models using assuming different error structures (normal, Poisson, negagive binomial),
    user can select the underlying function for the sub-epidemic building block (generalized-logistic model, Richards model, Gompertz model),
    user can select whether the sub-epidemics start synchronously at time 0 or asynchronously at different times as defined by parameter C_thr.
    
  
# Installation requirements

The n-subepidemic framework toolbox requires a MATLAB installation.

# Fitting the model to your data

To use the toolbox to fit the ensemble n-subepidemic framework to your data, you just need to:

    download the code
    open a MATLAB session
    define the model parameter values and time series parameters by editing options.m
    run the function Run_subepidemicFramework.m
    
# Plotting the fits of the top-ranked models and parameter estimates

After fitting the model to your data, you can use the toolbox to plot the model fits and parameter estimates as follows:

    define the model parameter values and time series parameters by editing options.m
    run the function plotFit_subepidemicFramework.m
   
# Plotting the top-ranked subepidemic model profiles and the corresponding AIC values

After fitting the model to your data, you can use the toolbox to plot the subepidemic profiles and AICc values as follows:

    define the model parameter values and time series parameters by editing options.m
    run the function plotRankings_subepidemicFramework.m

# Generating and plotting forecasts of the top-ranked and ensemble subepidemic models

After fitting the model to your data, you can use the toolbox to plot forecasts derived from the top-ranked and ensemble subepidemic models as follows:

    define the model parameter values and time series parameters by editing options.m and options_forecast.m
    run the function plotRankings_subepidemicFramework.m

After fitting the model to your data, you can use the toolbox to plot the subepidemic profiles and AICc values as follows:

    define the model parameter values and time series parameters by editing options.m
    run the function plotForecast_subepidemicFramework.m





   
   
   

