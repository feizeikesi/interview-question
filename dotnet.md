# .Net面试题

- [.Net面试题](#net%E9%9D%A2%E8%AF%95%E9%A2%98)
  - [问题](#%E9%97%AE%E9%A2%98)
    - [什么是ASP.NET](#%E4%BB%80%E4%B9%88%E6%98%AFaspnet)
    - [ASP.NET和C#有什么区别](#aspnet%E5%92%8Cc%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [ASP Net有哪些优点](#asp-net%E6%9C%89%E5%93%AA%E4%BA%9B%E4%BC%98%E7%82%B9)
    - [什么是MVC框架](#%E4%BB%80%E4%B9%88%E6%98%AFmvc%E6%A1%86%E6%9E%B6)
    - [ASP.NET WebFrom和MVC有什么区别](#aspnet-webfrom%E5%92%8Cmvc%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [什么是CLR](#%E4%BB%80%E4%B9%88%E6%98%AFclr)
    - [什么是CSS以及它用于什么](#%E4%BB%80%E4%B9%88%E6%98%AFcss%E4%BB%A5%E5%8F%8A%E5%AE%83%E7%94%A8%E4%BA%8E%E4%BB%80%E4%B9%88)
    - [什么是STA](#%E4%BB%80%E4%B9%88%E6%98%AFsta)
    - [什么是MTA](#%E4%BB%80%E4%B9%88%E6%98%AFmta)
    - [asp和ASP.NET中使用的线程模型是什么](#asp%E5%92%8Caspnet%E4%B8%AD%E4%BD%BF%E7%94%A8%E7%9A%84%E7%BA%BF%E7%A8%8B%E6%A8%A1%E5%9E%8B%E6%98%AF%E4%BB%80%E4%B9%88)
    - [页面生命周期事件是什么](#%E9%A1%B5%E9%9D%A2%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E4%BA%8B%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88)
    - [Union和Union all有什么区别](#union%E5%92%8Cunion-all%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [ASP.NET中的会话是什么](#aspnet%E4%B8%AD%E7%9A%84%E4%BC%9A%E8%AF%9D%E6%98%AF%E4%BB%80%E4%B9%88)
    - [ASP.NET中的应用程序和会话是什么](#aspnet%E4%B8%AD%E7%9A%84%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E5%92%8C%E4%BC%9A%E8%AF%9D%E6%98%AF%E4%BB%80%E4%B9%88)
    - [ASP.NET中的会话类型是什么](#aspnet%E4%B8%AD%E7%9A%84%E4%BC%9A%E8%AF%9D%E7%B1%BB%E5%9E%8B%E6%98%AF%E4%BB%80%E4%B9%88)
    - [ASP.NET中session和viewstate有什么区别](#aspnet%E4%B8%ADsession%E5%92%8Cviewstate%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [如何在ASP.NET中存储和维护会话](#%E5%A6%82%E4%BD%95%E5%9C%A8aspnet%E4%B8%AD%E5%AD%98%E5%82%A8%E5%92%8C%E7%BB%B4%E6%8A%A4%E4%BC%9A%E8%AF%9D)
    - [`Session.Abandon()`和`Clear()`有什么区别](#sessionabandon%E5%92%8Cclear%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [存储过程与函数有什么区别](#%E5%AD%98%E5%82%A8%E8%BF%87%E7%A8%8B%E4%B8%8E%E5%87%BD%E6%95%B0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [将数据从一个页面发送到另一个页面的方法有哪些](#%E5%B0%86%E6%95%B0%E6%8D%AE%E4%BB%8E%E4%B8%80%E4%B8%AA%E9%A1%B5%E9%9D%A2%E5%8F%91%E9%80%81%E5%88%B0%E5%8F%A6%E4%B8%80%E4%B8%AA%E9%A1%B5%E9%9D%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B)
    - [`sealed`类与`static`类有什么区别](#sealed%E7%B1%BB%E4%B8%8Estatic%E7%B1%BB%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [抽象类与接口有什么区别](#%E6%8A%BD%E8%B1%A1%E7%B1%BB%E4%B8%8E%E6%8E%A5%E5%8F%A3%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [Web API和Web services有什么区别](#web-api%E5%92%8Cweb-services%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [REST和SOAP有什么区别](#rest%E5%92%8Csoap%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [进程和线程有什么区别](#%E8%BF%9B%E7%A8%8B%E5%92%8C%E7%BA%BF%E7%A8%8B%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [ASP.NET中的装箱和拆箱是什么](#aspnet%E4%B8%AD%E7%9A%84%E8%A3%85%E7%AE%B1%E5%92%8C%E6%8B%86%E7%AE%B1%E6%98%AF%E4%BB%80%E4%B9%88)
    - [C＃中`equals()`和`==`有什么区别](#c%EF%BC%83%E4%B8%ADequals%E5%92%8C%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [什么是反射](#%E4%BB%80%E4%B9%88%E6%98%AF%E5%8F%8D%E5%B0%84)
    - [`typeof()`与`GetType()`有什么区别](#typeof%E4%B8%8Egettype%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
    - [什么是XSS](#%E4%BB%80%E4%B9%88%E6%98%AFxss)
    - [什么是 .NET Core](#%E4%BB%80%E4%B9%88%E6%98%AF-net-core)
    - [.NET Core 与现有的 .NET Framework有何不同](#net-core-%E4%B8%8E%E7%8E%B0%E6%9C%89%E7%9A%84-net-framework%E6%9C%89%E4%BD%95%E4%B8%8D%E5%90%8C)
    - [什么是 **.NET Platform Standards**](#%E4%BB%80%E4%B9%88%E6%98%AF-net-platform-standards)
    - [什么是 ASP .NET Core](#%E4%BB%80%E4%B9%88%E6%98%AF-asp-net-core)
    - [ASP.NET Core 中新引入的功能有哪些](#aspnet-core-%E4%B8%AD%E6%96%B0%E5%BC%95%E5%85%A5%E7%9A%84%E5%8A%9F%E8%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B)
    - [什么是ASP.NET核心中间件以及它与HttpModule有何不同](#%E4%BB%80%E4%B9%88%E6%98%AFaspnet%E6%A0%B8%E5%BF%83%E4%B8%AD%E9%97%B4%E4%BB%B6%E4%BB%A5%E5%8F%8A%E5%AE%83%E4%B8%8Ehttpmodule%E6%9C%89%E4%BD%95%E4%B8%8D%E5%90%8C)
    - [ASP.NET Core中的各种JSON文件是什么](#aspnet-core%E4%B8%AD%E7%9A%84%E5%90%84%E7%A7%8Djson%E6%96%87%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88)
    - [ASP.NET Core中的Startup.cs文件是什么](#aspnet-core%E4%B8%AD%E7%9A%84startupcs%E6%96%87%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88)
    - [什么是Kestral](#%E4%BB%80%E4%B9%88%E6%98%AFkestral)
    - [什么是WebListener](#%E4%BB%80%E4%B9%88%E6%98%AFweblistener)
    - [什么是ASP.NET核心模块（ANCM）](#%E4%BB%80%E4%B9%88%E6%98%AFaspnet%E6%A0%B8%E5%BF%83%E6%A8%A1%E5%9D%97ancm)
    - [app.Use与app.Run有什么区别](#appuse%E4%B8%8Eapprun%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)

## 问题

### 什么是ASP.NET

ASP.NET是一个Web开发平台,它提供了编程模型,全面的软件基础架构以及构建基于Web的应用程序所需的各种服务.它于2002年1月首次发布 .NET Framework 1.0版.Active Server Pages（ASP）技术.ASP.NET基于公共语言运行时（CLR）构建,允许程序员使用任何支持的.NET语言编写ASP.NET代码.

### ASP.NET和C#有什么区别

C＃是为.NET框架设计的CLS编程语言.ASP.NET是.NET框架的一部分,允许您使用任何符合CLS的语言（如C＃,VB.NET,F＃等）编写Web应用程序.

### ASP Net有哪些优点

- 内置Windows身份验证和每个应用程序配置可确保您的应用程序安全.
- ASP.NET减少了开发大型应用程序所需的代码行.
- ASP代码和HTML平滑地相互混合以生成动态网页.
- 这是一种理想的服务器端脚本技术,这就是为什么代码在Windows服务器上运行之前在Web浏览器上显示的原因.
- DotNET框架与语言无关,因此请选择最适合发应用程序的编程语言.
- 由于内置配置信息,ASP.NET易于部署.
- Windows Web服务器精确监视网页,各种组件和在其上运行的应用程序.
- 它立即发出任何内存泄漏,无限循环和其他非法行为的警报.它会立即杀死这些行为并自动重启.
- ASP.Net功能,如早期绑定,JIT编译,缓存服务和本机优化支持,以获得高水平的性能.
- 所有应用程序都经过精心监控和管理,以帮助应用程序持续可用于处理请求.

### 什么是MVC框架

__Model-View-Controller(MVC)__ 架构模式将应用程序分为三个主要组件：模型(Model),视图(View)和控制器(Controller).ASP.NET MVC框架提供了用于创建Web应用程序的ASP.NET Web窗体模式的替代方法.

### ASP.NET WebFrom和MVC有什么区别

- WebFrom
  - 定义
    - ASP.NET Webform提供了一个类似于Winform的事件响应GUI模型（event-drivenGUI）,隐藏了HTTP、HTML、 JavaScript等细节,将用户界面构建成一个服务器端的树结构控件（Control）,每个控件通过ViewState保持自己的状态,并自动把客户端的js事件和服务器端的事件联系起来.这种做法使得开发WinForm和Webform程序具有相近的开发体验,填平WinForm开发（有状态、面向对象的）和Webform开发（无状态、面向HTML的）之间的鸿沟.
  - MVP（Model-View-Presenter,模型-视图-表示器）模式
  - 优点
    - 有大量的服务器控件支持,比如：GridView、Repeater等控件可以方便的进行数据绑定,从而减少的大量代码的编写.
    - 学习成本低,由于微软封装的比较深,造成深入学习的难度加大.
    - 基于事件驱动编程,如：click事件等,aspx和cs文件分离,即显示逻辑和处理逻辑分离.
    - 支持视图状态,每个控件以“隐藏域”的形式存在当前表单页面未达到“有状态”,即ViewState.
  - 缺点
    - 由于使用的ViewState会增加页面的负担,造成性能不是很高.
    - 代码重用性不高,缺少对并行开发的支持.
    - 因为采用code-behind 代码后植技术,使aspx页面与cs紧密耦合度太高.
    - 对Seo不友好,因为URL指定具体的aspx页面.
    - 因为紧密耦合度太高、使用大量的事件处理函数,不利于单元测试.
- MVC
  - 定义
    - 一种 低耦合、可测试的web应用程序框架
  - MVC 模式
  - 优点
    - 架构降低了程序间的耦合性.
    - 不支持ViewState,页面更加干净,可以提升程序的性能.
    - 支持并行开发,可扩展性好,继承了ASP.NET的特性,表单验证、缓存、会话等.
    - 由于程序耦合度低,可以比较顺利的进行单元测试.
    - 通过修改路由规则,可以控制生成自定义的url,因此控制生成seo友好的url将更加容易.
    - 强类型view实现,更安全,更高效.
  - 缺点
    - 需要有一定的html、css、js、jquery前端技术,也就增加了一些学习的成本

### 什么是CLR

公共语言运行时（CLR）是Microsoft .NET框架的虚拟机组件,用于管理.NET程序的执行.称为即时编译的过程将编译后的代码转换为计算机CPU然后执行的机器指令.

### 什么是CSS以及它用于什么

CSS是描述网页呈现的语言,包括颜色,布局和字体.它允许人们将演示文稿适应不同类型的设备,例如大屏幕,小屏幕或打印机.CSS独立于HTML,可以与任何基于XML的标记语言一起使用.

### 什么是STA

单线程单元(Single Threaded Apartment),创建STA线程单元拥有它自己的线程.在任何一单元之内都只能有一个线程.在STA线程模式中,对线程的所有调用都放到一个队列中

### 什么是MTA

多线程单元(Multi Threaded Apartment),只有一个单元将在那里,所有线程将在该单一单元内执行.可以同时运行多个线程,并使用所有可用的共享数据

### asp和ASP.NET中使用的线程模型是什么

ASP使用的STA线程模型和ASP.NET使用MTA线程模型

### 页面生命周期事件是什么

Page_PreInit->Page_Init->Page_InitComplete->Page_PreLoad->Page_Load->Page_LoadComplete->Page_PreRender->Render

### Union和Union all有什么区别

Union和Union all的区别在于Union all不会消除重复的行,而只是从所有适合查询细节的表中提取所有行并将它们组合成一个表.UNION语句有效地对结果集执行SELECT DISTINCT.

### ASP.NET中的会话是什么

ASP.NET会话状态使您能够在用户在Web应用程序中导航ASP.NET页面时存储和检索用户的值.HTTP是无状态协议.这意味着Web服务器将页面的每个HTTP请求视为独立请求

### ASP.NET中的应用程序和会话是什么

Application和Session对象可用于存储对特定用户（会话）或所有用户（应用程序）全局的值

### ASP.NET中的会话类型是什么

- InProc
- StateServer
- SQLServer
- Custom

### ASP.NET中session和viewstate有什么区别

SessionState持久保存服务器中特定用户的数据.此数据可用,直到用户关闭浏览器或会话时间完成.视图状态主要在回发期间有效,信息仅存储在客户端中.Viewstate仅对可序列化数据有效.

### 如何在ASP.NET中存储和维护会话

当用户第一次请求Web应用程序时,服务器会创建一个sessionID并将其存储在客户端浏览器的cookie中.此会话ID在所有后续请求中发送到服务器

### `Session.Abandon()`和`Clear()`有什么区别

`Clear`从session的state集合中删除所有键和值, `Abandon`删除session 存储的所有对象

### 存储过程与函数有什么区别

函数必须返回一个值,但在存储过程中它是可选的.函数只能有输入参数,而存储过程可以有输入/输出参数.可以从存储过程调用函数,但不能从函数调用存储过程.

### 将数据从一个页面发送到另一个页面的方法有哪些

- `Response. Redirect()`
- `Server.Transfer()`
- `WebClient.DownloadFile()`

### `sealed`类与`static`类有什么区别

密封类不能被继承.静态类只能有静态成员（例如静态方法,属性和变量）.静态类限制用户调用类的默认构造函数.静态类只能有静态构造函数来初始化静态成员.

### 抽象类与接口有什么区别

实现接口的类必须提供该接口所有方法的实现.抽象类可以包含状态（数据成员）和 实现（方法）.抽象类可以在不实现抽象方法的情况下继承（尽管这样的派生类本身是抽象的）.接口可以继承多个,抽象类只能继承一个

### Web API和Web services有什么区别

Web services基于SOAP协议.Web API是一个较新的Microsoft框架,可帮助您构建基于REST的界面.响应可以是JSON或XML,但是无法自动生成客户端,因为Web Api不提供Web服务中的WSDL之类的服务描述.

### REST和SOAP有什么区别

Web服务有两种：简单对象访问协议（SOAP）和Representational State Transfer（REST）.SOAP定义了基于XML的消息交换的标准通信协议（规则集）规范.SOAP使用不同的传输协议,例如HTTP和SMTP.

### 进程和线程有什么区别

线程用于小任务,而进程用于更多“重量级”任务.基本上是应用程序的执行.线程和进程之间的另一个区别是同一进程中的线程共享相同的地址空间,而不同的进程则不共享

### ASP.NET中的装箱和拆箱是什么

装箱是将值类型转换为类型对象或由此值类型实现的任何接口类型的过程.当CLR选中一个值类型时,它将值包装在System.Object中并将其存储在托管堆上.拆箱从对象中提取值类型.

### C＃中`equals()`和`==`有什么区别

`==`如果比较的是值类型,则比较两个对象的值；如果比较的是引用类型,则比较两个对象的引用地址是否相同
`equals()`是Object里的虚方法,默认用`==`进行比较,但是大部分微软的类,及用户定义的类,都重写了该虚方法,也就是微软和用户各自为自己编写的Object的子类定义了相等比较规则

### 什么是反射

通过反射我们可以动态创建类型的实例,将类型绑定到现有对象,或从现有对象获取类型并调用其方法或访问其字段和属性.我们还可以使用反射访问属性信息.

### `typeof()`与`GetType()`有什么区别

`typeof()`是一个C＃关键字,当您拥有该类的名称时使用.它在编译时计算,因此不能在运行时创建的实例上使用. `GetType()`是可以在实例上使用的对象类的方法.

### 什么是XSS

 跨站点脚本(XSS)是指客户端代码注入攻击,其中攻击者可以将恶意脚本（通常也称为恶意负载）执行到合法网站或Web应用程序中.

### 什么是 .NET Core

.NET Core是.NET的新版本,它是跨平台的,支持Windows,MacOS和Linux,可用于设备,云和嵌入式/物联网场景.

- 优点:
  - 灵活部署：可以包含在您的应用程序中,也可以安装在并行用户或机器范围内.
  - 跨平台：在Windows,MacOS和Linux上运行; 可以移植到其他操作系统.受支持的操作系统（OS）,CPU和应用程序方案将随着时间的推移而增长,由Microsoft,其他公司和个人提供.
  - 命令行工具：可以在命令行中执行所有产品方案.
  - 兼容：.NET Core通过 .NET标准库与 .NET Framework,Xamarin和Mono兼容.

### .NET Core 与现有的 .NET Framework有何不同

基本上可以认为 **.NET Core*- 是 **.NET Framework*- 的子集,因为 **.NET Core*- 包含 **.NET Framework*- 的核心功能,包括运行时和框架库.例如,**.NET Core*- 和 **.NET Framework*- 共享GC中,JIT和类型,如String和.List
 **.NET Core*- 的创建使.NET可以是开源的,跨平台的,并且可以在更加资源受限的环境中使用.

### 什么是 **.NET Platform Standards**

**.NET Platform Standards*- 身并不是一个平台.它是实现平台的标准.

### 什么是 ASP .NET Core

ASP.NET Core 1.0是ASP.NET的下一个版本.它是开源和跨平台框​​架（支持Windows,Mac和Linux）,适用于构建基于云的互联网连接应用程序,如Web应用程序,物联网应用程序和移动应用程序.ASP.NET Core应用程序可以在.NET Core或完整的.NET Framework上运行.

### ASP.NET Core 中新引入的功能有哪些

- 1.0
  - ASP.NET Core是开源和跨平台的
  - ASP.NET Core使用两个运行时环境（.NET Core和.NET Framework）..NET核心适用于所有平台（windows,linux和OSx）,其中.NET框架适用于Windows
  - .NET Platform Standard是使用PCL解决实际二进制可移植性的新方法
  - ASP.NET Core适用于文件系统,允许更快的开发周期.它检测代码更改（甚至在visual studio之外）,编译到内存中并加载应用程序.
  - ASP.NET Core内置了对依赖注入的支持.ASP.NET Core包含一个简单的内置容器（由`IServiceProvider`接口表示）,默认支持构造函数注入,ASP.NET通过DI提供某些服务
  - ASP.NET Core也支持云,因为它支持基于环境的配置.在launchSetting.json文件中阅读有关基于环境的配置的更多信息.
  - ASP.NET Core使用全新的轻量级和模块化HTTP请求管道.
  - `HTTPHandler` 和 `HTTPModules`被 `Middleware` 替代了
  - 移除了 **System.web*- DLL
  - 对于配置设置,JSON优先于XML
  - `web.config`替换`appsettings.json`,`global.asax`替换`Startup.cs`,`Startup.cs`是应用程序本身的入口点
  - 新的`Project.json`文件是项目的核心.它定义依赖项,使用的运行时,以及定义构建和发布设置.它将项目定义为DNX项目
  - `wwwroot`项目中的目录用于静态内容,如css,Js,images.它是您服务器的默认根.如果磁盘上的静态文件有请求,如果该文件位于此文件夹中,则它可以返回到客户端.可以从`project.json`文件更改名称
- 2.0
  - ASP.NET Core应用程序也可以通过dotnet cli创建

     ``` shell
     # 1.0
     dotnet new web #创建项目
     dotnet restore #恢复项目依赖包
     # 2.0
     dotnet new web #创建项目并恢复项目依赖包
     ```

  - ASP.NET Core 2.0应用程序现在引用单个元包,Microsoft.AspNetCore.All以包含产品版本的所有ASP.NET Core包
  - ASP.NET Core 2.0引入了一种构建Web主机配置的新方法.此新方法使用`WebHost.CreateDefaultBuilder()`API 设置Web主机配置的默认值

     Program.cs (ASP.NET Core 1.1)

     ``` C#
     public class Program
     {
        public static void Main(string[] args)
        {
            var host = new WebHostBuilder()
                .UseKestrel()
                .UseContentRoot(Directory.GetCurrentDirectory())
                .UseIISIntegration()
                .UseStartup<Startup>()
                .Build();

            host.Run();
        }
     }
     ```

     Program.cs (ASP.NET Core 2.0)

     ``` C#
     public class Program
     {
        public static void Main(string[] args)
        {
            BuildWebHost(args).Run();
        }

        public static IWebHost BuildWebHost(string[] args) =>
            WebHost.CreateDefaultBuilder(args)
                .UseStartup<Startup>()
                .Build();
      }
     ```

  - `Startup.cs`不再写`Log`和构建配置相关代码.而是放到`Program.cs` 的`CreateDefaultBuilder`中

    Startup.cs (ASP.NET Core 1.1)

     ``` C#
     public class Startup
      {
          public Startup(IHostingEnvironment env)
          {
              var builder = new ConfigurationBuilder()
                  .SetBasePath(env.ContentRootPath)
                  .AddJsonFile("appsettings.json", optional: false, reloadOnChange: true)
                  .AddJsonFile($"appsettings.{env.EnvironmentName}.json", optional: true)
                  .AddEnvironmentVariables();
              Configuration = builder.Build();
          }

          public IConfigurationRoot Configuration { get; }

          // This method gets called by the runtime. Use this method to add services to the container.
          public void ConfigureServices(IServiceCollection services)
          {
              // Add framework services.
              services.AddMvc();
          }

          // This method gets called by the runtime. Use this method to configure the HTTP request pipeline.
          public void Configure(IApplicationBuilder app, IHostingEnvironment env, ILoggerFactory loggerFactory)
          {
              loggerFactory.AddConsole(Configuration.GetSection("Logging"));
              loggerFactory.AddDebug();

              app.UseMvc();
          }
      }
     ```

     Startup.cs (ASP.NET Core 2.0)

     ``` C#
     public class Startup
      {
          public Startup(IConfiguration configuration)
          {
              Configuration = configuration;
          }

          public IConfiguration Configuration { get; }

          // This method gets called by the runtime. Use this method to add services to the container.
          public void ConfigureServices(IServiceCollection services)
          {
              services.AddMvc();
          }

          // This method gets called by the runtime. Use this method to configure the HTTP request pipeline.
          public void Configure(IApplicationBuilder app, IHostingEnvironment env, ILoggerFactory loggerFactory)
          {
              app.UseMvc();
          }
      }
      ```

  - ASP.NET Core 2.0引入了 **Razor Pages**. **Razor Pages**是简单的页面或视图,没有与之关联的控制器.Razor页面包含在`Microsoft.AspNetCore.Mvc`包中.他们处理约定,需要放在`Pages`文件夹中,扩展名为`.cshtml`
  - 身份验证已经过2.0的一些重大变化.所有Auth中间件现在都是服务,现在只需要一个身份验证中间件`app.UseAuthentication()`

      .NET Core 1.1中启用cookie身份验证

      ``` C#
      public void Configure(IApplicationBuilder app, IHostingEnvironment env, ILoggerFactory loggerFactory)
        {
            app.UseCookieAuthentication(new CookieAuthenticationOptions()
            {
                AuthenticationScheme = "MyCookieMiddlewareInstance",
                LoginPath = new PathString("/Account/Unauthorized/"),
                AccessDeniedPath = new PathString("/Account/Forbidden/"),
                AutomaticAuthenticate = true,
                AutomaticChallenge = true
            });
            app.UseMvc();
        }
      ```

      .NET Core 2.0中启用cookie身份验证

      ``` C#
      public void ConfigureServices(IServiceCollection services)
      {
          services.AddCookieAuthentication(o => o.LoginPath = "/api/login");
      }

      public void Configure(IApplicationBuilder app)
      {
          app.UseAuthentication();
          app.UseMvc();
      }
      ```

      | ASP.NET Core 1.1                     | ASP.NET Core 2.0                          |
      | ------------------------------------ | ----------------------------------------- |
      | `app.UseOpenIdConnectAuthentication` | `services.AddOpenIdConnectAuthentication` |
      | `app.UseJwtBearerAuthentication`     | `services.AddJwtBearerAuthentication`     |
      | `app.UseFacebookAuthentication`      | `services.AddFacebookAuthentication`      |

### 什么是ASP.NET核心中间件以及它与HttpModule有何不同

| HttpModule                                                              | Middleware                                                                                                                      |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `HttpModules`通过`web.config`或`global.asax`配置                        | `Middleware`是通过代码而不是`web.config`配置的.ASP.NET Core 1.0具有`Startup.cs`文件（应用程序的入口点）,其中添加了`Middleware`. |
| 无法控制其执行顺序.由于`HttpModules`的顺序主要基于应用程序生命周期事件. | 与`HttpModules`不同,您可以完全控制执行的内容和顺序.因为它们按照**添加顺序**执行.                                                |
| 请求和响应的执行顺序保持不变.                                           | 响应的中间件顺序与请求的顺序相反.                                                                                               |
| `HttpModules`可以帮助您附加特定于应用程序事件的代码.                    | `Middleware`独立于这些事件.                                                                                                     |
| `HttpModules`与之相关`System.web`.                                      | `Middleware`独立于主机.                                                                                                         |

### ASP.NET Core中的各种JSON文件是什么

### ASP.NET Core中的Startup.cs文件是什么

在ASP.NET中,`Global.asax`（尽管是可选的）充当应用程序的入口点.`Startup.cs`,它是应用程序本身的入口点.`Startup`类配置处理对应用程序发出的所有请求的请求管道.

### 什么是Kestral

Kestrel是一个基于libuv的ASP.NET Core的跨平台Web服务器,libuv是一个跨平台的异步I / O库.Kestrel是默认包含在ASP.NET Core新项目模板中的Web服务器.如果您的应用程序仅接受来自内部网络的请求,您可以单独使用Kestrel.

如果将应用程序公开到Internet,则必须使用IIS,Nginx或Apache作为反向代理服务器.反向代理服务器接收来自Internet的HTTP请求,并在进行一些初步处理后将它们转发给Kestrel.使用反向代理进行边缘部署（暴露于来自Internet的流量）的最重要原因是安全性.Kestrel相对较新,尚未完全抵御攻击

### 什么是WebListener

ASP.NET Core提供了两个服务器实现Kestral和WebListener.WebListener也是ASP.NET Core的Web服务器,仅在Windows上运行.它建立在Http.Sys内核模式驱动程序之上.WebListener是Kestrel的替代品,可用于直接连接到Internet,而无需依赖IIS作为反向代理服务器.

### 什么是ASP.NET核心模块（ANCM）

ASP.NET核心模块（ANCM）允许您在IIS后面运行ASP.NET核心应用程序,它只适用于Kestrel; 它与WebListener不兼容.ANCM是一个本机IIS模块,它挂接到IIS管道并将流量重定向到后端ASP.NET Core应用程序.ASP.NET Core应用程序在与IIS工作进程分开的进程中运行,ANCM也进行进程管理.当第一个请求进入时,ANCM启动ASP.NET Core应用程序的进程,并在崩溃时重新启动它.简而言之,它位于IIS中,并将对ASP.NET Core应用程序的请求路由到Kestral.

### app.Use与app.Run有什么区别

`app.Use`可能会调用管道中的下一个中间件组件,`app.Run`永远不会调用后续的中间件

``` C#
public void Configure(IApplicationBuilder app, IHostingEnvironment env, ILoggerFactory loggerFactory)
{
    app.Use(async (context, next) =>
    {
        await context.Response.WriteAsync("<html><body>");
        await context.Response.WriteAsync("<div>Inside middleware defined using app.Use</div>");
        await next();
        await context.Response.WriteAsync("</body></html>");
    });

    app.Run(async context => {
       await context.Response.WriteAsync("<div>Inside middleware defined using app.Run</div>"); 
    });

    app.Use(async (context, next) =>
    {
        await context.Response.WriteAsync("<html><body>");
        await context.Response.WriteAsync("<div>Another Middleware defined using app.Use</div>");
        await next();
        await context.Response.WriteAsync("</body></html>");
    });
    app.UseIISPlatformHandler(options => options.AuthenticationDescriptions.Clear());
    app.UseStaticFiles();
    app.UseIdentity();
    app.UseMvc(routes =>
    {
        routes.MapRoute(
            name: "default",
            template: "{controller=Home}/{action=Index}/{id?}");
    });
}
```

![Alt text](/images/app.Use-vs-app.Run-in-ASP.NET-Core-middleware.png)