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
| [`current/current`](https://github.com/currentphp/monorepo/tree/main/packages/current) | Pages, breadcrumbs, menus, and subjects for Laravel 13 and PHP 8.3+. [Packagist](https://packagist.org/packages/current/current) |
| [`current/inertia`](https://github.com/currentphp/monorepo/tree/main/packages/inertia) | Shares the current page, subject, breadcrumbs, and menus with Inertia, with TypeScript types. [Packagist](https://packagist.org/packages/current/inertia) |

Development happens in the [`currentphp/monorepo`](https://github.com/currentphp/monorepo)
repository; package repositories such as `currentphp/current` are read-only
mirrors. See [Direction and decisions](https://github.com/currentphp/monorepo/blob/main/docs/decisions.md)
for what is planned, and [CONTRIBUTING.md](https://github.com/currentphp/monorepo/blob/main/CONTRIBUTING.md)
for how to give feedback. Current was named WavyKit until November 2026; the
`wavykit/*` packages are abandoned in favour of these.

Current is a [Wavy](https://wavy.dev) project. Questions or feedback:
[hello@wavy.dev](mailto:hello@wavy.dev)
