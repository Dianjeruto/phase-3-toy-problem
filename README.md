# phase-3-toy-problem

This repository contains solutions for three coding challenges. These challenges cover various programming concepts and are designed to test your problem-solving skills. Below, you'll find a description of each challenge along with usage examples for the provided functions.

## challenge 1: Converting 12-hour time to 24-hour time

### Description
This challenge involves converting a 12-hour time (e.g., "8:30 am" or "8:30 pm") to 24-hour time (e.g., "0830" or "2030").

### Function
The function `convert_to_24_hour(hour, minute, period)` takes three inputs: `hour` (in the range of 1 to 12), `minute` (in the range of 0 to 59), and `period` ("am" or "pm"). It returns a four-digit string representing the time in 24-hour format.

### Example

time_1 = convert_to_24_hour(8, 30, "am")
print(time_1)  # Output: "0830"

time_2 = convert_to_24_hour(8, 30, "pm")
print(time_2)  # Output: "2030"


## Challenge 2: Two numbers are positive
### Description

This challenge involves determining whether exactly two out of three given integers are positive numbers.
Function

The function exactly_two_positive(a, b, c) takes three integer inputs: a, b, and c. It returns True if exactly two of the three integers are positive numbers, and False otherwise.

### Example
result_1 = exactly_two_positive(2, 4, -3)
print(result_1)  # Output: True

result_2 = exactly_two_positive(-4, 6, 8)
print(result_2)  # Output: True

result_3 = exactly_two_positive(4, -6, 9)
print(result_3)  # Output: True


## Challenge 3: Consonant value
### Description

This challenge involves finding the highest value of consonant substrings in a given lowercase string.
Function

The function solve(s) takes a single input: a lowercase string containing only alphabetic characters (no spaces). It returns the highest value of consonant substrings, where consonants are any letters except "aeiou".
### Example
value_1 = solve("zodiacs")
print(value_1)  # Output: 26

value_2 = solve("strength")
print(value_2)  # Output: 57

### Installation

Step-by-step instructions on installing the project.

1. Clone the repository: `git clone git@github.com:Dianjeruto/phase-3-toy-problem.git`
2. Change into the project directory: `cd phase-3-toy-problem`


This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
Author: Dian Jeruto

