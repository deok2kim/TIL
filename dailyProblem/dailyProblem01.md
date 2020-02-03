# daily problem

![image-20200203193133278](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20200203193133278.png)

```python
def solution(a, b):
    answer = 0
    if b < a:
        a, b = b, a
    for i in range(a,b+1):
        answer += i
    return answer
```

