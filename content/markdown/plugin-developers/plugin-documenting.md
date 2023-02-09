title: Developers centre - Documentation Plugins Strategies
author: Vincent Siveton
date: 2006-10-01

<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->
## Introduction


 A [Guide to the Plugin Documentation Standard](../guides/development/guide-plugin-documentation.html) was created. This document is intended to verify it during the Plugins development.



## Verify Plugin Documentation


 The [maven-docck-plugin](../plugins/maven-docck-plugin) checks that a project complies with the Plugin Documentation Standard.


 You **should** verify that all Plugin documentation respects this standard. The maven-docck-plugin can be run:



```
mvn docck:check
```


## References



 - [Maven Plugin Documentation](http://cwiki.apache.org/confluence/display/MAVENOLD/Maven\+Plugin\+Documentation)


