# Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/chiraggude/awesome-laravel/master.svg?style=flat)](https://travis-ci.org/chiraggude/awesome-laravel)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Code Snippets](#code-snippets)
- [Tutorials & Blogs](#tutorials--blogs)
- [Videos](#videos)
- [Conferences](#conferences)
- [Books](#books)
- [Starter Projects](#starter-projects)
- [Codebases for Reference](#codebases-for-reference)
- [Content Management Systems](#content-management-systems)
- [Podcasts](#podcasts)
- [Community](#community)
- [Jobs](#jobs)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)

## Essentials

* [Laravel](https://laravel.com) ([Documentation](https://laravel.com/docs))
* [Laravel API Reference](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com) ([Documentation](https://lumen.laravel.com/docs))
* [Laracasts](https://laracasts.com)
* [Laravel News](https://laravel-news.com) ([Archive](https://laravel-news.com/archive/))

## Packages

* [Packagist](https://packagist.org/)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## Popular Packages

> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators
* [Laravel API/Scaffold/CRUD Generator](https://github.com/InfyOmLabs/laravel-generator) - Generator for APIs, CRUD scaffolds etc.
* [Laravel Tinx](https://github.com/furey/tinx) - Reload your Laravel Tinker session from inside Tinker
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages
* [Workbench Export to Migrations](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - Workbench plugin for exporting Models to Laravel migrations
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - List all installed packages, their dependencies, app & server details
* [LaRecipe](https://github.com/saleem-hadad/larecipe) - Write gorgeous documentations for your products using Markdown inside your Laravel app.
* [Prequel](https://github.com/Protoqol/Prequel/) - A clear and concise database management GUI tweaked for Laravel.

##### Testing & Debugging

* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Ignition](https://github.com/facade/ignition) - A beautiful error page for Laravel apps
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - Record exceptions into a database and will send you a notification
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger
* [Laravel Terminal](https://github.com/recca0120/laravel-terminal) - run artisan in a web browser
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Telescope](https://github.com/laravel/telescope) - Laravel Telescope is an elegant debug assistant for the Laravel framework

##### Authentication & Authorization

* [Bouncer](https://github.com/JosephSilber/bouncer) - Roles & Permissions
* [Laratrust](https://github.com/santigarcor/laratrust) - Roles, Permissions and teams
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs
* [Laravel Permission](https://github.com/spatie/laravel-permission) - Associate users with roles and permissions
* [Defender](https://github.com/artesaos/defender) - Roles & Permissions
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc.
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100+ social authentication providers for Socialite with Lumen support
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - Handle the user verification flow and validate email
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP authentication and Active Directory management
* [Doorman](https://github.com/clarkeash/doorman) - Limit access to your Laravel applications by using invite codes
* [Laravel Heyman](https://github.com/imanghafoori1/laravel-heyman) - Heyman continues where the above role-permission packages left off

##### Utilities

* [Awes.io](https://github.com/awes-io/awes-io) - boilerplate for CRM, SaaS, ERP based on Vue (Nuxt.js), TailwindCSS plus Laravel as a backend.
* [Artisan View](https://github.com/svenluijten/artisan-view) - Manage the views in Laravel projects via artisan
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Captcha](https://github.com/mewebstudio/captcha) - An anti-bot image captcha system
* [Charts](https://github.com/ConsoleTVs/Charts) - Multi-library chart package to create interactive charts
* [Lavacharts](https://github.com/kevinkhill/lavacharts) - Charts and Graphs for PHP Powered by the Google Chart API
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - Filter models and their Relationships
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Sortable behaviour for Eloquent models
* [HTML](https://github.com/LaravelCollective/html) - HTML and Form Builders for Laravel
* [Multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of routes, assets and databases
* [Laravel Form Builder](https://github.com/kristijanhusak/laravel-form-builder) - Form builder inspired by Symfony's form builder
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - Log activity inside your Laravel app
* [Laravel Auditing](https://github.com/owen-it/laravel-auditing) - Audit for Eloquent models
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - A set of handy collection macros
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - Make your Laravel app comply with the crazy EU cookie law
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - jQuery DataTables API
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the location of website visitors based on their IP addresses
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users
* [Laravel Mailbox](https://github.com/beyondcode/laravel-mailbox) - A package to handle incoming emails
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel Menu](https://github.com/spatie/laravel-menu) - Html menu generator for Laravel
* [Laravel Talk](https://github.com/nahid/talk) - Realtime User messaging system
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - Approve or reject resources like posts, comments, users, etc.
* [Laravel Tags](https://github.com/spatie/laravel-tags) - Add tags and taggable behaviour
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Purifier](https://github.com/mewebstudio/purifier) - HTML filter
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques
* [Page Cache](https://github.com/JosephSilber/page-cache) - Caches responses as static files on disk for lightning fast page loads
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - Persistent configuration settings that are stored in JSON files
* [Friendship](https://github.com/hootlex/laravel-friendships) - Friendship management system
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations
* [Laravel UUID](https://github.com/webpatser/laravel-uuid) - Generate a UUID according to the RFC 4122 standard
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - Allow users to install your application just by following the setup wizard, like WordPress
* [Laravel Modules](https://github.com/nWidart/laravel-modules) - Easy module management
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - Phone number validator and formatter
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - Simplify blocking and banning Eloquent models
* [Laravel Proxy](https://github.com/fideloper/TrustedProxy) - Handling sessions when behind load balancers or other intermediaries.
* [Laravel Video Chat](https://github.com/PHPJunior/laravel-video-chat) - Video Chat using Socket.IO and WebRTC
* [Widgets for Laravel](https://github.com/arrilot/laravel-widgets) - A powerful alternative to view composers.
* [Secure Headers](https://github.com/BePsvPT/secure-headers) - Add security related headers to HTTP response
* [Laravel Nova](https://nova.laravel.com/) - Nova is a beautifully designed administration panel for Laravel
* [Laravel Love](https://github.com/cybercog/laravel-love) - It lets people express how they feel about the content. React on Eloquent models with Likes or Dislikes.
* [stancl/tenancy](https://github.com/stancl/tenancy) - Automatic tenancy for your Laravel app. No code changes needed.

##### Media & Document Management

* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images
* [Laravel ImageUp](https://github.com/qcod/laravel-imageup) - Yet another image manipulation package, adds tons of extra functionality
* [Laravel Glide](https://github.com/spatie/laravel-glide) - Easily convert images with Glide
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf
* [Laravel DOMPDF](https://github.com/barryvdh/laravel-dompdf) - HTML to PDF generator using [dompdf](https://github.com/dompdf/dompdf)
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files
* [Fast Excel](https://github.com/rap2hpoutre/fast-excel) - Fast XLSX, CSV and ODT import and export for Laravel
* [Laravolt Avatar](https://github.com/laravolt/avatar) - Plug n play avatar, turn name, email, and any other string into beautiful avatar (or gravatar), effortless.
* [Laravel FFmpeg](https://github.com/pascalbaljetmedia/laravel-ffmpeg) - This package provides an integration with FFmpeg for Laravel 5.8.

##### Integration with Javascript

* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - Pass server-side string/array/collection/whatever to JavaScript
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client-side
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - A Pjax middleware
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - A Blade directive to export variables to JavaScript
* [Ziggy](https://github.com/tightenco/ziggy) - Use your Laravel named routes in JavaScript
* [LiveWire](https://github.com/livewire/livewire) - A magical front-end framework for Laravel

##### Databases, ORMs, Migrations & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc.
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - Nested Sets pattern implementation
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver via OCI8
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager
* [Laravel Repository](https://github.com/andersao/l5-repository) - Repositories to abstract the database layer
* [Lada Cache](https://github.com/spiritix/lada-cache) - A Redis based, fully automated and scalable database cache layer
* [Laravel MySQL Spatial extension](https://github.com/grimzy/laravel-mysql-spatial) - easily work with MySQL Spatial Data Types and MySQL Spatial Functions

##### Search

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP
* [TNTSearch driver](https://github.com/teamtnt/laravel-scout-tntsearch-driver) - Driver for [Laravel Scout](https://github.com/laravel/scout) search package based on TNTSearch
* [Laravel-Searchy](https://github.com/TomLingham/Laravel-Searchy) - Fuzzy search, basic string matching, Levenshtein Distance

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal
* [Laravel GraphQL](https://github.com/rebing/graphql-laravel) - Supports Relay, eloquent models, validation and GraphiQL
* [Lighthouse](https://github.com/nuwave/lighthouse) - An up and coming GraphQL library for Laravel
* [Laravel Responder](https://github.com/flugger/laravel-responder) - Build custom API responses with Fractal

##### Tasks, Commands and Scheduling

* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands
* [Elixir](https://github.com/laravel/elixir) - Node (NPM) package to run Gulp tasks
* [Mix](https://github.com/JeffreyWay/laravel-mix) - Fluent API for defining basic webpack build steps
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner

##### Payments

* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library

##### Optimization

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier
* [Rememberable](https://github.com/dwightwatson/rememberable) - Query caching for Eloquent
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Page Partial caching
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up app by caching the entire response

##### Monitoring

* [Horizon](https://github.com/laravel/horizon) - Monitor and configure queues with a simple web UI
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - Get notified when a queued job fails
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - A powerful and easy to configure uptime and ssl monitor
* [Larametrics](https://github.com/aschmelyun/larametrics) - A self-hosted metrics and notifications platform for Laravel apps

##### Localization

* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - Translate Eloquent models into multiple languages
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - Manage language files from Artisan Console
* [Laravel Translation](https://github.com/waavi/translation) - Translation and localization management
* [Linguist](https://github.com/keevitaja/linguist) - i18n localization support for Laravel

##### Third-party Service Integration

* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - Retrieve pageviews and other data from Google Analytics
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API bridge
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API bridge

## Development Setup

* [Homestead](https://laravel.com/docs/master/homestead) - Official Vagrant box for Laravel
* [Valet](https://laravel.com/docs/master/valet) - Development environment for Mac users
* [Valet Linux](https://github.com/cpriego/valet-linux) - Development environment for Linux users
* [LaraDock](https://github.com/LaraDock/laradock) - Run Laravel on Docker (Like Homestead but for Docker instead of Vagrant)
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - Homestead environment in a single Docker container
* [Laragon](https://laragon.org/) -  Isolated development environment on Windows
* [Stacker](https://github.com/Maxlab/stacker) - The environment for local web development on Docker
* [Devilbox](https://github.com/cytopia/devilbox) - A dockerized and general-purpose LAMP/MEAN stack for every PHP version
* [Vessel](https://vessel.shippingdocker.com) - Simple Docker development environments for Laravel
* [Lando](https://docs.lando.dev/config/laravel.html) - A local development environment tool built on Docker

## Application Hosting

* [Vapor](https://vapor.laravel.com)
* [Forge](https://forge.laravel.com/) ([ForgeRecipes](https://forgerecipes.com/))
* [FortRabbit](https://www.fortrabbit.com/laravel-hosting)
* [Heroku](https://www.heroku.com/) ([Documentation](https://devcenter.heroku.com/articles/getting-started-with-laravel))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([Tutorial](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)
* [Ploi](https://ploi.io/)
* [CodePier](https://codepier.io?ref=awesome-laravel)
* [RunCloud](https://runcloud.io/)

## Application Deployment

* [Deployer](https://deployer.org/) - A deployment tool with support for Laravel out of the box
* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package

## Code Snippets

* [Laravel LTS Cheat Sheet ](https://summerblue.github.io/laravel5-cheatsheet/) ([Chinese version](https://cs.phphub.org/))
* [Laravel Tricks](http://laravel-tricks.com/)

## Tutorials & Blogs

* [Taylor Otwell](http://taylorotwell.com/)
* [Tuts+](https://code.tutsplus.com/categories/laravel)
* [Medium](https://medium.com/tag/laravel/latest)
* [Laravel Daily](https://laraveldaily.com/)
* [Scotch](https://scotch.io/tag/laravel)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&primary_filter=newest&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/blog)
* [Vegi Bit](https://vegibit.com/tag/laravel/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Dor.ky](https://dor.ky/tag/laravel/)
* [Stillat](https://stillat.com/explore/categories/laravel-5)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/category/laravel-5/) (ES)
* [Cloudways Laravel Blog](http://cloudways.com/blog/laravel)
* [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices)
* [Pusher Laravel Tutorials](https://pusher.com/tutorials?tag=Laravel)
* [LaraShout](https://larashout.com/)
* [Laravel 12 GitHub OAuth Login with Socialite](https://github.com/itstuffsolutions/laravel-12-socialite-login-with-github-oauth-example)

## Videos

* [Laracasts](https://laracasts.com/)
* [Codecourse](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Servers for Hackers](https://serversforhackers.com/laravel-perf)
* [Test-Driven Laravel](https://course.testdrivenlaravel.com/)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel) (ES)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Laracademy](https://laracademy.co/)
* [Dev Marketer](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel)
* [Lynda](https://www.lynda.com/search?q=laravel)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Bitfumes](https://www.youtube.com/bitfumes)
* [ConfidentLaravel](https://confidentlaravel.com/)

## Conferences

* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [Laracon Online](https://laracon.net/)
* [Laraconf Brasil](http://laraconfbrasil.com.br/)
* [Laracon Australia](https://laracon.com.au/)
* [Laravel Live UK](https://laravellive.uk/)
* [Laravel Live India](https://laravellive.in/)
* [Laravel Nigeria](https://laravelnigeria.com)

##### Videos

* [Laracon EU 2018](https://www.youtube.com/playlist?list=PLMdXHJK-lGoC64wnqvm6v1R5dsuAV-MpS)
* [Laracon US 2018](https://www.youtube.com/playlist?list=PL-yJve--iT5oM2LgF37VXsBb8Os4ZulIc)
* [Laracon EU 2017](https://www.youtube.com/playlist?list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Laracon US 2017](https://www.youtube.com/playlist?list=PL-yJve--iT5oaLQA6OI8TWLVSOBP1qhs3)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon US 2016](https://www.youtube.com/playlist?list=PL-yJve--iT5o9fH_cRY0u6P751pcF59GK)
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* Laracon US 2015
* [Laracon EU 2014](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCYhxlU3OJ5bOGhcKtDMkcN)
* [Laracon US 2014](https://www.youtube.com/channel/UCRawXmZv30Vf_MivyPYb_GQ/videos)
* [Laracon EU 2013](https://www.youtube.com/playlist?list=PLMdXHJK-lGoB-CIVsiQt0WU8WcYrb5eoe)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## Books

* [Laravel Starter](https://www.amazon.com/Laravel-Starter-Shawn-McCool-ebook/dp/B00ABFQ0AS) by Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: Code Smart](https://leanpub.com/codesmart) by Dayle Rees
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way
* [Refactoring to Collections](https://adamwathan.me/refactoring-to-collections/) by Adam Wathan
* [Implementing Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel) by Chuck Heintzelman
* [Laravel Application Development Blueprints](https://www.packtpub.com/web-development/laravel-application-development-blueprints) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by Phil Sturgeon
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel Design Patterns and Best Practices](https://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Learning Laravel 4 Application Development](https://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Getting Started with Laravel 4](https://www.packtpub.com/web-development/getting-started-laravel-4) by Raphaël Saunier
* [Laravel Application Development Cookbook](https://www.packtpub.com/web-development/laravel-application-development-cookbook) by Terry Matula
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api) by Mhd Zaher Ghaibeh
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework) by Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) by W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce) by W. Jason Gilmore and Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign) by Kelt Dockins
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) by Christopher John Pecoraro
* [How to Build Real-Time Laravel Apps with Pusher](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [Learning Laravel's Eloquent](https://www.amazon.com/Learning-Laravels-Eloquent-Francesco-Malatesta-ebook/dp/B00YSILQ6C) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel and AngularJS](https://leanpub.com/laravel-and-angularjs) by Daniel Schmitz and Daniel Pedrinha Georgii
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [Writing APIs With Lumen](https://leanpub.com/lumen-apis) by Paul Redmond
* [The Laravel Survival Guide](https://leanpub.com/laravelsurvivalguide) by Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck
* [Laravel 5.4 For Beginners](https://leanpub.com/laravel-5-4-for-beginners) by Bill Keck
* [Laravel Up & Running](https://www.amazon.com/gp/product/1491936088) by Matt Stauffer
* [Laravel Companion](https://leanpub.com/laravelcompanion-secondedition) by Johnathon Koster
* [Deploy Laravel on AWS with CloudFormation](https://leanpub.com/laravel-aws) by Lionel Martin
* [React Native and Laravel for Future Mobile Development](https://leanpub.com/rn_laravel) by Ega Radiegtya
* [Servers for Hackers](https://book.serversforhackers.com) by Chris Fidao
* [Full-Stack Vue.js 2 and Laravel 5](https://www.amazon.com/Full-Stack-Vue-js-Laravel-frontend-together/dp/1788299582) by Anthony Gore
* [Build an API with Laravel](https://buildanapi.com) by Wacky Studio

## Starter Projects

* [Spark](https://spark.laravel.com/)
* [LaraAdmin](https://github.com/dwijitsolutions/laraadmin)
* [Grafite Builder](https://github.com/GrafiteInc/Builder)
* [Laravel Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter)
* [AdminLTE Laravel](https://github.com/acacha/adminlte-laravel)
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter)
* [Laravel API Starter Kit](https://github.com/joselfonseca/laravel-api)
* [Backpack for Laravel](https://github.com/Laravel-Backpack/Base)
* [SomelineStarter](https://github.com/someline/someline-starter)
* [Laravel Admin](https://github.com/z-song/laravel-admin)
* [Voyager](https://github.com/the-control-group/voyager)
* [Orchid](https://github.com/TheOrchid/Platform)
* [Laravel REST API Boilerplate](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt)
* [Hello API](https://github.com/Porto-SAP/Hello-API)
* [REST API With Lumen](https://github.com/hasib32/rest-api-with-lumen)
* [Laravel Zero - Console application](https://github.com/laravel-zero/laravel-zero)
* [Apiato](https://github.com/apiato/apiato)
* [Laravel Adminpanel](https://github.com/viralsolani/laravel-adminpanel)
* [Laravel Vue Boilerplate](https://github.com/alefesouza/laravel-vue-boilerplate)
* [Laravel Enso](https://github.com/laravel-enso/enso)
* [Laravel Template with Vue](https://github.com/wmhello/laravel_template_with_vue)

## Codebases for Reference

* [Cachet](https://github.com/cachethq/Cachet) - Status page system for websites and APIs
* [Deployer](https://github.com/REBELinBLUE/deployer) - Application deployment system
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - Task management with Git and Scrum
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - Invoicing, expenses, & time-tracking application
* [Koel](https://github.com/phanan/koel) - Personal music streaming server
* [Laravel.io](https://github.com/laravelio/portal) - Source for the Laravel.io Community Portal
* [Attendize](https://github.com/Attendize/Attendize) - Ticket selling and event management platform
* [Antvel](https://github.com/ant-vel/App) - Ecommerce platform
* [Jigsaw](https://github.com/tightenco/jigsaw) - Static site generator
* [Canvas](https://github.com/cnvs/canvas) - A Laravel Publishing Platform
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo is blog platform, built with Laravel and Vue.js
* [Screeenly](https://github.com/stefanzweifel/screeenly) - Create website screenshots through an API
* [Voten](https://github.com/voten-co/voten) - A real-time social bookmarking for the 21st century
* [Monica](https://github.com/monicahq/monica) - Personal relationship management system
* [Snipe-IT](https://github.com/snipe/snipe-it) - IT asset/license management system
* [Akaunting](https://github.com/akaunting/akaunting) - Accounting software for small businesses and freelancers
* [Torch](https://github.com/mattstauffer/Torch) - Examples of using each Illuminate component in non-Laravel applications
* [Pixelfed](https://github.com/pixelfed/pixelfed) - A free and ethical photo sharing platform, powered by ActivityPub federation


## Content Management Systems

* [OctoberCMS](https://github.com/octobercms/october)
* [SleepingOwlAdmin](https://github.com/LaravelRUS/SleepingOwlAdmin)
* [PyroCMS](https://github.com/pyrocms/pyrocms)
* [Lavalite](https://github.com/LavaLite/cms)
* [TypiCMS](https://github.com/typicms/base)
* [Asgard CMS](https://github.com/AsgardCms/Platform)
* [Microweber](https://github.com/microweber/microweber)
* [Coaster CMS](https://github.com/web-feet/coastercms)
* [Statamic](https://statamic.com/)
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/)
* [PJ Blog](https://github.com/jcc/blog/)
* [Laralum](https://github.com/Laralum/Laralum)
* [Twill](https://github.com/area17/twill)

## Podcasts

* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](https://laravel-news.com/podcast/ )
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (Spanish)](http://hechoenlaravel.com)

## Community

* [Laracasts Forum](https://laracasts.com/discuss)
* [Laravel.io Forum](http://laravel.io/forum)
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.co/register))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](https://www.quora.com/topic/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/4419933/profile)

##### Local User Groups

* [Laravel Global Community](https://www.facebook.com/groups/group.laravel/)
* [LaravelES Slack](https://laraveles.slack.com) ([Signup](http://laraveles.com/blog/wp-login.php?action=slack-invitation))
* [Laravel India](https://laravellive.in/), [Slack Signup](https://laravelliveindia.slack.com/join/shared_invite/enQtNjQyMDE4NDA3MDQzLWMyZmIxNGZkNGVkNGFmMzE1MTgyOGNiZGY1ZmU1ZDQ3Mzk2ODBlZGJlODk3ZmI0OWNlZmI5MzQyZDJhYzg1NjE), [Twitter](https://twitter.com/LaravelLiveIN), [Facebook](https://www.facebook.com/laravellive/), [Youtube](https://www.youtube.com/channel/UC6TxYSHI7g9FMJ7VlHk72Yg)
* [Laravel UK](https://laravelphp.uk/), [Slack Signup](https://laravelphp.uk/login/slack)
* [Laravel Russia](https://laravel.ru/) ([VK group](http://m.vk.com/laravel_rus))
* [Laravel France](https://laravel.fr/)
* [Laravel Bangladesh](https://www.facebook.com/groups/LaravelBanglaDesh/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook](https://www.facebook.com/groups/laravel/), [Telegram](https://t.me/laravelindonesia))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook](https://www.facebook.com/groups/laravelbrasil/), [Slack](http://slack.laravel.com.br), [Telegram](https://telegram.me/laravelbr), [GitHub](https://github.com/laravelbrasil), [Discord](https://discord.gg/9dpuWeZ))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laravelnigeria.com/) ([Facebook](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](https://phphub.org/)
* [Laravel Taiwan](https://laravel.tw/) ([Facebook](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](https://www.laravel.co.kr/) ([Facebook](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Japan](http://laravel.jp/) ([Facebook](https://www.facebook.com/groups/laravel.jp/))
* [Laravel Malaysia](https://www.facebook.com/groups/laravel.my/)
* [Laravel Algeria](https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel Greece](http://www.laravel.gr) ([Facebook](https://www.facebook.com/laravelgr))
* [Laravel Middle East](http://laravelme.com/) ([Facebook](https://www.facebook.com/laravelme))
* [Laravel Georgia](https://www.facebook.com/groups/laravel.georgia/)
* [Laravel Italy](http://laravel-italia.it)
* [Laravel Vietnam](https://www.facebook.com/groups/vietnam.laravel/)
* [Laravel Slovenia](https://www.facebook.com/groups/laravelslovenija/)
* [Laravel Hungary](https://laravel.hu)
* [Laravel Cameroon](https://laravelcm.com/) ([Slack](https://laravelcm.slack.com), [GitHub](https://github.com/laravelcm), [Facebook](https://www.facebook.com/laravelcm), [Twitter](https://twitter.com/laravelcm))
* [Laravel Philippines](https://www.facebook.com/groups/laravelph)

##### Meetups

* [All Meetups](http://www.meetup.com/topics/laravel/)
* [London Meetup](https://www.meetup.com/London-Laravel/)
* [Buenos Aires Meetup](https://www.meetup.com/Laravel-Buenos-Aires/)
* [Athens-Greece Meetup](https://www.meetup.com/athens-laravel-meetup/)
* [Copenhagen Meetup](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [Detroit Meetup](https://www.meetup.com/Laravel-Detroit/)
* [Paris Meetup](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [Melbourne Meetup](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [Budapest Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

## Jobs

* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](https://laravelgurus.com/)

## Hosted Development Tools

* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [StyleCI](https://styleci.io) - PHP Coding Style Service

## Miscellaneous

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins
* [Laravel Collections](https://laravelcollections.com) - Every Laravel Developers Goto Resource Site
* [LaravelLinks](https://telegram.me/laravellinks) - A Telegram Channel dedicated to sharing great Laravel Resources

## Contributing

Found an awesome package, blog, course or video? Send me a pull request!

#### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the Travis tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome Laravel is licensed under a  [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
