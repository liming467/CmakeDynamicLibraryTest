# CmakeDynamicLibraryTest
windows系统下利用cmake生成c++动态库示例

在windows系统下使用cmake命令生成c++动态库，一般情况下不会生成.lib文件，此时需要在添加如下命令：
set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)

根目录下的.bat文件是为了避免重复在cmd中输入并执行cmake命令而用，使用时直接在根目录双击该bat文件即可，作用和cmd命令
mkdir build
cd build
cmake ..
cmake ---build .
一毛一样~
