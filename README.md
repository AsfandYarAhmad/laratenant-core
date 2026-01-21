# LaraTenant-Core 🚀

[![Laravel Version](https://img.shields.io/badge/Laravel-12.x-red.svg)](https://laravel.com)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**LaraTenant-Core** is a production-ready, multi-tenant SaaS architecture built on Laravel 12. It demonstrates how to handle complex data isolation, custom domain mapping, and subscription-based feature gating in a B2B environment.

## 🌟 Key Features

- **Multi-Tenancy:** Automatic database/schema isolation using `stancl/tenancy`.
- **Domain Mapping:** Support for subdomains (`tenant.app.test`) and custom apex domains.
- **Beautiful Dashboard:** Full-featured admin panel built with **Filament PHP**.
- **Subscription Engine:** Integrated with **Laravel Cashier (Stripe)** for tiered billing.
- **Developer Experience:** 100% test coverage using **Pest PHP**.
- **Real-time Ready:** Configured for **Laravel Reverb** for instant notifications.

## 🛠 Tech Stack

- **Backend:** Laravel 12 (PHP 8.3+)
- **Frontend:** TALL Stack (Tailwind, Alpine.js, Livewire 3)
- **Admin UI:** Filament PHP v3
- **Database:** PostgreSQL (Optimized for schema-based tenancy)
- **Cache/Queue:** Redis

## 🚀 Getting Started

### Prerequisites
- PHP 8.3+
- Composer
- Docker (Laravel Sail recommended)

### Installation
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/laratenant-core.git
   cd laratenant-core
