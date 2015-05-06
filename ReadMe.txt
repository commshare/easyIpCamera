1. fork from https://github.com/mtdxc/easyIpCamera
出现错误：error PRJ0019: 某个工具从以下位置返回了错误代码: "Assembly d:\liveUSBCamera\x264\common\x86\x86inc.asm"	libH264Encoder

解决办法：将yasm-1.1.0-win32.exe重命名为yasm.exe，放到VS的IDE目录中，以VS2008为例，放在目录：C:\Program Files\Microsoft Visual Studio 9.0\Common7\IDE

2. 20150506 compile ok on win7_64 with vs2013
