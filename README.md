# php常见的资源、库 中文版本

转载自：[https://github.com/ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

> 大部分转载自awesome-php 由于本人英文太差所以用api翻译成了中文 有些翻译不对 请见谅

### 不定时更新同步 [更新时间:2022-11-30 11:37:14]

一个精心策划的令人惊叹的PHP库、资源和闪亮的东西列表。

---

## 目录

- [很棒的PHP](#awesome-php)

    - [作曲家存储库 Composer-Repositories](#作曲家存储库-composer-repositories)

    - [依赖关系管理 Dependency-Management](#依赖关系管理-dependency-management)

    - [依赖关系管理临时演员 Dependency-management-extras](#依赖关系管理临时演员-dependency-management-extras)

    - [网络通信引擎 Network-Communication-Engine](#网络通信引擎-network-communication-engine)

    - [框架 Frameworks](#框架-frameworks)

    - [额外的框架 Framework-extras](#额外的框架-framework-extras)

    - [内容管理系统 Content-management-systems-cms](#内容管理系统-content-management-systems-cms)

    - [组件 Components](#组件-components)

    - [微框架 micro-frameworks](#微框架-micro-frameworks)

    - [微观框架-扩展 Micro-framework-extras](#微观框架-扩展-micro-framework-extras)

    - [路由 Routers](#路由-routers)

    - [模板 Templating](#模板-templating)

    - [静态网站生成器 Static Site Generators](#静态网站生成器-static-site-generators)

    - [HTTP客户端 HTTP Client](#HTTP客户端-HTTP-Client)

    - [爬虫 Scraping](#爬虫-scraping)

    - [中间件 Middlewares)](#中间件-middlewares)

    - [URL](#url)

    - [电子邮件 Email](#电子邮件-email)

    - [文件 Files](#文件-files)

    - [流 Streams](#流-streams)

    - [依赖注入 Dependency Injection](#依赖注入-dependency-injection)

    - [图像 Imagery](#图像-imagery)

    - [测试 Testing](#测试-testing)

    - [持续集成 Continuous Integration](#持续集成-continuous-integration)

    - [文档 Documentation](#文档-documentation)

    - [安全 Security](#安全-security)

    - [密码 Passwords](#密码-passwords)

    - [代码分析 Code Analysis](#代码分析-code-analysis)

    - [代码质量 Code Quality](#代码质量-code-quality)

    - [静态分析 Static Analysis](#静态分析-static-analysis)

    - [建筑 Architectural](#建筑-architectural)

    - [调试和性能分析 Debugging and Profiling](#调试和性能分析-debugging-and-profiling)

    - [构建工具 Build Tools](#构建工具-build-tools)

    - [任务运行者 Task Runners](#任务运行者-task-runners)

    - [导航 Navigation](#导航-navigation)

    - [资产管理 Asset Management](#资产管理-asset-management)

    - [地理位置 Geolocation](#地理位置-geolocation)

    - [日期和时间 Date and Time](#日期和时间-date-and-time)

    - [事件 Event](#事件-event)

    - [日志记录 Logging](#日志记录-logging)

    - [电子商务 E-commerce](#电子商务-e-commerce)

    - [PDF](#PDF)

    - [办公 Office](#办公室-office)

    - [数据库 Database](#数据库-database)

    - [迁移 Migrations](#迁移-migrations)

    - [NoSQL](#nosql)

    - [队列 Queue](#队列-queue)

    - [搜索 Search](#搜索-search)

    - [命令行 Command Line](#命令行-command-line)

    - [身份验证和授权 Authentication and Authorization](#身份验证和授权-authentication-and-authorization)

    - [标记和CSS Markup and CSS](#标记和CSS-markup-and-css)

    - [JSON](#json)

    - [字符串 Strings](#字符串-strings)

    - [数字 Numbers](#数字-numbers)

    - [过滤和验证 Filtering and Validation](#过滤和验证-filtering-and-validation)

    - [API](#api)

    - [缓存和锁定 Caching and Locking](#缓存和锁定-caching-and-locking)

    - [数据结构和存储 Data Structure and Storage](#数据结构和存储-data-structure-and-storage)

    - [通知 Notifications](#通知-notifications)

    - [部署 Deployment](#部署-deployment)

    - [国际化和本土化 Internationalisation and Localisation](#国际化和本土化-internationalisation-and-localisation)

    - [无服务器的 Serverless](#无服务器的-serverless)

    - [配置 Configuration](#配置-configuration)

    - [第三方api Third Party APIs](#第三方api-third-party-apis)

    - [扩展 Extensions](#扩展-extensions)

    - [杂项 Miscellaneous](#杂项-miscellaneous)

- [软件 Software](#软件-software)

    - [PHP安装 PHP Installation](#PHP安装-PHP-installation)

    - [开发环境 Development Environment](#开发环境-development-environment)

    - [虚拟机 Virtual Machines and Compilers](#虚拟机-virtual-Machines-and-compilers)

    - [文本编辑器和ide Text Editors and IDEs](#文本编辑器和ide-text-editors-and-ides)

    - [Web应用程序 Web Applications](#Web应用程序-web-applications)

    - [基础设施 Infrastructure](#基础设施-infrastructure)

- [资源 Resources](#资源-resources)

    - [PHP的网站 PHP Websites](#PHP的网站-php-websites)

    - [PHP的书 PHP Books](#PHP的书-php-books)

    - [PHP的视频 PHP Videos](#PHP的视频-php-videos)

    - [PHP播客 PHP Podcasts](#PHP播客-php-podcasts)

    - [PHP通讯 PHP Newsletters](#PHP通讯-php-newsletters)

    - [PHP阅读 PHP Reading](#PHP阅读-php-reading)

    - [PHP内部阅读 PHP Internals Reading](#PHP内部阅读-php-internals-reading)

### 作曲家存储库 composer-repositories

*作曲家存储库.*

* [Firegento](https://packages.firegento.com/) - 线上购物模块作曲家库.
* [Packagist](https://packagist.org/) - PHP包存储库.
* [Private Packagist](https://packagist.com/) - 作曲家包存档作为PHP的服务.
* [WordPress Packagist](https://wpackagist.org/) - 管理你的插件与作曲家.

### 依赖关系管理 dependency-management

*用于依赖项和包管理的库。*

* [Composer Installers](https://github.com/composer/installers) - 作曲家多框架库安装程序.
* [Composer](https://getcomposer.org/) - 一个包和依赖管理器.
* [Phive](https://phar.io/) - PHAR经理.
* [Pickle](https://github.com/FriendsOfPHP/pickle) - 一个PHP扩展安装程序.

### 依赖关系管理临时演员 dependency-management-extras

*附加内容与依赖项管理相关。*

* [Composed](https://github.com/joshdifabio/composed) - 一个库来解析您的项目的作曲家在运行时环境中.
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - 一个作曲家插件合并几个作曲家.json`
  files.
* [Composer Normalize](https://github.com/ergebnis/composer-normalize) - 一个插件正常化的作曲家.json` files.
* [Composer Patches](https://github.com/cweagans/composer-patches) - 作曲家的插件应用补丁.
* [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) - CLI工具分析作曲家的依赖关系,并验证没有未知的符号是用于一个包的来源.
* [Composer Unused](https://github.com/composer-unused/composer-unused) - 一个CLI工具扫描未使用的作曲家包.
* [Prestissimo](https://github.com/hirak/prestissimo) - 一个作曲家插件使平行的安装过程.
* [Repman](https://repman.io) - 一个私人的PHP包repository manager和Packagist代理.
* [Satis](https://github.com/composer/satis) - 一个静态的作曲家库发生器.
* [Tooly](https://github.com/tommy-muehle/tooly-composer-script) - 一个图书馆管理PHAR文件在项目使用的作曲家.
* [Toran Proxy](https://toranproxy.com) - 一个静态的作曲家库和代理.

### 网络通信引擎 Network-Communication-Engine

*php的一些网络通信引擎。*

* [Workerman](https://github.com/walkor/Workerman) - 一个事件驱动的非阻塞I / O库.
* [Swoole](https://github.com/swoole) - 面向生产环境的 PHP 异步网络通信引擎
* [Swow](https://github.com/swow/swow) - Swow是一个使用PHP和C编写的高性能纯协程网络通信引擎。它致力于使用最小C核心及多数PHP代码以支持PHP高性能网络编程。

### 框架 frameworks

*Web开发框架。*

* [CakePHP](https://cakephp.org/) - 一个快速的应用程序开发框架.
* [Laminas](https://getlaminas.org/) - 框架组成的单个组件(之前Zend框架).
* [Laravel](https://laravel.com/) - 富有表现力的web应用程序框架,优雅的语法.
* [Nette](https://nette.org) - 一个web框架组成的成熟的组件.
* [Phalcon](https://phalcon.io/en-us) - 一个框架实现为一个C扩展.
* [Spiral](https://spiral.dev/) - 一个高性能的PHP /框架.
* [Symfony](https://symfony.com/) - 一组可重用的组件和web框架.
* [Yii2](https://github.com/yiisoft/yii2/) - 一种快速、安全、高效的web框架.
* [Leaf](https://leafphp.dev/) - 轻薄的web框架.
* [Swoole相关](https://github.com/swoole/awesome-swoole)
    - [SwooleDistributed](https://github.com/SwooleDistributed/SwooleDistributed) - swoole 分布式全栈框架
    - [Swoft](https://github.com/swoft-cloud/swoft) - 基于Swoole原生协程，新时代PHP高性能协程框架 https://www.swoft.org
    - [Hyperf](https://github.com/hyperf-cloud/hyperf) - 企业级的 PHP 协程微服务框架
    - [Mixphp](https://github.com/mixstart/mixphp) - 基于 Swoole 的FPM、常驻内存、协程三模 PHP 高性能框架 (
      开发文档完善) http://mixphp.cn
    - [Laravel-s](https://github.com/hhxsv5/laravel-s) - 集成 Swoole 到 Laravel 或 Lumen
    - [Laravel-swoole](https://github.com/swooletw/laravel-swoole) - 基于Swoole的高性能HTTP服务器。加速你的Laravel或Lumen应用程序。
    - [LaravelFly](https://github.com/scil/LaravelFly) - 成为一个绝对安全的解决方案来运行Laravel与Swoole。Laravel +
      Swoole Coroutine +
      Safety + Tinker Online.
    - [Laravoole](https://github.com/garveen/laravoole) - Laravel && ( Swoole || Workerman ) 获得比php-fpm快10倍的速度
    - [Easyswoole](https://github.com/easy-swoole/easyswoole) - 使用swoole很容易，就像echo "hello world "一样。;
    - [Swoolefy](https://github.com/bingcool/swoolefy) - swoolefy是一个基于swoole实现的轻量级、高性能、协程级、开放性的API和MVC应用服务框架
    - [Zan](https://github.com/youzan/zan) - 有赞开源的 PHP 框架 (已停止维护)
    - [Msf](https://github.com/pinguo/php-msf) - Camera360开源的微服务框架* [swoole相关](https://github.com/swoole) -
      面向生产环境的 PHP
      异步网络通信引擎
* [Workerman相关](https://www.workerman.net/related_projects)
    - [Webman](https://github.com/walkor/webman) - 基于Workerman的PHP的高性能HTTP服务框架。.
* [CodeIgniter](https://github.com/bcit-ci/CodeIgniter) - CodeIgniter是一个应用程序开发框架--一个工具包--为使用PHP建立网站的人服务.

### 额外的框架 framework-extras

*附加内容与web开发框架相关。*

* [CakePHP CRUD](https://github.com/friendsofcake/crud) - CakePHP的快速应用程序开发(RAD)插件.
* [Knp RAD Components](https://rad.knplabs.com/) - 一组快速应用程序开发(RAD)组件Symfony.
* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - 内容管理框架来创建自定义的CMS.
* [Livewire](https://laravel-livewire.com/) - Laravel的完整框架,构建动态ui的痛苦了.

### 内容管理系统 content-management-systems-cms

*管理数字内容的工具。*

* [Backdrop](https://backdropcms.org) - CMS针对中小企业和非营利组织(Drupal的叉子).
* [Concrete5](https://www.concretecms.com/) - CMS的目标用户用最少的技术技能.
* [CraftCMS](https://github.com/craftcms/cms) - 一种灵活的、用户友好的CMS为创建自定义web上的数字体验.
* [Drupal](https://www.drupal.org) - 企业级内容管理系统.
* [Grav](https://github.com/getgrav/grav) - 一个现代的平面文件CMS.
* [Joomla](https://www.joomla.org/) - 另一家领先的CMS.
* [Kirby](https://getkirby.com/) - 一个文件的CMS,适应任何项目.
* [Magento](https://business.adobe.com/products/magento/magento-commerce.html) - 最受欢迎的电子商务平台.
* [Moodle](https://moodle.org/) - 一个开源的学习平台.
* [Pico CMS](https://picocms.org/) - 一个愚蠢简单,速度极快,平面文件的CMS.
* [Statamic](https://statamic.com/) - 构建美丽的、易于管理的网站.
* [WordPress](https://wordpress.org/) - 一个博客平台和CMS.

### 组件 components

*来自web开发框架和开发小组的独立组件。*

* [Aura](https://auraphp.com/) - 互相独立的组件,充分解耦和从任何框架.
* [CakePHP Plugins](https://plugins.cakephp.org/) - CakePHP插件的目录中.
* [Laravel Components](https://github.com/illuminate) - Laravel框架组件.
* [League of Extraordinary Packages](https://thephpleague.com/) - 一个PHP包开发团队.
* [Spatie Open Source](https://spatie.be/open-source) - 开源的PHP和Laravel包的集合.
* [Symfony Components](https://symfony.com/components) - Symfony的组件.
* [Laminas Components](https://docs.laminas.dev/components/) - 使计算框架的组件.

### 微框架 micro-frameworks

*微框架和路由器。*

* [Laravel-Zero](https://laravel-zero.com) - micro-framework控制台应用程序.
* [Lumen](https://lumen.laravel.com/) - 一个由Laravel micro-framework.
* [Mezzio](https://getexpressive.org/) - 一个micro-framework进行计算.
* [Radar](https://github.com/radarphp/Radar.Adr) - 一个Action-Domain-Responder PHP实现.
* [Silly](https://github.com/mnapoli/silly) - micro-framework CLI应用程序.
* [Slim](https://www.slimframework.com/) - 另一个简单的微框架.
* [Nano](https://nano.hyperf.wiki/) - Hyperf的一个微框架.

### 微观框架-扩展 micro-framework-extras

*与微框架和路由器相关的额外内容。*

* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - 纤细的骨架.
* [Slim Twig View](https://github.com/slimphp/Slim-Views) - 树枝融入苗条.
* [Slim PHP View](https://github.com/slimphp/PHP-View) - 一个简单的PHP苗条的渲染器.

### 路由 Routers

*用于处理应用程序路由的库。*

* [Aura.Router](https://github.com/auraphp/Aura.Router) - 一个全功能的路由图书馆.
* [Fast Route](https://github.com/nikic/FastRoute) - 一个快速的路由图书馆.
* [Klein](https://github.com/klein/klein.php) - 灵活的路由器.
* [Pux](https://github.com/c9s/Pux) - 另一个快速的路由库.
* [Route](https://github.com/thephpleague/route) - 路由图书馆建立在快速的路线.
* [Macaw](https://github.com/NoahBuscher/Macaw) - 一个简单的 PHP 路由器，超级精简、快速而且很性感。

### 模板 Templating

*用于模板和词法的库和工具。*

* [Latte](https://latte.nette.org/) - 最安全、真正直观的PHP模板.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - HAML模板语言的PHP实现.
* [Mustache](https://github.com/bobthecow/mustache.php) - 胡子的PHP实现模板语言.
* [PHPTAL](https://phptal.org/) - 一个PHP实现的(TAL) [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language)
  模板语言.
* [Plates](http://platesphp.com/) - 一个原生PHP模板库.
* [Smarty](https://www.smarty.net/) - PHP模板引擎来补充.
* [Twig](https://twig.symfony.com/) - 一个全面的模板语言.
* [asm89/twig-cache-extension](https://github.com/asm89/twig-cache-extension) - 用于Twig的模板片段缓存库.
* [rcrowe/TwigBridge](https://github.com/rcrowe/TwigBridge) - Twig 模板引擎支持.
* [Phly Mustache](https://github.com/weierophinney/phly_mustache) - 另一个PHP实现的Mustache模板语言.
* [Lex](https://github.com/pyrocms/lex) - 一个轻量级模板解析器.
* [Aura.View](https://github.com/auraphp/Aura.View) - 提供TemplateView和TwoStepView.

### 静态网站生成器 Static Site Generators

*用于预处理内容以生成网页的工具。*

* [Cecil](https://cecil.app/) - Cecil是一个CLI应用程序，合并Markdown文件，图像和Twig模板，以生成一个静态网站.
* [Couscous](http://couscous.io) - 蒸粗麦粉减价文档变成漂亮的网站. 它是GitHub页面的立体化.
* [Jigsaw](https://jigsaw.tighten.com/) - 简单的静态站点Laravel的叶片.
* [Sculpin](https://sculpin.io) - 一个将Markdown和Twig转换为静态HTML的工具.
* [Spress](http://spress.yosymfony.com) - 一个可扩展的工具，将Markdown和Twig转换成HTML.

### HTTP客户端 HTTP Client

*用于使用HTTP的库.*

* [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个HTTP客户端.
* [Guzzle]( https://github.com/guzzle/guzzle) - 全面的HTTP客户端.
* [HTTPlug](http://httplug.io) - 没有绑定到特定实现的HTTP客户机抽象.
* [Nyholm PSR-7](https://github.com/Nyholm/psr7) - 一个超级轻量级PSR-7实现. 非常严格和非常快.
* [PHP VCR](https://php-vcr.github.io/) - 用于记录和重放HTTP请求的库.
* [Requests](https://github.com/WordPress/Requests) - 一个简单的HTTP库.
* [Retrofit](https://github.com/tebru/retrofit-php) - 图书馆,以缓解创建REST API的客户.
* [Symfony HTTP Client](https://github.com/symfony/http-client) - 同步或获取HTTP资源的组件异步.
* [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP消息实现.
* [amphp/artax](https://github.com/amphp/artax) - An Asynchronous HTTP Client for PHP
* [HTTPFul](https://github.com/nategood/httpful) - 一个链式HTTP客户端
* [php-curl-class](https://github.com/php-curl-class/php-curl-class) - PHP的Curl类
* [php-mod/curl](https://github.com/php-mod/curl) - PHP Curl Class
* [medz/cors](https://github.com/medz/cors) - PHP CORS（跨源资源共享）中间件.
* [barryvdh/laravel-cors](https://github.com/barryvdh/laravel-cors) - laravel-cors包允许你用Laravel中间件配置发送跨源资源共享头信息。
* [lezhnev74/openapi-psr7-validator](https://github.com/lezhnev74/openapi-psr7-validator) -
  它根据OpenAPI规范验证PSR-7消息（HTTP请求/响应）.

### 爬虫 Scraping

*图书馆刮网站。*

* [Chrome PHP](https://github.com/chrome-php/chrome) - 从PHP工具无头Chrome /铬实例.
* [DiDOM](https://github.com/Imangazaliev/DiDOM) - 一个超级快速的HTML清理器和解析器.
* [Embed](https://github.com/oscarotero/Embed) - 一个信息提取器从任何web服务或页面.
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - 一个简单的web刮刀.
* [Symfony Panther](https://github.com/symfony/panther) - 浏览器测试PHP和web爬行库和Symfony.
* [PHP Spider](https://github.com/mvdbos/php-spider) - 一个可配置的和可扩展的PHP web蜘蛛.
* [PHP Scraper](https://github.com/spekulatius/phpscraper) - 一个非常有意见的网络界面.
* [Phpquery](https://github.com/phpquery/phpquery) - phpQuery实现了CSS3选择器驱动的文档对象模型（DOM）API，基于jQuery的JavaScript库
  .
* [Beanbun](https://github.com/kiddyuchina/Beanbun) - 多进程网络爬虫框架
* [QueryList](https://github.com/jae-jae/QueryList) - QueryList是一套简洁、优雅、可扩展的PHP采集工具(爬虫)，基于phpQuery。

### 中间件 Middlewares

*图书馆使用中间件来构建应用程序。*

* [PSR-7 Middlewares](https://github.com/oscarotero/psr7-middlewares) - 鼓舞人心的方便的中间件)的集合.
* [Relay](https://github.com/relayphp/Relay.Relay) - 一个PHP 5.5 PSR-7 中间件调度员.
* [Stack](https://github.com/stackphp) - 一个图书馆的堆叠Symfony的中间件.
* [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) - 中间件为PHP PSR-7之上.

### URL

*解析URL的库。*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - 一个域后缀解析器库.
* [Purl](https://github.com/jwage/purl) - 一个URL处理库.
* [sabre/uri](https://github.com/sabre-io/uri) - 一个操纵功能URI库.
* [Uri](https://github.com/thephpleague/uri) - 另一个URL处理库.

### 电子邮件 Email

*库发送和解析电子邮件。*

* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - 图书馆内联CSS邮件模板.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - 解析器库的电子邮件回复.
* [Email Validator](https://github.com/nojacko/email-validator) - 一个小的电子邮件地址验证库.
* [Fetch](https://github.com/tedious/Fetch) - 一个IMAP库.
* [Mautic](https://github.com/mautic/mautic) - 电子邮件营销自动化.
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - 一个全功能的 PHP 电子邮件创建和传输类.
* [PHP IMAP](https://github.com/barbushin/php-imap) - 库访问通过POP3邮箱,IMAP和NNTP.
* [ddeboer/imap](https://github.com/ddeboer/imap) - 面向对象，经过充分测试的PHP IMAP库.
* [Stampie](https://github.com/Stampie/Stampie) - 图书馆的电子邮件服务,如[SendGrid] (https://sendgrid.com/)
  , [PostMark](https://postmarkapp.com)
  , [MailGun](https://www.mailgun.com/)and [MailChimp](https://mailchimp.com/features/transactional-email/).
* [SwiftMailer](https://swiftmailer.symfony.com) - 梅勒的解决方案.
* [Symfony Mailer](https://github.com/symfony/mailer) - 一个强大的库创建和发送电子邮件.
* [PhpMail-SMTP-POP3-IMAP](https://github.com/weiyixi/PhpMail-SMTP-POP3-IMAP) - 改造PhpMail得到的`邮件接收、发送`库.

### 文件 Files

*库文件操作和MIME类型检测。*

* [CSV](https://github.com/thephpleague/csv) - 一个CSV数据操作库.
* [Flysystem](https://github.com/thephpleague/Flysystem) - 本地和远程文件系统的抽象.
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - 一个文件系统抽象层.
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - 一个包装器(FFmpeg)[FFmpeg](https://www.ffmpeg.org/) 视频库.
* [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - 一个统一的读者和作家的压缩档案.
* [symfony/finder](https://github.com/symfony/finder) - 通过一个直观而流畅的接口来寻找文件和目录
* [Canal](https://github.com/dflydev/dflydev-canal) - 一个检查互联网媒体类型的库
* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - 一个解析Apache MIME类型的库
* [Ferret](https://github.com/versionable/Ferret) - 一个MIME检测库
* [Hoa Mime](https://github.com/hoaproject/Mime) - 另一个MIME检测库
* [Lurker](https://github.com/henrikbjorn/Lurker) - 一个资源跟踪库
* [PHP File Locator](https://github.com/herrera-io/php-file-locator) - 一个在大型项目中定位文件的库
* [GrahamCampbell/Laravel-Flysystem](https://github.com/GrahamCampbell/Laravel-Flysystem) - 文件系统操作,多平台支持

### 流 Streams

*库处理流。*

* [byte-stream](https://github.com/amphp/byte-stream) - AMPHP 是用于 PHP 的事件驱动库的集合，设计时考虑到了纤维和并发性。Ampp/byte-stream
  特别提供了流抽象，以简化处理各种字节流的工作.
* [Streamer](https://github.com/fzaninotto/Streamer) - 一个简单的面向对象流包装器库.
* [php-byte-buffer](https://github.com/Ne-Lexa/php-byte-buffer) -
  这个类定义了读取和写入所有基元类型的值的方法。根据缓冲区的当前字节顺序，基元值被转换为(或从)
  字节序列，可以通过顺序方法检索和修改这些字节顺序。字节缓冲区的初始顺序始终是大端序.

### 依赖注入 Dependency Injection

*图书馆实现依赖注入的设计模式。*

* [Aura.Di](https://github.com/auraphp/Aura.Di) - 一个可序列化的依赖注入容器构造函数和setter注入,接口和品质意识,配置继承,和更多.
* [Acclimate](https://github.com/AcclimateContainer/acclimate-container) - 一个共同的接口依赖注入容器和服务定位器.
* [Auryn](https://github.com/rdlowrey/Auryn) - 一个递归依赖注入器.
* [Container](https://github.com/thephpleague/container) - 另一个灵活的依赖注入容器.
* [Disco](https://github.com/bitExpert/disco) - PSR-11兼容,基于注解的依赖注入容器.
* [PHP-DI](https://php-di.org/) - 依赖注入容器,支持自动装配.
* [Pimple](https://pimple.symfony.com/) - 一个微小的依赖注入容器.
* [Symfony DI](https://github.com/symfony/dependency-injection) - 依赖注入容器组件.

### 图像 Imagery

*库操作图像。*

* [Color Extractor](https://github.com/thephpleague/color-extractor) - 从图像中提取颜色的图书馆.
* [Glide](https://github.com/thephpleague/glide) - 随需应变图像处理库.
* [Image Hash](https://github.com/jenssegers/imagehash) - 一个库生成散列感性形象.
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - 一个图书馆优化图像.
* [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - 一个图像处理库.
* [Intervention Image](https://github.com/Intervention/image) - 另一个图像处理库.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - 另一个图像处理库.
* [Intervention/imagecache](https://github.com/Intervention/imagecache) - 图片缓存增强工具
* [Sybio/GifFrameExtractor](https://github.com/Sybio/GifFrameExtractor) - 一个提取GIF动画帧信息的库
* [Sybio/GifCreator](https://github.com/Sybio/GifCreator) - 从多幅图片中创建GIF动画的库
* [nmcteam/image-with-text](https://github.com/nmcteam/image-with-text) - 在图像中嵌入文本的库
* [PHPThumb](https://github.com/masterexploder/PHPThumb) - 缩略图处理库
* [t0k4rt/phpqrcode](https://github.com/t0k4rt/phpqrcode) - 二维码生成库
* [endroid/qr-code](https://github.com/endroid/qr-code) - 另一个二维码生成库
* [Bacon/BaconQrCode](https://github.com/Bacon/BaconQrCode) - PHP的QR码生成器.
* [SimpleSoftwareIO/simple-qrcode](https://github.com/SimpleSoftwareIO/simple-qrcode) - 二维码生成工具
* [lsolesen/pel](https://github.com/lsolesen/pel) - PHP Exif 库
* [php-exif](https://github.com/PHPExif/php-exif) - PHP Exif信息读取库
* [Gregwar/Captcha](https://github.com/Gregwar/Captcha) - 图形验证码
* [google/recaptcha](https://github.com/google/recaptcha) - google reCAPTCHA 验证码Client 库
* [mewebstudio/captcha](https://github.com/mewebstudio/captcha) - 图片验证码方案.
* [PhenX/php-svg-lib](https://github.com/PhenX/php-svg-lib) - SVG文件解析/渲染库.
* [darylldoyle/svg-sanitizer](https://github.com/darylldoyle/svg-sanitizer) - 一个PHP SVG/XML消毒器.

### 测试 Testing

*库进行测试代码库和生成测试数据。*

* [Alice](https://github.com/nelmio/alice) - 富有表现力的夹具一代图书馆.
* [AspectMock](https://github.com/Codeception/AspectMock) - PHPUnit) / Codeception mocking框架.
* [Atoum](https://github.com/atoum/atoum) - 一个简单的测试库.
* [Behat](https://docs.behat.org/en/latest/) - 行为驱动开发(BDD)测试框架.
* [CakePHP Fixture Factories](https://github.com/vierge-noire/cakephp-fixture-factories) - 立即编写测试fixture，框架不可知.
* [Codeception](https://github.com/Codeception/Codeception) - 一个完整的堆栈测试框架.
* [Faker](https://github.com/fakerphp/faker) - 一个假数据生成器图书馆.
* [Foundry](https://github.com/zenstruck/foundry) - 夹具厂一代图书馆为原则.
* [HTTP Mock](https://github.com/InterNations/http-mock) - 在单元测试中模拟HTTP请求的库。
* [Infection](https://github.com/infection/infection) - 一个AST-based PHP变异测试框架.
* [Kahlan](https://github.com/kahlan/kahlan) - 完整的堆栈单元/ BDD测试框架内置存根,模拟和代码覆盖的支持.
* [Mink](https://mink.behat.org/en/latest/) - 网站验收测试.
* [Mockery](https://github.com/mockery/mockery) - 一个模拟对象库进行测试.
* [ParaTest](https://github.com/paratestphp/paratest) - PHPUnit)的并行测试库.
* [Pest](https://pestphp.com/) - 与专注于简单的测试框架.
* [Peridot](https://github.com/peridot-php/peridot) - 一个事件驱动的测试框架.
* [Phake](https://github.com/phake/phake) - 另一个模拟对象库进行测试.
* [Pho](https://github.com/danielstjules/pho) - 另一个行为驱动开发测试框架.
* [PHP-Mock](https://github.com/php-mock/php-mock) - 一个模拟库内置PHP函数(e.g. time()).
* [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) - 一个MySQL引擎用纯PHP编写的.
* [PHPSpec](https://github.com/phpspec/phpspec) - 一个由规范设计单元测试库.
* [PHPT](https://qa.php.net/write-test.php) - PHP本身所使用的测试工具.
* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - 一个单元测试框架.
* [Prophecy](https://github.com/phpspec/prophecy) - 非常固执己见的mocking框架.
* [VFS Stream](https://github.com/bovigo/vfsStream) - 一个虚拟文件系统流包装器进行测试.

### 持续集成 Continuous Integration

*持续集成库和应用程序。*

* [CircleCI](https://circleci.com) - 持续集成平台.
* [GitlabCi](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/) - 让GitLab CI测试、构建、部署代码.
  TravisCi
  like.
* [Jenkins](https://www.jenkins.io/) - 持续集成平台([PHP支持](https://www.jenkins.io/solutions/php/)).
* [JoliCi](https://github.com/jolicode/JoliCi) - 持续集成的客户端用PHP编写的,由码头工人.
* [PHPCI](https://github.com/dancryer/phpci) - 一个开源的PHP持续集成平台.
* [SemaphoreCI](https://semaphoreci.com/) - 持续集成平台开源和私人项目.
* [Shippable](https://jfrog.com/blog/weve-acquired-shippable-to-complete-devops-pipeline-automation-from-code-to-production/)
    - 持续基于码头工人为开源和私人项目集成平台.
* [Travis CI](https://travis-ci.org/) - 持续集成平台.
* [Setup PHP](https://github.com/shivammathur/setup-php) - PHP的GitHub的行动.

### 文档 Documentation

*用于生成项目文档库。*

* [APIGen](https://github.com/apigen/apigen) - 另一个API文档生成器.
* [daux.io](https://github.com/dauxio/daux.io) - 一个使用减价文件文档生成器.
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor) - 一个文档生成器.
* [phpDox](https://phpdox.net/) - PHP项目文档生成器(即不限于API文档).

### 安全 Security

*库生成安全的随机数,加密数据和漏洞扫描和检测。*

* [Halite](https://paragonie.com/project/halite) -
  一个简单的库加密使用[libsodium] (https://github.com/jedisct1/libsodium).
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
* [IniScan](https://github.com/psecio/iniscan) - 一个工具,扫描PHP INI文件的安全.
* [Optimus](https://github.com/jenssegers/optimus) - 基于Knuth的乘法散列方法Id困惑.
* [PHPGGC](https://github.com/ambionics/phpggc) - 一个PHP库unserializable载荷以及工具来生成它们.
* [PHP Encryption](https://github.com/defuse/php-encryption) - 安全的PHP加密库.
* [PHP SSH](https://github.com/Herzult/php-ssh) - 一个实验对象导向SSH包装器库.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - 一个纯PHP安全通信库.
* [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
* [RandomLib](https://github.com/ircmaxell/RandomLib) - 一个库生成随机数字和字符串.
* [Symfony Security Monitoring](https://security.symfony.com/) - web工具来检查你的作曲家依赖安全警告,以前被称为“SensioLabs安全检查”.
* [SQLMap](https://github.com/sqlmapproject/sqlmap) - 自动数据库SQL注入和收购工具.
* [TCrypto](https://github.com/timoh6/TCrypto) - 一个简单的加密键值存储库.
* [VAddy](https://vaddy.net/) - 一个持续的安全测试web应用程序的平台.
* [Zap](https://owasp.org/www-project-zap/) - 一个集成的渗透测试web应用程序的工具.

### 密码 Passwords

*库和工具用于处理和存储的密码。*

* [GenPhrase](https://github.com/timoh6/GenPhrase) - 一个库生成随机密码安全.
* [Password Compat](https://github.com/ircmaxell/password_compat) - 一个兼容库新PHP 5.5 password functions.
* [Password Policy](https://github.com/ircmaxell/password-policy) - 密码策略库为PHP和JavaScript.
* [Password Validator](https://github.com/jeremykendall/password-validator) - 图书馆为验证和升级密码散列.
* [Password-Generator](https://github.com/hackzilla/password-generator) - PHP库生成随机密码.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - 库生成和验证密码.
* [phpass](https://www.openwall.com/phpass/) - 一个便携式密码散列的框架.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - 一个现实的PHP密码强度估计基于Zxcvbn JS库.
* [tuupola/base62](https://github.com/tuupola/base62) - base62编码库(短网址应用)
* [stephen-hill/base58php](https://github.com/stephen-hill/base58php) - base58编码库(
  Bitcoin中使用的一种独特的编码方式，主要用于产生Bitcoin的钱包地址)
* [base85](https://github.com/tuupola/base85) - base85编码库(
  在base64的基础上进一步压缩数据量,应用于Adobe的PostScript语言和PDF文档格式)

### 代码分析 Code Analysis

*库和工具分析,解析和操作代码库。*

* [Better Reflection](https://github.com/Roave/BetterReflection) - 基于ast的反射库，允许分析和 代码操作
* [Code Climate](https://codeclimate.com) - 一个自动代码审查.
* [GrumPHP](https://github.com/phpro/grumphp) - 一个PHP代码质量工具.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - 用PHP编写的一个PHP解析器.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - 一个命令行实用程序,比较两组源,并确定适当的语义版本控制应用.
* [Phpactor](https://github.com/phpactor/phpactor) - PHP完成、重构和内省工具.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - 快速的工具测量一个PHP项目的大小.
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - 的工具运行QA工具(phploc、phpcpd phpcs, pdepend, phpmd, phpmetrics).
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - 一个工具来可视化指标和源代码.
* [Rector](https://github.com/rectorphp/rector) - 升级工具和重构代码.
* [Scrutinizer](https://scrutinizer-ci.com/) - 一个网络工具(PHP代码审查)(https://github.com/scrutinizer-ci/php-analyzer)
  .
* [UBench](https://github.com/devster/ubench) - 一个简单的微基准库.
* [Text_Diff](https://github.com/pear/Text_Diff) - 代码文件比较工具.
* [sebastian/diff](https://github.com/sebastianbergmann/diff) - PHP 的 Diff 实现，将 PHPUnit 分解为一个独立组件.
* [Tolerant PHP Parser](https://github.com/microsoft/tolerant-php-parser) - 微软出品的 PHP 语法解析器.

### 代码质量 Code Quality

*库管理代码质量、格式和产品毛羽。*

* [CaptainHook](https://github.com/captainhookphp/captainhook) - 一个易于使用的和灵活的Git库.
* [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - 库,发现PHP, CSS和javascript编码标准违规.
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - 一个编码标准工库.
* [PHP Mess Detector](https://github.com/phpmd/phpmd) - 图书馆扫描代码错误,次优的代码,未使用的参数等等.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - 一个工具来帮助遵守特定的编码惯例.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - 库,发现复制粘贴代码.

### 静态分析 Static Analysis

*库执行PHP代码的静态分析。*

* [Exakat](https://github.com/exakat/exakat) - PHP的静态分析引擎.
* [Deptrac](https://github.com/qossmic/deptrac) - 一个静态代码分析工具,以帮助执行规则的软件层之间的依赖关系.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - 利用图论的代码分析工具.
* [phan](https://github.com/phan/phan) - 基于PHP的静态分析器7和php-ast扩展.
* [PHP Architecture Tester](https://github.com/carlosas/phpat) - 容易使用PHP架构测试工具.
* [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) - 一个PHP为PHP CodeSniffer兼容性检查器.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - 一个工具来创建可定制的依赖图.
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - 一个静态度量库.
* [PHP Migration](https://github.com/monque/PHP-Migration) - 一个静态分析器为PHP版本迁移.
* [PHPStan](https://github.com/phpstan/phpstan) - 一个PHP静态分析工具.
* [Psalm](https://github.com/vimeo/psalm) - 静态分析工具寻找PHP应用程序中的错误.

### 建筑 Architectural

*有关设计模式库,编程方法和方式来组织代码。*

* [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP ) - 用PHP实现存储库的软件模式.
* [Finite](https://yohan.giarel.li/Finite/) - 一个简单的PHP有限状态机.
* [Functional PHP](https://github.com/lstrojny/functional-php) - 函数式编程库.
* [Iter](https://github.com/nikic/iter) - 图书馆提供了迭代原语使用发电机.
* [Patchwork](https://patchwork2.org/) - 重新定义用户的库函数.
* [Pipeline](https://github.com/thephpleague/pipeline) - 管道模式实现.
* [Porter](https://github.com/ScriptFUSION/Porter) - 数据导入抽象库消费Web api和其他数据源.
* [RulerZ](https://github.com/K-Phoen/rulerz) - 一个强大的规则引擎和实施规范的模式.
* [symfony/workflow](https://github.com/symfony/workflow) - Workflow组件提供的工具用来管理一个工作流或有限状态机
* [Patchwork](http://antecedent.github.io/patchwork/) - 一个重新定义用户的函数库
* [Finite](http://yohan.giarel.li/Finite) - 一个简单的PHP有限状态机
* [Ruler](https://github.com/bobthecow/Ruler) - 一个简单的无状态的产生环境规则的引擎

### 调试和性能分析 Debugging and Profiling

*调试错误,分析代码的库和工具。*

* [APM](https://pecl.php.net/package/APM) - 监测扩展收集错误和统计数据到SQLite / MySQL / StatsD.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - 另一个使用Google Chrome web调试控制台.
* [Blackfire.io](https://www.blackfire.io) - 一个低开销的代码分析器.
* [Kint](https://github.com/kint-php/kint) - 调试和分析工具.
* [Metrics](https://github.com/beberlei/metrics) - 一个简单的度量标准API库.
* [PCOV](https://github.com/krakjoe/pcov) - 一个自我包含的代码覆盖率兼容的驱动程序.
* [PHP Console](https://github.com/Seldaek/php-console) - web调试控制台.
* [PHP Debug Bar](http://phpdebugbar.com/) - 调试工具栏.
* [PHPBench](https://github.com/phpbench/phpbench) - 一个基准测试框架.
* [PHPSpy](https://github.com/adsr/phpspy) - 一个低开销抽样分析器.
* [Symfony VarDumper](https://github.com/symfony/var-dumper) - 一个变量翻车机组件.
* [Tideways.io](https://tideways.com/) - 监控和分析工具.
* [Tracy](https://github.com/nette/tracy) - 一个简单的错误检测,记录和时间测量库.
* [Whoops](https://github.com/filp/whoops) - 一个美丽的错误处理库.
* [xDebug](https://github.com/xdebug/xdebug) - PHP的调试和配置工具.
* [XHProf](https://github.com/phacility/xhprof) - 最初由Facebook开发的分析工具.
* [Z-Ray](https://www.zend.com/products/z-ray) - Zend调试和配置工具服务器.
* [PHP-Error](https://github.com/JosephLenton/PHP-Error) - PHP错误对于开发来说是不够好的，就这么简单。这旨在解决这个问题。.

### 构建工具 Build Tools

*项目构建和自动化工具。*

* [Box](https://github.com/box-project/box) - 一个实用程序来构建PHAR文件.
* [Construct](https://github.com/jonathantorres/construct) - 一个PHP项目/ micro-package生成器.
* [Phing](https://www.phing.info/) - 一个PHP项目构建系统的灵感来自Apache Ant.
* [RMT](https://github.com/liip/RMT) - 库的版本控制和发布软件.

### 任务运行者 Task Runners

*图书馆自动化和运行任务。*

* [Bldr](https://bldr.io/) - 一个PHP跑任务建立在Symfony的组件.
* [Jobby](https://github.com/jobbyphp/jobby) - 一个PHP cron作业管理器没有修改crontab.
* [Robo](https://github.com/consolidation/Robo) - 一个PHP跑任务与面向对象配置.
* [Task](https://taskphp.github.io/) - 纯PHP运动员受繁重任务和吞咽.
* [Cron](https://github.com/poliander/cron/) - Crontab 格式解析.

### 导航 Navigation

*构建工具导航结构。*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - 一个菜单库.
* [Menu](https://github.com/spatie/menu) - 一个灵活的菜单与连贯接口库.

### 资产管理 Asset Management

*工具管理、压缩和缩减网站资产。*

* [JShrink](https://github.com/tedious/JShrink) - 一个JavaScript库缩小镜.
* [Laravel Mix](https://github.com/laravel-mix/laravel-mix ) - 一个优雅的包装Webpack 80飐e.
* [Symfony Asset](https://github.com/symfony/asset) - 管理网络资产的URL生成和版本.
* [Symfony Encore](https://github.com/symfony/webpack-encore) - 一个简单但功能强大的API来处理和编制资产围绕Webpack构建的.
* [protobuf](https://github.com/protocolbuffers/protobuf/tree/main/php) - 谷歌 protobuf 运行库.

### 地理位置 Geolocation

*为地理编码库地址和使用纬度和经度。*

* [Country List](https://github.com/umpirsky/country-list) - 所有的国家名称的列表和ISO 3166 - 1码.
* [GeoCoder](https://geocoder-php.org/) - 一个地理编码库.
* [GeoJSON](https://github.com/jmikola/geojson) - GeoJSON实现.
* [GeoTools](https://github.com/thephpleague/geotools) - 一个图书馆geo-related工具.
* [PHPGeo](https://github.com/mjaschen/phpgeo) - 一个简单的地理库.

### 日期和时间 Date and Time

*库处理日期和时间。*

* [CalendR](https://yohan.giarel.li/CalendR/) - 日历管理图书馆.
* [Carbon](https://github.com/briannesbitt/Carbon) - 一个简单的DateTime API扩展.
* [Chronos](https://github.com/cakephp/chronos) - 一个DateTime API扩展支持可变和不可变的日期/时间.
* [moment](https://github.com/fightbulc/moment.php) - 时刻.受js启发的PHP DateTime处理程序，支持i18n.
* [Yasumi](https://github.com/azuyalabs/yasumi) - 一个库来帮助你计算假期的日期和名称.
* [php-calendar](https://github.com/liujiawm/php-calendar) - calendar、日历、中国农历、阴历、节气、干支、生肖、星座.

### 事件 Event

*图书馆事件驱动或实现非阻塞事件循环。*

* [Amp](https://github.com/amphp/amp) - 一个事件驱动的非阻塞I / O库.
* [Broadway](https://github.com/broadway/broadway) - 一个事件源和CQRS图书馆.
* [CakePHP Event](https://github.com/cakephp/event) - 事件调度程序库.
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - 另一个图书馆网络套接字.
* [Evenement](https://github.com/igorw/evenement) - 事件调度程序库.
* [Event](https://github.com/thephpleague/event) - 一个事件库重点领域的事件.
* [Pawl](https://github.com/ratchetphp/Pawl) - 异步web socket客户机.
* [Prooph Event Store](https://github.com/prooph/event-store) - 用于保存事件消息的事件源组件
* [PHP Defer](https://github.com/php-defer/php-defer) - 为PHP Golang推迟的语句.
* [Ratchet](https://github.com/ratchetphp/Ratchet) - 图书馆网络套接字.
* [ReactPHP](https://github.com/reactphp/reactphp) - 一个事件驱动的非阻塞I / O库.
* [RxPHP](https://github.com/ReactiveX/RxPHP) - 反应性扩展库.
* [Guzzle Promises](https://github.com/guzzle/promises) - 具有同步支持的PHP的Promises / A +库.

### 日志记录 Logging

*库生成和使用日志文件。*

* [Monolog](https://github.com/Seldaek/monolog) - 一个全面的日志记录器.
* [KLogger](https://github.com/katzgrau/KLogger) - 一个易于使用的PSR-3日志类
* [Analog](https://github.com/jbroadway/analog) - 一个机遇闭包的微型日志包
* [SeasLog](https://github.com/neeke/seaslog) - 一个高效的日志扩展
* [Laravel-Log-Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - 非常方便的页面 Log 查看工具

### 电子商务 E-commerce

*库和应用程序支付和构建在线电子商务商店。*

* [Money](https://github.com/moneyphp/money) - 福勒的钱的PHP实现模式.
* [Brick\Money](https://github.com/brick/money) - PHP的钱库,支持情况下,现金四舍五入,货币转换.
* [OmniPay](https://github.com/thephpleague/omnipay) - 一个框架不可知论者multi-gateway支付处理库.
* [Payum](https://github.com/payum/payum) - 付款抽象图书馆.
* [Shopware](https://github.com/shopware/shopware) - 高度可定制的电子商务软件
* [Swap](https://github.com/florianv/swap) - 一个汇率库.
* [Sylius](https://sylius.com/) - 一个开源的电子商务解决方案.
* [yansongda/pay](https://github.com/yansongda/pay) - 优雅的 Alipay 和 WeChat 的支付 SDK 扩展包
* [Sebastian Money](https://github.com/sebastianbergmann/money) - 一个处理货币价值的库

### PDF

*库和软件处理PDF文件。*

* [Dompdf](https://github.com/dompdf/dompdf) - 一个HTML到PDF的转换器.
* [PHPPdf](https://github.com/psliwa/PHPPdf) - 从XML生成的pdf文件和图片的库.
* [Snappy](https://github.com/KnpLabs/snappy) - 一个PDF和图像生成库.
* [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - 一个将HTML转换为PDF的工具.
* [phpwkhtmltopdf](https://github.com/mikehaertl/phpwkhtmltopdf)
* [php-pdftk](https://github.com/mikehaertl/php-pdftk) - 一个基于pdftk的PDF转换和表格工具.
* [laravel-snappy](https://github.com/barryvdh/laravel-snappy) - PDF 处理工具

### 办公 Office

*处理办公套件库文件。*

* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - 图书馆工作与微软PowerPoint演示.
* [PHPWord](https://github.com/PHPOffice/PHPWord) - 使用Microsoft Word文档库.
* [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - 纯PHP库读写电子表格文件(PHPExcel的继任者).
* [Spout](https://github.com/box/spout) - 读和写电子表格文件(CSV, XLSX和ODS),在一个快速和可伸缩的方式.

### 数据库 Database

*库与数据库进行交互使用对象关系映射(ORM)或datamapping技术。*

* [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) - 数据映射器实现你的持久性模型在PHP.
* [Aura.Sql](https://github.com/auraphp/Aura.Sql) - 提供了一个扩展本机PDO和分析器和连接定位器.
* [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) - 独立查询建筑商MySQL、PostgreSQL SQLite和Microsoft SQL
  Server.
* [Baum](https://github.com/etrepat/baum) - 一组嵌套实现雄辩的.
* [CakePHP ORM](https://github.com/cakephp/orm) - 对象关系映射器,使用DataMapper模式实现的.
* [Cycle ORM](https://github.com/cycle/orm) - PHP DataMapper ORM.
* [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions ) - 教义的集合行为扩展.
* [Doctrine](https://www.doctrine-project.org/) - 一个全面的DBAL和ORM.
* [Laravel Eloquent](https://github.com/illuminate/database) - 一个简单的ORM.
* [Pomm](https://github.com/chanmix51/Pomm) - PostgreSQL的对象模型经理.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - 一组实用程序来生成代理对象进行数据映射器.
* [RedBean](https://redbeanphp.com/index.php) - 一个轻量级,configuration-less ORM.
* [Slimdump](https://github.com/webfactory/slimdump) - 一个简单的翻车机MySQL的工具.
* [Spot2](https://github.com/spotorm/spot2) - MySQL datamapper ORM.

### 迁移 Migrations

*帮助管理数据库模式和迁移的库。*

* [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - 迁移库教义.
* [Migrations](https://github.com/icomefromthenet/Migrations) - 迁移管理图书馆.
* [Phinx](https://github.com/cakephp/phinx) - 另一个图书馆数据库迁移.
* [PHPMig](https://github.com/davedevelopment/phpmig) - 另一个迁移管理图书馆.
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - 数据库迁移ala ActiveRecord迁移支持MySQL, PHP Postgres
  SQLite.

### NoSQL

*处理NoSQL后端的库.*

* MongoDB
    * [MongoDB](https://github.com/mongodb/mongo-php-driver) - MongoDB PHP驱动程序.
    * [mongo-php-library](https://github.com/mongodb/mongo-php-library) - MongoDB 官方PHP库
    * [MongoQB](https://github.com/alexbilbie/MongoQB) - 一个MongoDB的查询构建库
    * [Monga](https://github.com/thephpleague/monga) - 一个MongoDB的抽象库
    * [mongodm](https://github.com/purekid/mongodm) - 一个MongoDB ORM
    * [PHPMongo](https://github.com/sokil/php-mongo) - 一个MongoDB ORM.
* Redis
    * [Predis](https://github.com/predis/predis) - 一个功能完整的复述,图书馆.
    * [codis](https://github.com/CodisLabs/codis) - Codis 是一个分布式 Redis 解决方案
    * [twemproxy](https://github.com/twitter/twemproxy) - 是twtter开源的一个redis和memcache代理服务器
    * [pika](https://github.com/Qihoo360/pika) - Pika是一个可持久化的大容量redis存储服务
* ClickHouse
    * [smi2/phpClickHouse](https://github.com/smi2/phpClickHouse) - php ClickHouse(列式数据库) wrapper

### 队列 Queue

*来处理事件和任务队列的库。*

* [Bernard](https://github.com/bernardphp/bernard) - multibackend抽象库.
* [BunnyPHP](https://github.com/jakubkulhan/bunny) - 一个高性能pure-PHP AMQP (RabbitMQ)同步和异步(ReactPHP)图书馆.
* [Pheanstalk](https://github.com/pheanstalk/pheanstalk) - 一个Beanstalkd客户端库.
* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - 一个纯PHP AMQP库.
* [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP绑定Tarantool队列.
* [Thumper](https://github.com/php-amqplib/Thumper) - RabbitMQ模式库.
* [Enqueue](https://github.com/php-enqueue/enqueue-dev) - 消息队列包为PHP支持RabbitMQ AMQP,跺脚,Amazon SQS,复述和教义传输.

### 搜索 Search

*库和软件上执行搜索查询索引和数据。*

* [Elastica](https://github.com/ruflin/Elastica) - ElasticSearch的客户端库.
* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) -
  官方客户端库[ElasticSearch] (https://www.elastic.co/).
* [Solarium](https://www.solarium-project.org/) - (Solr) (https://solr的客户端库.apache.org/).
* [Solarium](https://www.solarium-project.org/) - (Solr) (https://solr的客户端库.apache.org/).
* [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - (Sphinx)
  查询图书馆(https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) 搜索引擎.
* [Tntsearch](https://github.com/teamtnt/tntsearch/) - 纯 PHP 实现的全文搜索引擎.

### 命令行 Command Line

*库相关的命令行。*

* [Aura.Cli](https://github.com/auraphp/Aura.Cli) -提供请求(上下文)和响应(Stdio)对象用于命令行接口，包括Getopt支持，以及用于的独立Help对象
  描述命令
* [Boris](https://github.com/borisrepl/boris) - 一个微小的PHP REPL.
* [Cilex](https://github.com/Cilex/Cilex) - 一个微型的框架来构建命令行工具.
* [CLI Menu](https://github.com/php-school/cli-menu) - 图书馆建设CLI菜单.
* [CLIFramework](https://github.com/c9s/CLIFramework) - 命令行框架支持zsh和bash完成生成,子命令和选项约束. It also powers
  phpbrew.
* [CLImate](https://github.com/thephpleague/climate) - 库输出颜色和特殊的格式.
* [Commando](https://github.com/nategood/commando) - 另一个简单的命令行解析器.
* [Cron Expression](https://github.com/mtdowling/cron-expression) - 图书馆计算cron运行日期.
* [GetOpt](https://github.com/getopt-php/getopt-php) - A command line opt parser.
* [GetOptionKit](https://github.com/c9s/GetOptionKit) - 另一个命令行选择解析器.
* [PsySH](https://github.com/bobthecow/psysh) - 另一个PHP REPL.
* [ShellWrap](https://github.com/MrRio/shellwrap) - 一个简单的命令行包装器库.

### 身份验证和授权 Authentication and Authorization

*图书馆实现用户身份验证和授权。*

* [Aura.Auth](https://github.com/auraphp/Aura.Auth) - 使用各种适配器提供了身份验证功能和会话跟踪.
* [SocialConnect Auth](https://github.com/socialConnect/auth) - 一个开源的社会符号(OAuth1 \ OAuth2 \ OpenID \
  OpenIDConnect).
* [Json Web Token](https://github.com/lcobucci/jwt) - Json令牌验证和传递信息.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - OAuth 1.0 client library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - OAuth 2.0 client library.
* [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - 另一个OAuth2服务器实现.
* [OAuth2 Server](https://oauth2.thephpleague.com/) - 一个OAuth2身份认证服务器,资源服务器和客户端库.
* [Opauth](https://github.com/opauth/opauth) - multi-provider认证框架.
* [Paseto](https://github.com/paragonie/paseto) - 平台无关的安全令牌.
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - 另一个OAuth库.
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - 图书馆对社会网络身份验证.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - 一个框架不可知论者的身份验证.
* [TwitterOAuth](https://github.com/abraham/twitteroauth) - 一个Twitter OAuth图书馆.

### 标记和CSS Markup and CSS

*用于处理标记和CSS格式的库*.

* [Cebe Markdown](https://github.com/cebe/markdown) - 一个快速和可扩展的减价解析器.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - 高度可扩展的减价解析器,完全支持(
  CommonMark规范)(https://spec.commonmark.org/).
* [Decoda](https://github.com/milesj/decoda) - 一个轻量级标记解析器库.
* [Essence](https://github.com/essence/essence) - 库中提取网络的媒体.
* [Embera](https://github.com/mpratt/Embera) - 一个消费者Oembed库.
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - 将HTML转换为Markdown.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - HTML5解析器和序列化器库.
* [Parsedown](https://github.com/erusev/parsedown) - 另一个减价解析器.
* [PHP CSS Parser](https://github.com/sabberworm/PHP-CSS-Parser) - 用PHP编写的一个CSS文件解析器.
* [PHP Markdown](https://github.com/michelf/php-markdown) - 减价解析器.
* [Shiki PHP](https://github.com/spatie/shiki-php) - A [Shiki](https://github.com/shikijs/shiki) 代码高亮显示 PHP中的包.
* [VObject](https://github.com/sabre-io/vobject) - 一个库解析电子名片和iCalendar对象.

### JSON

*处理JSON库*

* [JSON Lint](https://github.com/Seldaek/jsonlint) - 一个JSON线头效用.
* [JSONMapper](https://github.com/JsonMapper/JsonMapper) - JSON库映射到PHP对象.

### 字符串 Strings

*库解析和操作字符串。*

* [Agent](https://github.com/jenssegers/agent) - 一个PHP桌面/移动用户代理解析器,基于Mobiledetect.
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - 一个ANSI到HTML5的转换库.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - 一个图书馆操纵和转换颜色.
* [Device Detector](https://github.com/matomo-org/device-detector) - 另一个库解析用户代理字符串.
* [Jieba-PHP](https://github.com/fukuball/jieba-php) - 一个PHP Python的jieba港. 中文文本分词为自然 语言处理.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - 一个轻量级的PHP类检测移动设备(包括平板电脑).
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - 一个可移植的库来处理utf - 8编码的字符串.
* [Portable ASCII](https://github.com/voku/portable-ascii) - 图书馆将字符串转换为ascii.
* [Portable UTF-8](https://github.com/voku/portable-utf8) - 一个字符串处理库与utf - 8安全的替代方法.
* [Slugify](https://github.com/cocur/slugify) - 将字符串转换成蛞蝓的图书馆.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - 一个图书馆格式化SQL语句.
* [Stringy](https://github.com/voku/Stringy) - 与多字节字符串处理库的支持.
* [T-Regx](https://github.com/T-Regx/T-Regx) - 一个高级的正则表达式库，消除了PHP的陷阱.
* [PHPVerbalExpressions](https://github.com/VerbalExpressions/PHPVerbalExpressions) - 更优雅的书写正则方式，就像 SQL
  Builder 一样.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - 库解析用户代理字符串.
* [URLify](https://github.com/jbroadway/urlify) - 一个PHP Django的URLify港.js.
* [UUID](https://github.com/ramsey/uuid) - 一个库生成uuid.
* [Pinyin](https://github.com/overtrue/pinyin) - 基于 mozillazg/pinyin-data 词典的中文转拼音工具，更准确的支持多音字的汉字转拼音解决方案。.
* [VicWord](https://github.com/lizhichao/VicWord) - 一个纯php的分词.
* [Emoji](https://github.com/spatie/emoji) - 以编程方式使用表情符号字符

### 数字 Numbers

*与数字有关的php库*

* [Brick\Math](https://github.com/brick/math) - 图书馆提供大量支持:先导入BigInteger’’,‘BigDecimal’和‘BigRational’.
* [ByteUnits](https://github.com/gabrielelana/byte-units) - 库来解析,在二进制格式和转换字节单位和公制系统.
* [DecimalObject](https://github.com/spryker/decimal-object) - 一个值对象来处理小数/浮动容易和更准确.
* [IP](https://github.com/darsyn/ip) - 一个不可变的值对象使用IPv4和IPv6地址.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - 一个PHP实现谷歌的电话号码处理库.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - 另一个库之间的转换单位的措施.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - 一个图书馆的计量单位之间的转换.
* [MathPHP](https://github.com/markrogoyski/math-php) - PHP数学库.
* [Belt](https://github.com/ilya-dev/belt) - 工具函数库.

### 过滤和验证 Filtering and Validation

*库筛选和验证数据。*

* [Assert](https://github.com/beberlei/assert) - 与一组丰富的断言验证库. 支持断言链接和延迟断言
* [Aura.Filter](https://github.com/auraphp/Aura.Filter) - 提供了一些工具来验证和清洁对象和数组.
* [CakePHP Validation](https://github.com/cakephp/validation) - 另一个验证库.
* [Filterus](https://github.com/ircmaxell/filterus) - 一个简单的PHP筛选库.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - 图书馆为验证输入从ISO标准,国际金融,公共管理,GS1,图书行业,电话号码.
* [JSON Schema](https://github.com/justinrainbow/json-schema) - 一个JSON模式(https://json-schema.org/) 验证库.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - 一个模式验证库,支持YAML、JSON和XML.
* [Respect Validation](https://github.com/Respect/Validation) - 一个简单的验证库.
* [Upload](https://github.com/brandonsavage/Upload) - 一个库来处理文件上传和验证.
* [Valitron](https://github.com/vlucas/valitron) - 另一个验证库.
* [Volan](https://github.com/serkin/Volan) - 另一个简化的验证库.

### API

*图书馆和网络工具开发api。*

* [API Platform](https://api-platform.com ) - 在几分钟内公开一个包含JSON-LD、Hydra的超媒体REST API 格式.
* [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) - 一个API builder构建与计算框架.
* [Drest](https://github.com/leedavis81/drest) - 为揭露教条实体图书馆REST资源端点.
* [HAL](https://github.com/blongden/hal) - 超文本应用程序语言(HAL)构建器库.
* [Hateoas](https://github.com/willdurand/Hateoas) - 一个HATEOAS REST web服务库.
* [Jane](https://github.com/janephp/janephp/) - 一个OpenApi客户端发电机与验证支持.
* [Negotiation](https://github.com/willdurand/Negotiation) - 内容协商库.
* [Restler](https://github.com/Luracast/Restler) - 一个轻量级的框架,使PHP方法基于rest的web API.
* [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - 一个工具来从SOAP WSDL文件生成PHP类.

### 缓存和锁定 Caching and Locking

*库缓存数据和获取锁。*

* [APIx Cache](https://github.com/apix/cache) - 一层薄薄的PSR-6缓存包装各种缓存后端强调缓存标签和索引.
* [CacheTool](https://github.com/gordalina/cachetool) - 一个工具清除APC /从命令行操作码缓存.
* [CakePHP Cache](https://github.com/cakephp/cache) - 缓存库.
* [Doctrine Cache](https://github.com/doctrine/cache) - 缓存库.
* [Metaphore](https://github.com/sobstel/metaphore) - 缓存大满贯防御使用信号量,防止dogpile效果.
* [Stash](https://github.com/tedious/Stash) - 缓存的另一个库.
* [Laminas Cache](https://github.com/laminas/laminas-cache) - 另一个缓存库.
* [Lock](https://github.com/php-lock/lock) - 一个锁库提供独家的执行.

### 数据结构和存储 Data Structure and Storage

*库实现的数据结构和存储技术。*

* [CakePHP Collection](https://github.com/cakephp/collection) - 一个简单的集合库.
* [Fractal](https://github.com/thephpleague/fractal) - 图书馆将复杂的数据结构转换为JSON输出.
* [Ginq](https://github.com/akanehara/ginq) - 另一个基于PHP库.NET's LINQ.
* [JsonMapper](https://github.com/cweiske/jsonmapper) - 库映射到PHP类嵌套的JSON结构.
* [JSON Machine](https://github.com/halaxa/json-machine) - 使用simple . json在巨大的json上提供迭代 `foreach`
* [Knapsack](https://github.com/DusanKasan/Knapsack) - 收集图书馆受Clojure的序列.
* [msgpack.php](https://github.com/rybakit/msgpack.php) - 一个纯PHP实现的[MessagePack] (https://msgpack.org/) 序列化 格式。
* [PINQ](https://github.com/TimeToogo/Pinq) - 一个基于PHP库.NET's LINQ (Language Integrated Query).
* [Serializer](https://github.com/schmittjoh/serializer) - 图书馆的连载和de-serialising数据.
* [YaLinqo](https://github.com/Athari/YaLinqo) - 另一个LINQ为PHP对象.
* [PHP Option](https://github.com/schmittjoh/php-option) - 一个PHP选项类型的库
* [Laminas Serializer](https://github.com/laminas/laminas-serializer) - 另一个图书馆连载和de-serialising数据.
* [Compose](https://github.com/igorw/compose) - 一个功能组合库
* [Monad PHP](https://github.com/ircmaxell/monad-php) - 一个简单Monad库
* [Galapagos](https://github.com/endel/galapagos) - 语言转换进化
* [Lib Accessor](https://github.com/phine/lib-accessor) - 一个简化访问的库
* [laracasts/Laravel-5-Generators-Extended](https://github.com/laracasts/Laravel-5-Generators-Extended) - Laracasts
  出品的代码快速生成工具

### 通知 Notifications

*库处理通知软件。*

* [JoliNotif](https://github.com/jolicode/JoliNotif) - 用于桌面通知的跨平台库(支持 咆哮，通知-发送，烤面包机等)
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - 一个独立的库设备推送通知.
* [Notificato](https://github.com/mac-cain13/notificato) - 一个库来处理推送通知.
* [Notificator](https://github.com/namshi/notificator) - 一个轻量级的通知图书馆.
* [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - PHP库轻松地发送推送通知Pushwoosh REST Web服务.
* [ApnsPHP](https://github.com/immobiliare/ApnsPHP) - 一整套开源的PHP类与iPhone、iPad和iPod Touch的苹果推送通知服务互动。.

### 部署 Deployment

*库项目部署。*

* [Deployer](https://github.com/deployphp/deployer) - 部署工具.
* [Envoy](https://github.com/laravel/envoy) - 一个用PHP运行SSH任务的工具.
* [Rocketeer](https://github.com/rocketeers/rocketeer) - 快速和容易部署PHP的世界.

### 国际化和本土化 Internationalisation and Localisation

*图书馆为国际化(I18n)和本地化(L10n)。*

* [Aura.Intl](https://github.com/auraphp/Aura.Intl) - 提供国际化(I18N)工具,特别是package-oriented per-locale消息翻译.
* [CakePHP I18n](https://github.com/cakephp/i18n) - 消息翻译和本地化的日期和数字.

### 无服务器的 Serverless

*库和工具帮助建立serverless web应用程序。*

* [Bref](https://bref.sh/) - 在AWSλServerless PHP.
* [OpenWhisk](https://openwhisk.apache.org/) - 一个开源serverless云平台.
* [Serverless Framework](https://www.serverless.com/framework) - 一个开源框架构建serverless应用程序.
* [Laravel Vapor](https://vapor.laravel.com/) - Laravel serverless部署平台,由AWS.
* [AWSGoat](https://github.com/ine-labs/AWSGoat) - AWSGoat是AWS上的一个设计脆弱的基础设施.

## 配置 Configuration

*对配置库和工具。*

* [PHP Dotenv](https://github.com/vlucas/phpdotenv) - 解析和加载环境变量的.env` files.
* [Symfony Dotenv](https://github.com/symfony/dotenv)- 解析并加载环境变量.env的文件。
* [Yo! Symfony TOML](https://github.com/yosymfony/toml) - 一个PHP解析器(TOML) (https://github.com/toml-lang/toml).
* [Yaconf](https://github.com/laruence/yaconf) - 一个高性能的配置管理扩展
* [config](https://github.com/hassankhan/config) - 一个轻量级的配置加载器, 支持 PHP, INI, XML, JSON, YAML files
* [Zend-config](https://github.com/zendframework/zend-config)
* [symfony/yaml](https://github.com/symfony/yaml) - 加载和剥离YAML配置文件.

### 第三方api Third Party APIs

*库访问第三方api。*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - 官方PHP AWS SDK库.
* [AsyncAWS](https://async-aws.com/) - 一个非官方的异步PHP AWS SDK.
* [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - 官方活动监控PHP库.
* [Github](https://github.com/KnpLabs/php-github-api) - 一个图书馆和Github API接口.
* [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
* [Square](https://github.com/square/connect-php-sdk) - 官方的方形PHP SDK的支付和其他api.
* [Stripe](https://github.com/stripe/stripe-php) - 官方的条纹PHP库.
* [Twilio](https://github.com/twilio/twilio-php) - 官方为什么Twilio PHP REST API.
* [Notion](https://github.com/brd6/notion-sdk-php/) - 用于概念API的PHP库.
* [GeoIP2-php](https://github.com/maxmind/GeoIP2-php) - MaxMind GeoIP2 地理位置服务
* [mgp25/Instagram-API](https://github.com/mgp25/Instagram-API) - Instagram的私有 API
* [maknz/slack](https://github.com/maknz/slack) - Slack 服务的集成
* [Twitter-sdk](https://github.com/lyrixx/twitter-sdk) - 一个经过完全测试的Twitter SDK
* [Twitter](https://github.com/thujohn/twitter) - Twitter API 的支持
* [overtrue/weather](https://github.com/overtrue/weather) - 基于高德开放平台接口的 PHP 天气信息组件
* [中国的一些库]
    - [Wechat](https://github.com/overtrue/wechat) - 让微信开发更简单
    - [Qiniu/sdk](https://github.com/qiniu/php-sdk) - 七牛云资源存储SDK for PHP
    - [Qiniu/qshell](https://github.com/qiniu/qshell) - qshell是利用七牛文档上公开的API实现的一个方便开发者测试和使用七牛API服务的命令行工具。
    - [Tencentyun/wafer](https://github.com/tencentyun/wafer) - 快速构建具备弹性能力的微信小程序
    - [PingPlusPlus/pingpp-php](https://github.com/PingPlusPlus/pingpp-php) - ping++聚合支付SDK
    - [aliyun/aliyun-oss-php-sdk](https://github.com/aliyun/aliyun-oss-php-sdk) - 阿里云对象存储
    - [aliyun/openapi-sdk-php](https://github.com/aliyun/openapi-sdk-php) - 阿里云 SDK for PHP
    - [overtrue/laravel-filesystem-qiniu](https://github.com/overtrue/laravel-filesystem-qiniu) - Laravel filesystem
      七牛云的文件存储
    - [jacobcyl/Aliyun-oss-storage](https://github.com/jacobcyl/Aliyun-oss-storage) - 阿里云OSS laravel扩展
    - [overtrue/easy-sms](https://github.com/overtrue/easy-sms) - 满足多种发送需求的短信发送组件
    - [mingyoung/dingtalk](https://github.com/mingyoung/dingtalk) - 钉钉 SDK
    - [wowiwj/ding-notice](https://github.com/wowiwj/ding-notice) - 钉钉推送机器人消息发送laravel扩展包
    - [Easytbk](https://github.com/flutterbest/easytbk) - 淘宝联盟、京东联盟、多多进宝、唯享客、苏宁推客SDK封装。
      仅支持laravel5-laravel8，这不是可以直接拿来用的返利系统。

### 扩展 Extensions

*图书馆帮助建立PHP扩展。*

* [PHP CPP](https://www.php-cpp.com/) - 开发PHP扩展的C库.
* [Zephir](https://github.com/zephir-lang/zephir ) - 编译语言PHP开发PHP扩展和C之间.
* [PHP-X](https://github.com/swoole/PHP-X) - Zend API的C++封装器.

### 杂项 Miscellaneous

*有用的库或工具不符合上面的类别。*

* [Annotations](https://github.com/doctrine/annotations) - 一个注释库(教义的一部分).
* [BotMan](https://github.com/botman/botman) - 不可知论者PHP库框架构建跨平台聊天机器人.
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - 为优化半自动的图书馆.
* [Hprose-PHP](https://github.com/hprose/hprose-php) - 一个跨语言的RPC.
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - 帮助谷歌noCAPTCHA(说的).
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - 一个分页库.
* [Safe](https://github.com/thecodingmachine/safe) - 所有的PHP函数,重写抛出异常,而不是返回false.
* [SuperClosure](https://github.com/jeremeamia/super_closure) - 一个库,允许闭包进行序列化.
* [RTCKit/SIP](https://github.com/rtckit/php-sip) - 一个符合RFC 3261的SIP解析/渲染库.
* [DeepCopy](https://github.com/myclabs/DeepCopy) - DeepCopy 可以帮助您创建对象的深度副本(克隆)。它被设计用于处理关联图中的循环.
* [php-helper](https://github.com/kakuilan/php-helper) - php 常用函数库/工具集,仅测试支持php 7.2/7.3/7.4/8.0.

# 软件 Software

*创建一个软件开发环境。*

### PHP安装 PHP Installation

*工具来帮助PHP在您的计算机上安装和管理。*

* [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher) - 酿造PHP切换器.
* [HomeBrew](https://brew.sh/) - OSX的包管理器.
* [Laravel Valet](https://laravel.com/docs/master/valet) - macOS的开发环境.
* [PHP Brew](https://github.com/phpbrew/phpbrew) - 一个PHP版本管理器和安装程序.
* [PHP Build](https://github.com/php-build/php-build) - 另一个PHP版本的安装程序.
* [PHP OSX](https://php-osx.liip.ch/) - OSX的PHP安装程序.

### 开发环境 Development Environment

*软件和工具用于创建和共享一个开发环境。*

* [Ansible](https://www.ansible.com/) - 一个彻底的简单的编制框架.
* [Docker](https://www.docker.com/) - 一个集装箱化平台.
* [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer) - 很容易在集装箱码头工人安装PHP扩展.
* [Expose](https://github.com/beyondcode/expose) - 一个开源的PHP隧道服务.
* [Lando](https://lando.dev/) - 自动化的开发环境.
* [Laravel Homestead](https://laravel.com/docs/master/homestead) - Laravel本地开发环境.
* [Laradock](http://laradock.io/) - 一个完整的PHP开发环境基于码头工人.
* [Puppet](https://puppet.com/) - 一个服务器自动化框架和应用程序.
* [Takeout](https://github.com/tighten/takeout) - 一个Docker-based发展依赖管理器.
* [Vagrant](https://www.vagrantup.com/) - 一个便携式开发环境工具.
* [ddev](https://github.com/drud/ddev) - 用于PHP的本地web开发环境系统.
* [devilbox](https://github.com/cytopia/devilbox) - 用于本地开发的现代Docker LAMP堆栈和MEAN堆栈.
* [docksal](https://github.com/docksal/docksal) - 统一的Docker:whale:支持macOS、Windows和Linux的web开发环境.

### 虚拟机 Virtual Machines and Compilers

*可选的PHP虚拟机.*

* [Hack](https://hacklang.org/) - 一种用于HHVM的编程语言.
* [HHVM](https://github.com/facebook/hhvm) - 一个虚拟机,为PHP运行时和JIT Facebook.
* [PeachPie](https://github.com/peachpiecompiler/peachpie) - PHP编译器和运行时.NET and .NET Core.
* [KPHP](https://github.com/VKCOM/kphp) - 将PHP转换为c++和c++运行时的编译器.

### 文本编辑器和ide Text Editors and IDEs

*文本编辑器和集成开发环境(IDE)支持PHP。*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - 一个PHP IDE基于Eclipse平台.
* [Apache NetBeans](https://netbeans.apache.org/) - 支持PHP和HTML5的IDE.
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - 一个商业PHP IDE.
* [VS Code](https://code.visualstudio.com/) - 一个开源的代码编辑器.

### Web应用程序 Web Applications

*基于web的应用程序和工具。*

* [3V4L](https://3v4l.org/) - 一个在线PHP & HHVM shell.
* [Adminer](https://www.adminer.org/) - 数据库管理在一个PHP文件.
* [Cachet](https://github.com/cachethq/cachet) - 开源系统状态页.
* [DBV](https://github.com/victorstanciu/dbv) - 数据库版本控制的应用程序.
* [Lychee](https://github.com/electerious/Lychee) - 一个易于使用的和漂亮的photo-management-system.
* [MailCatcher](https://github.com/sj26/mailcatcher) - web工具来捕获和查看电子邮件.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - MySQL / MariaDB的web界面.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - 一个应用程序来管理队列的后端.
* [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - 一个简单的web界面来管理(复述)(https://redis.io/)
  databases.
* [PHPSandbox](https://phpsandbox.io) - 一个在线的PHP IDE浏览器.

### 基础设施 Infrastructure

*基础设施提供PHP应用程序和服务。*

* [appserver.io](https://github.com/appserver-io/appserver) - 多线程应用程序服务器的PHP,用PHP编写的.
* [kubephp](https://github.com/sherifabdlnaby/kubephp) - 用于云本地部署的生产级、无根和优化的PHP容器映像模板.
* [php-pm](https://github.com/php-pm/php-pm) - 进程管理器,增压器和PHP应用程序的负载平衡器.
* [RoadRunner](https://github.com/roadrunner-server/roadrunner) - 高性能的PHP应用程序服务器、负载平衡器和过程管理.

# 资源 Resources

各种资源，如书籍、网站和文章，用于提高您的PHP开发技能和知识。

### PHP的网站 PHP Websites

*有用与php相关的网站。*

* [libs.garden: PHP](https://libs.garden/php) - 增长最快的概述PHP库.
* [Nomad PHP](https://nomadphp.com/) - 一个PHP在线学习资源.
* [Laravel News](https://laravel-news.com/) - Laravel官方博客.
* [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - 每月消化PHP的消息.
* [PHP Best Practices](https://phpbestpractices.org/) - 一个PHP最佳实践指南.
* [PHP FIG](https://www.php-fig.org/) - PHP开发框架的互操作性.
* [PHP Package Development Standards](http://php-pds.com) - 包为PHP开发标准.
* [PHP School](https://www.phpschool.io/) - PHP开源学习.
* [PHP Security](https://phpsecurity.readthedocs.io/en/latest/index.html) - PHP安全指南.
* [PHP The Right Way](https://phptherightway.com/) - 一个PHP最佳实践快速参考指南.
* [PHP UG](https://php.ug) - 一个网站,帮助人们找到他们最近的PHP用户组(UG).
* [PHP Versions](http://phpversions.info/) - 列出可用的版本的PHP在几个流行的web主机.
* [PHP Watch](https://php.watch/) - PHP的文章,新闻,即将到来的变化,rfc等等.
* [PHP Weekly](https://www.phpweekly.com/archive.html) - PHP每周时事通讯.
* [Seven PHP](https://7php.com/) - 一个网站,访问PHP社区的成员.
* [PHPTrends](http://phptrends.com/) - 一些快速发展的PHP类库检索

### PHP的书 PHP Books

*奇妙与php相关的书籍。*

* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - 用PHP编写的实际例子展示DDD建筑风格.
* [Functional Programming in PHP](https://www.functionalphp.com/) - 这本书将告诉你如何利用这些新PHP5.3+ features by
  understanding
  functional programming principles
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](https://www.brandonsavage.net/) - 一本关于面向PHP布兰登野蛮.
* [Modern PHP New Features and Good Practices](https://www.oreilly.com/library/view/~/9781491905173/) -
  一本关于Josh洛克哈特新的PHP特性和最佳实践.
* [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - 一本关于现代化遗留PHP应用程序由保罗·M. Jones.
* [PHP 7 Upgrade Guide](https://leanpub.com/php7) - 电子书覆盖的所有功能和PHP的变化由Colin O 'Dell 7.
* [PHP Pandas](https://daylerees.com/php-pandas/) - 一本关于学习的书编写PHP黛尔里斯.
* [Scaling PHP Applications](https://www.scalingphpbook.com) - 电子书对扩展PHP应用程序由史蒂夫电晕.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - 一本关于共同安全条款和实践由Chris
  Cornutt PHP.
* [Signaling PHP](https://leanpub.com/signalingphp) - 一本关于捕捉PCNTL信号在CLI脚本由卡尔埃文斯.
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - Chris
  Hartjes写的关于构建测试PHP应用程序的书.
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) -
  这本书涵盖了解析和验证XML文档,使用XPath表达式,使用名称空间以及如何通过编程方式创建和修改XML文件.

### PHP的视频 PHP Videos

*奇妙与php相关的视频。*

* [Nomad PHP Lightning Talks](https://www.youtube.com/c/nomadphp) - 10到15分钟闪电会谈由PHP社区成员.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - 一组来自英国PHP的视频会议.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - 安东尼·费拉拉的视频系列.
* [Taking PHP Seriously](https://www.infoq.com/presentations/php-history/) - 演讲概述了PHP的优势基斯·亚当斯的Facebook.
* [Laracasts](https://laracasts.com) - 演示对Laravel, Vue JS和更多.
* [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - 官方Laravel YouTube频道.
* [SymfonyCasts](https://symfonycasts.com/) - 关于PHP和Symfony视频和教程.

### PHP播客 PHP Podcasts

*播客和专注于PHP的话题。*

* [Laravel Podcast](https://laravelpodcast.com/) - Laravel和PHP开发的新闻和讨论.
* [PHP Internals News](https://phpinternals.news) - 一个关于PHP内部播客.
* [PHP Roundtable](https://phproundtable.com/) - PHP圆桌会议是PHP开发人员讨论主题的休闲聚会书呆子关心.
* [PHP Town Hall](https://phptownhall.com/) - 随意的PHP播客由本·埃德蒙兹和菲尔鲟鱼.
* [Voices of the ElePHPant](https://voicesoftheelephpant.com/) - 对使PHP社区变得特别的人的采访.

### PHP通讯 PHP Newsletters

*与php相关消息直接发送到您的收件箱中。*

* [PHP Weekly](https://www.phpweekly.com/) - 关于PHP每周时事通讯.

### PHP阅读 PHP Reading

*与php相关的阅读材料。*

* [php[architect]](https://www.phparch.com/magazine/) - 每月杂志致力于PHP.
* [advanced-php](https://github.com/elarity/advanced-php) - PHP多进程、socket等相关文章
* [LEARN REGEX THE EASY WAY](https://github.com/ziishaned/learn-regex/blob/master/translations/README-cn.md) - 正则表达式学习
* [The Linux Command Line](http://linuxcommand.org/) - Linux 命令行教程
* [architecture.of.internet-product](https://github.com/davideuler/architecture.of.internet-product) - 互联网公司技术架构
* [architect-awesome](https://github.com/xingshaocheng/architect-awesome) - 后端架构师技术图谱

### PHP内部阅读 PHP Internals Reading

*PHP内部或阅读材料相关性能。*

* [PHP RFCs](https://wiki.php.net/rfc) - PHP的家rfc(注释请求).
* [Externals](https://externals.io/) - PHP内部讨论.
* [PHP RFC Watch](https://php-rfc-watch.beberlei.de/) - 观看最新PHP (rfc) (https://wiki.php.net/rfc).
* [PHP Internals Book](https://www.phpinternalsbook.com/) - 在线图书对PHP内部,由三个核心开发人员写的.

