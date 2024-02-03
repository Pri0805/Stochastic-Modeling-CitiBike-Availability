# Stochastic-Modeling-CitiBike-Availability

1. Estimating the steady-state of the number of available bikes in a CitiBike station using Markov chains. Goal is to come up with a simple estimation of the number of available bikes in that station at the end of the morning of any given day in July 2023.
2. Choosing three CitiBike stations in NYC. Choosing popular stations where there is a lot of movements (i.e., bike coming in/biking going out very frequently).
3. Splitting the day into two blocks of time, morning/evening and focus only on weekdays.
4. Discretizing each block in periods of 10 minutes.
5. Modeling the number of available bikes in a station as a Discrete Markov Chain.
6. The states of the Markov Chain are all the integers between 0 and the capacity of the stations (i.e., number of docks).
7. Using the full month of data estimating the transition probability matrix of each station.
8. Note: Estimating one matrix for the morning block and another one for the evening block since the patterns are different.
9. Using only weekdays because again patterns are different on the weekend.
10. Computing the stationary distribution for each station (the morning one and the evening one) and commenting on the results. Explaining insights driven from this study.
