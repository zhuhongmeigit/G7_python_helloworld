# 项目 1: Python入门与基础
## 完成个税计算器

### 安装要求
这个项目要求使用 **Python 2.7** 以及安装下列python库

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
  ​

你还需要安装和运行 [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html#optional-for-experienced-python-developers-installing-jupyter-with-pip)。


推荐安装 [Anaconda](https://www.continuum.io/downloads)，一个包含了项目需要的所有库和软件的 Python 发行版本。[这里](https://classroom.udacity.com/nanodegrees/nd002/parts/0021345403/modules/317671873575460/lessons/5430778793/concepts/54140889150923)介绍了如何安装Anaconda。

如果你使用macOS系统并且对命令行比较熟悉，可以安装[homebrew](http://brew.sh/)，以及brew版python

```bash
$ brew install python
```

再用下列命令安装所需要的python库

```bash
$ pip install numpy pandas matplotlib scikit-learn scipy jupyter
```

### 代码
​
核心代码在 `python_helloworld.ipynb` 文件中，辅助代码在 `titanic_visualizations.py` 文件中。尽管已经提供了一些代码帮助你上手，你还是需要补充些代码使得项目要求的功能能够成功实现。

### 运行
​
在命令行中，确保当前目录为 `G7_python_helloworld/` 文件夹的最顶层（目录包含本 README 文件），运行下列命令：

```bash
$ jupyter notebook python_helloworld.ipynb
```
​
这会启动 Jupyter Notebook 把项目文件打开在你的浏览器中。

对jupyter不熟悉的同学可以看一下这两个链接：

- [Jupyter使用视频教程](http://cn-static.udacity.com/mlnd/how_to_use_jupyter.mp4)
- [为什么使用jupyter？](https://www.zhihu.com/question/37490497)
​
​
​
​
​
​
​
​
​
​
​
​
​
​

### 数据
​
这个项目的数据包含在 `python_helloworld.csv` 文件中。文件包含下列特征：
​
- **name**：名称
- **salary**：税前薪水
- **tax_maybe**：可能的缴税额度

