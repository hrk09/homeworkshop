# Homework

### 1.

```python
# 변경 가능: list, set, dictionary 


# 변경 불가: string, tuple, range
```



### 2.

```python
홀수 = []
for num in range(50):
    if num % 2 == 1:
        홀수 += [num]
print(홀수)
```



### 3.

```python
student_name = ['Kim', 'Lee', 'Song', 'Park', 'Han']
student_age = [22, 24, 26, 28, 30]
student_dict = dict(zip(student_name, student_age))
print(student_dict)
```



