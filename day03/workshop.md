# Workshop

### 1.

```python
# 1번째 방법(for문 활용)
def Palindrome(word):     
    for i in range(len(word) // 2):  # 단어 절반까지만 비교
        if word[i] != word[-1 - i]:
            return('False')
    return('True')

print(Palindrome('level'))
```





```python
# 2번째 방법(reversed 활용)
def Palindrome(word):
        if list(word) == list(reversed(word)):     
            return True        
        else:
            return False

print(Palindrome('amama'))
```

