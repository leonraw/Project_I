# Day 5 (周五)

## 上午

1. ### 分析昨天晚上训练的结果

    结果表明，新的lr和model确实带来了loss稳定下降、iou稳定上升的现象，但是由于递减策略过于激进，80epoch之后的loss下降过慢，于是略微减缓了lr的递减。

2. ### 对结果进行可视化分析

    将道路和水系的影像进行预测结果和DLG的对比，并可视化上传到neptune上，点击链接之后，点击页面上的compare标签即可查看结果对比。  
    *注：DLG和预测结果的颜色可能不一致，需自行判断。*

    [道路可视化结果](https://ui.neptune.ai/leonliu/deeplearning/e/DEEP-15/logs)  
    [水系可视化结果](https://ui.neptune.ai/leonliu/deeplearning/e/DEEP-14/logs)

## 下午

1. ### 午睡没醒过来
