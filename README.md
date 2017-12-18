<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>我的一个C语言作业</title>
</head>

<body>
<p><strong><font size="+5"><center>魔方阵</center></font></strong></h1></p><br /><br />
<p><font size="+3">魔方阵的排列规律:</font></p><br />
<p><font size="+3">(1)   将1放在第一行中间一列；</font></p><br />
<p><font size="+3">(2)   从2开始直到n×n止各数依次按下列规则放每一个数存放的行比前一个数的行数减1，列数加1（例如上面的三阶魔方阵，5在4的上一行后一列）；</font></p><br />
<p><font size="+3">(3)   如果上一个数的行数为1，则下一个数的行数为n(指最下一行);例如1在第一行，则2应放在最下一行，列数同样加1；</font></p><br />
<p><font size="+3">(4)   当上一个数的列数为n时，下一个数的列应为1，行数减去1。例如2在第3行最后一列，则3应放在第二行第一列；</font></p><br />
<p><font size="+3">(5)    如果按上面规则确定的位置上已有数，或上一个数是第一行第n列时，则把下一个数放在上一个数的下面。例如按上面的规定，4应该放在第1行第2列，但该位置已经被占据，所以4就放在3的下面。</font></p><br /><br />
<p style="text-indent:20em"><font size="+3">代码如下：</font></p>
<P><center>
  <img src="https://github.com/jidaozuoye/zzq/blob/master/%E4%BB%A3%E7%A0%81/2017-12-18_145907.png" width="771" height="745" />
</center><p><br />
<p style="text-indent:20em"><font size="+3">运行结果如下</font></p>
<P><center><img src="https://github.com/jidaozuoye/zzq/blob/master/%E4%BB%A3%E7%A0%81/2017-12-18_150139.png" width="970" height="540" /></center></P><br /><br />
<p style="text-indent:20em"><font size="+3">该代码需要用 Dev-C++ 中运行：</font></p>
<p><font size="+3"><center>魔方阵代码.cpp  <a href="https://github.com/jidaozuoye/zzq/blob/master/%E4%BB%A3%E7%A0%81/%E9%AD%94%E6%96%B9%E9%98%B5%E4%BB%A3%E7%A0%81.cpp">点击查看</a></center></font></p>
<p><font size="+3"><center>软件Dev-C++  <a href="../网页文件/代码/Dev-Cpp 5.11 TDM-GCC 4.9.2 Setup.exe">点击下载</a>
</center></font></p>
</body>
</html>
