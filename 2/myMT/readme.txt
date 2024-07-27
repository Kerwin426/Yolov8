一、把classes.txt复制到labels文件夹中（如果里面没有的话）
二、打开anaconda promopt
三、分别输入下列命令行：
	1:   
	activate label
	请自行将label跟换为自己电脑的labelimg环境名
	2：
	cd /d D:\python_zy\yolo8 (2)\_mycode\myMT
	请改成自己的路径
	labelImg  ./images  ./classes.txt
四、为了避免标签保存路径出错，打开labelImg界面后，点击Change Save Dir,选择标签保存的路径（我以前出过错）