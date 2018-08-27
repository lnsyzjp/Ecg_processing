# Ecg_processing
ecg stuff, methods to denoise signals , detect features and classify heart disease.
1.Preprocess
数据预处理部分，心电波形的滤波，数据质量评估，数据归一化等。
2.Measure
心搏参数的测量，如：QRS波群的起点、终点、形态，主峰位置。T波的形态、起始点、峰值点。P波的位置、起始点等信息。
3.Calculate
根据测量好的参数信息计算出正常心电图报告应当给出的参数：如QRS时限，QTC，PR间期，QT间期，心电轴等
4.Classify
将12导联心电图进行单心拍的节律分类，判断出单个心搏的节律：窦性，房性，室性等。
5.Diagnose
根据前面获取的所有信息，判断出具体的疾病。
6.Logic
将所有的疾病根据逻辑关系进行筛除，得到最终的诊断报告。
