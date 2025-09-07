# WhatsJet Laravel Application

## Overview
This is a WhatsJet application - a Laravel-based WhatsApp business management platform that has been imported from GitHub and set up to run in the Replit environment.

## Current State
- **Status**: Basic setup complete, requires database migration for full functionality
- **Framework**: Laravel 12.x with PHP 8.2
- **Database**: Currently using SQLite with minimal configuration tables
- **Server**: Running on port 5000 via `php artisan serve`

## Project Architecture
- **Backend**: PHP Laravel framework
- **Database**: SQLite (development) - can be migrated to PostgreSQL for production
- **Frontend**: Laravel Blade templates (included in the application)
- **Configuration**: Uses custom Yantrana framework components

## Recent Changes (September 7, 2025)
- Installed PHP 8.2 and Composer dependencies
- Created basic .env configuration with SQLite database
- Generated Laravel application key
- Created minimal configurations table to resolve bootstrap errors
- Set up Laravel development server on port 5000
- Configured deployment for autoscale target
- Server is running successfully but shows database errors for missing application tables

## Dependencies Installed
- PHP 8.2 with all required extensions
- SQLite system package
- All Composer dependencies including:
  - Laravel Framework 12.x
  - WhatsApp service components
  - Payment processing (Stripe, Razorpay)
  - Various Laravel packages

## Configuration Requirements
- The application requires full database migration to be functional
- Uses custom configuration system via `configurations` table
- Requires WhatsApp API credentials and other service keys for full functionality
- Translation system is available but requires database setup

## Database Schema
- Primary database connection: SQLite (for development)
- Custom tables expected: configurations, pages, users, contacts, campaigns, etc.
- Uses Laravel's Eloquent ORM with custom Yantrana base models

## User Preferences
- Standard Laravel development workflow
- Uses Artisan commands for management
- Prefers SQLite for development, can scale to PostgreSQL for production