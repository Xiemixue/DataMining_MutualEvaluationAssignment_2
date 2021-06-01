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

## Trending YouTube Video Statistics [(download)](https://www.kaggle.com/datasnaek/youtube-new)

* Description: 

    该数据集包含有关YouTube每日热门视频的数月（且在不断增加）的数据。包含美国，GB，DE，CA和FR地区（分别为美国，英国，德国，加拿大和法国）的数据，每天最多列出200个趋势视频。
    
    YouTube会在平台上不断更新热门视频的列表。 为了确定本年度最热门的视频，YouTube使用了多种因素，包括衡量用户的互动情况(观看次数，分享次数，评论和喜欢的次数)。
    
    数据集包括video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count属性。

* Contents:
    ```
    CA_category_id.json
    CAvideos.csv 
    DE_category_id.json
    DEvideos.csv 
    FR_category_id.json 
    FRvideos.csv
    GB_category_id.json
    GBvideos.csv
    IN_category_id.json
    INvideos.csv 
    JP_category_id.json
    JPvideos.csv 
    KR_category_id.json
    KRvideos.csv 
    MX_category_id.json
    MXvideos.csv 
    RU_category_id.json
    RUvideos.csv 
    US_category_id.json
    USvideos.csv
    ```

# 使用说明
下载数据集并上传至main.ipynb文件所在目录，然后使用jupyter notebook 打开main.ipynb文件，运行指定cell，即可得到相应可视化结果。
