---
description: 全局函数是可以在任意脚本中使用的函数
---

# 全局函数



最常用的全局函数

| 基本格式 | 用途 |
| :--- | :--- |
| `print(字符串)` | 在日志中打印信息。（输入可以是任何数据类型，它们会自动转型为 `string`） |
| `isNull(对象)` | 检测对象是否为`null`（空），经常用这个规避NPE（空指针异常）。对数据类型对象（`int`、`float` 等）无效。 |
| `pow(双精度浮点数A, 双精度浮点数B)` | 返回A的B次方 |
| `min(整型A,整型B)` | 返回A与B较小的一个 |
| `max(整型A,整型B)` | 返回A与B较大的一个 |
