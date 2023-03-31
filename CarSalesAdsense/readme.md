# Project description
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.

# Description of the data
* `price` - price of the vehicle
* `model_year` - model year of the vehicle
* `model` - type of model
* `condition` - condition of the vehicle
* `cylinders` - number of cylinders
* `fuel` — gas, diesel, etc.
* `odometer` — the vehicle's mileage when the ad was published
* `transmission` - type of transmission
* `paint_color` - color of the vehicle
* `is_4wd` — whether the vehicle has 4-wheel drive (Boolean type)
* `date_posted` — the date the ad was published
* `days_listed` — from publication to removal

# Answer these questions:
* Study the following parameters: price, vehicle's age when the ad was placed, mileage, number of cylinders, and condition. Plot histograms for each of these parameters. Study how outliers affect the form and readability of the histograms.
* Determine the upper limits of outliers, remove the outliers and store them in a separate DataFrame, and continue your work with the filtered data.
* Use the filtered data to plot new histograms. Compare them with the earlier histograms (the ones that included outliers). Draw conclusions for each histogram.
* Study how many days advertisements were displayed (days_listed). Plot a histogram. Calculate the mean and median. Describe the typical lifetime of an ad. Determine when ads were removed quickly, and when they were listed for an abnormally long time.
* Analyze the number of ads and the average price for each type of vehicle. Plot a graph showing the dependence of the number of ads on the vehicle type. Select the two types with the greatest number of ads.
* What factors impact the price most? Take each of the popular types you detected at the previous stage and study whether the price depends on age, mileage, condition, transmission type, and color. For categorical variables (transmission type and color), plot box-and-whisker charts, and create scatterplots for the rest. When analyzing categorical variables, note that the categories must have at least 50 ads; otherwise, their parameters won't be valid for analysis.

# Libraries Used
* Pandas
* Matplotlib.pyplot
