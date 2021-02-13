This is a python skills task for a job application.

There are 2 data sets. 

The main data: order_data.csv

createdAt : the order creation timestamp
status : the order status (complete, canceled, etc.)
restaurantName : the restaurant name attached to the order
pickupDeadline : timestamp corresponding to the ETA of the driver in the restaurant
driverArrivedAtRestaurantAt : timestamp corresponding to the arrival time of the driver in the restaurant
pickedAt : timestamp corresponding to the driver picking the food in the restaurant

The restaurant area data: restaurantarea_data.csv

restaurantName : the restaurant name
area : the speaking area for the restaurant

The task is to take the data between the dates 2021-01-25 to 2021-01-31 by considering only the complete orders and removing the orders with missing timestamps.

Questions: 

What are the most popular restaurants in number of orders ?
At which time of the day do we have a peak in average ? ex : between 11:00 and 12:00 ? between 18:00 and 19:00 ?
For each restaurant compute the average waiting time for the driver : pickedAt - driverArrivedAtRestaurantAt
If the waiting time is to high (> 6min), add a warning flag to the restaurant
Make a join with the restaurant's area data and compute the waiting time per area

You will find the answers with accompanying visualizations in the notebook.
