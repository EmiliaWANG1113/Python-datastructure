# Python-fuction

### 函式的定義
```python
 # 表示法
 def 函數名稱(參數1,參數2,...):
     函數主體...
     …
     return 回傳值1,回傳值2
```

### Lambda運算式
lambda 參數1, 參數2,... : 函式本體
```python
 # 表示法
 max = lambda n1, n2 : n1 if n1>n2 else n2
 print(max(10,5)) # 結果 =10
```

### Pass by value, Pass by reference
1. 傳遞參數時，若此參數是Immutable，則自動使用Pass by value
2. 若此參數是Mutable，則自動使用Pass by reference的方式傳入

|     |Immutable(不可變動的)|Mutable(可變動的)|
|  ----  | ----  | ----  |
| 定義  | 變數建立以後就不可以再變動的 |變數建立以後仍然可以新增或移除資料 |
| 型態   | numbers, booleans, strings, tuples |lists, dictionaries, set  |


