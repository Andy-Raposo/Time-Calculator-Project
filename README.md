## Time Duration Calculator - Time Calculator with AM/PM and Weekday Support

This is my custom Python function to add a duration to a given start time in 12-hour AM/PM format. It's a project I designed as part of
freeCodeCamp's Certification in Python (Scientific Computing). It optionally supports calculating the resulting weekday and tracks how many
days later the time ends up.

## Features:

- Takes a start time with AM/PM format (e.g., 2:59 AM)
- Adds a duration given in hours and minutes (e.g., 24:00)
- Optionally handles weekday input and calculates resulting weekday
- Returns time with correct AM/PM, minutes formatted with leading zero
- Shows if the result is on the next day or several days later
- Validates input formats with helpful error messages

## Usage

Call the function add_time with the following parameters:

```python
add_time(start, duration, weekday=None)
```


## Example

```python
print(add_time('2:59 AM', '24:00'))
print(add_time('11:30 AM', '2:32', 'Monday'))
print(add_time('11:43 PM', '24:20', 'tuesday'))
```

## Output

```python
2:59 AM (next day)
2:02 PM, Monday
12:03 AM, Wednesday (2 days later)
```
