# Skari_TC_Feature_Env
Jack Skari's tropical cyclone and buoyancy research project under Dr. David Neelin and Dr. Fiaz Ahmed at UCLA
The goal of this project is to better understand how tropical cyclones interact with the environment. By using TempestExtremes ERA5 data from histroical tropical cyclones from 2002-2013 and the [equations dervied by Drs. Neelin and Ahmed](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021GL094108), I seek to understand how the components of buoyancy vary from storm to storm and from inside of the storm to outside the storm.

The current direction of the project is to compare the difference between averaged buoyancy inside and outside of the storm for every storm that has values inside of the tropics (35 South to 35 North), and find a general trend. Due to TempestExtremes lacking the size values of each storm, current results are not as accurate as they could be. In addition, ERA5 data conflicts with reported National Hurricane Center data, and has a limited scope in years.

The current step I am taking is to use machine learning and the averaged subsaturation between inside and outside of the storm in order to use logistic regression to classify the inside and outside of a storm via the subsaturation values.
