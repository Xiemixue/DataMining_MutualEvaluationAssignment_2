# 互评作业2: 频繁模式与关联规则挖掘
 
# 作业要求
1. 问题描述：

   本次作业中，将选择1个数据集进行频繁模式和关联规则挖掘。

2. 数据集

    可选数据集包括：
    ```
    Consumer & Visitor Insights For Neighborhoods

    Wine Reviews

    Oakland Crime Statistics 2011 to 2016

    Chicago Building Violations

    Trending YouTube Video Statistics

    Melbourne Airbnb Open Data

    MLB Pitch Data 2015-2018
    ```

3. 数据分析要求

    3.1 数据可视化和摘要

    * 数据摘要：

      标称属性，给出每个可能聚会的频数

      数值属性，给出5数概括及缺失值的个数

    * 数据可视化：

      使用直方图、盒图等检查数据分布及离群点

    3.2 数据缺失的处理

        对数据集进行处理，转换成适合进行关联规则挖掘的形式；
        找出频繁模式；
        导出关联规则，计算其支持度和置信度;
        对规则进行评价，可使用Lift、卡方和其它教材中提及的指标, 至少2种；
        对挖掘结果进行分析；
        可视化展示。
4. 提交内容

    * 对数据集进行处理的代码
    * 关联规则挖掘的代码
    * 挖掘过程的报告：展示挖掘的过程、结果和你的分析
    * 所选择的数据集在README中说明，数据文件不要上传到Github中

# 选择的数据集介绍

## Wine Reviews [(download)](https://www.kaggle.com/zynicide/wine-reviews)

* Description: 

    130k wine reviews with variety, location, winery, price, and description.

* Contents:
    ```
    winemag-data-130k-v2.csv: contains 10 columns and 130k rows of wine reviews.

    winemag-data_first150k.csv: contains 10 columns and 150k rows of wine reviews.

    winemag-data-130k-v2.json: contains 6919 nodes of wine reviews.
    ```

## Oakland Crime Statistics 2011 to 2016 [(download)](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016?select=records-for-2012.csv)

* Description: 

    This is a dataset hosted by the city of Oakland in California. The organization has an open data platform found here and they update their information according to the amount of data that is brought in. Explore Oakland's Data using Kaggle and all of the data sources available through the city of Oakland organization page!

* Contents:
    ```
    records-for-2011.csv
    records-for-2012.csv
    records-for-2013.csv
    records-for-2014.csv
    records-for-2015.csv
    records-for-2016.csv
    ```

# 使用说明
下载数据集并上传至main.ipynb文件所在目录，然后使用jupyter notebook 打开main.ipynb文件，运行指定cell，即可得到相应可视化结果。
