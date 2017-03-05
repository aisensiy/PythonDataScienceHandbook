# Python 数据科学手册

这里包含了 [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do) 的中文译本，当然也遵循了其采用 Jupyter notbook 的形式。在翻译的过程中，译者自感水平有限，为避免误导读者，在中文译文下保留了英文原文，中文内容仅仅辅助加速阅读速度。翻译过程中在尽量遵循原著的文笔的前提下，采用了意译。每翻译完成一个章节都会将下面的目录更改成标题，当然有些标题实在是不适合翻译为中文，就保留了英文的形式。

![cover image](notebooks/figures/PDSH-cover.png)

本书编写和测试的环境是 Python 3.5，作者提及在 Python 2.7 这样的环境运行也问题不大，作为译者我就在 Python 2.7 对此进行了检查并对一些不适用于 Python 2.7 的代码做了更改（当然，都有明确的批注）。

本书详细的介绍了目前在 Python 中进行数据分析、数据处理、机器学习相关的几个重要的库的使用，其中包含：[IPython](http://ipython.org)，[NumPy](http://numpy.org)，[Pandas](http://pandas.pydata.org)，[Matplotlib](http://matplotlib.org)， [Scikit-Learn](http://scikit-learn.org)以及其他相关库。阅读本书的前提是对 Python 语言有一定的了解，如果你需要语言的大概的介绍，可以去看[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython)：它是一本面向研究人员和科学家的 Python 入门书籍。

以下的目录指向 [nbviewer](http://nbviewer.jupyter.org)：

---
## [Table of Contents](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/Index.ipynb)

### [序言](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/00.00-Preface.ipynb)

### [1. IPython: Beyond Normal Python](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.00-IPython-Beyond-Normal-Python.ipynb)
- [在 IPython 中使用帮助与文档](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.01-Help-And-Documentation.ipynb)
- [IPython 中的快捷键](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.02-Shell-Keyboard-Shortcuts.ipynb)
- [IPython 中的魔法命令](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.03-Magic-Commands.ipynb)
- [输入输出历史](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.04-Input-Output-History.ipynb)
- [在 IPython 中使用 shell 命令](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.05-IPython-And-Shell-Commands.ipynb)
- [错误与调试](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.06-Errors-and-Debugging.ipynb)
- [性能分析](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.07-Timing-and-Profiling.ipynb)
- [更多 IPython 资源](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/01.08-More-IPython-Resources.ipynb)

### [2. Introduction to NumPy](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.00-Introduction-to-NumPy.ipynb)
- [理解 Python 的数据类型](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.01-Understanding-Data-Types.ipynb)
- [NumPy 数组基础](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.02-The-Basics-Of-NumPy-Arrays.ipynb)
- [NumPy 数组的计算方式：Universal Functions](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.03-Computation-on-arrays-ufuncs.ipynb)
- [聚合：最大值，最小值以及其他](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.04-Computation-on-arrays-aggregates.ipynb)
- [矩阵计算：广播](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.05-Computation-on-arrays-broadcasting.ipynb)
- [比较、掩码、布尔运算](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.06-Boolean-Arrays-and-Masks.ipynb)
- [Fancy Indexing](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.07-Fancy-Indexing.ipynb)
- [Sorting Arrays](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.08-Sorting.ipynb)
- [Structured Data: NumPy's Structured Arrays](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/02.09-Structured-Data-NumPy.ipynb)

### [3. Data Manipulation with Pandas](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.00-Introduction-to-Pandas.ipynb)
- [Introducing Pandas Objects](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.01-Introducing-Pandas-Objects.ipynb)
- [Data Indexing and Selection](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.02-Data-Indexing-and-Selection.ipynb)
- [Operating on Data in Pandas](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.03-Operations-in-Pandas.ipynb)
- [Handling Missing Data](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.04-Missing-Values.ipynb)
- [Hierarchical Indexing](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.05-Hierarchical-Indexing.ipynb)
- [Combining Datasets: Concat and Append](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.06-Concat-And-Append.ipynb)
- [Combining Datasets: Merge and Join](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.07-Merge-and-Join.ipynb)
- [Aggregation and Grouping](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.08-Aggregation-and-Grouping.ipynb)
- [Pivot Tables](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.09-Pivot-Tables.ipynb)
- [Vectorized String Operations](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.10-Working-With-Strings.ipynb)
- [Working with Time Series](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.11-Working-with-Time-Series.ipynb)
- [High-Performance Pandas: eval() and query()](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.12-Performance-Eval-and-Query.ipynb)
- [Further Resources](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/03.13-Further-Resources.ipynb)

### [4. Visualization with Matplotlib](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.00-Introduction-To-Matplotlib.ipynb)
- [Simple Line Plots](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.01-Simple-Line-Plots.ipynb)
- [Simple Scatter Plots](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.02-Simple-Scatter-Plots.ipynb)
- [Visualizing Errors](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.03-Errorbars.ipynb)
- [Density and Contour Plots](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.04-Density-and-Contour-Plots.ipynb)
- [Histograms, Binnings, and Density](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.05-Histograms-and-Binnings.ipynb)
- [Customizing Plot Legends](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.06-Customizing-Legends.ipynb)
- [Customizing Colorbars](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.07-Customizing-Colorbars.ipynb)
- [Multiple Subplots](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.08-Multiple-Subplots.ipynb)
- [Text and Annotation](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.09-Text-and-Annotation.ipynb)
- [Customizing Ticks](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.10-Customizing-Ticks.ipynb)
- [Customizing Matplotlib: Configurations and Stylesheets](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.11-Settings-and-Stylesheets.ipynb)
- [Three-Dimensional Plotting in Matplotlib](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.12-Three-Dimensional-Plotting.ipynb)
- [Geographic Data with Basemap](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.13-Geographic-Data-With-Basemap.ipynb)
- [Visualization with Seaborn](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.14-Visualization-With-Seaborn.ipynb)
- [Further Resources](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/04.15-Further-Resources.ipynb)

### [5. Machine Learning](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.00-Machine-Learning.ipynb)
- [What Is Machine Learning?](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.01-What-Is-Machine-Learning.ipynb)
- [Introducing Scikit-Learn](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.02-Introducing-Scikit-Learn.ipynb)
- [Hyperparameters and Model Validation](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.03-Hyperparameters-and-Model-Validation.ipynb)
- [Feature Engineering](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.04-Feature-Engineering.ipynb)
- [In-Depth: Naive Bayes Classification](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.05-Naive-Bayes.ipynb)
- [In-Depth: Linear Regression](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.06-Linear-Regression.ipynb)
- [In-Depth: Support Vector Machines](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.07-Support-Vector-Machines.ipynb)
- [In-Depth: Decision Trees and Random Forests](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.08-Random-Forests.ipynb)
- [In-Depth: Principal Component Analysis](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.09-Principal-Component-Analysis.ipynb)
- [In-Depth: Manifold Learning](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.10-Manifold-Learning.ipynb)
- [In-Depth: k-Means Clustering](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.11-K-Means.ipynb)
- [In-Depth: Gaussian Mixture Models](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.12-Gaussian-Mixtures.ipynb)
- [In-Depth: Kernel Density Estimation](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.13-Kernel-Density-Estimation.ipynb)
- [Application: A Face Detection Pipeline](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.14-Image-Features.ipynb)
- [Further Machine Learning Resources](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/05.15-Learning-More.ipynb)

### [Appendix: Figure Code](http://nbviewer.jupyter.org/github/aisensiy/PythonDataScienceHandbook-CN/blob/master/notebooks/06.00-Figure-Code.ipynb)

---

## Required Packages

The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.


## License

### Code
The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text
The text content of the book is released under the [CC-BY-NC-ND license](LICENSE-TEXT). Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).
