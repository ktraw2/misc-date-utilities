# Misc Date Utilities
Provides date subtraction, parsing, and random timestamp generation. Source code [on GitHub](https://github.com/ktraw2/misc-date-utilities).

### date_difference
For subtracting two dates from each other, provides class `DateDifference` that can store the difference between two dates, provides some overloaded functionality, and provides some static methods `subtract_datetimes` and `subtract_datestrings` to subtract datetimes and formatted date strings, respectively.

### simple_parse
A simple parser that is used in the interpretation of date strings, provides `parse_raw_date_string` to get a datetime from a string formatted as `"%Y-%m-%d "` (note the trailing space), or as `"%Y-%m-%d %H:%M"`.

### random_timestamps
Functionality for getting a random time within a specified range, provides `generate_random_timestamp` to generates a random timestamp in the range [00:00:00 - hours:minutes:seconds).

### tests
Unit tests are provided for `subtract_datestrings`.
