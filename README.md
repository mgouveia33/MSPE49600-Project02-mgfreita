# Project 2: Predictive Modeling and Engineering Optimization #
Name: Maico Freitas

_MSPE 49600 – Data Analytics for Motorsports_

This project uses synthetic data representing a vehicle setup study at the Indianapolis Motor Speedway road course. It examines how rear-wing angle and rear ride height affect Sector 3 time and top speed using quadratic surrogate models.

An unconstrained optimization is first performed to minimize predicted Sector 3 time within the tested setup bounds. A constrained optimization is then performed with the additional requirement that predicted top speed remains at or above 284 km/h. The solutions are also checked using a grid-based search and a penalty-function approach.

The final candidate wing_angle_deg = 9.541827	and rear_ride_height_mm = 38.327667 was chosen based on the trade-off between sector 3 lap time and top speed rather than simply selecting the setup with the fastest predicted sector time. The optimization results and independent grid search were compared to make sure the selected setup was consistent and feasible.
