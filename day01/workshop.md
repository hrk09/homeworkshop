# workshop

### 1번

```python
# 첫 번째 방법
n = 5
m = 9
print(('*'*n + '\n')*m)

# 두 번째 방법
n = 5
m = 9

for i in range(9):
    for k in range(5):
        print('*', end='')
    print()

```





### 2번

```python
print('"파일은 C:\Windows\\Users\\내문서\\Python에 저장이 되어있습니다."\n나는생각했다.\'cd를 써서 git bash로 들어가봐야지\'')
```





### 3번

```python
print('ax2 + bx + c = 0')

a = float(input('a : '))
b = float(input('b : '))
c = float(input('c : '))

D = b * b - 4 * a * c

if a == 0:
    print('a = 0 :이차방정식이 아님.')

if D > 0:
    x1 = (-b + math.sqrt(D)) / (2 * a)
    x2 = (-b - math.sqrt(D)) / (2 * a)
    print('2개의 해 :', x1, x2)

if D == 0:
    x = -b / (2 * a)
    print('1개의 해(중근) :', x)

if D < 0:
    print('해가 없음')
```

