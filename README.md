C#  EditPlus环境设置

设定语法加亮文件

Tools|Preferences|Settings & Syntax|Add

描述填csharp, 文件扩展名cs;aspx

选择语法加亮文件 csharp.stx



配置编译工具

Tools | Config User Tools | Add

MenuText填：Compile C#(编译C#)

Command选：D:\WINDOWS\Microsoft.NET\Framework\v2.0.50727\csc.exe

Argument填：/unsafe $(FileName)

InitDir填：$(FileDir)

打勾：Capture Output



配置运行工具

Tools | Config User Tools | Add

MenuText填：Run C#(运行C#)

Command填：cmd /c

Argument填：$(FileNameNoExt).exe

InitDir填：$(FileDir)

不打勾：Capture Output
