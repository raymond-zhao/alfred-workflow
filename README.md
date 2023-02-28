# alfred-workflow

## 使用方式

因为工作流中需要进行网络请求，并使用浏览器 Cookie 信息，并且工作流使用 Python 3 实现，所以需要两个 Python 库。

```shell
python3 -m pip install requests pycookiecheat
```

## LeetCode 工作流

包含《剑指 Offer》与《Hot 100》两个题集及其题解，支持按照题目编号与题目名称进行搜索，回车后通过浏览器跳转至 [LeetCode 中文网站](https://leetcode.cn/)。唤起方式：

- `sto`：获取《剑指 Offer》题目；
- `stos`：获取《剑指 Offer》题解；
- `hot100`：获取《Hot 100》题目；
- `hot100s`：获取《Hot 100》题解；
