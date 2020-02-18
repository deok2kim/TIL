# dailyProblem12

![dailyProblem12](dailyProblem12.assets/dailyProblem12.jpg)

```python
def solution(n):
    answer = []
    word = str(n)
    for i in range(-1,(-1)*len(word)-1,-1):
        answer.append(int(word[i]))
    return answer
```

