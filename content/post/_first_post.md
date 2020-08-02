---
title: My Fisrt Post
data: 2020-08-02

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

**这是我的第一篇博客，仅用作测试。**

## 第一部分

### 代码测试

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

### 公式测试

$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$