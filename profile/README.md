# Current

One description of your Laravel app's experience — where users are, how they
move around, and what they see — that every part of the interface reads.

Laravel has primitives for handling requests, but none for the experience
around them, so route names, breadcrumb arrays, menu configuration, and page
headings tend to drift apart. Current lets you define each page and subject
once and have breadcrumbs, menus, and your frontend read from that definition.
Routes, controllers, authorization, and rendering stay with your application.

```sh
composer require current/current
```

| Package | |
| --- | --- |
| [`current/current`](https://github.com/currentphp/monorepo/tree/main/packages/current) | Pages, breadcrumbs, menus, subjects, and actions for Laravel 13 and PHP 8.3+, with optional Inertia support. [Packagist](https://packagist.org/packages/current/current) |
| [`@currentphp/client`](https://github.com/currentphp/monorepo/tree/main/packages/client) | TypeScript types for the shared experience data, and `is()`, matching `Current::is()`. [npm](https://www.npmjs.com/package/@currentphp/client) |

Development happens in the [`currentphp/monorepo`](https://github.com/currentphp/monorepo)
repository; package repositories such as `currentphp/current` are read-only
mirrors. See [Direction and decisions](https://github.com/currentphp/monorepo/blob/main/docs/decisions.md)
for what is planned, and [CONTRIBUTING.md](https://github.com/currentphp/monorepo/blob/main/CONTRIBUTING.md)
for how to give feedback.

Current is made by Brenden Chu. Questions or feedback:
[hello@currentphp.com](mailto:hello@currentphp.com)
