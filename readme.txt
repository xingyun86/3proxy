1.拷贝目录
	dependencies\openssl_static\openssl_release\include
	dependencies\openssl_static\openssl_release\lib
到VisualStudio2015的VC目录：
	C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC
中
2.在3proxy-devel目录执行命令行
  3proxy-devel>C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\vcvarsall.bat
  3proxy-devel>nmake /f Makefile.msvc
  