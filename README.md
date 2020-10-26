# NYC Taxi Trip Duration 

![Taxi](https://user-images.githubusercontent.com/71483128/97131773-06ebfa80-176b-11eb-820e-be10a3f97820.jpg)

## Problem Statement: 

The NYC Taxi company wants us to predict the duration of each trip at the point when the trip starts.

## Hypothesis Generation:

- Start datetime: Weekends tend to have lesser trip duration due to less congestion.
- Pickup and Drop Location : Distance between these locations.
- Weather 
- Traffic

## Data Extraction:

We collect data from different systems, like:
- Trip
- Traffic and Geographic Information
- Weather

So the data points are:

- id 
- vendor_id
- pickup_datetime
- dropoff_datetime
- passengers_count
- pickup_longitude
- pickup_latitude
- dropoff_longitude
- dropoff_latitude
- store_and_fwd_flag
- trip_duration

