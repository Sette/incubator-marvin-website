---
layout: page
title: Starter Guilde
description: Project Community Page
group: nav-right
---
<!--
{% comment %}
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to you under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->

{% include JB/setup %}

# Iris Species v0.0.1

## Overview

Iris Species classification engine from Kaggle


## Requirements

_REPLACE: Add here the list of requirements. For example:_

 - Python 2.7
 - Numpy 1.11.0 or higher


## Installation

_REPLACE: Add here the best way to install this engine


## Development

### Getting started

First, create a new virtualenv

```
mkvirtualenv marvin_iris_species_engine_env
```

Now install the development dependencies

```
make marvin
```

You are now ready to code.


### Adding new dependencies

It\`s very important. All development dependencies should be added to `setup.py`.

### Running tests

This project uses *[py.test](http://pytest.org/)* as test runner and *[Tox](https://tox.readthedocs.io)* to manage virtualenvs.

To run all tests use the following command

```
marvin test
```

To run specific test

```
marvin test tests/test_file.py::TestClass::test_method
```


### Writting documentation

The project documentation is written using *[Jupyter](http://jupyter.readthedocs.io/)* notebooks. 
You can start the notebook server from the command line by running the following command

```
marvin notebook
```

Use notebooks to demonstrate how to use the lib features. It can also be useful to show some use cases.


### Bumping version

```
marvin pkg-bumpversion [patch|minor|major]
git add . && git commit -m "Bump version"
```


### Tagging version

```
marvin pkg-createtag
git push origin master --follow-tags
```


### Logging

The default log level is set to _WARNING_. You can change the log level at runtime setting another value to one of the following environment variable: `MARVIN_IRIS_SPECIES_ENGINE_LOG_LEVEL` or `LOG_LEVEL`. The available values are _CRITICAL_, _ERROR_, _WARNING_, _INFO_ and _DEBUG_.

Be careful using `LOG_LEVEL`, it may affect another lib.

----

* [Get Started](/marvin-platform-book/ch3_get_started/overview)