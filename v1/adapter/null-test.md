---
layout: default
permalink: /v1/docs/adapter/null-test/
title: Null Adapter
---

## Installation

Comes with the main Flysystem package.

## Usage

Acts like `/dev/null`

```php
$adapter = new League\Flysystem\Adapter\NullAdapter;
$filesystem = new League\Flysystem\Filesystem($adapter);
```