# ML project procedure

## Importing the necessary libraries and overview the datasets

    - Importing the dataset

    - View the first and last 5 rows of the dataset

    - Understand the shape of the dataset (how many rows and how many columns)

    - Check the data types of the columns for the dataset

    - Check the missing values in the dataset
    
## Exploratory data analysis (EDA) 变量的分布，不同变量之间存在的分布，异常数据（缺失or异常），如何处理它们已准备数据集以构建预测模型

    - Check the statistical summary of dataset
    
    - check the count of each unique category in each of the categorical variables

    - 缺失值处理：通过平均值、中位数、和使用KNN等方法估算出缺失值

       - 估算完缺失值后需要再次检查training set和testing set来判断是否存在缺失值
    
- Univariate analysis 单变量分析：通过一次获取一个变量来分析数据集

    - Plot 需要决定绘制哪些图表以更好的理解数据，比如什么图表对分析分类变量有意义，什么图表适合数值变量
    
- Bivariate analysis 双变量分析：变量如何相互关联，x和y是否存在很强的关系

    - 是否存在多重共线性（即x和x之间是否关联）

    - Plot，比如line chart或者heat map
    
- Data preprocessing

    - Feacture engineering 特征工程: 从现有的变量中提取有用值，创建一个新的变量
    
    - Outlier check
    
    - Data preparation for modeling

        - create dummy variables for categorical variables

        - separating the independent variables x and dependent variables y

        - 缩放数据

        - 将数据分成70%的训练集和30%的测试集
    
    - Check for multicollinearity
    
## Building models （逻辑回归+KNN）

    - model performance on the test and train data
    
    - create the model 1
    
    - get the model 1 summary 
    
    - checking model 1 performance
    
- Drop insignificant variables 
    
    - Create the model 2
    
    - Get the model summary 
    
    - Checking model 2 performance

## Feature selection

       - Removing multicollinearity 检测多重共线性：衡量VIF；检测p值

       - 删除不重要的变量
    
## Checking for the assumptions and rebuilding the model

   - checking the linear regression assumptions
    
        - mean of residuals should be zero 残差的平均值应该为0
        
        - no heteroscedasticity 无异方差
        
        - linearity of variables 变量的线性
        
        - normality of error terms 误差项的正态性

## Evaluation metrics 评估指标

    - R-squared

    - Mean squared error

    - Root mean squared error

    - Apply cross validation to improve the model and evaluate it using different evaluation metrics

    - 使用KNN的时候记得用GridSearchCV对模型进行超参数调优


## Prediction on the test dataset

## Conclustion and recommendations
    
    
    
    
    
    
    
    
    
    
    
    
    
