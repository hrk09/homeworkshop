# homework

### 1.

```python
# Local scope: 정의된 함수
# Enclosed scope: 상위 함수
# Global scope: 함수 밖의 변수 혹은 import된 모듈
# Built-in scope: 파이썬안에 내장되어 있는 함수 또는 속성
```



### 2.

```python
(1)o
def a(n):
    if n < 3:
        return 1, 3
    else:
        print

print(a(2))
```

```python
# (2)
def func():
    print('a')

print(func())  # print 하면 None 값이 출력됨
```

```python
# (3)
# parameter(매개변수)는 변수, argument(전달인자)는 값(value)
```

```python
# (4)
def func(*args):
    print(type(args))

    
func(123, 342, 345)  # 출력하면 type 이 tuple로 출력되는 것을 알 수 있다.
```





### 3.

- **장점**

  - 직관적이고 이해하기 쉽다.(직관적인 코딩 가능)

    ```python
    # 재귀함수를 활용한 코드 예시(피보나치수열)
    def fibo(n):
        if n < 3:
            return 1
        else:
            return fibo(n - 1) + fibo(n - 2)
    print(fibo(4))
    ```

    ```python
    # for문 활용한 코드 예시(피보나치수열)
    def fibo(n):
        list = []
        for i in range(0, n):
            if i <2:
                list.append(1)
            else:
                list.append(list[i - 1] + list[i - 2])
        return list[n - 1]
    
    print(fibo(4))
    ```

  - 점화식을 코드로 표현하는 데 효율적이다. (수학적으로 정의한 규칙 구현에 용이함)

- 단점

  - 만들기 어렵다
  - 반복문에 비해 느리다 (메모리 차지가 상당함)