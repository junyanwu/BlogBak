---
title: tqdm使用说明
date: 2017-12-21 11:05:23
categories: Python
tags:
- Python
---

## from tqdm import trange

这个是一个强大的终端进度条工具

```python
from tqdm import tqdm
for i in tqdm(range(10000)):
  pass
```

76%|████████████████████████████        | 7568/10000 [00:33<00:10, 229.00it/s]
