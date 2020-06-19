# 用Python做自动化测试——unitest/pytest

## 单元测试的概念
> 标准的白盒测试 对代码最小的单元进行测试
> 单元测试进展不好 大多类的覆盖
1. 单元测试的价值
2. 单元测试的难点

## 单元测试覆盖率
1. 语句覆盖

测试过程中被击中的代码行即称为被覆盖的语句

2. 判断覆盖

运行测试中被击中的判断语句

3. 条件覆盖
4. 路径覆盖

被测试函数：
```python
def demomethod(a, b, x):
  if (a>1 and b==0): x = x / a
  if (a==2 or x>1): x = x + 1
  return x
```
## pytest框架（比unitest好）

## Unittest的编写规范
