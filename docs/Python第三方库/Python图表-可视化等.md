



## Seaborn
Seaborn主要关注统计模型的可视化；这种可视化包括热图，这些热图（heat map）总结数据但仍描绘整体分布。Seaborn基于Matplotlib，并高度依赖于此。

## Bokeh 
Bokeh 是一个专门设计可视化交互并用于现代的 Web 浏览器的展示。开发者可以利用 Bokeh 以类似于D3.js的方式创建一流的可视媒体。除此之外，你可以利用非常大的或者流式的数据集来扩展更强的表现交互的能力。你可以通过 Bokeh 创建可视化端点，仪表盘和数据应用。开发者也可以利用 Bokeh 处理通过其他类库，比如 Matplotlib, Seaborn 和 ggplot 创建的可视化图形。Bokeh 也可以和 Jupyter Notebooks 很好的结合来用于研究领域。

## Plotly
它是一个基于Web用于构建可视化的工具箱，提供API给一些编程语言（Python在内）。在plot.ly网站上有一些强大的、上手即用的图形。为了使用Plotly，你将需要设置API密钥。图形将在服务器端处理，并发布到互联网，但有一种方法可以避免。

## pyEcharts


## PyQtGraph
pyqtgraph是Python平台上一种功能强大的2D/3D绘图库，相对于matplotlib库，由于其在内部实现方式上，使用了高速计算的numpy信号处理库以及Qt的GraphicsView框架，因此它在大数据量的处理及快速显示方面有着天然的优势，非常适合于需要快速绘图更新、视频或实时交互性的操作场合，在数学、科学和工程领域都有着广泛的应用。
Scientific Graphics and GUI Library for Python  
官网：<http://www.pyqtgraph.org/>  
介绍：[Python+pyqtgraph：跟我学如何绘制股票K线图](https://baijiahao.baidu.com/s?id=1623441546635160463&wfr=spider&for=pc)  


## Matplotlib

一个SciPy Stack核心软件包以及 Python库，Matplotlib为轻松生成简单而强大的可视化而量身定制。它是一个顶尖的软件（在NumPy，SciPy和Pandas的帮助下），它使Python成为像MatLab或Mathematica这样的科学工具的竞争对手。然而，这个库是低层级的，这意味着你需要编写更多的代码才能达到高级的可视化效果，而且通常会比使用更多的高级工具付出更多的努力，但总体上这些努力是值得的。  
注意： 对应python2.7的安装(支持py2.7的最小长期支持版本2.2.3)：`pip install matplotlib==2.2.3  `  
官网：<https://matplotlib.org/index.html>
源码：<https://github.com/matplotlib/matplotlib> 

使用是可能遇到的错误信息：
ImportError: Python is not installed as a framework. The Mac OS X backend will not be able to function correctly if Python is not installed as a framework. See the Python documentation for more information on installing Python as a framework on Mac OS X. Please either reinstall Python as a framework, or try one of the otherbackends. If you are using (Ana)Conda please install python.app and replace the use of 'python' with 'pythonw'. See 'Working with Matplotlib on OSX' in the Matplotlib FAQ for more information.

解决办法：
import matplotlib as mpl
mpl.use('TkAgg')
import matplotlib.pyplot as plt
在import matplotlib as mpl之后进阶着跟一句mpl.use('TkAgg')即可将绘图窗口调到最前面。但是这句代码必须紧跟mpl且不能放在plt之后；

refer：
[Mac系统下Python-Matplotlib问题及解决方法汇总](https://www.jianshu.com/p/9632b0cb0b47)

 










