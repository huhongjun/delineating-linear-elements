## 项目说明
 python，博士论文，提取植被边界线条
 
## 开发环境
	conda环境 lidar
	conda create -n chrislucas python==2.7.12 NumPy==1.11.2 SciPy==0.18.1 pandas==0.18.1 scikit-learn==0.17.1 Shapely==1.5.13
	Python (2.7.12) with the 
    NumPy (1.11.2),
	SciPy (0.18.1), 
	pandas (0.18.1), 
	scikit-learn (0.17.1)
	Shapely (1.5.13)

	LASTools (version 160429)  点云文件转换
	Cloud-Compare (v2.8) 可视化与下采样点云

	硬件：Intel Xeon E3-1220 3.1GHz 8核处理器，16GB内存
## 文件与目录 
	/Code
		par_pipeline	准备数据:计算近邻参数与删除不相关点
		clf_pipeline	分类点云：提取特征，平衡随机森林分类低植被和树木
		lin_pipeline	提取线条:提取线条、边界生成shape文件
## 工作记录
	code下三个pipeline文件是主程序入口,针对这三个做notebook
	python中调用外部工具做文件操作和下采样
	有完整的论文资料，pdf全部阅读并加目录

## 参考资料
Delineating linear vegetation elements in agricultural landscapes using LiDAR point clouds

[介绍文章](https://spatialeconomics.nl/en/a-new-method-for-measuring-vegetation-lidar-data/)