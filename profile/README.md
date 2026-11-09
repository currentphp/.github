# WavyKit

One description of your Laravel app's experience — where users are, how they
move around, and what they see — that every part of the interface reads.

Laravel has primitives for handling requests, but none for the experience
around them, so route names, breadcrumb arrays, menu configuration, and page
headings tend to drift apart. WavyKit lets you define each page once and have
breadcrumbs and menus read from that definition. Routes, controllers,
authorization, and rendering stay with your application.

```sh
composer require wavykit/core
```

| Package | |
| --- | --- |
| [`wavykit/core`](https://github.com/wavykit/wavykit/tree/main/packages/core) | Pages, breadcrumbs, and menus for Laravel 13 and PHP 8.3+. [Packagist](https://packagist.org/packages/wavykit/core) |

Development happens in the [`wavykit/wavykit`](https://github.com/wavykit/wavykit)
monorepo; package repositories such as `wavykit/core` are read-only mirrors.
See [Direction and decisions](https://github.com/wavykit/wavykit/blob/main/docs/decisions.md)
for what is planned, and [CONTRIBUTING.md](https://github.com/wavykit/wavykit/blob/main/CONTRIBUTING.md)
for how to give feedback.

Questions or feedback: [hello@wavykit.com](mailto:hello@wavykit.com) ·
[wavykit.com](https://wavykit.com)
