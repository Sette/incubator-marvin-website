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

# Working in an existing engine

1. If you don't have an engine locally, clone one to your local machine

2. On Python Toolbox environment, set VirtualEnv and get to engine's path

```
marvin engine-generateenv /path/to/engine/
workon <engine_name>-env
```

3. Test your engine

```
marvin
```

4. Bring up the notebook and access it from your browser

```
marvin notebook
```

----

* [Get Started](/marvin-platform-book/ch3_get_started/overview)
