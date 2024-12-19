# Laravel Study Guide

Welcome to the **Laravel Study Guide**! This repository is a comprehensive resource designed to help you learn Laravel from the ground up. Whether you are a beginner or looking to deepen your understanding of Laravel, this guide provides a structured path to mastering the framework.

## Resources
Here are some additional resources to help you learn Laravel:

- [Laravel Official Website](https://laravel.com)
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
Codecourse provides in-depth tutorials focusing on practical application development using Laravel.


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

### TALL Stack Development

- The TALL stack is a modern web development solution that combines four key technologies:

	- Tailwind CSS for utility-first styling
	- Alpine.js for minimal JavaScript interactions
	- Laravel as a robust PHP framework
	- Livewire for seamless server-side rendering without extensive JavaScript.