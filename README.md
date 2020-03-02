# fetch-bduss-baiduid ![Python package](https://github.com/ffreemt/fetch-bduss-baiduid/workflows/Python3.6|3.7%20package/badge.svg) [![codecov](https://codecov.io/gh/ffreemt/fetch-bduss-baiduid/branch/master/graph/badge.svg)](https://codecov.io/gh/ffreemt/fetch-bduss-baiduid)
简单方便 BDUSS 和 BAIDUID

### Installation
Not available yet
```pip install fetch-bduss-baiduid```

To validate installation
```
python -c "import fetch_bduss_id; print(fetch_bduss_id.__version__)"
# 0.0.1 或当时版本号
```

### Usage
先用Chrome浏览器登录 baidu。

```
import pyperclip
from fetch_bduss_id import fetch_bduss_id

bduss, baiduid = fetch_bduss_id()
print(bduss, baiduid)
# 输出： 你的 BDUSS 和 BAIDUID
# 并可从系统剪贴板里拷出 BDUSS
```
