# daily problem

![dailyProblem01](dailyProblem01.assets/dailyProblem01.jpg)

```python
def solution(a, b):
    answer = 0
    if b < a:
        a, b = b, a
    for i in range(a,b+1):
        answer += i
    return answer
```

