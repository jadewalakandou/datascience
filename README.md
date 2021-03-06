# 《数据科学Python编程基础》

2018课程


## 课程描述（Course Description）

本课程注重编程训练、数学建模、可计算思维。本课程致力于介绍python编程和数据科学基础知识。

- 时间：周三 第5-6节 逸夫楼C-405 1-17周
- 教师：王成军

[王成军](http://chengjun.github.io)，南京大学新闻传播学院副教授，奥美数据科学实验室主任，南京大学计算传播学实验中心副主任。

## 课程内容



| 序号          |  日期         |    时间   |内容        | 课时数量   |
| -------------|:-------------:|:-------------:|:-------------:|-----:|
| 1 | 9月5日 | 14:00-16:00 | 引言：[数据科学简介](/1.intro/01.intro2datasci.ipynb)/[课程简介](/1.intro/03.python_intro.ipynb)| 2学时
| 2 | 9月12日 | 14:00-16:00 | Python基础: [Introduction](/2.tour/00-Introduction.ipynb)、[How to Run Python Code](/2.tour/01-How-to-Run-Python-Code.ipynb)、[Basic Python Syntax](/2.tour/02-Basic-Python-Syntax.ipynb)| 2学时|
| 3 | 9月19日 | 14:00-16:00 |  Python基础: [ Variables](/2.tour/03-Semantics-Variables.ipynb) & [Operators](/2.tour/04-Semantics-Operators.ipynb) |2学时|
| 4 | 9月26日 | 14:00-16:00 | Python基础: [Built-In Scalar Types](/2.tour/05-Built-in-Scalar-Types.ipynb) & [Data Structures](/2.tour/06-Built-in-Data-Structures.ipynb) | 2学时|
| 5 | 10月3日 | 14:00-16:00 | <del>**国庆节放假**(不补课)</del> | 0学时|
| 6 | 10月10日| 14:00-16:00 | Python基础: [Control Flow Statements](/2.tour/07-Control-Flow-Statements.ipynb)、[Defining Functions](/2.tour/08-Defining-Functions.ipynb)、[Errors and Exceptions](/2.tour/09-Errors-and-Exceptions.ipynb)| 2学时|
| 7 | 10月17日 | 14:00-16:00 | Python基础: [Iterators](/2.tour/10-Iterators.ipynb) & [List Comprehensions](/2.tour/11-List-Comprehensions.ipynb)| 2学时|
| 8 | 10月24日 | 14:00-16:00 | Python基础: [Generators and Generator Expressions](/2.tour/12-Generators.ipynb)、[Modules and Packages](/2.tour/13-Modules-and-Packages.ipynb)、[Strings and Regular Expressions](/2.tour/14-Strings-and-Regular-Expressions.ipynb)| 2学时|
| 9 | 10月31日 | 14:00-16:00 | 统计基础：[描述数据](/3.scratch/code-python3/5.statistics.ipynb)、[概率](data-science-from-scratch/code-python3/6.probability.ipynb) | 2学时|
| 10 | 11月7日 |  14:00-16:00  | 统计基础：[假设检验](/3.scratch/code-python3/7.hypothesis_inference.ipynb)、[梯度递减](/3.scratch/code-python3/8.gradient_descent.ipynb) |2学时|
| 11 | 11月14日 | 14:00-16:00 | 统计基础：[回归分析](/3.scratch/code-python3/14.regression.ipynb)| 2学时
| 12 | 11月21日 | 14:00-16:00 | 数据科学: [Introduction to NumPy](/4.datasci/notebooks/02.00-Introduction-to-NumPy.ipynb)| 2学时|
| 13| 11月28日 | 14:00-16:00 |  数据科学:[Data Manipulation with Pandas](/4.datasci/notebooks/03.00-Introduction-to-Pandas.ipynb) | 2学时|
| 14 | 12月5日 | 14:00-16:00 | 数据科学: [Visualization with Matplotlib](/4.datasci/notebooks/04.00-Introduction-To-Matplotlib.ipynb)、[Seaborn](/4.datasci/notebooks/04.14-Visualization-With-Seaborn.ipynb) | 2学时|
| 15 | 12月12日| 14:00-16:00 |数据科学:[Machine Learning](/4.datasci/notebooks/05.00-Machine-Learning.ipynb)| 2学时|
| 16 | 12月19日 | 14:00-16:00 | 数据科学:[Machine Learning](/4.datasci/notebooks/05.00-Machine-Learning.ipynb)| 2学时|
| 17 | 12月26日 | 14:00-16:00 | 数据科学:[Machine Learning](/4.datasci/notebooks/05.00-Machine-Learning.ipynb)| 2学时|


## Mybinder
Mybinder.org turns a GitHub repo into a collection of interactive notebooks. Have a repository full of Jupyter notebooks? With Binder, open those notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere.

https://hub.mybinder.org/user/computational-c-datascience2018-x6d61dtj/tree

## 研究项目 Final Project

本课程鼓励采用公开的竞赛数据作为研究项目。现有数据竞赛平台很多，包括:
- [Kaggle](https://www.kaggle.com/)
- [DataFoundation](https://www.datafoundation.org/)
- [阿里云天池大赛](https://tianchi.aliyun.com/)
- [DC竞赛](http://www.dcjingsai.com/static_page/cmpList.html)
- [BienData](https://www.biendata.com/)
- [Kesci](https://www.kesci.com/home/dataset)

**课程研究项目**的基本要求：
1. 必选项目来自以下四个推荐题目。
  - 使用Jupyter Notebook进行数据分析并提交Jupyter notebook，注明姓名和学号。
  - Jupyter Notebook应该采用Markdown的形式提供充足的文字描述，对代码和分析结果进行解读。
  - 建议包括以下部分：
    - 项目简介：包括项目题目、主要的想法等
    - 数据读入和清洗：使用pandas读取数据，提取和构造需要的变量
    - 描述性分析：描述Y、X的单个变量分布、均值、标准差、
    - 统计分析
      - 建立研究假设
      - 采用T检验、方差分析、相关分析、回归分析对变量间的关系进行分析
    - 机器学习
      - 使用sklearn
      - 将数据分割成为train和test两部分，采用train data训练模型，采用test data进行模型评价
        - 回归任务，报告：R2指标
        - 分类任务，报告accuracy、precision、recall、f1、roc_auc_score
      - 采用cross validation的方法，对整个train data进行分析，并进行模型评价
      - **使用多种不同的算法**
    - 数据可视化：采用可视化辅助进行描述性分析、统计分析、机器学习
    - 总结：对整个研究项目的发现进行总结。
2. 任选项目
  - 属于额外加分项，不做强制要求
  - 也可以从四个当中再选一个，或者自己选择其他题目
3. Deadline:
  - 2019年2月4日（农历大年夜）；
  - 每晚交一天，减少20%分数，晚交两天不及格；
  - 请确保提交的文件可以打开；


#### 推荐题目：
1. 房价预测 https://www.kaggle.com/c/house-prices-advanced-regression-techniques/
2. 预测银行用户是否参与定期存款 http://www.dcjingsai.com/common/cmpt/ANZ%20Chengdu%20Data%20Science%20Competition_%E7%AB%9E%E8%B5%9B%E4%BF%A1%E6%81%AF.html?lang=en_US
3. 游戏玩家的付费预测 http://www.dcjingsai.com/common/cmpt/%E6%B8%B8%E6%88%8F%E7%8E%A9%E5%AE%B6%E4%BB%98%E8%B4%B9%E9%87%91%E9%A2%9D%E9%A2%84%E6%B5%8B%E5%A4%A7%E8%B5%9B_%E7%AB%9E%E8%B5%9B%E4%BF%A1%E6%81%AF.html
4. 预测假新闻 https://www.kaggle.com/c/fake-news

### 曾使用过的题目

1. 分析《权力的游戏》中的核心人物及其演变

**A Network analysis of Game of Thrones**: Analyze the network of characters in Game of Thrones and how it changes over the course of the books. https://www.datacamp.com/projects/76

Get the [Data](https://github.com/computational-class/asoiaf)

* Winter is Coming. Let's load the dataset ASAP
* Time for some Network of Thrones
* Populate the network with the DataFrame
* Finding the most important character in Game of Thrones
* Evolution of importance of characters over the books
* What's up with Stannis Baratheon?
* What does the Google PageRank algorithm tell us about Game of Thrones?
* Correlation between different measures
* Conclusion

2. Kaggle比赛数据分析 《众包模式下的数据科学编程比赛》

* https://www.kaggle.com/kaggle/meta-kaggle/data
* https://www.kaggle.com/canggih/voted-kaggle-dataset

3. IMDB电影数据 《让电影成功的元素：基于IMDB数据的分析》

* https://www.kaggle.com/tmdb/tmdb-movie-metadata
* https://www.kaggle.com/PromptCloudHQ/imdb-data/data

## 案例分析

- Wikileaks Afghanistan Data Analysis and Visualization https://github.com/chengjun/WikileaksAfghanistanDataAnalysis
- Olympic Data Analysis https://github.com/data-journalism/olympic


## 推荐教材（Recommended Textbooks）

- **Whirlwind Tour Of Python** https://jakevdp.github.io/WhirlwindTourOfPython/
- **Data Science from Scratch** https://github.com/joelgrus/data-science-from-scratch
- **Python Data Science Handbook** https://jakevdp.github.io/PythonDataScienceHandbook/

## 参考书
- **Python for Data Analysis** by Wes McKinney, published by O'Reilly Media https://github.com/data-science-lab/pydata-book
- **Introduction to Machine Learning with Python: A Guide for Data Scientist** https://github.com/amueller/introduction_to_ml_with_python.
- **Machine Learning in Action** https://github.com/pbharrin/machinelearninginaction & https://github.com/RedstoneWill/MachineLearningInAction-Camp & https://github.com/TingNie/Machine-learning-in-action
- 周志华《机器学习》,北京:清华大学出版社,2016. (ISBN 978-7-302-42328-7)
- Easley, David and [Jon Kleinberg](http://www.cs.cornell.edu/home/kleinber/). 2011.[Networks, Crowds, and Markets: Reasoning About a Highly Connected World](http://www.cs.cornell.edu/home/kleinber/networks-book/). New York: Cambridge University. 大卫・伊斯利, & 乔恩・克莱因伯格. (2011). [网络、群体与市场](https://www.baidu.com/s?wd=%E7%BD%91%E7%BB%9C%E3%80%81%E7%BE%A4%E4%BD%93%E4%B8%8E%E5%B8%82%E5%9C%BA):揭示高度互联世界的行为原理与效应机制. 清华大学出版社.
- Jure Leskovec, Anand Rajaraman, Jeffrey David Ullman.2011. Mining massive datasets (2nd)http://www.mmds.org/


## 相关课程

- 复旦大学新媒体硕士项目《计算新闻传播学》课程  https://github.com/computational-class/cjc
- 南京大学《数据新闻》2017课程 https://github.com/data-journalism/dj2017
- 用Python玩转数据_南京大学_中国大学MOOC(慕课) http://www.icourse163.org/course/nju-1001571005
- Advanced Machine Learning with scikit-learn, Andreas Müller http://bit.ly/advanced_machine_learning_scikit-learn & https://github.com/computational-class/PythonMachineLearning & **https://www.bilibili.com/video/av23775865**
