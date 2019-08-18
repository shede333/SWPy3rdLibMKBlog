  




## Django
无需多说，最强大的PythonWeb框架；  
官网: <https://www.djangoproject.com/>

## Flask
也无需多说，和Django并驾齐驱，Python最成熟的两个Web开发框架；  
官网: <http://flask.pocoo.org/>  
源码: <https://github.com/pallets/flask>  

## CherryPy
A Minimalist Python Web Framework;  
CherryPy 允许开发者以他们构建其他面向对象Python程序近乎同样的方式来开发web应用。这使得可以在更短的时间内开发出更精简的源代码。CherryPy允许你进行很多常规的Python编程，但是它并没有整合一个模板系统，你需要自己去找一个。（它支持大多数的模板）  
CherrPy 能够很好适应默认的Python功能和结构，它在使用更少的代码创建web应用  
官网：<http://www.cherrypy.org/>    
源码：<https://github.com/cherrypy/cherrypy>  

## Tornado
Tornado是一个Python web框架，而且是一个异步网络库，最初是为 FriendFeed开发的。通过使用非阻塞I/O，Tornado可以处理数以万计打开的链接，这使它成为长轮询、WebSocket和其他需要为用户提供长连接的应用的理想选择。  
Thomas Allen写了一个简单的教程，关于Tornado是如何工作的以及如何创建一个简单的静态页面。    
源码：<https://github.com/tornadoweb/tornado>  
官网：<http://www.tornadoweb.org/en/stable/>  

## twisted
Twisted是用Python实现的基于事件驱动的网络引擎框架。Twisted诞生于2000年初，在当时的网络游戏开发者看来，无论他们使用哪种语言，手中都鲜有可兼顾扩展性及跨平台的网络库。Twisted的作者试图在当时现有的环境下开发游戏，这一步走的非常艰难，他们迫切地需要一个可扩展性高、基于事件驱动、跨平台的网络开发框架，为此他们决定自己实现一个，并从那些之前的游戏和网络应用程序的开发者中学习，汲取他们的经验教训。  
Twisted支持许多常见的传输及应用层协议，包括TCP、UDP、SSL/TLS、HTTP、IMAP、SSH、IRC以及FTP。就像Python一样，Twisted也具有“内置电池”（batteries-included）的特点。Twisted对于其支持的所有协议都带有客户端和服务器实现，同时附带有基于命令行的工具，使得配置和部署产品级的Twisted应用变得非常方便。  
官网: <https://twistedmatrix.com/trac/>

## Pyramid
一个附带开放源代码的python框架，可用于创建任意的web应用程序。这个框架最有优势的地方是，它包含了一些Python/Perl/Ruby独有的特性．这个开源框架拥有不依赖平台的MVC架构，和最快的启动开发的能力   
官网: <https://trypyramid.com/>

## Wheezy Web
一个轻量级、高性能、高并发的WSGI web框架，具备创建现代，高效网络应用的关键功能。这里有一篇来自Andriy Kornatskyy，关于Wheezy的介绍   
源码：<https://bitbucket.org/akorn/wheezy.web/src>  
文档: <http://pythonhosted.org/wheezy.web/>

## web2py
简单功能强大，零限制

## web.py
web.py是一个Python 的web框架，既简单，有强大。web.py处于公有域内，你可以处于任何目的去使用它，没有限制。你可以看Lucas’s Kauffman博客上的指导文章以及关于它和Django的比较（好吧，我认为我们不能管这叫做比较）。  
官网：<http://webpy.org/>

## ObjectWeb
简单、快速，不依赖第三方库，主要用来匹配CGI和WSGI标准，带有嵌入式web开发服务器基础。  
源码：<https://github.com/aisola/ObjectWeb>

## Klein Python
也属于微型框架平台，可开发生产就绪的应用程序和web服务。Klein是使用韦尔实验组件，比如Werkzeug和Twisted。  
源码：<https://github.com/twisted/klein>    
<http://klein.readthedocs.io/en/latest/>

## Pecan
创造Pecan是为了填补Python web框架世界的一个空缺——一个提供object-dispatch方式路由的超轻量级的框架。Pecan的目标并不是要成为一个“全栈”框架，因此没有支持一些额外的功能，比如session或是数据库 。相反，Pecan专注于HTTP本身。  
主要目的是为用户提供一个轻量级框架，这个Python框架并不是完整的堆栈框架，因此，不要期望 Pecan能为远程连接信息和数据库组件提供永久支持， Pecan更侧重于HTTP框架。  
源码：<https://github.com/pecan/pecan>

## Morepath
这也是一个Python WSGI 微型框架，Morepath的特性是模型驱动REST式，其灵活性和敏捷性使得Morepath深受码农喜爱。  
源码：<https://github.com/morepath/morepath>    
文档: <http://morepath.readthedocs.io/en/latest/>  

