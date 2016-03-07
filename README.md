Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Code Snippets](#code-snippets)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Articles, Tutorials, Blogs etc.](#articles-tutorials-blogs-etc)
- [Videos](#videos)
- [Conferences](#conferences)
- [Books](#books)
- [Starter Projects](#starter-projects)
- [Codebases for Reference](#codebases-for-reference)
- [Newsletters](#newsletters)
- [Podcasts](#podcasts)
- [Community](#community)
- [Jobs](#jobs)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)

## Essentials
* [Laravel](http://laravel.com)
* [Laravel Documentation](http://laravel.com/docs)
* [Laravel API Reference](http://laravel.com/api/master)
* [Lumen](http://lumen.laravel.com)
* [Lumen Documentation](http://lumen.laravel.com/docs)
* [Laracasts](http://laracasts.com)
* [Laravel News](https://laravel-news.com/)

## Code Snippets
* [Laravel Cheat Sheet](http://cheats.jesse-obrien.ca)
* [Laravel Tricks](http://laravel-tricks.com/)
* [Laravel Recipies](http://laravel-recipes.com/)

## Packages
* [Packagist](https://packagist.org/)
* [Laravel Collective](http://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Cartalyst](https://cartalyst.com/)
* [Spatie](https://spatie.be/opensource/laravel)

## Popular Packages
> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) -  Extends built-in file generators
* [Laravel API/Scaffold/CRUD Generator](http://labs.infyom.com/laravelgenerator/) - Generator for APIs, CRUD scaffolds etc.

##### Debugging & Profiling
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer for Laravel 5

##### Authentication & Authorisation
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs
* [Laravel Permission](https://github.com/spatie/laravel-permission) Associate users with roles and permissions
* [Defender](https://github.com/artesaos/defender) Roles & Permissions
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server
* [Laravel Roles](https://github.com/romanbican/roles) - Roles And Permissions
* [Sentinel](https://github.com/cartalyst/sentinel) - Framework agnostic authentication & authorization system
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc.
* [Socialite Providers](http://socialiteproviders.github.io/) - 70+ social authentication providers for Socialite
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module

##### Utilities
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Datatable](https://github.com/Chumper/Datatable) - Server-side and client-side integration for jQuery Datatables plugin
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models
* [HTML](https://github.com/LaravelCollective/html) - Official HTML and Form Builders for Laravel
* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs
* [Laravel Datatable](https://github.com/yajra/laravel-datatables) - jQuery DataTables API
* [Laravel Dot Env Generator](https://github.com/mathiasgrimm/laravel-dot-env-gen) - Generate .env.gen file based on the project source code
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the geographical location of website visitors based on their IP addresses
* [Laravel Hashids](https://github.com/vinkla/hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up a Laravel app by caching the entire response
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques
* [Setting](https://github.com/Phil-F/Setting) - Persistent configuration settings that are stored in JSON files
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations
* [Laravel Uuid](https://github.com/webpatser/laravel-uuid) - Laravel package to generate a UUID according to the RFC 4122 standard.

##### Working with Javascript
* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) -  Pass server-side string/array/collection/whatever to JavaScript
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client side without need to write any Javascript code

##### Databases, ORMs, Migrations & Seeding
* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc.
* [Baum](https://github.com/etrepat/baum) - Nested Sets pattern implementation
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM
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
* [Elixir](https://github.com/laravel/elixir) - Node(NPM) package to run Gulp tasks that watch files, run tests, minify CSS, concatenate scripts etc.
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner

##### Payments
* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library

##### Optimization
* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier

##### Localization
* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances
* [Laravel Translator](https://github.com/vinkla/translator) - Translate Eloquent models into multiple languages
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon.

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
  * [Getting Started with Laravel Homestead](https://scotch.io/tutorials/getting-started-with-laravel-homestead)
  * [Installation on OSx and Linux](https://laracasts.com/series/laravel-5-from-scratch/episodes/3)
  * [Installation on  Windows](http://blog.teamtreehouse.com/laravel-homestead-on-windows)
* Install Laravel with Composer
 * [Windows](https://www.youtube.com/watch?v=m3D894qZKws)
 * [Mac OSX or Linux](https://laracasts.com/lessons/laravel-installation-for-newbs)

## Application Hosting
* [Forge](https://forge.laravel.com/) - Provision optimized PHP servers on Linode, DigitalOcean etc.
  * [Server Management with Forge](https://laracasts.com/series/server-management-with-forge) (Laracasts)
  * [Getting your first site up and running in Laravel Forge](https://mattstauffer.co/blog/getting-your-first-site-up-and-running-in-laravel-forge) (Matt Stauffer)
  * [ForgeRecipes](http://forgerecipes.com/)
* [FortRabbit](http://www.fortrabbit.com/laravel-hosting) ([Video](https://laracasts.com/lessons/from-zero-to-deploy-with-fortrabbit))
* [PagodaBox](https://pagodabox.io/) ([Documentation](https://pagodabox.io/docs/framework_laravel))
* [Heroku](https://www.heroku.com/) ([Tutorial](https://mattstauffer.co/blog/installing-a-laravel-app-on-heroku))
* [IBM BlueMix](https://console.ng.bluemix.net/) ([Tutorial](https://developer.ibm.com/bluemix/2014/06/17/getting-started-laravel-bluemix/))

## Application Deployment
* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
 * [Deployments with Envoyer](https://laracasts.com/series/envoyer) (Laracasts)
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package

## Articles, Tutorials, Blogs etc.
* [Tuts+](http://code.tutsplus.com/categories/laravel)
* [SitePoint](http://www.sitepoint.com/php/page/0/?filter[4047]=on)
* [Christopher Pitt](https://medium.com/laravel-4)
* [Culttt](http://culttt.com/tag/cribbb/)
* [Scotch](https://scotch.io/tag/laravel)
* [Fideloper](http://fideloper.com/tag/laravel)
* [Maxoffsky](http://maxoffsky.com/tag/laravel/)
* [KodeInfo](http://kodeinfo.com/main_category/laravel)
* [CodeForest](http://www.codeforest.net/tag/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&type=tutorials)
* [RTFM](http://matthewhailwood.co.nz/tag/laravel/)
* [Matt Stauffer](https://mattstauffer.co/tags/laravel)
* [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
* [Ryan Tablada](http://ryantablada.com/tag/Laravel)
* [Mohammad Gufran](http://www.gufran.me/tag/Laravel/)
* [Adam Engebretson](http://blog.enge.me/4)
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
* [Jens Segers](https://jenssegers.com/)
* [Neon Tsunami](http://www.neontsunami.com/tags/laravel)
* [Amitav Roy](http://amitavroy.com/justread/content/term/laravel-4)
* [Into Laravel](http://www.intolaravel.com/)
* [Stidges](http://blog.stidges.com/)
* [Scott Wilcox](http://dor.ky/tag/laravel/)
* [Clivern](http://clivern.com/tag/laravel/)
* [Code Gains](http://codegains.com/tag/laravel-2/)
* [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Bosnadev](https://bosnadev.com/tag/laravel-2/)
* [Vagner Luís (PT-BR)](http://blog.vagnerdocarmo.com.br/category/laravel/)
* [Vedovelli (PT-BR)](http://www.vedovelli.com.br/tag/laravel/)
* [CodeTutorial](https://www.codetutorial.io/tag/laravel/)
* [Ryan Chenkie](http://ryanchenkie.com/tag/laravel/)
* [Laravelista](http://laravelista.com/tag/laravel/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](http://tuts.codingo.me/category/web-development/laravel/)
* [Antonio Carlos Ribeiro](https://antoniocarlosribeiro.com/technology)
* [Laravel Coding](http://laravelcoding.com/blog)
* [Styde](https://styde.net/proyectos/) (ES)
* [Laravel Daily](http://laraveldaily.com/)
* [Freek Van der Herten](https://murze.be/tag/laravel/)
* [Alfred Nutile](https://alfrednutile.info/tags/laravel)
* [Tutsnare](http://tutsnare.com/category/tutorials/laravel/)
* [ForLaravel](https://forlaravel.com/)
* [Good Heads](http://goodheads.io/category/laravel/)

## Videos
* [Laracasts](https://laracasts.com/)
* [Coursecode](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel&lang=en)
* [Treehouse](https://teamtreehouse.com/library/q:laravel)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos)
* [DevDojo](https://www.youtube.com/playlist?list=PL_UnIDIwT95NUvLU14l_QFFV2ZxO1phpQ)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Lynda](http://www.lynda.com/Laravel-training-tutorials/2779-0.html)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)

## Conferences
* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [ArtisanConf](https://www.artisanconf.com/)

##### Videos
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* [Laracon EU 2014](http://laracon.eu/2014/#schedule)
* [Laracon US 2014](http://userscape.com/laracon/2014/)
* [Laracon EU 2013](http://laracon.eu/2013/talks/)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## Books
* [Laravel Starter](https://www.packtpub.com/web-development/laravel-starter-instant) by Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way
* [Implementing Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel) by Chuck Heintzelman
* [Laravel Application Development Blueprints](http://www.packtpub.com/web-development/laravel-application-development-blueprints) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by Phil Sturgeon
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel Design Patterns and Best Practices](http://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Step by Step Real World Application with Laravel 4](https://leanpub.com/real-world-laravel4) by Ibrahim Yusuf
* [Learning Laravel 4 Application Development](http://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Getting Started with Laravel 4](http://www.packtpub.com/web-development/getting-started-laravel-4) by Raphaël Saunier
* [Laravel Application Development Cookbook](http://www.packtpub.com/web-development/laravel-application-development-cookbook) by Terry Matula
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api) by Mhd Zaher Ghaibeh
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework) by Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) by W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce) by W. Jason Gilmore and Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign) by Kelt Dockins
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) by Christopher John Pecoraro
* [How to Build Real-Time Laravel Apps with Pusher](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [Learning Laravel's Eloquent](https://www.packtpub.com/web-development/learning-laravel%E2%80%99s-eloquent) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel and AngularJS](https://leanpub.com/laravel-and-angularjs) by Daniel Schmitz and Daniel Pedrinha Georgii
* [Laravel 5 UnFolded](http://www.amazon.com/Laravel-UnFolded-Application-Programming-Simplified-ebook/dp/B011I0DVWO/) by Sanjib Sinha
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [Writing APIs With Lumen](https://leanpub.com/lumen-apis) by Paul Redmond
* [The Laravel Survival Guide](https://leanpub.com/laravelsurvivalguide) by Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck

## Starter Projects
* [Laravel 5.1 Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel 5 Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter)
* [Acacha adminlte-laravel](https://github.com/acacha/adminlte-laravel)
* [Laravel Spark](https://github.com/laravel/spark)
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter)

## Codebases for Reference
* [92Five](https://github.com/chintanbanugaria/92five)
* [Bootstrap CMS](https://github.com/BootstrapCMS/CMS)
* [Cachet](https://github.com/cachethq/Cachet)
* [Deployer](https://github.com/REBELinBLUE/deployer)
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja)
* [Koel](https://github.com/phanan/koel)
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
* [Laramap](https://github.com/laramap/laramap.com)

## Newsletters
* [Laravel News](https://laravel-news.com/) ([archive](https://laravel-news.com/archive/))
* [Laravel Weekly](http://laravelweekly.com/)

## Podcasts
* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](http://podcast.laravel-news.com/)
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)

## Community
* [Laravel.io Forum](http://laravel.io/forum) ([Old Forum Archive](http://forumsarchive.laravel.io/))
* [Laracasts Forum](https://laracasts.com/discuss) ([Old Forum Archive](https://www.laracasts.com/forum/))
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.typeform.com/to/wqvupv))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](http://www.quora.com/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/Laravel-PHP-Framework-4419933)

##### Local User Groups
* [Laravel Russia](https://laravel.ru/) ([VK group](http://vk.com/laravel_rus))
* [Laravel France](http://laravel.fr/)
* [Laravel Myanmar](http://laravelmyanmar.com)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook group](https://www.facebook.com/groups/laravel/))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook group](https://www.facebook.com/groups/laravelbrasil/))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook group](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laranaija.com/) ([Facebook group](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](https://phphub.org/)
* [Laravel Taiwan](http://laravel.tw/) ([Facebook group](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](https://www.laravel.co.kr/) ([Facebook group](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Morocco](http://moroccanphpartisans.github.io/)
* [Laravel Japan](http://laravel.jp/) ([Facebook group](https://www.facebook.com/groups/laravel.jp/))
* [Laravel Tokyo](http://laravel.tokyo/) ([Facebook group](https://www.facebook.com/groups/laraveltokyo/))
* [Laravel Malaysia](https://www.facebook.com/groups/laravel.my/)
* [Laravel Algeria] (https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel Greece](http://www.laravel.gr) ([Facebook page](https://www.facebook.com/laravelgr))
* [Laravel Middle East](http://laravelme.com/) ([Facebook page](https://www.facebook.com/laravelme))

##### Meetups
* [All Meetups](http://laravel.meetup.com/)
* [London Meetup](http://www.meetup.com/London-Laravel/)
* [Buenos Aires, Argentina Meetup](http://www.meetup.com/Laravel-Buenos-Aires)
* [Morocco Meetup](http://www.meetup.com/moroccan-php-artisans/)
* [Athens-Greece Meetup](http://www.meetup.com/athens-laravel-meetup)
* [Copenhagen Meetup](http://www.meetup.com/Copenhagen-Laravel-Meetup/)

## Jobs
* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](http://laravelgurus.com/)
* [With Laravel](http://withlaravel.com/)

## Hosted Development Tools
* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Versions {x.y.z}](https://laraver.xyz/) - Monitor Laravel for updates
* [Laragen](http://makzumi.com/laragen/) - View generator
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [Laravel Database Designer](http://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - Graphical tool to create database schemas

## Miscellaneous
* [Larasites](https://www.larasites.com/) - Collection of websites and apps built with Laravel
* [CodeCanyon](http://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins
* [Laramap](https://laramap.com/) - Interactive map of Laravel developers

## Contributing
Found an awesome package, blog, video etc.? Send me a pull request!

#### Guidelines
* Please make an individual pull request for each suggestion
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

Awesome Laravel is licensed under a  [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
