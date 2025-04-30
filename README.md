该项目主要有两个任务：第一个为判断是否患有心脏病的二分类任务，第二个为判断具体患有哪种心脏病的四分类任务。具体而言各板块的内容为：

## 一、Code

1. **Extract_bispectrum.ipynb**包含的是二阶谱的代码。
2. **Feature_Engineering.ipynb**包含的是提取二阶谱、MFCC的代码。
3. **Import_Data.ipynb**包含的是从MongoDB数据库中导出二分类任务的数据，四分类任务的数据因有现成的故无需导出。
4. **Make_Database.ipynb**包含的是对多个开源心音数据集进行数据整合的代码(文件夹two_class_data是整合后的结果)。
5. **MyPreprocess.ipynb**包含的是对心音数据进行数据预处理的代码。
6. **Runmodel.ipynb**包含的是建立二分类模型的代码。
7. **Runmodel_four class.ipynb**包含的是建立四分类模型的代码。

## 二、datasets

​	包含的是搜集到的开源心音数据集。

## 三、二分类结果分析：

- CNN模型：
- ![image-20250430214340795](https://github.com/cocatwice/-Heart-Sound-/blob/main/images/image-20250430214340795.png)
- CRNN模型：
- ![image-20250430214440844](https://github.com/cocatwice/-Heart-Sound-/blob/main/images/image-20250430214440844.png)
- CRNN-Transformer模型：
- ![image-20250430214532509](https://github.com/cocatwice/-Heart-Sound-/blob/main/images/image-20250430214532509.png)

## 四、四分类结果分析：

- CNN模型：

- ![image-20250430214747842](https://github.com/cocatwice/-Heart-Sound-/blob/main/images/image-20250430214747842.png)

- MS-SE-Net模型:

  ![image-20250430214812329](https://github.com/cocatwice/-Heart-Sound-/blob/main/images/image-20250430214812329.png)

这是本人大三时的比赛项目，仍存在不少有待完善的地方，但碍于精力有限后续不会进行维护了，代码仅供参考！希望能够有所帮助...
