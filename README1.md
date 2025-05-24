# Weekly Step Analysis Report

## Overview

This report presents an analysis of the **number of steps walked each day** over a week. We compare daily steps with personal goals and against our friends' performances.

---

## Goals and Motivation

- Walk at least *10,000 steps per day*
- Beat average step count of friends
- Maintain consistency through the week

<!-- This is a hidden comment in Markdown -->

## Summary Table

| Day       | My Steps | Friend A | Friend B |
|-----------|----------|----------|----------|
| Monday    | 12,345   | 10,004   | 9,876    |
| Tuesday   | 10,876   | 11,222   | 10,000   |
| Wednesday | 9,210    | 10,345   | 11,765   |
| Thursday  | 10,342   | 10,654   | 9,876    |
| Friday    | 12,120   | 11,400   | 12,300   |
| Saturday  | 8,954    | 10,876   | 10,000   |
| Sunday    | 13,002   | 11,111   | 12,678   |

---

## Key Insights

1. Consistently met the 10k target on **5 out of 7 days**.
2. Friend B was the top performer on Sunday.
3. ~~Missed step goals on Wednesday and Saturday~~

## Technical Notes

Here's the snippet used to generate the weekly average:

```python
# Python snippet to calculate weekly average
def average(steps):
    return sum(steps) / len(steps)

my_steps = [12345, 10876, 9210, 10342, 12120, 8954, 13002]
print(average(my_steps))

Add documentation for step analysis project
