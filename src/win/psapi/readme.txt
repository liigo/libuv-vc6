复制以下文件即可使用：

psapi.lib复制到vc++6.0的lib目录下（如：C:\Program Files\Microsoft Visual Studio\VC98\Lib）
psapi.h复制到Include目录下（如：C:\Program Files\Microsoft Visual Studio\VC98\Include）
psapi.dll一般在system32目录下会自带，所以可以不做操作

在vc中使用时，需加入以下代码：

#include <psapi.h>
#pragma comment(lib,"psapi.lib")
