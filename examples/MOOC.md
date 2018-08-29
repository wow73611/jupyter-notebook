# 2017 政大 MOOC 上課 - 成為python數據分析達人的第一課(自學課程)

參考：
http://moocs.nccu.edu.tw/course/123/intro
https://github.com/yenlung/Python-3-Data-Analysis-Basics

# [第一周]Python程式基礎 IPython的開發環境、串列與繪圖

###  簡介
安裝 Python 3.6
安裝 Anaconda 4.x
使用 Jupyter Notebook


### 建立 Jupyter環境

mkdir JupyterWorkspace
cd JupyterWorkspace
jupyter notebook


### Jupyter 魔術指令(建議少用)

執行Jupyter指令：shift + enter

參考：https://github.com/yenlung/Python-3-Data-Analysis-Basics/blob/master/2017%20%E6%94%BF%E5%A4%A7%20MOOC%20%E4%B8%8A%E8%AA%B2/0104%20Jupyter%20%E7%9A%84%E9%AD%94%E8%A1%93%E7%95%AB%E5%9C%96%E6%B3%95.ipynb

In: %pylab inline
    Populating the interactive namespace from numpy and matplotlib
In: sin(pi/2)
In: plot([-2, 10, 3, 13, 5])
In: randn(10)
In: plot(randn(100))
In: plot([-2, 1, 2.7, 3.3], [3, -5, 6, 0])
    #[x, ...],[y, ...]

查詢說明：
- 指令後面加上問號，例如 In: sin?
- shift + tab
- tag鍵可以自動補齊


### Jupyter - Markdown mode

從 Code mode 切換到 Markdown
Markdown mode切換快速鍵：Ctrl + m , m

Markdown語法
[Title](http://your.url)
![Titile](img.png)
我們有一個函數 $f(x)=x^3 - 2x^2 + 5$, 我想給它積分:\n
$$\\int_a^b f(x) \\, dx$$


### 數據分析的標準動作

%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
np.pi
plt.plot([3,-4,1,5,-2])
plt.plot(np.random.randn(100))
np.array([3,-4,1,5,-2])


# [第四週] 處理與展示資料的技巧： Python的字典檔與jupyter互動功能
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

from ipywidgets import interact

def f(x):
    print(x)
interact(f, x=3)

