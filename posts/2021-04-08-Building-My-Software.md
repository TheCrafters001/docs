---
layout: post
title: Build Requirements for Most of My Software
excerpt: Learn about the build requirements here.
author: TheCrafters001
---
Building my software is quite easy, but it does have some requirements in order to get them built. Most of the time, you will need the following:

 * [Visual Studio 2017 Community or Higher](http://visualstudio.com/download)
   * .NET desktop development Workload
 * [.NET Framework 4.8 or Higher](https://dotnet.microsoft.com/download/dotnet-framework)

As of recently, I used to use [Inno Setup](https://jrsoftware.org/isinfo.php) for installers, and sometimes I still do, but now I use [WiX Toolset](https://wixtoolset.org/) to build my installers.
In my newer projects, WiX Toolset is required.
