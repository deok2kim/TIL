# dailyProblem06

![dailyProblem06](dailyProblem06.assets/dailyProblem06.png)

```python
### 기존의 이중 for문을 이용해 검사하는 방법은 답은 나오나 time error가 발생
### '에라토스테네스의 체' 라는 수학적 방법을 코드로 적용하여 해결!
def solution(n):
    answer = 0
    
    numbers = [ x for x in range(n+1)]
    answer -= 1
    for i in range(2, n+1):
        if numbers[i] == 0:
            continue
        for j in range(2*i, n+1, i):
            numbers[j] = 0
            
    for i in numbers:
        if i != 0:
            answer += 1
    return answer
```

