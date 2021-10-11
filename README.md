# lego-minidolls-visualization
# 乐高minidolls系列可视化
网址：https://rpubs.com/arobotdog/lego_minidoll
### 概述：
使用R对乐高的迷你娃娃系列数据进行解析，可视化，挖掘其中的“大众脸”脸部部件、系列产品最多的角色、和肤色分布规律
library包括：tidyverse， tidyr，ggplot2，dplyr，waffle
常用方法包括：subset（）、merge（）、ggplot（）、gsub（）

### 困难：
角色名有很多不同的后缀，导致难以计算整个数据库中角色出现的数量

### 措施：
使用gsub（）将角色名区分开，只留下名

### 成果：
通过多种可视化手段呈现肤色分布规律，如lollipop图，柱状图，waffle图，派图，分析发现waffle图的效果最好；
可视化成果详见https://rpubs.com/arobotdog/lego_minidoll


