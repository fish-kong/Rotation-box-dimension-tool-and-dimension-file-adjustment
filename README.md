# Rotation-box-dimension-tool-and-dimension-file-adjustment
Rotation box dimension tool and dimension file adjustment
1.cwhaxml转4坐标txt.py 可将labelimg2/rolabelimg标注的[cx cy w h angle]xml文件转换为[class x0 y0 x1 y1 x2 y2 x3 y3]的txt文件

2.4坐标txt转4坐标xml.py 可将[class x0 y0 x1 y1 x2 y2 x3 y3]的txt文件转换为4个坐标点的xml文件

3.4坐标xml转cwhaXML.py 可将4个坐标点的xml文件重新转换为[cx cy w h angle]的xml文件
 
4 labelimg2标注的angle的值得范围：顺时针旋转 0-2π（即12点方向为0, 3点方向为pi/2 ,6点方向为π9点方向为3π/2）
