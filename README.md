# 大学基础物理实验报告

这是南开大学2023年春季学期《大学基础物理实验》的课程报告集合，同时作为本人的LaTeX练习。

## 第三周 《伸长法测量金属丝杨氏模量》

> 本文的模板来自于[知乎：用LaTeX完成物化实验报告](https://zhuanlan.zhihu.com/p/31311327)和[CSDN:中大近代物理实验实验报告（LaTeX实现）](https://blog.csdn.net/m0_49180353/article/details/122735113)

### 封面

​		封面用到的图片来自于网络，清晰度一般，而且尺寸是自己裁的[笑哭]。封面的制作参考了[知乎：用LaTeX完成物化实验报告](https://zhuanlan.zhihu.com/p/31311327)。

​		至于下方的信息表格

```latex
	\begin{table}[h] 
		\centering	
		\begin{Large} 
			\begin{tabular}{p{3cm} p{5cm}<{\centering}}
				姓\qquad 名: & xxx \\
				\hline
				学\qquad 院: & xxx \\
				\hline
				学\qquad 号: & xxxxxxx \\
				\hline
				分\qquad 组: & xxx \\
				\hline
				实验时间: & 2023.3.3\\
				\hline
				指导教师: & xxx\\
				\hline
			\end{tabular}
		\end{Large}
	\end{table}
```

​		这里 **p{5cm}<{\centering}**一开始死活编译不出来，后来查阅了资料才发现原来需要在前面加上array宏包[笑哭]。

### 图片

​		本实验报告中的B款杨氏模量测量仪原理图是使用geogebra画出来的，源文件我也放在了figure文件夹内，值得注意的是，我电脑上的geogebra就是不能导出图片，最后还是截图+自己裁剪才然后用figure环境添加进去的。

​		另外geogebra也可以导出Tikz代码，但由于Tikz宏包本人了解有限，而且这篇报告中截图的效果也还不错(画质)，所以暂且不表，等以后有时间了再好好学习一下。

### 表格

​		本实验报告中所用到的表格均使用[在线生成LaTeX表格]([Create LaTeX tables online – TablesGenerator.com](https://www.tablesgenerator.com/))生成，流程是

1. 在excel中，完成表格的数据标题和合并
2. 直接复制表格，在网站的file->paste table data中粘贴
3. 调整样式
4. generate,复制到Texstudio中
5. 添加标题和样式，设置table环境(table后面的[h]选型老是忘记加！)

### 公式

​	本次实验报告的公式全部手打，下次试试Axmath编辑。

## 第四周 《碰撞》
**重大失误**完成拓展实验后figure文件夹丢失，这下变成永远的半成品了。
