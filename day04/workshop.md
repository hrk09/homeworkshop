# workshop

### 1.

```python
# 조건문 활용
def round_sqrt_root(x):
    if x > 0:
        if type(x) is int: 
            return f'제곱근 {x}의 근삿값은 {round(x ** 0.5, 2)}입니다.'
    else:
        return '양의 정수를 입력하세요'

print(round_sqrt_root(3))  # 제곱근 3의 근삿값은 1.73입니다.
```



