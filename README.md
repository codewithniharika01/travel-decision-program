# Travel Decision Program

This Python program determines whether a person can travel based on distance, weather conditions, and available transportation options.

## Variables

* `distance_mi` → Distance to destination in miles
* `is_raining` → Whether it is raining (`True` or `False`)
* `has_bike` → Whether a bike is available
* `has_car` → Whether a car is available
* `has_ride_share_app` → Whether a ride-sharing app is available

## Logic

1. If no distance is provided, the program prints `False`.
2. If the distance is 1 mile or less, walking is allowed only when it is not raining.
3. If the distance is between 1 and 6 miles, a bike can be used if it is not raining.
4. If the distance is greater than 6 miles, a car or ride-sharing service is required.

## Example

```python
distance_mi = 4
is_raining = False
has_bike = True
has_car = False
has_ride_share_app = False
```

Output:

```python
True
```

## Technologies Used

* Python 3
  
* # Author
  Niharika
* Conditional Statements (`if`, `elif`, `else`)
* Boolean Logic
