Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Laravel 5](#laravel-5)
- [Lumen](#lumen)
- [Code Snippets](#code-snippets)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Articles, Tutorials, Blogs etc.](#articles-tutorials-blogs-etc)
- [Video Tutorials](#video-tutorials)
- [Conferences](#conferences)
- [Books](#books)
- [Codebases for Reference](#codebases-for-reference)
- [Jobs](#jobs)
- [Miscellaneous](#miscellaneous)

## Essentials
* [Documentation](http://laravel.com/docs)
* [API Reference](http://laravel.com/api/)
* [Laracasts](http://laracasts.com)
* [Laravel News](http://laravel-news.com/)

## Laravel 5
*Released on 4th February, 2015*
* Laravel 5 Fundamentals - [Laracasts](https://laracasts.com/series/laravel-5-fundamentals)
* New Features in Laravel 5 - [Laracasts](https://laracasts.com/series/whats-new-in-laravel-5) and [Matt Stauffer's blog](http://mattstauffer.co/tags/laravel+5)
* Release Notes - [Laravel.com](http://laravel.com/docs/master/releases) and [Laravel News](https://laravel-news.com/2015/01/laravel-5/)
* Upgrade Guide - [Laravel.com](http://laravel.com/docs/master/upgrade) and [Matt Stauffer](http://mattstauffer.co/blog/upgrading-from-laravel-4-to-laravel-5)
* Learn Laravel 5 From Scratch - [Laracasts](https://laracasts.com/series/laravel-5-from-scratch)
* Learn Laravel 5 in Spanish [duilio.me](http://duilio.me/laravel-5/)

## Lumen
*Released on 14th April, 2015*
* [Introduction](https://laracasts.com/lessons/introducing-lumen) (Laracasts)
* [Documentation](http://lumen.laravel.com/docs/installation)

## Code Snippets
* [Laravel Cheat Sheet](http://cheats.jesse-obrien.ca)
* [Laravel Tricks](http://www.laravel-tricks.com/)
* [Laravel Recipies](http://laravel-recipes.com/)
* [Laravel Snippets](http://laravelsnippets.com/)

## Packages
* [Packagist](https://packagist.org/)
* [Laravel Collective](http://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Cartalyst](https://cartalyst.com/)

## Popular Packages
> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) -  Extends built-in file generators
* [Laravel API/Scaffold/CRUD Generator](https://github.com/mitulgolakiya/laravel-api-generator) - Generator for APIs, CRUD scaffolds etc.

##### Debugging & Profiling
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer

##### Authentication & Authorisation
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server
* [Sentinel](https://github.com/cartalyst/sentinel) - Framework agnostic authentication & authorization system
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc.
* [Socialite Providers](http://socialiteproviders.github.io/) - 70+ social authentication providers for Socialite

##### Utilities
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Datatable](https://github.com/Chumper/Datatable) - Server-side and client-side integration for jQuery Datatables plugin
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models
* [HTML](https://github.com/LaravelCollective/html) - Official HTML and Form Builders for Laravel
* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs
* [Laravel Dot Env Generator](https://github.com/mathiasgrimm/laravel-dot-env-gen) - Generate .env.gen file based on the project source code
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files
* [Laravel Hashids](https://github.com/vinkla/hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up a Laravel app by caching the entire response
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command for Laravel 5
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models
* [SEOTools](https://github.com/artesaos/seotools) - SEOTools - SEO Tools for Laravel and Lumen
* [Setting](https://github.com/Phil-F/Setting) - Persistent configuration settings that are stored in JSON files
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models

##### Working with Javascript
* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) -  Pass server-side string/array/collection/whatever to JavaScript

##### Database, Migrations & Seeding
* [Backup Manager](https://github.com/backup-manager/laravel) - Backup to and restore databases from S3, Dropbox, SFTP etc.
* [Baum](https://github.com/etrepat/baum) - Nested Sets pattern implementation
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel Backup](https://github.com/spatie/laravel-backup) - A package to backup your Laravel 5 app
* [Laravel Doctrine](https://github.com/mitchellvanw/laravel-doctrine) - Doctrine 2 ORM implementation for Laravel
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager

##### Search
* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models

##### APIs
* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support

##### Tasks, Commands and Scheduling
* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands
* [Elixr](https://github.com/laravel/elixir) - Node(NPM) package to run Gulp tasks that watch files, run tests, minify CSS, concatenate scripts etc.
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner

##### Payments
* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/omnipay/omnipay) PHP library

##### Optimization
* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier

##### Localization
* [Language Files](https://github.com/caouecs/Laravel4-lang) - Validation, Pagination and Reminders language lines in 37 languages
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances
* [Laravel Translator](https://github.com/vinkla/translator) - Translate Eloquent models into multiple languages

##### Third-party Service Integration
* [Laravel Algolia](https://github.com/vinkla/algolia) - Algolia API bridge
* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - An opinionated Laravel 5 package to retrieve pageviews and other data from Google Analytics
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge
* [Laravel Dropbox](https://github.com/GrahamCampbell/Laravel-Dropbox) - Dropbox bridge
* [Laravel Facebook](https://github.com/schimpanz/Laravel-Facebook) - Facebook API bridge
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge
* [Laravel GitLab](https://github.com/vinkla/gitlab) - GitLab API bridge
* [Laravel Googletagmanager](https://github.com/spatie/laravel-googletagmanager) - Easily setup and send data to Google Tag Manager
* [Laravel Instagram](https://github.com/vinkla/instagram) - Instagram API bridge
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp
* [Laravel Parse](https://github.com/GrahamCampbell/Laravel-Parse) - PHP Parse SDK bridge
* [Laravel Pusher](https://github.com/vinkla/pusher) - Pusher API bridge
* [Laravel Pushwoosh](https://github.com/schimpanz/Laravel-Pushwoosh) - Pushwoosh API bridge
* [Laravel Vimeo](https://github.com/vinkla/vimeo) - Vimeo API bridge


## Development Setup
* [Homestead](http://laravel.com/docs/homestead) - Official Vagrant box for Laravel
  * [Getting Started with Laravel Homestead](http://scotch.io/tutorials/php/getting-started-with-laravel-homestead)
  * [Installation on OSx and Linux](https://laracasts.com/series/laravel-5-from-scratch/episodes/3)
  * [Installation on  Windows](http://blog.teamtreehouse.com/laravel-homestead-on-windows)
* Install Laravel with Composer
 * [Windows](https://www.youtube.com/watch?v=m3D894qZKws)
 * [Mac OSX or Linux](https://laracasts.com/lessons/laravel-installation-for-newbs)

## Application Hosting
* [Forge](https://forge.laravel.com/) - Provision optimized PHP servers on Linode, DigitalOcean etc.
  * [Server Management with Forge](https://laracasts.com/series/server-management-with-forge) (Laracasts)
  * [Getting your first site up and running in Laravel Forge](http://mattstauffer.co/blog/getting-your-first-site-up-and-running-in-laravel-forge) (Matt Stauffer)
  * [ForgeRecipes](http://forgerecipes.com/)
* [FortRabbit](http://fortrabbit.com/solutions/laravel-hosting) ([Video](https://laracasts.com/lessons/from-zero-to-deploy-with-fortrabbit))
* [PagodaBox](https://pagodabox.io/) ([Documentation](https://pagodabox.io/docs/framework_laravel))
* [Heroku](https://www.heroku.com/) ([Tutorial](http://mattstauffer.co/blog/installing-a-laravel-app-on-heroku))
* [IBM BlueMix](https://ace.ng.bluemix.net/) ([Tutorial](https://developer.ibm.com/bluemix/2014/06/17/getting-started-laravel-bluemix/))

## Application Deployment
* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
 * [Deployments with Envoyer](https://laracasts.com/series/envoyer) (Laracasts)
* [Rocketeer](https://github.com/Anahkiasen/rocketeer) - Task runner and deployment package

## Articles, Tutorials, Blogs etc.
* [Tuts+](http://code.tutsplus.com/categories/laravel)
* [SitePoint](http://www.sitepoint.com/php/page/0/?filter[4047]=on)
* [Christopher Pitt](https://medium.com/laravel-4)
* [Culttt](http://culttt.com/tag/cribbb/)
* [Scotch](http://scotch.io/tag/laravel)
* [Fideloper](http://fideloper.com/tag/laravel)
* [Maxoffsky](http://maxoffsky.com/tag/laravel/)
* [KodeInfo](http://kodeinfo.com/category/laravel/)
* [CodeForest](http://www.codeforest.net/tag/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?primary_filter=tutorials&query=laravel)
* [RTFM](http://matthewhailwood.co.nz/tag/laravel/)
* [Matt Stauffer](http://mattstauffer.co/tags/laravel)
* [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
* [Ryan Tablada](http://ryantablada.com/tag/Laravel)
* [Mohammad Gufran](http://www.gufran.me/tag/Laravel)
* [Adam Engebretson](http://blog.enge.me/tag/Laravel)
* [CodeHeaps](http://www.codeheaps.com/)
* [Laravel India](http://blog.laravel.in/)
* [Sheikh Heera](http://heera.it/tag/laravel-2)
* [Vegi Bit](http://vegibit.com/tag/laravel/)
* [WSnippets](http://wsnippets.com/category/laravel/)
* [Ed Zynda](http://www.edzynda.com/category/laravel-2/)
* [Kirk Bushell](http://kirkbushell.me/)
* [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
* [DeveloPHP](http://www.develophp.org/category/web/laravel/)
* [Jason Lewis](http://jasonlewis.me/category/laravel)
* [Eric Barnes](http://ericlbarnes.com/blog/tags/laravel)
* [Jens Segers](http://jenssegers.be/)
* [Neon Tsunami](http://www.neontsunami.com/tag/laravel)
* [Amitav Roy](http://amitavroy.com/justread/content/term/laravel-4)
* [Into Laravel](http://www.intolaravel.com/)
* [Stidges](http://blog.stidges.com/)
* [Scott Wilcox](http://dor.ky/tag/laravel/)
* [Clivern](http://clivern.com/tag/laravel/)
* [Code Gains](http://codegains.com/tag/laravel-2/)
* [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Bosnadev](https://bosnadev.com/tag/laravel-2/)
* [Blog do Vluzrmos (PT-BR)](http://blog.vluzrmos.com.br/category/laravel)
* [CodeTutorial](http://www.codetutorial.io/tag/laravel/)
* [Ryan Chenkie](http://ryanchenkie.com/tag/laravel/)
* [Laravelista](http://laravelista.com/tag/laravel/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](http://tuts.codingo.me/category/web-development/laravel/)
* [Antonio Carlos Ribeiro](https://antoniocarlosribeiro.com/technology)
* [Laravel Coding](http://laravelcoding.com/)
* [Styde](https://styde.net/proyectos/) (ES)
* [Laravel Daily](http://laraveldaily.com/)
# [Freek Van der Herten](https://murze.be/tag/laravel/)

## Video Tutorials
* [Laracasts](https://laracasts.com/)
* [PHP Academy](https://www.youtube.com/user/phpacademy/playlists)
* [Fallendown2005](https://www.youtube.com/user/fallendown2005/playlists)
* [Userscape](http://vimeo.com/userscape/videos)
* [Treehouse](http://teamtreehouse.com/library/laravel-basics)
* [Anthony Vipond](https://www.youtube.com/user/anthonytrading81/playlists)
* [Design Code Blade](https://www.youtube.com/playlist?list=PLl0rlrKS77Mr5T6k8ZPfvCcaJ8ctk1ChU)
* [Format C:](http://www.formatccolon.com/blog/category/code-web-development/laravel/)
* [Brandon Boswell](https://www.youtube.com/watch?v=QBdudSQ1aLg)
* [Jason Chaney](https://www.youtube.com/watch?v=BtbB26VWTBI)
* [David Mosher](https://www.youtube.com/watch?v=hqAyiqUs93c)
* [Maarten (muukrls)](https://www.youtube.com/channel/UCrehvx9t0p_TFAIw6YLtzDQ/videos)
* [Yavor Kirov](https://www.youtube.com/playlist?list=PL2uFHrRTF1xxC4nG9gMUmwONI3d_vJEJf)
* [Lynda](http://www.lynda.com/Laravel-tutorials/Up-Running-Laravel/166513-2.html)
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Novica Vukobratovic](http://www.youtube.com/playlist?list=PLaWzibV7A82RMFW58Iq2gZHpB_TLrixFY)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos)

## Conferences
* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [ArtisanConf](https://www.artisanconf.com/)

#### Conference Videos
* [Laracon EU 2014](http://laracon.eu/2014/#schedule)
* [Laracon US 2014](http://userscape.com/laracon/2014/)
* [Laracon EU 2013](http://laracon.eu/2013/talks/)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## Books
* [Laravel: Code Bright](https://leanpub.com/codebright)
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel)
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook)
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded)
* [Implementing Laravel](https://leanpub.com/implementinglaravel)
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel)
* [Laravel Application Development Blueprints](http://www.packtpub.com/laravel-application-development-blueprints/book)
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate)
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend)
* [Laravel Design Patterns and Best Practices](http://www.packtpub.com/laravel-design-patterns-and-best-practices/book)
* [Step by Step Real World Application with Laravel 4](https://leanpub.com/real-world-laravel4)
* [Learning Laravel 4 Application Development](http://www.packtpub.com/learning-laravel-4-application-development/book)
* [Getting Started with Laravel 4](http://www.packtpub.com/getting-started-with-laravel-4/book)
* [Laravel Application Development Cookbook](http://www.packtpub.com/laravel-application-development-cookbook/book)
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api)
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework)
* [Easy Laravel 5](https://leanpub.com/easylaravel/)
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials)
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce)
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty)
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign)
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy)
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel)

## Codebases for Reference
* [92Five](https://github.com/chintanbanugaria/92five)
* [Bootstrap CMS](https://github.com/BootstrapCMS/CMS)
* [Cachet](https://github.com/cachethq/Cachet)
* [Invoice Ninja](https://github.com/hillelcoren/invoice-ninja)
* [Larahunt](https://github.com/larahunt/larahunt)
* [Laravel 5 Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel Tricks](https://github.com/CodepadME/laravel-tricks)
* [Laravel.IO](https://github.com/LaravelIO/laravel.io)
* [October](https://github.com/octobercms/october)
* [Paperwork](https://github.com/twostairs/paperwork)
* [PHPHub](https://github.com/summerblue/phphub)
* [PyroCMS](https://github.com/pyrocms/pyrocms)
* [StyleCI](https://github.com/StyleCI/StyleCI)
* [TypiCMS](https://github.com/TypiCMS/Base)
* [Wardrobe](https://github.com/wardrobecms/wardrobe)
* [Flarum](https://github.com/flarum/flarum)
* [Lavalite](https://github.com/LavaLite/cms)

## Newsletters
* [Laravel News](http://laravel-news.com/) ([archive](http://laravel-news.com/archive))
* [Laravel Weekly](http://laravelweekly.com/)

## Community
* [Laravel.io Forum](http://laravel.io/) ([Old Forum Archive](http://forumsarchive.laravel.io/))
* [Laracasts Forum](https://laracasts.com/discuss) ([Old Forum Archive](https://www.laracasts.com/forum/))
* [Laravel Podcast](http://www.laravelpodcast.com/)
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.typeform.com/to/wqvupv))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](http://www.reddit.com/r/laravel)
* [Quora](http://www.quora.com/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/Laravel-PHP-Framework-4419933)

#### Local User Groups
* [Laravel Russia](http://laravel.ru/) ([VK group](http://vk.com/laravel_rus))
* [Laravel France](http://laravel.fr/)
* [Laravel Myanmar](http://laravelmyanmar.com)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook group](https://www.facebook.com/groups/laravel/))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook group](https://www.facebook.com/groups/laravelbrasil/))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook group](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laranaija.com/) ([Facebook group](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](http://phphub.org)
* [Laravel Taiwan](http://laravel.tw/) ([Facebook group](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](http://laravel.co.kr/) ([Facebook group](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Morocco](http://moroccanphpartisans.github.io/)
* [Laravel Japan](http://laravel.jp/) ([Facebook group](https://www.facebook.com/groups/laravel.jp/))

#### Meetups
* [All Meetups](http://laravel.meetup.com/)
* [London Meetup](http://www.meetup.com/London-Laravel/)
* [Buenos Aires, Argentina Meetup](http://www.meetup.com/Laravel-Buenos-Aires)
* [Morocco Meetup](http://www.meetup.com/moroccan-php-artisans/)

## Jobs
* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](http://laravelgurus.com/)
* [With Laravel](http://withlaravel.com/)

### Hosted Development Tools
* [Laragen](http://makzumi.com/laragen/) - View generator
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [Laravel Database Designer](http://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - Graphical tool to create database schemas

## Miscellaneous
* [Larasites](https://www.larasites.com/) - Collection of projects built with Laravel
* [Built with Laravel](http://builtwithlaravel.com/) - Collection of open source projects built with Laravel
* [CodeCanyon](http://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins
* [Laramap](https://laramap.com/) - Interactive map of Laravel developers

## Contributing
Found an awesome package, blog, video etc.? Send me a PR!

#### Guidelines
* Please make an individual pull request for each suggestion
* Use the following format for resources: \[Resource\]\(URL\)
* Use the following format for packages: \[Package\]\(URL\) - Short description
* New categories or improvements to the existing categorisation are welcome

## License

Awesome Laravel is licensed under [The MIT License (MIT)](LICENSE).
