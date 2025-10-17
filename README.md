# VPython-02

## Python 新手教學：變數與資料型態 (Variables and Data Types)

Python 是一種非常適合初學者的程式語言，它語法簡潔、易於閱讀。

## 1. 什麼是變數 (Variables)？

在程式設計中，變數就像是一個標籤或容器，用來儲存資料。你可以用一個好記的名字來代表這些資料，方便在程式中取用和修改。

### 如何建立變數？ (Creating Variables)

在 Python 中，你不需要事先宣告變數的型態，可以直接用 = 賦值（assign）來建立變數。

**範例 (Example):**

```python
# 建立一個變數來儲存數字
age = 30

# 建立一個變數來儲存文字
name = "小明"

# 建立一個變數來儲存是/非的狀態
is_student = True
```

### 變數命名規則 (Variable Naming Rules)

- **開頭**: 必須以字母或底線 (_) 開頭。不能以數字開頭。
- **內容**: 只能包含字母、數字和底線。
- **大小寫**: 變數名稱是區分大小寫的（Age 和 age 是兩個不同的變數）。
- **保留字**: 不能使用 Python 的保留字（例如 if, for, while, True, False 等）。

## 2. 什麼是資料型態 (Data Types)？

資料型態決定了資料在電腦中是以什麼形式儲存、以及程式可以對它進行什麼操作。Python 有許多內建的基本資料型態，我們從最常見的開始：

### (A) 數值型態 (Numeric Types)

用於處理數字。主要分為兩種：

| 型態 | 英文名稱 | 說明 | 範例 |
|------|----------|------|------|
| 整數 | int (Integer) | 不帶小數點的數，可以是正、負或零。 | `10`, `-5`, `0` |
| 浮點數 | float (Floating Point Number) | 帶有小數點的數（即實數）。 | `3.14`, `-0.5`, `10.0` |

```python
integer_number = 100         # int (整數)
float_number = 99.9          # float (浮點數)
```

### (B) 字串型態 (String Type)

用於處理文字。在 Python 中，字串是用單引號 (') 或雙引號 (") 括起來的任何內容。

| 型態 | 英文名稱 | 說明 | 範例 |
|------|----------|------|------|
| 字串 | str (String) | 一個或多個字元的序列。 | `"Hello"`, `'Python'`, `"123"` |

```python
greeting = "歡迎來到 Python 世界"  # str (字串)
char = 'A'                      # 雖然只有一個字元，在 Python 中仍是 str
```

### (C) 布林型態 (Boolean Type)

用於處理邏輯。只有兩個可能的值：

| 型態 | 英文名稱 | 說明 | 範例 |
|------|----------|------|------|
| 布林 | bool (Boolean) | 表示真 (True) 或 假 (False)。 | `True`, `False` |

```python
is_adult = True           # bool (布林)
is_raining = False        # bool (布林)
```

## 3. 如何檢查資料型態？

你可以使用內建的 `type()` 函式來查看任何變數或資料的型態。

**範例:**

```python
a = 15
b = 3.14159
c = "教學"
d = True

print(type(a))  # 輸出: <class 'int'>
print(type(b))  # 輸出: <class 'float'>
print(type(c))  # 輸出: <class 'str'>
print(type(d))  # 輸出: <class 'bool'>
```


## 練習

### 1. 簡單的輸出 (Output)

使用 `print()` 函式可以將變數或資料的內容顯示在畫面上。

**請使用程式編輯器輸出:**
1. 自己的名字
2. 自己的身高
3. 自己的年齡
