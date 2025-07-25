# Laravel Study Guide

Welcome to the **Laravel Study Guide**! This repository is a comprehensive resource designed to help you learn Laravel from the ground up. Whether you are a beginner or looking to deepen your understanding of Laravel, this guide provides a structured path to mastering the framework.

## Resources
Here are some additional resources to help you learn Laravel:

- [Laravel Official Website](https://laravel.com),
- [Laravel Documentation](https://laravel.com/docs)
- [Laracasts (Video Tutorials)](https://laracasts.com)
- [Laravel News](https://laravel-news.com)
- [Laravel GitHub Repository](https://github.com/laravel/laravel)
- [Recommended YouTube Channels for Laravel Tutorials](#Recommended-YouTube-Channels-for-Laravel-Tutorials)

## Recommended YouTube Channels for Laravel Tutorials

Here are some highly recommended YouTube channels and playlists that cover a wide range of Laravel topics, from beginner to advanced:

1. Traversy Media - Brad Traversy is known for creating beginner friendly crash courses. This crash course is great for getting started with Laravel quickly.
	- Laravel Crash Course - 1 [https://www.youtube.com/watch?v=ImtZ5yENzgE]
	- Laravel Crash Course - 2 [https://www.youtube.com/watch?v=MFh0Fd7BsjE]

2. Laravel Official Channel - The official Laravel's channel provides tutorials, conference talks, and announcements for new Laravel releases.
	- Laravel PHP Framework [https://www.youtube.com/laravelphp]

3. Academind - Laravel Series [https://www.youtube.com/watch?v=MFh0Fd7BsjE&list=PL55RiY5tL51rrC3sh8qLiYHqUV3twEYU_]https://www.youtube.com/watch?v=MFh0Fd7BsjE&list=PL55RiY5tL51rrC3sh8qLiYHqUV3twEYU_
Max from Academind has a detailed Laravel series that covers the essentials, including MVC, routes, controllers, models, and Blade templates.

4. Learn with Jon - Laravel Crash Course [https://www.youtube.com/playlist?list=PL38wFHH4qYZXH8Gb7PIbmyjdsWdEJLImp]
This channel covers various Laravel topics from the basics to more advanced concepts like API development and authentication.

5. Laravel Daily - Povilas Korop Tutorials [https://www.youtube.com/@LaravelDaily]
This channel is fantastic for short, focused tutorials on various Laravel topics, including Eloquent tips, Blade templates, validation, testing, and more.
It also covers more niche topics like job queues, notifications, and real world scenarios.

6. Codecourse - Laravel Series [https://www.youtube.com/@codecourse]
Codecourse provides in-depth tutorials focusing on practical application development using Laravel..


## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Routing](#routing)
- [Controllers](#controllers)
- [Middleware](#middleware)
- [Custom Middleware](#Custom-Middleware)
- [Blade Templating](#blade-templating)
- [Database and Eloquent ORM](#database-and-eloquent-orm)
- [Database Optimization](#Database-Optimization)
- [Authentication](#Authentication)
- [Service Container and Dependency Injection](#Service-Container-and-Dependency-Injection)
- [Service Providers](#Service-Providers)
- [Queues and Jobs](#Queues-and-Jobs)
- [Testing](#Testing)
- [Task Scheduling](#Task-Scheduling)
- [Packages Development](#Packages-Development)
- [API Development](#API-Development)
- [Performance Optimization](#Performance-Optimization)
- [File Storage](#File-Storage)
- [Security](#Security)
- [Custom Artisan Commands](#Custom-Artisan-Commands)
- [Localization](#Localization)
- [Single Page Applications (SPA) with Laravel](Single-Page-Applications-(SPA)-with-Laravel)
- [Laravel Nova](#Laravel-Nova)
- [Event Sourcing](#Event-Sourcing)
- [Laravel Mix](#Laravel-Mix)
- [API Throttling and Rate Limiting](#API-Throttling-and-Rate-Limiting)
- [Real time Broadcasting](#Real-time-Broadcasting)
- [Dependency Injection and Service Container](#Dependency-Injection-and-Service-Container)
- [Advanced Validation](#Advanced-Validation)
- [Custom Error Pages](#Custom-Error-Pages)
- [Laravel Sanctum](#Laravel-Sanctum)
- [Laravel Dusk](#Laravel-Dusk)
- [TALL Stack Development](#TALL-Stack-Development)
- [Setting Up Continuous Integration (CI) for Laravel Projects](#Setting-Up-Continuous-Integration-(CI)-for-Laravel-Projects)
- [Laravel Core Structure](#Laravel Core Structure)
- [Laravel Plugins](#laravel-Plugins)
- [Useful Links](#Useful-Links)


## Introduction

Laravel is a powerful and flexible PHP framework designed for developers who need an elegant, yet simple toolkit to build web applications. This guide aims to simplify your learning process by providing clear explanations, code examples, exercises and more.

## Getting Started

### Prerequisites

Before diving into the Laravel make sure you have the following installed on your machine:

- PHP (>= 8.0)
- Composer
- MySQL or any other supported database
- Node.js and NPM

### Routing

Routing is a core concept in Laravel. It allows you to define how your application responds to various HTTP requests.

- Basic Routing
- Route Parameters
- Named Routes
- Route Groups
- Route Model Binding

### Controllers

Controllers handle the logic for your routes. They help keep your routes file clean and organized.

- Creating Controllers
- Resource Controllers
- Dependency Injection in Controllers

### Middleware

Middleware acts as a bridge between a request and a response. Learn how to create and apply middleware to protect your routes and manage HTTP requests.

- Creating Middleware
- Registering Middleware
- Middleware Parameters

### Custom Middleware 

- Creating and using custom middleware.
- Middleware parameters and how to pass data to middleware.

### Blade Templating

Blade is Laravel’s powerful templating engine. It allows you to create clean, readable templates with minimal effort.

- Blade Syntax
- Blade Components
- Layouts and Sections
- Laravel Blade Components
	- [https://www.youtube.com/playlist?list=PL1JpS8jP1wgAm1z3ntJZQ0ef9vokjJ56Z]
	- [https://www.youtube.com/watch?v=7E76PPoIVW4]

### Database and Eloquent ORM

Laravel's Eloquent ORM provides a beautiful, simple ActiveRecord implementation for working with your database.

- Migrations
- Eloquent Models
- Query Builder
- Eloquent Relationships
	- [https://www.youtube.com/playlist?list=PL1JpS8jP1wgA7YIkG5pJDa0XwvonK-mQR]
- Eloquent Querying Relationships
	- [https://www.youtube.com/playlist?list=PL1JpS8jP1wgBXWb3YmpoVU7yQj4ka1GuG]
- Eloquent Advanced Relationships
	- [https://www.youtube.com/playlist?list=PL2DahmvUpeuv2VgLKcR20-jwSFdugNBzG]
	
### Database Optimization

- Indexing and optimizing queries for better performance.
- Using caching to optimize Eloquent queries.
- Understanding the Query Log and database profiling.

### Authentication 

Authentication is a key aspect of web applications. Laravel makes it easy to implement authentication out of the box.

- Basic Authentication
- Laravel Breeze
- Roles and Permissions

### Service Container and Dependency Injection

- Service Container: Understanding how Laravel’s service container works is crucial for managing class dependencies and performing dependency injection.
- Binding and Resolving: Understanding how to bind classes and interfaces into the service container and resolve them.
- Service Providers: Understand how service providers work to register bindings and perform bootstrapping tasks.


### Service Providers

- Custom Service Providers: Create your own service providers to encapsulate and modularize functionality.
- Deferred Providers: Explore how to load service providers only when they are needed, optimizing performance.

### Queues and Jobs

- Queueing Systems: Laravel's built-in queue system allows you to defer the processing of time-consuming tasks, such as sending emails, until later.
- Job Dispatching: Learn how to dispatch jobs to different queues.
- Queue Workers: Understand how to run and manage queue workers, and how to configure different queue drivers like Redis or Amazon SQS.

### Testing

- Unit Testing: Write tests for your application’s logic using PHPUnit and Laravel’s testing utilities.
- Feature Testing: Test entire features of your application, including HTTP requests and responses.
- Mocking and Fakes: Use Laravel’s testing helpers to mock external services and test components in isolation.

### Task Scheduling

- Scheduler: Utilize Laravel’s task scheduler to automate repetitive tasks by defining schedules in the app/Console/Kernel.php file.
- Scheduling Artisan Commands: Schedule commands and tasks that should run periodically.

### Packages Development

- Creating Packages: Learn how to create reusable packages that can be shared across multiple Laravel projects.
- Package Discovery: Understand how Laravel automatically discovers and registers packages using package discovery.

### API Development

- RESTful APIs: Build RESTful APIs using Laravel’s routing and resource controllers.
- API Resources: Use API resources and transformers to format your API responses.
- Rate Limiting and Throttling: Protect your API from abuse by implementing rate limiting.

### Performance Optimization

- Caching: Use Laravel’s caching mechanisms to store frequently accessed data.
- Route Caching: Optimize route loading by caching your routes.
- Config Caching: Speed up your application by caching configuration files.

	- [https://summonshr.medium.com/the-7-levels-of-laravel-optimization-from-rookie-to-optimization-overlord-with-benchmark-49009488419b]

### File Storage

- Storage Facade: Learn how to use Laravel’s storage facade to manage file uploads, downloads, and storage across different disk drivers (local, Amazon S3, etc.).
- Cloud Storage: Integrate cloud storage services and manage files in distributed environments.

### Security

- CSRF Protection: Ensure that your forms are protected against cross-site request forgery.
- Encryption: Utilize Laravel’s built-in encryption services to secure sensitive data.
- Authentication Guards: Implement and customize different authentication guards to manage user sessions and API tokens.
	- [https://laravel-news.com/laravel-sessions?ref=dailydev]

### Custom Artisan Commands

- Creating Commands: Write custom Artisan commands to automate tasks and enhance your workflow.
- Interactive Commands: Create commands that interact with the user through the command line.

### Localization

- Multilingual Support: Add support for multiple languages in your application.
- Language Files: Manage translations using Laravel language files.

### Single Page Applications (SPA) with Laravel

- Vue.js Integration: Build dynamic SPAs using Vue.js with Laravel.
- Inertia.js: Use Inertia.js to create SPAs without an API.

### Laravel Nova

- Admin Panel: Explore Laravel Nova for building beautiful and fully customizable admin panels.
- Custom Tools and Resources: Extend Nova with custom tools, cards, and resources.

### Event Sourcing

- Event Sourcing Concepts: Learn how to use event sourcing in Laravel applications to track all changes to your application state as a series of events.

### Laravel Mix

- Introduction to Laravel Mix for managing frontend assets like CSS, JavaScript, and more.
- Using Laravel Mix for compiling Sass, Less, and JavaScript files.

### API Throttling and Rate Limiting

- Implementing rate limiting for API routes.
- Customizing rate limiting logic for different user roles and for some other conditions.

### Real time Broadcasting

- Using Laravel Echo for real-time events.
- Setting up broadcasting with Pusher, Redis, or other drivers.
- Using channels and broadcasting events.

### Dependency Injection and Service Container

- Understanding dependency injection in Laravel.
- Binding services into the service container.
- Using dependency injection in controllers, routes, and commands.

### Advanced Validation

- Custom validation rules and creating custom rule classes.
- Conditional validation logic using sometimes() and required_if.

### Custom Error Pages

- Customizing the default error pages (404, 500, etc.).
- Using Blade templates for custom error pages.

### Laravel Sanctum

- Setting up Laravel Sanctum for API authentication.
- Using tokens for single-page applications (SPAs).

### Laravel Dusk

- Browser testing with Laravel Dusk.
- Writing and running automated browser tests.

### Setting Up Continuous Integration (CI) for Laravel Projects

- Integrating CI tools like GitHub Actions or GitLab CI.
- Running tests and deployment scripts through CI pipelines.

### Laravel Core Structure
 
- Deep dive into Laravel’s core files and directory structure.
- Exploring Illuminate and Foundation packages.

### Laravel Plugins

- Top 10 Laravel Plugins
	[https://blog.stackademic.com/top-10-laravel-plugins-d7786e9ceb02]
	[https://laravel-news.com/laravel-seo-honeystone?ref=dailydev]
	
### Useful Links

- Upload Files in Laravel [https://devdojo.com/inspector/upload-file-in-laravel?ref=dailydev]
- Serverless Search using Laravel and the Typesense Cloud [https://laravel-news.com/serverless-search-laravel-typesense]
- Laravel File Uploader: A Production-Ready Guide[https://medium.com/@raiyanmemon/laravel-file-uploader-a-production-ready-guide-5e3278a5de27]
- Notify me! Using Laravel 11 and FCM[https://medium.com/@yacine.superieut/notify-me-using-laravel-and-fcm-fd5d3caccaaa]
- Laravel guide for React developers [https://www.luckymedia.dev/blog/laravel-guide-for-react-developers]
- A Golang framework for web artisans. Tribute to Laravel. [https://app.daily.dev/posts/goravel-goravel-a-golang-framework-for-web-artisans-tribute-to-laravel--fovma8ckq]
- Laravel groupBy Full Code Example [https://postsrc.com/code-snippets/laravel-group-by-full-code-example]
- Laravel Handle Queue Jobs Asynchronously [https://dev.to/devmahfuz/php-is-a-single-threaded-language-so-how-does-laravel-handle-queue-jobs-asynchronously-5dgc]
- Laravel Inertia Nav Link Component [https://postsrc.com/code-snippets/laravel-inertia-nav-link-component]
- Laravel Get Total Relationship Count [https://postsrc.com/code-snippets/laravel-get-total-relaionship-count]
- Seven Level’s of Laravel Optimiztion [https://summonshr.medium.com/the-7-levels-of-laravel-optimization-from-rookie-to-optimization-overlord-with-benchmark-49009488419b]
- Laravel Nova vs Filament: The Best Admin Panels [https://dev.to/varzoeaa/laravel-nova-vs-filament-the-best-admin-panels-5f9a]
- reCAPTCHA in PHP within minutes [https://featuredeveloper.blogspot.com/2024/05/recaptcha-in-php-within-minutes.html]
- Laravel on any Developer Machine with Gitpod [https://laravel-news.com/laravel-on-any-developer-machine-with-gitpod]
- Make 5x faster outbound requests in Laravel [https://aaronfrancis.com/2024/make-5x-faster-outbound-requests-in-laravel-192e8e98]
- Cancel a Specific Batch of Queued Jobs With This Laravel Package [https://laravel-news.com/cancel-a-specific-batch-in-laravel]
- Laravel Advanced Problem-Solving Quiz [https://quizapi.io/predefined-quizzes/laravel-advanced-problem-solving-quiz]
- How do I deploy my Laravel applications using Github Action [https://achyutneupane.medium.com/how-do-i-deploy-my-laravel-applications-using-github-action-ebb2c0a79e8f]
- Laravel 11 Middleware Configuration: A Comprehensive Guide [https://dev.to/bhaidar/laravel-11-middleware-configuration-a-comprehensive-guide-1lic]
- Laravel Nova 5.0 Now Available [https://blog.laravel.com/laravel-nova-5-now-available]
- Access Request Data Fluently in Laravel 11.34 version [https://laravel-news.com/laravel-11-34-0]
- In Laravel, always use the env() within config files and nowhere else [https://dev.to/tkouleris/in-laravel-always-use-the-env-within-config-files-and-nowhere-else-3823]
- Wirechat A Robust Laravel Livewire chat Packages [https://app.daily.dev/posts/wirechat---a-robust-laravel-livewire-chat-package-bpmqkzweh]
- File Manager Package for Livewire [https://laravel-news.com/file-manager-package-for-livewire]
- Converting Laravel Models to JSON for API Responses [https://laravel-news.com/toJson]
- Using AI to Manage Translations in Laravel [https://laravel-news.com/using-ai-to-manage-translations-in-laravel]
- Customizing Model Date Formats in Laravel [https://laravel-news.com/date-formats]
- For Fixes for Property on Null Error in laravel[https://www.youtube.com/watch?v=YJZ0VGYrVio]
- Laravel Livewire Crash Course [https://www.youtube.com/watch?v=bkoJyn8hg5k]
- Laravel Policies: Add Custom Methods [https://www.youtube.com/watch?v=PO7NXcYcdds]
- 10 Simple Laravel Interview Questions [https://quizapi.io/predefined-quizzes/10-simple-laravel-interview-questions]
- Using 1password for Laravel environment variables [https://freek.dev/2769-using-1password-for-laravel-environment-variables]
- Automated API documentation of Laravel API resources [https://laravel-news.com/automated-api-documentation-of-laravel-api-resources]
- PHP & Laravel running natively on iOS [https://app.daily.dev/posts/php-laravel-running-natively-on-ios-glckxiolx]
- A Laravel Package to Use the Deepseek API With V3 AI Models [https://laravel-news.com/deepseek-laravel]
- Laravel Authentication Tutorial #6 - Logging Users In [https://www.youtube.com/watch?v=TwdVGN_AlPM]
- Laravel CRUD: 15+ Questions to Solve [https://www.youtube.com/watch?v=S2xTVFsZyCM]
- Create GitHub Issues from Exceptions and Logs in Laravel [https://laravel-news.com/create-github-issues-from-exceptions-and-logs-in-laravel]
- Interactive Console Commands in Laravel [https://laravel-news.com/interactive-console-commands]
- Laravel Rewind is a Versioning Package for Eloquent [https://laravel-news.com/laravel-rewind-eloquent-versioning]
- Working with JSON Attributes Using Laravel's Array Casts [https://laravel-news.com/json-attributes-array-casts]
- Laravel Mix vs Vite: Why did Laravel Transitioned to Vite [https://dev.to/varzoeaa/laravel-mix-vs-vite-why-did-laravel-transitioned-to-vite-2k25]
- New Eloquent Relation Existence Methods in Laravel 11.37 [https://laravel-news.com/laravel-11-37-0]
- Integrating Web Sockets in Laravel via Pusher [https://medium.com/@raiyanmemon/integrating-web-sockets-in-laravel-via-pusher-044166a8bfe1]
- Laravel SpaceOCR: Parse Images and Multi-page PDFs in Laravel [https://laravel-news.com/laravel-spaceocr]
- 18 Tips to optimize laravel database queries [https://dudi.dev/optimize-laravel-database-queries/]
- 10 Simple Laravel Interview Questions [https://quizapi.io/predefined-quizzes/10-simple-laravel-interview-questions]
- Essential Laravel Commands Every Developer Should Know [https://dev.to/thedevricha/essential-laravel-commands-every-developer-should-know-5c04]
- Livewire Crash Course: Creating and Enhancing Page Components [https://app.daily.dev/posts/livewire-crash-course-creating-and-enhancing-page-components-lz33cdto7]
- Open Telemetry Package for Laravel [https://laravel-news.com/laraotel-opentelemetry-package-for-laravel]
- A Package to Manage Model Status in Laravel [https://app.daily.dev/posts/a-package-to-manage-model-status-in-laravel-r6icf8gaf]
- Handling Missing Request Data in Laravel [https://laravel-news.com/handling-missing-request-data]
- Laravel Security Guide: Preventing Hack Attempts [https://app.daily.dev/posts/laravel-security-guide-preventing-hack-attempts-dkhkunqxs]
- An Introduction to Laravel Queues and Temporary URLs [https://www.thisdot.co/blog/an-introduction-to-laravel-queues-and-temporary-urls]
- Advanced Laravel Concepts: A Developer Guide for Senior Roles [https://medium.com/@khouloud.haddad/advanced-laravel-concepts-a-developer-guide-for-senior-roles-5c9409df4d28]
- Tim Leland: URL Shorteners, browser extensions, and more [https://laravel-news.com/tim-leland]
- How to document multiple APIs in Laravel with Scramble [https://laravel-news.com/how-to-document-multiple-apis-in-laravel-with-scramble]
- Boost Your SEO with Laravel Slugify [https://medium.com/@h.ghorashi/boost-your-seo-with-laravel-slugify-9a3856797696]
- Five Practical Tips to Improve Search in Laravel Apps With Typesense [https://tighten.com/insights/five-practical-tips-to-improve-search-in-laravel-apps-with-typesense/]
- First Factor One-Time Passwords for Laravel with OTPZ [https://laravel-news.com/otpz]
- Unorthodox Monoliths in Laravel [https://freek.dev/2817-unorthodox-monoliths-in-laravel]
- Advanced Authorization methods in Laravel [https://juststeveking.com/articles/advanced-authorization-methods-in-laravel/]
- Auto-Redirect Logged-In Users from Homepage [https://www.youtube.com/watch?v=cHeoWIt8S64]
- Manage Metadata on Laravel Eloquent Models with JSON Support [https://laravel-news.com/manage-metadata-on-laravel-eloquent-models-with-json-support]
- Working with JSON Attributes Using Laravel's Array Casts [https://laravel-news.com/json-attributes-array-casts]
- Running Laravel Octane on local host with FrankenPHP & Laravel Herd [https://devdojo.com/tinahammar/running-laravel-octane-on-local-host-with-frankenphp-laravel-herd]
- Supercharge Your Laravel Development with the Laravel Wow VSCode Extension [https://app.daily.dev/posts/supercharge-your-laravel-development-with-the-laravel-wow-vscode-extension-e80gmzhff]
- Monitor Every Request in your application with Laravel Telescope [https://medium.com/@raiyanmemon/monitor-every-request-in-your-application-with-laravel-telescope-5a7ec562966e]
- Laravel Queues Speed Test - Generate 5,000 PDFs [https://www.youtube.com/watch?v=CLZTniuU_fA]
- Mastering PHP Fibers: A Game-Changer in Concurrency Programming [https://medium.com/@arifhossen.dev/mastering-php-fibers-a-game-changer-in-concurrency-programming-a2a66b3f1448]
- Packistry is a Self-hosted Composer Repository Made with Laravel [https://laravel-news.com/packistry-is-a-self-hosted-composer-repository-made-with-laravel]
- Log requests and responses in Laravel [https://medium.com/@mehhfooz/log-requests-and-responses-in-laravel-f859d1f47b74]
- Laravel Livewire Crash Course - Validation Rules [https://www.youtube.com/watch?v=KD2whSRsMtg]
- Laravel Livewire Crash Course - Faster Navigation [https://www.youtube.com/watch?v=1rWOCK6iciE]
- Dagger Components: A Powerful Alternative to Laravel Blade Components [https://laravel-news.com/dagger]
- Laravel 12: Install Breeze Starter Kit [https://www.youtube.com/watch?v=oLK29lOiKfY]
- Route bind For Model Binding Resolution Logic In Laravel [https://msamgan.com/routebind-for-model-binding-resolution-logic-in-laravel]
- Laravel IDEA v10 [https://laravel-news.com/laravel-idea-v10]
- Optimize with Smart Caching [https://medium.com/@raiyanmemon/stop-slow-laravel-apps-optimize-with-smart-caching-e7fe7f2be534]
- Laravel Service Repository Pattern [https://medium.com/@devajayantha/laravel-service-repository-pattern-my-experience-and-key-benefits-afa985cd8b18]
- VILT vs TALL Stack: Choosing the Right Approach for Your Next Laravel Project [https://icreatorstudio.com/blog/vilt-vs-tall-stack]
- Everything we know about Laravel [https://laravel-news.com/everything-we-know-about-laravel-12]
- Seamless Document Conversion in Laravel With Docswap [https://laravel-news.com/seamless-document-conversion-in-laravel-with-docswap]
- Temporary Context Scope in Laravel 12.1 [https://laravel-news.com/laravel-12-1-0]
- Level up your Laravel development with Typesense [https://laravel-news.com/level-up-your-laravel-development-with-typesense]
- Simplified HTTP Response Mocking in Laravel Tests [https://laravel-news.com/simplified-http-response-mocking]
- Laravel 12 Livewire Starter Kit: First CRUD [https://www.youtube.com/watch?v=o237gJQV3MA]
- Eloquent Relationship Queries in Laravel with whereRelation [https://laravel-news.com/whereRelation]
- Laravel Custom Role Permission [https://medium.com/@shakil3334426/laravel-custom-role-permission-289e18512eb0]
- Manage Global Data in Laravel with the World Package [https://laravel-news.com/manage-global-data-in-laravel-with-the-world-package]
- Laravel MongoDB 5.2 Released: Support for Laravel 12, Laravel Scout, Vector Search, and more [https://laravel-news.com/laravel-mongodb-5-2]
- How Do You Set Cookie Consent in Laravel? [https://dev.to/themeselection/how-do-you-set-cookie-consent-in-laravel-iop]
- Enhancing Laravel Authorization with Backed Enums [https://laravel-news.com/authorization-backed-enums]
- Control Hardware Components in Laravel with Pinout [https://laravel-news.com/control-hardware-components-in-laravel-with-pinout]
- Streamline Your Laravel Models with Stringable Attributes [https://laravel-news.com/attributes-as-stringable]
- Use Filament as Laravel Starter Kit [https://www.youtube.com/watch?v=U0vMdj1h1xM]
- How to UPDATE Laravel Starter Kits? [https://www.youtube.com/watch?v=yRrd3adaR9Y]
- Livewire Starter Kit: Switch Flux to Flowbite [https://www.youtube.com/watch?v=sZhGXtEfT58]
- Laravel Vue Starter Kit: Custom Page, Menu and Shadcn [https://www.youtube.com/watch?v=Mcl5yGN_Bu8]
- Simple Cookie Consent Package for Laravel [https://laravel-news.com/simple-cookie-consent-packge-for-laravel]
- Laravel Starter Kits: A New Beginning for Your Next Project [https://blog.laravel.com/laravel-starter-kits-a-new-beginning-for-your-next-project]
- Resource Response Customization in Laravel APIs [https://laravel-news.com/withresponse]
- Solo Dumps for Laravel [https://laravel-news.com/solo-dumps-for-laravel]
- Laravel APIs: 3 Bad Practices [https://www.youtube.com/watch?v=VIEbKXeG7rU]
- Generate Documentation in Laravel with AI [https://laravel-news.com/docudoodle-laravel-ai-documentation]
- Generate Persistent Unique Values in Laravel [https://laravel-news.com/generate-persistent-unique-values-in-laravel]
- A guide to custom model casts in Laravel [https://www.honeybadger.io/blog/custom-laravel-casts/]
- Support for Query Builder Pipelines in Laravel 12.4 [https://laravel-news.com/laravel-12-4-0]
- Eloquent Cast for HTML Strings in Laravel [https://laravel-news.com/eloquent-cast-for-html-strings-in-laravel]
- Feature Flags with Laravel Pennant [https://laravel-news.com/feature-flags-with-laravel-pennant]
- Laravel Wayfinder [https://devdojo.com/tnylea/laravel-wayfinder]
- Local Model Scopes in Laravel with the Scope Attribute [https://laravel-news.com/local-model-scopes-in-laravel-with-the-scope-attribute]
- A cookieless, cache-friendly image proxy in Laravel [https://aaronfrancis.com/2025/a-cookieless-cache-friendly-image-proxy-in-laravel-inspired-by-cloudflare-9e95f7e0]
- Why You Should Use a GDPR-Compliant Cookie Consent in Your Laravel Project [https://medium.com/@devrabiul/why-you-should-use-a-gdpr-compliant-cookie-consent-in-your-laravel-project-e1c4fd0fa5eb]
- Implementing Multitenancy in Laravel [https://freek.dev/2841-implementing-multitenancy-in-laravel]
- 6 Laravel Tips from Senior Developer Benjamin [https://www.youtube.com/watch?v=QCpFKZcQBog]
- Laravel Unique [https://laravel-news.com/laravel-unique]
- Laravel Herd Raycast Extension [https://laravel-news.com/laravel-herd-raycast-extension]
- Post-Process Query Results Elegantly with Laravel's afterQuery Method [https://laravel-news.com/afterQuery]
- Cursor YOLO-mode: Which Laravel Commands to Allow? [https://www.youtube.com/watch?v=BxG2hJIDQmI]
- Laravel Test Assertions Package [https://laravel-news.com/laravel-test-assertions-package]
- 13 Laravel Tips in 10 Minutes: March 2025 [https://www.youtube.com/watch?v=xHaiAeYsn3I]
- Enhancing Database Error Diagnostics with Laravel's getRawSql [https://laravel-news.com/getrawsql]
- Laravel Cookie Consent [https://laravel-news.com/laravel-cookie-consent]
- Memoized Cache Driver in Laravel 12.9 [https://laravel-news.com/laravel-12-9-0]
- Laravel Code Example: Livewire, Service, Unit Tests, and OpenAI [https://www.youtube.com/watch?v=-f6m98mSI5g]
- Laravel Simple RabbitMQ Package [https://laravel-news.com/laravel-simple-rabbitmq-package]
- Laravel Toaster Magic [https://laravel-news.com/laravel-toaster-magic]
- Laravel Cookie Consent [https://laravel-news.com/laravel-cookie-consent]
- Top 20 Laravel Packages Every Developer Should Know in 2025  [https://medium.com/@devrabiul/top-20-laravel-packages-every-developer-should-know-in-2025-d3d903b42c3c]
- Livewire in 11 Minutes: Main Things You Need to Know [https://www.youtube.com/watch?v=9Ya6MvJPQ54]
- Verifying Exception Reporting in Laravel with assertReported [https://laravel-news.com/exception-assertreported]
- DevOps With Laravel: Queues and Workers in Production [https://freek.dev/2846-devops-with-laravel-queues-and-workers-in-production]
- Habits I recommend to succeed as a developer [https://www.saiyangrowthletter.com/p/habits-i-recommend-to-succeed-as]
- Tricking Laravel Into Auto-Loading Routes [https://msamgan.com/tricking-laravel-into-auto-loading-routes]
- Track Job Progress and Status in Laravel with the Laravel Job Status Package [https://laravel-news.com/laravel-job-status-package]
- Mastering Laravel’s Advanced Eloquent: Best Practices for Complex Queries [https://medium.com/@mohamadshahkhajeh/mastering-laravels-advanced-eloquent-best-practices-for-complex-queries-b15a0f60d2d4]
- Laravel Observers vs Event Listeners: What’s the Difference [https://freek.dev/2847-laravel-observers-vs-event-listeners-whats-the-difference]
- A first look at Laravel Nightwatch [https://laravel-news.com/a-first-look-at-laravel-nightwatch]
- HTTP Caching APIs with Laravel and Vapor [https://apisyouwonthate.com/blog/http-caching-for-laravel-vapor/]
- Revolutionize Laravel Email Creation System [https://github.com/maantje/laravel-react-email]
- Safely Retry API calls in Laravel [https://laravel-news.com/idempotency-laravel-package]
- Top 3 Mistakes with Roles/Permissions in Laravel [https://www.youtube.com/watch?v=2nMpZYEVhkI]
- Livewire and Inertia: how we love and use both at Spatie [https://freek.dev/2852-livewire-and-inertia-how-we-love-and-use-both-at-spatie]
- A package to handle passkeys in Laravel [https://freek.dev/2854-a-package-to-handle-passkeys-in-laravel]
- Populate is a Supercharged Seeder for Laravel [https://laravel-news.com/populate]
- BelongsToMany vs Polymorphic: Performance Benchmark [https://www.youtube.com/watch?v=wwbGIfk0vfc]
- Five levels of handling images in Laravel [https://freek.dev/2857-five-levels-of-handling-images-in-laravel]
- Managing Encrypted Environment Variables In Laravel With Veil [https://laravel-news.com/veil-managing-encrypted-environment-variables]
- Laravel Auth with Phone and OTP SMS [https://www.youtube.com/watch?v=SeNk60KCV1U]
- NativePHP for Mobile: Demo Laravel Project [https://www.youtube.com/watch?v=NBNYJsMbo70]
- Auto-translate Application Strings with Laratext [https://laravel-news.com/auto-translate-application-strings-with-laratext]
- Five levels of handling images in Laravel [https://freek.dev/2857-five-levels-of-handling-images-in-laravel]
- Stress-Testing Laravel App Performance with k6 and Http Client [https://www.youtube.com/watch?v=CikyLcP31Kw]
- 8 Security Best Practices in Laravel [https://medium.com/@dsjayamal/8-security-best-practices-in-laravel-ad7513798cfb]
- Simplifying work with custom stubs in Laravel [https://freek.dev/2860-simplifying-work-with-custom-stubs-in-laravel]
- Streamline API Resources with Laravel's Fluent Methods [https://laravel-news.com/api-resources-fluent-methods]
- A package to handle one-time passwords (OTP) in Laravel apps [https://freek.dev/2864-a-package-to-handle-one-time-passwords-otp-in-laravel-apps]
- OAuth2 server implementation using Laravel [https://github.com/muhammadsanwarulislam/oauth2-laravel]
- 3 Laravel Security Features You Need to Know [https://medium.com/@aramayis_m/3-laravel-security-features-you-need-to-know-with-examples-54004d143d2d]
- Volet is a Customer Feedback Widget for Laravel [https://laravel-news.com/volet-is-a-customer-feedback-widget-for-laravel]
- Building a Complete Blog API with Laravel API CRUD Generator [https://medium.com/@davidrai441/building-a-complete-blog-api-with-laravel-api-crud-generator-7349f46f046e]
- ElasticLens: Eloquent-Powered Elasticsearch for Laravel [https://laravel-news.com/elasticlens-eloquent-powered-elasticsearch-for-laravel]
- Mastering The Laravel App Service Pattern [https://jotonsutradhar.com/blogs/mastering-the-laravel-app-service-pattern-15]
- laravel-taxonomy [https://github.com/aliziodev/laravel-taxonomy]
- Alpine.js Open-Source Example by Spatie: PHP Operators (no Livewire) [https://www.youtube.com/watch?v=RVigaDLJbZM]
- Supercharge Your Laravel App With Queues – A Developer’s Experience With Background Email Sending [https://jotonsutradhar.com/blogs/supercharge-your-laravel-app-with-queues-a-developers-experience-with-background-email-sending-]
- Laravel Routing: Explained in 3 Minutes [https://www.youtube.com/watch?v=157RdwN2pzM]
- 3 Tools to Draw/Manage Database Schema [https://www.youtube.com/watch?v=Kh5-WohujJc]
- Efficiently remove expired cache data with Laravel Cache Evict [https://laravel-news.com/laravel-cache-evict]
- 11 Laravel Packages for User Extra Behavior [https://www.youtube.com/watch?v=KlhmXKZ7jm8]
- High-Traffic Optimization with Cache, Queue & Session Tactics [https://medium.com/@mohamadshahkhajeh/laravel-under-pressure-high-traffic-optimization-with-cache-queue-session-tactics-8d22ca5848c3]
- Laravel File Viewer [https://github.com/vish4395/laravel-file-viewer]
- Bring Laravel Tinker to Your Browser with PHP DevTools Console [https://fullstackintellect.com/bring-laravel-tinker-to-your-browser-with-php-devtools-console-25d8461d4941]
- A package to handle the SEO in any Laravel-application [https://ralphjsmit.com/laravel-seo-package]
- Level Up Your Laravel Forms with These 5 Validation Tricks [https://medium.com/@developerawam/level-up-your-laravel-forms-with-these-5-validation-tricks-eaeb42014425]
- Laravel Migration With Schema Validation in MongoDB [https://laravel-news.com/laravel-migration-with-schema-validation-in-mongodb]
- On Laravel, Full-Stack JavaScript, and Productive Frameworks [https://www.jplhomer.org/posts/on-laravel-full-stack-javascript-and-productive-frameworks/]
- Manage Taxonomies, Categories, and Tags in Laravel [https://laravel-news.com/laravel-taxonomy]
- Laravel Service Repository Pattern: My Experience and Key Benefits [https://medium.com/@devajayantha/laravel-service-repository-pattern-my-experience-and-key-benefits-afa985cd8b18]
- Larallow is a Permissions Package With Support for Scopes [https://laravel-news.com/larallow-laravel-permissions-package].
- FrankenPHP with Laravel can do a magical thing [https://freek.dev/2620-frankenphp-with-laravel-can-do-a-magical-thing]
- Manipulate Image URLs in Laravel with the Image Transform Package [https://laravel-news.com/laravel-image-transform-url]
- Filament Plugin: PDF Preview After Upload [https://github.com/AsmitNepali/filament-upload]
- Test Deferred Operations Easily with Laravel's withoutDefer Helper [https://laravel-news.com/withoutdefer]
- Lightning Fast Schedule Management for Laravel [https://laravel-news.com/lightning-fast-schedule-management-for-laravel]
- Grouping and Filtering Data Faster with groupBy() & having() in Laravel [https://medium.com/@developerawam/grouping-and-filtering-data-faster-with-groupby-having-in-laravel-5519e62ed4dd]
- Laravel Migrations Foreign ID: Do You Specify Table Name? [https://www.youtube.com/watch?v=GCF9j-Rbo_M]
- 11 Laravel Packages for User Extra Behavior [https://www.youtube.com/watch?v=KlhmXKZ7jm8&t=3s]
- Building a Task Reminder With Laravel and MongoDB [https://laravel-news.com/building-a-task-reminder-with-laravel-and-mongodb]
- larastan/larastan Adds code analysis to Laravel improving developer productivity and code quality. [https://github.com/larastan/larastan]
- Translate Your App to Other Languages With Laravel Gemini Translator [https://laravel-news.com/laravel-gemini-translator]
- Laravel Performance Testing With Volt-Test PHP [https://laravel-news.com/laravel-volt-test-php] 
- Laravel Request Content Type Inspection Methods [https://laravel-news.com/request-accepts]
- 3 Ways How Devs Use Vue.js in Laravel [https://www.youtube.com/watch?v=JPFevHc5i8k] 
- Laravel AI Chat Starter Kit [https://laravel-news.com/laravel-ai-chat-starter-kit]
- Laravel Shortcuts: 5 Simple Functions to Speed Up Your Coding Workflow [https://medium.com/@developerawam/laravel-shortcuts-5-simple-functions-to-speed-up-your-coding-workflow-8718f4188c5a]
- A Security Checklist for Your Laravel App Before You Hit Deploy [https://app.daily.dev/posts/a-security-checklist-for-your-laravel-app-before-you-hit-deploy-balfwtns3]
- Livewire Doctor [https://github.com/devrabiul/livewire-doctor] 
- Laravel: Complex Pricing Structure for E-Commerce (Flight Check-in Demo) [https://www.youtube.com/watch?v=0QFkKjVCLeg]
- Laravel + Node.js: PHP in Watt Runtime [https://blog.platformatic.dev/laravel-nodejs-php-in-watt-runtime]
- Laravel's toUri() Method for Dynamic URL Construction [https://laravel-news.com/touri]
- Upload Large Files with Filepond and Chunks [https://www.youtube.com/watch?v=xxo2uX5HoM8]
- Laravel Serializable Closure: serialize the unserializable [https://freek.dev/2886-laravel-serializable-closure-serialize-the-unserializable]
- Blade Service Injection: Direct Service Access in Laravel Templates [https://laravel-news.com/blade-inject]
- NativePHP: Build Mobile App with Laravel (Example of Event App) [https://www.youtube.com/watch?v=oyMTvnPUTqY]


### TALL Stack Development

- The TALL stack is a modern web development solution that combines four key technologies:

	- Tailwind CSS for utility-first styling
	- Alpine.js for minimal JavaScript interactions
	- Laravel as a robust PHP framework
	- Livewire for seamless server-side rendering without extensive JavaScript.