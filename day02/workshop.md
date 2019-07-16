# workshop

### 1. 

```python
n = 5
m = 9

for i in range(9):
    for k in range(5):
        print('*', end='')
    print()
```



### 2.

```python
students = {'python': 80, 'algorithm': 99, 'django': 89, 'flask': 83}
sum = 0
for student in students:
    sum += students[student]

print(sum / len(students))
```



### 3.

```python
blood_types = ['A', 'B', 'A', 'O', 'AB', 'AB', 'O', 'A', 'B', 'O', 'B', 'AB']
# print(blood_types.count('A'))
dict_blood = {i : blood_types.count(i) for i in blood_types}
print(dict_blood)
```

