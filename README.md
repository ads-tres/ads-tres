# Hi, I'm Abel Asrat · አቤል አስራት 👋

**Full-stack and mobile developer in Addis Ababa.** I build the software Ethiopian businesses run on: operations platforms, multi-tenant SaaS back-ends and Flutter apps in Amharic and English, with Laravel, Filament and Flutter.

[![Portfolio](https://img.shields.io/badge/Portfolio-ads--tres.github.io-6A4BC4)](https://ads-tres.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abel-asrat-870536395)
[![Email](https://img.shields.io/badge/Email-asratabel03%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:asratabel03@gmail.com)
![Location](https://img.shields.io/badge/Addis_Ababa-UTC%2B3-2E7D52)

## 🟢 Right now

- **Lead software engineer at [Ethio-Heran PLC](https://ethioherantutor.com).** I lead the operations platform that runs a home-tutoring company end to end, from hiring tutors to billing, payroll and staff exits.
- **Full-stack developer (Laravel, remote) at [Adulis Media](https://dejenehodes.com).** I'm part of the team behind a multi-tenant platform that runs five tour and art brands from one codebase.
- **Building [Kiray](#featured-work),** a rent, lease and repair tracker for small Addis Ababa landlords.
- **Open to full-stack and Flutter work,** on-site in Addis Ababa or remote.

## Featured work

| Project | The problem it solves | How it's built | Result |
|---|---|---|---|
| **Ethio Heran tutoring platform** | Replaces manual hiring, attendance, billing and payroll at a tutoring company with one system for six roles | Filament and Livewire panels over service classes, Eloquent and MySQL; a cron-driven outbox for SMS, email and Telegram; Gemini AI with model fallback | Ledgers rebuild after late approvals; failed messages retry up to 3 times; 68 access policies |
| **Tourism and commerce platform** *(team project)* | Gives five tour and art brands their own domain, design and booking on one system instead of five | Hostname middleware, global query scopes and a service layer over MySQL and Redis; Blade and Alpine.js front-end; Stripe with verified, idempotent webhooks | Listing pages held at ≤ 4 queries by a regression test; 15-step release automated on push |
| **[Gym management platform](https://github.com/azabla/gym-platform)** | Lets gyms with many branches run memberships, payments and check-ins, each paid through its own Chapa account | One versioned Sanctum REST API serving a Filament staff panel and a Flutter app, over PostgreSQL in Docker | 520+ Pest tests, Larastan and Pint in GitHub Actions on every push |
| **[Volt member app](https://github.com/ads-tres/Volt-Fitness)** | Members renew, pay and check in from their phone instead of the front desk | Flutter with Riverpod and Dio calling the gym API; Chapa checkout; a fake back-end that follows the API contract | 84 tests across 17 screens; built before the live API existed |
| **Kiray** *(in progress)* | Small landlords track rent, leases and repairs in one Amharic and English app | Flutter app calling a Laravel API with Sanctum tokens from SMS codes; PostgreSQL with per-landlord scoping and encrypted tenant IDs | 76 tests covering the city's rent-cap rule, data isolation and sign-in |
| **Flutter app designs** | SHAD e-commerce, Equb savings groups, ServerDashboard and a prediction market | Reusable widgets, go_router and fl_chart on a mock data layer shaped like an API | 52 screens, including a 26-screen shopping flow |

Full case studies are on my portfolio: **[ads-tres.github.io](https://ads-tres.github.io)**

## How I build

- **Tenant isolation by default:** scoping at the query level, so one customer's data never reaches another.
- **Tested code:** Pest and Flutter tests, with CI running on every push.
- **Payments the server can trust:** Chapa and Stripe webhooks are verified and idempotent, so each payment counts once.
- **Built for Ethiopia:** Amharic and English interfaces, the Ethiopian calendar, Addis Ababa time, SMS and Telegram.

## Stack

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Filament](https://img.shields.io/badge/Filament-FDAE4B)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?logo=livewire&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?logo=alpinedotjs&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Pest](https://img.shields.io/badge/Pest-F472B6)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)

Also: Chapa payments, AfroMessage SMS, Telegram bots, Gemini API, Sanctum, Riverpod, Dio.

## 📫 Let's talk

Have a system to build? Email **asratabel03@gmail.com** or message me on [LinkedIn](https://www.linkedin.com/in/abel-asrat-870536395).
