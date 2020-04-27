# Challenge 6 (26/04/2020): Niven Numbers

## Specification

A niven number is a non-negative number that is divisible by the sum of its digits.

Write a function/method named `niven` which prints all the niven numbers from 0 to 100 inclusive, each on their own line. The function needs to compute the solution, i.e., it is not acceptable to use any pre-computed data structure or solution.

Source: https://code-golf.io/niven-numbers

## Solutions

### Python (73) by Duarte

```python
def niven():[print(i)for i in range(1,101)if i%sum([*map(int,str(i))])<1]
```

[Try it online!](https://tio.run/##LcwxCoAwDADAr2QREulgcRHxJ@Ig2GoGY0mr4OtjB/fj0luOS/ohqdkWIgg/QZDGOSlLQaZ4KTCwgK6yB/TOd544Ajf5PnFuzzVhlS4XrZoWmvxi/2If)
