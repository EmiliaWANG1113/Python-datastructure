# Python-file

### 檔案開啟語法
Python使用open()來開啟檔案，語法為:
```python
#file需要使用close來關閉檔案
file = open(“file path”, “mode”)
```
或是
```python
with open(“file path”,”mode”) as file:
#with body
```

### JSON
1. Javascript Object Notation
2. 相容性高
3. 格式容易了解、閱讀、修改
4. 支援多種不同的資料型態: 數值、字串、布林、陣列、字典
5. 多方函式庫支援

```python
#file需要使用close來關閉檔案
{
  key1:value1
  key2:[value2,value3]
  key3:
  {
     key4:value4
  }
}
```

### XML
1. Extensible Markup Language
2. 格式統一、符合標準
3. 容易與其他系統進行遠程交互，常用來傳輸數據
4. 可惜XML檔案龐大且複雜，不如JSON輕量

```python
#XML example
<?xml version="1.0"?>
<score>
  <student name="David">
    <Chinese>82</Chinese>
    <Math>80</Math>
    <Science>89</Science>
  </student>
</score>
```

### CSV
1. Comma-Separated Values
2. 文件結構簡單，基本上和文本差異不大
3. 可以和Excel或Google sheet進行轉換，非常方便
4. 格式十分簡單，所以儲存相同的資料，檔案大小也會比XML檔案小

```python
header1,header2,header3,...,headern
value1_1,value1_2,value1_3,...,value1_n
…
valuem_1,valuem_2,valuem_3,...,valuem_n
```
