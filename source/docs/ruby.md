---
layout: post
title: Ruby setup
category: Build sequence
---

Semaphore uses [rbenv](https://github.com/sstephenson/rbenv) for managing Ruby versions. This has no effect on builds based on other programming languages.

Before the commands are executed, we'll delete the `.ruby-version` file for you and use the selected version.

For a list of supported Ruby versions, checkout out our [stack](/docs/supported-stack.html#ruby_versions) (batteries included).
