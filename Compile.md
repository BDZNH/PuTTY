# 使用MinGW编译
这里我使用了MinGW-W64，你可以前往[https://sourceforge.net/projects/mingw-w64/](https://sourceforge.net/projects/mingw-w64/)下载你想要的版本，这里我使用了[Gcc-7.3.0](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/7.3.0/threads-posix/seh/)
下载后解压，将目录内的*bin*添加到系统环境变量，然后使用命令提示符切换到putty源码内的*windows*文件夹内，使用命令

```bash
mingw32-make -f Makefile.mgw
```

来编译，编译成功后，可执行程序将会出现在*windows*目录内

# 使用Visual Studio编译
操作如上，按目录替换文件之后，双击vs2017目录内的*putty.sln*，生成解决方案。