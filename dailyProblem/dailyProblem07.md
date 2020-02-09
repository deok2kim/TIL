# dailyProblem07

![dailyProblem06](C:\Users\korea\OneDrive\바탕 화면\새 폴더 (2)\dailyProblem06.png)

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

