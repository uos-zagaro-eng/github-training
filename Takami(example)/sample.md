<!--
AtCoder ABC086A - Product
https://atcoder.jp/contests/abc086/tasks/abc086_a
問題: 2 つの整数 a, b が与えられる。a×b が偶数なら Even、奇数なら Odd を出力せよ。
-->

# 回答（Python）
```python
a, b = map(int, input().split())
print("Even" if (a * b) % 2 == 0 else "Odd")
```