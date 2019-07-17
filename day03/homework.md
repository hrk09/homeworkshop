# Homework

### 1.

```python
dir(__builtins__)
```

- max

```python
def max_num(a, b):
    result = a if a > b else b
    return f'{result}가 더 크다'
result = max_num(1, 20)
print(result)
```

- list

```
def num_list[
```

- enumerate

```python
for key, val in enumerate(['a', 'b', 'c']):
    print(key, val)
```

- round

```python
def cylinder(r, h):
    return r ** 2 * h * 3.14
print(round(cylinder(2,5), 2))
```

- range

```python
list(range(1, 10, 3))
```





### 2.

```python
# 1번
def ssafy(name, location='서울'):
    print(f'{name}의 지역은 {location} 입니다.')
ssafy(location='대전', name='철수')  # 철수의 지역은 대전 입니다.
```

```python
# 2번
def ssafy(name, location='서울'):
    print(f'{name}의 지역은 {location} 입니다.')

ssafy('길동', location='광주')  # 길동의 지역은 광주 입니다.
```

```python
# 3번(오류 발생)
def ssafy(name, location='서울'):
    print(f'{name}의 지역은 {location} 입니다.')
ssafy(name='허준', '구미')
#     ssafy(name='허준', '구미')
                        ^
# SyntaxError: positional argument follows keyword argument
```



### 3.

```python
11
```

