<div class="github-widget" data-repo="marmelab/awesome-rest"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

有关 RESTful API 架构、开发、测试和性能的重要资源的协作列表. 随时为这个正在进行的列表做出贡献.




## Design

* [建筑风格和
基于网络的软件架构设计](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) - Roy Fielding 定义 REST 的论文
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - 由 Martin Fowler 解释，最初由 Leonard Richardson 在 [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) - 讨论非公共 API 的限制和灵活性，以及​​跨多个团队进行大规模 RESTful 集成的经验教训.
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) - 清楚解释 HATEOAS 是什么，以及为什么要使用它.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](http://www.restapitutorial.com/) - RestApiTutorial.com 致力于跟踪 REST API 最佳实践并提供资源，以便为开发人员提供快速参考和自我教育.
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) - 作为设计原则，Microsoft REST API 指南鼓励应用程序开发人员通过 RESTful HTTP 接口访问资源.
* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) - 关于 REST API 安全的最佳实践
* [Restful API Guidelines by Zalando](https://github.com/zalando/restful-api-guidelines) - 开发 Restful API：一套全面的指南.

## Standards

* [JSON API](http://jsonapi.org/) - 在 JSON 中构建 API 的标准.
* [RAML](http://raml.org/) - 描述 RESTful API 的简单明了的方式.
* [JSend](http://labs.omniti.com/labs/jsend) - 简单的规范，为来自 Web 服务器的 JSON 响应的格式设置了一些规则.
* [OData](http://www.odata.org/)  - 开放协议，允许创建和使用可查询和可互操作的 RESTful API. 相当复杂.
* [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) - 简单的格式，提供了一种一致且简单的方法来在 API 中的资源之间进行超链接（请参阅： [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - 在 JSON (W3C) 中描述关联数据和超媒体关系的标准.
* [Hydra](http://www.hydra-cg.com/) - 超媒体驱动的 Web API (W3C) 词汇表.
* [Schema.org](http://schema.org) - 描述通用数据模型的模式集合.
* [OpenAPI](https://openapis.org/) - 以前称为 Swagger 规范，OpenAPI 规范是世界上用于定义 Restful API 的最流行的描述格式.

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) - 用于使用 RESTful Web 服务的 HTTP 客户端和框架.
* [Buzz](https://github.com/kriswallsmith/buzz) - 另一个轻量级 HTTP 客户端.
* [unirest for PHP](https://github.com/Mashape/unirest-php) - 简化、轻量级的 HTTP 客户端库.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) - AngularJS 服务可以正确、轻松地处理 REST API.
* [restful.js](https://github.com/marmelab/restful.js) - 用于与服务器端 RESTful 资源交互的 JS 客户端.
* [traverson](https://github.com/basti1302/traverson) - 适用于 Node.js 和浏览器的超媒体 API/HATEOAS 客户端
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) - 为 js 生成静态客户端库.

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) - node.js 的 REST 客户端库.
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - 简化、轻量级的 HTTP 客户端库.

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) - 用于 Ruby 的简单 HTTP 和 REST 客户端，受用于指定操作的微框架语法的启发.
* [Spyke](https://github.com/balvig/spyke) - 以类似 ActiveRecord 的方式与 REST 服务交互.
* [excon](https://github.com/excon/excon)  - 可用、快速、简单的 Ruby HTTP 1.1. 它作为通用 HTTP(s) 客户端工作得很好，特别适合在 API 客户端中使用.
* [httparty](https://github.com/jnunemaker/httparty) - 让 HTTP 再次变得有趣！
* [Net::HTTP](http://ruby-doc.org/stdlib/libdoc/net/http/rdoc/Net/HTTP.html) - Net::HTTP 提供了一个丰富的库，可用于构建 HTTP 用户代理.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) - 从 RAML 文件自动生成 API 客户端.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - 小而简单的包，可轻松使用 REST API.
* [resty](https://github.com/go-resty/resty) - 受 Ruby rest-client 启发的用于 Go 的简单 HTTP 和 REST 客户端.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - 直接从现有 PostgreSQL 数据库提供完全 RESTful API.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - 适用于任何 MySQL 数据库的简单 REST-like / CRUD 服务器.
* [pREST](https://github.com/prest/prest) - 来自用 Go 编写的任何现有 PostgreSQL 数据库的完全 RESTful API.

### Node.js

* [node-restify](https://github.com/restify/node-restify) - 专门用于 REST API 的框架.
* [Sails.js](http://sailsjs.org/) - 嵌入命令以自动生成 REST API 的 Node.js Web 框架.
* [mers](https://github.com/jspears/mers) - 将 Mongoose 查找器公开为 RESTful API 的快速服务.
* [Baucis](https://github.com/wprl/baucis) - 基于您的 Mongoose 实体构建可扩展的 REST API.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) - JavaScript 的同构资源引擎.
* [loopback](http://loopback.io/) - 强大的 Node.js 框架，用于创建 API 并轻松连接到后端数据源.
* [Feathers](http://feathersjs.com/) - 是一个实时的微服务 Web 框架，可让您通过 RESTful 资源、套接字和灵活的插件来控制您的数据.
* [Expressa](https://github.com/thomas4019/expressa) - 使用简单的管理编辑器和权限模型从 JSON 模式创建 API 的快速中间件.
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) - 基于支持关系数据的猫鼬模型生成 RESTful API.
* [Nestjsx/crud](https://github.com/nestjsx/crud) - Generate CRUD controllers and services for RESTful API with NestJS and TypeORM.

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - 在任何关系数据库之上提供 REST API 的微型 Web 应用程序.
* [Drest](https://github.com/leedavis81/drest) - 将 Doctrine 实体公开为 REST 资源端点的库.
* [Restler](https://github.com/Luracast/Restler) - 将 PHP 方法公开为 RESTful Web API 的轻量级框架.
* [HAL](https://github.com/blongden/hal) - 超文本应用程序语言 (HAL) 构建器库.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - 使用 Zend Framework 2 构建的 API 构建器.
* [phprest](https://github.com/phprest/phprest) - 专门用于 PHP 的 REST 微框架.
* [Hateoas](https://github.com/willdurand/Hateoas) - PHP 库支持实现 HATEOAS REST Web 服务的表示.
* [Fusio](https://github.com/apioo/fusio) - 开源API管理平台.

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - 使用 Symfony2 框架构建最先进的 REST API 的完整指南.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - 为您的 REST API 捆绑处理视图、路由、错误处理等.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - 使用约定优于配置构建基于 Doctrine 实体的 REST API.
* [lakion/Lionframe](http://lakion.com/lionframe) - 多个社区库之间的 Glu 以简化 API 开发.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - 整合 [Hateoas](https://github.com/willdurand/Hateoas) 库到 Symfony2 应用程序中.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - 从 Symfony2 应用程序开始，预配置所有 REST 友好的捆绑包.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - 基于 `stanlemon/rest-bundle` 的 Boostrap ng-admin 配置.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - 构建一个遵循 Hydra/JSON-LD 规范的 REST API.
* [API Platform](https://github.com/api-platform/api-platform) - 专门用于创建超媒体 REST API 的 Symfony 版本.
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - 从注释为您的 REST API 生成文档.

### Python

* [Django REST framework](http://www.django-rest-framework.org/) - 强大而灵活的工具包，可以轻松构建 Web API.
* [django-tastypie](http://tastypieapi.org/) - 为 Django 应用程序创建美味的 API.
* [flask-restful](http://flask-restful.readthedocs.org/) - Flask 扩展，增加了对快速构建 REST API 的支持.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask 扩展，用于为使用 SQLAlchemy（或 Flask-SQLAlchemy）定义的数据库模型生成 ReSTful API.
* [hug](http://www.hug.rest/) - 轻量级和快速的 API 框架.
* [sandman](https://github.com/jeffknupp/sandman) - 现有数据库驱动系统的自动化 REST API.
* [restless](http://restless.readthedocs.org/en/latest/) - 基于从 TastyPie 吸取的经验教训的与框架无关的 REST 框架.
* [Python Eve](http://python-eve.org/)  - Eve 是一个为人类设计的开源 Python REST API 框架. 它允许轻松构建和部署高度可定制、功能齐全的 RESTful Web 服务.
* [Ramses](https://ramses.readthedocs.org/en/stable/) - 通过在运行时从 RAML 文件生成可用于生产的 API 来使 RAML 文件可执行.
* [Flask-Potion](https://github.com/biosustain/potion)  - Flask-Potion 是一个强大的 Flask 扩展，用于构建 RESTful JSON API. 它还提供了多个客户端，以便更轻松地访问 API.
* [apistar](https://github.com/encode/apistar) - 为 Python 3 设计的智能 Web API 框架. 
* [Falcon](https://github.com/falconry/falcon) - Falcon 是一个裸机 Python Web API 框架，用于构建高性能微服务、应用程序后端和更高级别的框架.
* [FastAPI](https://github.com/tiangolo/fastapi)  - FastAPI 是一个现代、快速（高性能）的 Web 框架，用于基于标准 Python 类型提示使用 Python 3.6+ 构建 API. 使用基于 OpenAPI 和 JSON Schema 的 Swagger UI 和 ReDoc 的自动 API 文档.

### Ruby

* [Grape](http://www.ruby-grape.org) - 用于在 Ruby 中创建类似 REST 的 API 的自以为是的微框架.
* [Rails](http://guides.rubyonrails.org/api_app.html) - RailsGuides：将 Rails 用于纯 API 应用程序.

### Go

* [gocrud](https://github.com/manishrjain/gocrud)：Go 库，用于简化任意深度结构化数据的创建、更新和删除——使构建 REST 服务变得快速和容易.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - `net/http` 之上的薄层，有助于轻松构建 RESTful API.
* [sleepy](https://github.com/dougblack/sleepy) - 用 Go 编写的 RESTful 微框架.
* [restit](https://github.com/yookoala/restit) - Go 微框架帮助编写 RESTful API 集成测试.
* [go-relax](https://github.com/codehack/go-relax) - 用于构建 RESTful API 的可插拔组件框架.
* [go-rest](https://github.com/ungerik/go-rest) - Go 的小而邪恶的 REST 框架.
* [go-restful](https://github.com/emicklei/go-restful) - 用于构建 restful API 的声明式高度可读框架.
* [Goat](https://github.com/bahlo/goat) - Go 中的简约 REST API 服务器.
* [Resoursea](https://github.com/resoursea/api) - 用于快速编写基于资源的服务的 REST 框架.
* [Zerver](https://github.com/cosiner/zerver) - Zerver 是一个富有表现力的、模块化的、功能完备的 RESTful 框架.

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) - 基于 Netty、高性能、轻量级、无容器、可插件扩展的框架，非常适合微服务架构.
* [Vertx-Web](https://github.com/vert-x3/vertx-web) - Vert.x-Web 是一组用于使用 Vert.x 构建 Web 应用程序的构建块，Vert.x 是一个用于在 JVM 上构建反应式应用程序的工具包.
* [Dropwizard](https://github.com/dropwizard/dropwizard) - 用于开发操作友好、高性能、RESTful Web 服务的框架.

### Scala

* [Chaos](https://github.com/mesosphere/chaos) - 用于在 Scala 中编写 REST 服务的轻量级框架.


### Haskell
* [Rest for Haskell](https://github.com/silkapp/rest)  - 这个包允许你在 Haskell 中创建 REST API. 这些 API 可以在不同的 Web 框架中运行. 它们还可用于自动生成文档以及客户端库.

## Testing

### Querying

* [httpie](https://github.com/jkbrzt/httpie) - 命令行 HTTP 客户端，比 curl 更友好.
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - 手动测试 REST API 必不可少的 Chrome 扩展.
* [resty](https://github.com/micha/resty) - 可以在管道（bash 或 zsh）中使用的小型命令行 REST 客户端.
* [jq](https://github.com/stedolan/jq) - 命令行 JSON 处理器，与 cURL 等命令行 HTTP 客户端结合使用.
* [HttpMaster](http://www.httpmaster.net)  - 用于测试 REST API 和服务的 GUI 工具. 仅限 Windows 操作系统.
* [Http-console](https://github.com/cloudhead/http-console) - HTTP 的命令行界面，让您*像本地人一样说 HTTP*
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) - HTTP Prompt 是一个交互式命令行 HTTP 客户端，具有自动完成和语法高亮功能，基于 HTTPie 和 prompt_toolkit 构建.
* [rest-assured](https://github.com/rest-assured/rest-assured) - 用于轻松测试 REST 服务的 Java DSL.
* [Insomnia](https://github.com/getinsomnia/insomnia) - 跨平台 HTTP 和 GraphQL 客户端
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 使用基于 Web 的简单 HTTP 客户端发出 HTTP 请求.
* [TestMace](https://testmace.com) - 用于 API 自动化测试的跨平台简单但功能强大的 IDE.
* [Milkman](https://github.com/warmuuh/milkman) - 可扩展的跨平台请求/响应工作台，不仅适用于 http 调用.
* [Schemathesis](https://github.com/schemathesis/schemathesis) - 基于属性的测试工具，用于使用 Open API 和 GraphQL 规范构建的 Web 应用程序.

### Mocking

* [RequestBin](https://requestbin.com/) - 检查和调试客户端或第三方 API 发送的 webhook 请求.
* [httpbin](http://httpbin.org) - HTTP 请求和响应服务 - 用于 HTTP 的瑞士军刀.
* [FakeRest](https://github.com/marmelab/FakeRest) - 修补 XMLHttpRequest 以伪造 REST API 客户端.
* [json-server](https://github.com/typicode/json-server) - 使用快速原型从夹具文件提供 REST API.
* [Mocky.io](http://www.mocky.io/) - 免费在线服务来创建虚假的 HTTP 响应.
* [MockServer](https://www.mock-server.com/) - 轻松模拟您通过 HTTP 或 HTTPS 集成的任何系统.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - 基于 swagger 模式的 Mock RESTful API
* [Request Baskets](https://github.com/darklynx/request-baskets) - 收集 HTTP 请求并通过 RESTful API 或 Web UI 检查它们的服务.
* [DuckRails](https://github.com/iridakos/duckrails) - 快速和动态地模拟 API 端点.
* [Mockoon](https://mockoon.com)  - 在本地轻松创建模拟 API. 无需远程部署，无需账号，开源.
* [Mockintosh](https://mockintosh.io/) - 一个模拟服务器生成器，能够生成 RESTful API 并与消息队列通信以模仿异步任务.

### Public REST APIs To Use In Tests
* [Deck of Cards API](http://deckofcardsapi.com) - 用于模拟一副纸牌的开放 API.
* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - 世界上最大的 API 存储库.
* [Public APIS](https://www.publicapis.com/) - 探索 Galaxy 中最大的 API 目录.
* [Marvel Comics API](http://developer.marvel.com/) - 查询漫威超级英雄的人物、故事、事件.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - 免费在线 REST 服务，您可以在需要一些虚假数据时使用.
* [APIs.guru](http://APIs.guru) - Web API 的维基百科，每个 API 都有 OpenAPI/Swagger 描述.

## Documentation

* [Swagger](http://swagger.io/) - REST API 的文档/查询 Web 界面.
* [API doc](http://apidocjs.com/) - RESTful Web API 的内联文档.
* [raml2html](https://github.com/raml2html/raml2html) - 从 RAML 文件生成 HTML 文档.
* [ReDoc](https://github.com/Rebilly/ReDoc/) - OpenAPI/Swagger 驱动的三面板文档.
* [Slate](https://github.com/lord/slate) - 使用 Middleman 的漂亮且响应迅速的三面板 API 文档.
* [Optic](https://github.com/opticdev/optic)  - 无需编写 OpenAPI/Swagger 即可维护准确的 API 规范. 适用于任何堆栈

## API Gateway

* [Kong](https://github.com/Kong/kong) - 由 Nginx 支持的可扩展、分布式和面向插件的 API 网关.
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) - 带有分析日志的轻量级 API 网关，用 Go 编写.
* [API Umbrella](https://github.com/NREL/api-umbrella) - 用于公开 Web 服务的 API 管理平台，带有 Web 界面和分析，用 Lua 编写.
* [WSO2 API Management](https://github.com/wso2/product-apim) - 具有轻量级网关和 API 生命周期管理的 API 管理工具，用 Java 编写.
* [Express Gateway](https://github.com/ExpressGateway/express-gateway) - 基于 ExpressJS (Node.js) 构建的微服务 API 网关.
* [KrakenD](https://github.com/devopsfaith/krakend) 带有中间件的超高性能 API 网关. 用围棋写的.

## SaaS Tools

* [Nango](https://github.com/NangoHQ/nango) - 使用 REST API（开源）的本机集成框架.
* [Runscope](https://www.runscope.com/) - 自动化 API 监控和测试.
* [Ping-API](https://ping-api.com/) - 自动化 API 监控和测试.
* [import.io Magic](https://magic.import.io/) - 一键从任何网站创建 REST API.
* [Apiary](https://apiary.io/) - 协同设计、即时 API 模拟、生成文档、集成代码示例、调试和自动化测试.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway 是一项完全托管的服务，可让开发人员轻松创建、发布、维护、监控和保护任何规模的 API.
* [Apigee](https://apigee.com) - Apigee 是为企业和开发人员提供 API 技术和服务的领先提供商.
* [3scale](https://www.3scale.net/) - 基于 Nginx 的 API 网关将内部和外部 API 服务与 3scale 的 API 管理平台集成.
* [Assertible](https://assertible.com) - 在部署后和跨环境持续测试和监控您的 API.
* [Moesif](https://www.moesif.com) - 用于 RESTful 和 GraphQL 的调试、监控和使用跟踪的 API 分析.
* [Beeceptor](https://beeceptor.com/)  - HTTP 检查、模拟和代理服务. 为创建模拟 API 端点和模拟响应提供命名端点.

## Miscellaneous

* [react-admin](https://github.com/marmelab/react-admin) - 将 ReactJS 管理 GUI 添加到任何 RESTful API.
* [ng-admin](https://github.com/marmelab/ng-admin) - 将 AngularJS 管理 GUI 添加到任何 RESTful API.
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) - 在给定 OpenAPI 规范（以前称为 Swagger 规范）的情况下自动生成客户端库或服务器存根.
* [Lumber](https://github.com/ForestAdmin/lumber) - 生成应用程序的管理界面.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

本作品已获得许可 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