## TurboGear 
是建立在其他框架基础上的框架，它把其他框架优秀的部分集成到一起．由于每个框架都有一些部分做得不好，TurboGear试图解决这个问题．它允许你从一个单文件服务开始，逐步扩展为一个全栈服务．

## Japronto:
是为你的需求量身打造的全新微服务框架。其主要目标就是快，可拓展并且轻量。通过 asyncio 使得同时同步和异步编程变成可能。而且 Japronto 出人意料的快，甚至快过 NodeJS 和 Go。

## Sanic
是一个与 Flask 类似，基于 uvloop 的 web 框架，它能让 Python 更快速。基于 Python 3.5 设计的，它允许开发者在 async/await 语法上建立定义异步函数。在 Sanic 之前，Python 没有办法做到如此之快。uvloop 服务作为一个极其快速的库，顺其自然地替代了异步默认事件的循环。  
Sanic 使得开发者能够在 Python 中编写异步应用，在这种方式下非常类似于 Node.js。但是通过 Sanic 作者的基准测试，uvloop 在处理超过每秒33k次请求时，依然表现良好，这超过了 Node.js 的性能。由于 Sanic 还很新，因此在不久的将来会有更多的改进和变更。你也可以到它的 开源库中 做出贡献。  
源码：<https://github.com/howie6879/Sanic-For-Pythoneer>  

## Quixote
历史悠久，豆瓣使用的就是此框架  
源码：<https://github.com/nascheme/quixote>

## Cyclone
Cyclone 是一个Python的web服务框架，它基于Twisted protocol实现了Tornado API 。我将把对这个框架的介绍，交给7co.的Gleicon，请看他的文章。  
源码：<https://github.com/fiorix/cyclone>

##AIOHTTP
aiohttp  
Asynchronous HTTP Client/Server for asyncio and Python.  
asyncio可以实现单线程并发IO操作。如果仅用在客户端，发挥的威力不大。如果把asyncio用在服务器端，例如Web服务器，由于HTTP连接就是IO操作，因此可以用单线程+coroutine实现多用户的高并发支持。
asyncio实现了TCP、UDP、SSL等协议，aiohttp则是基于asyncio实现的HTTP框架。  
源码：<https://github.com/aio-libs/aiohttp/>
文档：<https://docs.aiohttp.org/en/stable/>  


## Vibora
Vibora 是一个 Python 异步网络框架(Python 3.6+)，目前正在开发中，处于 alpha 阶段。  
按作者的说法，Vibora 翻译成中文就是“毒蛇”的意思。  
支持服务端、客户端  
介绍：<https://www.oschina.net/p/vibora>  
源码：<https://github.com/vibora-io/vibora>  
文档：<https://docs.vibora.io/docs>  

## OSROOM
OSROOM 是使用 Python 3(>=3.4) 语言，基于 Flask 微型框架 + MongoDB(>=3.4) + Redis 开发的一个 Web 系统(CMF, Rest Api)。通过 OSROOM，除了可以搭建常见的普通网站外，还可以作为小程序服务端，小程序客户端可直接调用 API 请求数据。  
源码：<https://gitee.com/osroom/osroom>

## API Star
A smart Web API framework, designed for Python 3.    
The Web API toolkit  
官网：<http://docs.apistar.com/>  
源码：<https://github.com/encode/apistar>  


## Falcon
官网：<http://falconframework.org/>  
文档：<https://falcon.readthedocs.io/en/stable/>  

## hug
官网：<http://www.hug.rest/>    
源码：<https://github.com/timothycrosley/hug>  


------
以下框架的代码量很小，适合快速阅读元am，了解其实现原理

## Bottle
Bottle是一个快速、简单、轻量级的WSGI微型Python web框架。它仅包含单一文件模块，并且不依赖除了Python标准库以外的其他库。  
源码量小，适合阅读；(代码4.4k行)  
官网：<http://www.bottlepy.org/docs/dev/index.html>  
源码：<https://github.com/bottlepy/bottle>

## Bobo
Bobo是一个轻量级的框架，用来创建WSGI web应用。它的目标是简单易用，容易记忆。  
Bobo 并不具备模板语言，数据库集成层或是其他一些WSGI中间件或特定应用程序库所提供的功能。Bobo建立在其他框架之上，尤其是WSGI和WebOb。  
源码量小，适合阅读；（代码1.5k行）    
文档：<http://bobo.readthedocs.io/en/latest/>  
源码：<https://github.com/zopefoundation/bobo>

## itty.py
itty.py是一个小实验，是受Sinatra的影响而尝试实现的一个微型框架，它刚好够用，没有额外的东西了。  
当心！如果你是要找一个久经考验的，企业级框架，你就来错地方了。但是它确实很有趣。  
源码量小，适合阅读；（代码1k行）  
源码：<https://github.com/toastdriven/itty>










## 参考

> [python官网的Web Frameworks 介绍 ](https://wiki.python.org/moin/WebFrameworks)