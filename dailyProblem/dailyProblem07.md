# dailyProblem07

![dailyProblem07](dailyProblem07.assets/dailyProblem07.jpg)

```python
def solution(arr):
    answer = []
    if len(arr) == 1:
        answer.append(-1)
    else:
        arr.remove(min(arr))
        answer = arr
    return answer
```

