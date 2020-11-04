mac 执行c#程序

https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial/create

1. 安装 .NET SDK

2. 创建项目
     dotnet new console -o myApp

3. 创建.cs 文件，并编写代码
     using System;
     namespace myApp
    { 
      class Program 
       { 
           static void Main(string[] args) 
            { 
              Console.WriteLine("Hello World!"); 
            }
         }
    }

4.  运行
    dotnet run
