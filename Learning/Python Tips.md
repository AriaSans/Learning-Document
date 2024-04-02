# Python Tips

## 一、文件

#### 1、文件路径

```py
import os

file_path = os.path.join('page1','page2','page3','img.png')
# file_path = "page1\page2\page3\img.png"
```

#### 2、创建文件

```python
f = open('img.png', mode='wb')		// 创建一个名字为 img.png 的文件, 模式写入
f.write(chunk)		// 写入
f.close()				//关闭
```

