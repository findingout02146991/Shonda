
实验步骤：
1、打开终端，根据文件夹路径，进入到文件夹目录下，本例为home文件夹下的os_1文件夹，即：cd /home/os_1
	
2、输入./compile.sh,对源程序进行编译，即：运行gcc -run.c -o run.o
3、输入./run.sh +参数，运行程序，传参时用'$@'进行传参，即：chmod 777 compile.sh或ch。