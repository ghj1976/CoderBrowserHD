# CoderBrowserHD
simple code reader for android


修改自 <https://github.com/zerob13/CoderBrowserHD> 的版本。

主要完成下面几个修改：

1、支持 go 代码的阅读；

2、默认启动时选择目录调整成我习惯的目录： 
大家用这个代码时，请修改这里成自己习惯的。 
修改的是 FileChoser.java 文件的这里：

	//private File mCurrentDirectory = Environment.getExternalStorageDirectory();
	private File mCurrentDirectory = new File("/storage/emulated/0/myCodes");

被注释的是之前的。