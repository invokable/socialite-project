# Socialite Demo

## Overview

This is a Laravel demonstration project showcasing various social authentication providers using Laravel Socialite and custom provider packages. The application provides a simple testing interface to authenticate with multiple social platforms.

### Included Packages

#### Socialite Providers

- **[socialite-amazon](https://github.com/invokable/socialite-amazon)** - Amazon Login with Socialite integration
- **[socialite-discord](https://github.com/invokable/socialite-discord)** - Discord OAuth provider for Laravel Socialite
- **[socialite-wordpress](https://github.com/invokable/socialite-wordpress)** - WordPress.com OAuth provider for Laravel Socialite
- **[socialite-mastodon](https://github.com/invokable/socialite-mastodon)** - Mastodon OAuth provider for Laravel Socialite

#### Laravel SDK Packages

- **[laravel-line-sdk](https://github.com/invokable/laravel-line-sdk)** - LINE SDK integration for Laravel
- **[laravel-threads](https://github.com/invokable/laravel-threads)** - Meta Threads API integration
- **[laravel-bluesky](https://github.com/invokable/laravel-bluesky)** - Bluesky AT Protocol integration

### Features

- Simple OAuth authentication testing interface
- Support for multiple social login providers
- Callback handling and user data display
- Laravel 12.x compatibility
- PHP 8.2+ support

### Usage

Visit the root URL to see available authentication providers. Click on any provider to test the OAuth flow:

- `/amazon/login` - Amazon authentication
- `/discord/login` - Discord authentication
- `/wordpress/login` - WordPress.com authentication
- `/mastodon/login` - Mastodon authentication

### Requirements

- PHP 8.2+
- Laravel 12.x
- Composer for dependency management

## Maintenance Notice

Since maintenance is infrequent, there is no guarantee that it will work with the latest versions of Laravel or PHP.
