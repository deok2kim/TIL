# dailyProblem18

![dailyProblem18](dailyProblem18.assets/dailyProblem18.jpg)

```python
def solution(x):
    answer = True
    hasa = 0
    for i in str(x):
        hasa += int(i)
    if x % hasa != 0:
        answer = False
    return answer
```

