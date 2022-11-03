# Research-on-vehicle-travel-behavior-portrait-analysis-relating-to-the-topological-characteristics

# 摘要
基于交通时空大数据的微观出行行为分析可以为精细化、个性化的交通管控措施制定提供支持，车牌识别数据作为一种精度高、准确性高、采样率全的时空大数据，近年来受到广泛关注。但是现有基于车牌识别数据的出行行为分析文献在进行行为分析的过程中较少考虑路网特征，即没有将出行者的行为与路网特性结合起来分析，这导致挖掘得到的出行模式与路网本身的关联不高。本文首先对车牌识别数据和路网拓扑数据进行数据融合，基于此融合数据，根据机动化出行者的出行行为特性使用聚类算法进行车辆画像，将路网上的车辆划分为临时办事车辆、频繁过境车辆、家庭不常用车辆、通勤车辆、网约出租车辆五类车辆。同时，结合复杂网络方法和聚类算法对交叉口进行画像分析，挖掘出交通管理者需要重点关注的交叉口。在此基础上，结合车辆出行行为和路网拓扑信息深入挖掘出行车辆的出行模式，构建车辆画像-交叉口画像-过车频次矩阵、车辆画像-交叉口画像-过车占比矩阵，进而对车辆出行时空特性进行深入挖掘，为交通管控措施的制定提供支持。

# abstract
Travel behavior analysis based on spatiotemporal big data can provide support for the formulation of refined and personalized traffic control measures. License plate recognition data, as a kind of spatiotemporal big data with high precision, high accuracy and full sampling rate, has attracted extensive attentions in recent years. However, existing literatures on travel behavior analysis based on license plate recognition data seldom consider the characteristics of the road network in the process of travel behavior analysis, which leads to low correlation between the mined travel patterns and the road network. This paper first fuses the license plate recognition data and the road network topology data. Based on the fusion data, a clustering algorithm is used to classify vehicles according to the travel behavior characteristics of motorized vehicles. And vehicles on the road network are divided into five categories, including vehicles for temporary business trips, vehicles that passing the area, rarely used vehicles for families, commuting vehicles, and taxis. At the same time, we classify intersections on the road network based on complex network method and clustering algorithm, and the intersections that traffic managers need to focus on have been successfully mined. On this basis, the travel pattern of travel vehicles is further explored based on the vehicle travel behavior and road network topology information. The passing frequency matrix and passing frequency ratio matrix are constructed, which supports the formulation of traffic control measures and suggestions.

# structure of code
project  
|--车辆画像分析  
|--|--packages_rely  
|--|--车辆画像分析.html  
|--|--车辆画像分析.ipynb  
|--各类型交叉口各类型车辆的出行需求分析  
|--|--各类型交叉口各类型车辆的出行需求分析.html  
|--|--各类型交叉口各类型车辆的出行需求分析.ipynb  
|--交叉口画像分析  
|--|--基于拓扑和实际重要性分析的交叉口画像分析  
|--|--|--基于拓扑和实际重要性分析的交叉口画像分析.html  
|--|--|--基于拓扑和实际重要性分析的交叉口画像分析.ipynb  
|--|--基于拓扑以及车辆画像结果的交叉口画像分析  
|--|--|--基于拓扑以及车辆画像结果的交叉口画像分析.html  
|--|--|--基于拓扑以及车辆画像结果的交叉口画像分析.ipynb  
|--|--结点实际重要性分析  
|--|--|--结点实际重要性分析.html  
|--|--|--结点实际重要性分析.ipynb  
|--|--拓扑重要性分析  
|--|--|--packages_rely  
|--|--|--文章  
|--|--|--拓扑重要性分析.html  
|--|--|--拓扑重要性分析.ipynb  
  
# notes about the code
论文大体可以分成三部分：
1. 车辆画像分析  
2. 交叉口画像分析   
3. 结合车辆画像和交叉口画像结果对车辆行为进行分析  
 
第一部分车辆画像分析的代码在“车辆画像分析”文件夹；第二部分交叉口画像分析的代码在“交叉口画像分析”的文件夹中；第三部分结合车辆画像和交叉口画像结果对车辆行为进行分析在“各类型交叉口各类型车辆的出行需求分析”文件夹中。  

# 参考文献
若希望引用代码或文中的方法可以引用下列论文：
姚文彬,戎栋磊,胡佑薇,苏弘扬,陈诺,金盛.关联路网拓扑特性的车辆出行行为画像分析研究[J/OL].交通运输工程与信息学报:1-20[2022-11-03].DOI:10.19961/j.cnki.1672-4747.2022.09.011.

Yao W.,Rong D.,Hu Y., et al.,Research on vehicle travel behavior portrait analysis relating to the topological characteristics of road network. Journal of Transportation Engineering and Information, 2022, doi:https://doi.org/10.19961/j.cnki.1672-4747.2022.09.011.
