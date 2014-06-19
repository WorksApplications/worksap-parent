Parent Maven project
====================
This is the parent Maven project for OSS from Works Applications.  
It is easy to use, and makes your OSS life better.

[![Build Status](https://secure.travis-ci.org/WorksApplications/worksap-parent.png)](http://travis-ci.org/WorksApplications/worksap-parent)

How to use
----------
Add `<parent>` into your pom.xml.

```xml
<project>
  <parent>
    <groupId>jp.co.worksap.oss</groupId>
    <artifactId>worksap-parent</artifactId>
    <version>1.1.1</version>
  </parent>
  ...
</project>
```

Feature
-------
- Help to make your pom.xml simple
    - you do not have to write `<version>` and `<scope>` in your own pom.xml
- Help to deploy to Maven central
    - provided by [oss-parent](https://github.com/sonatype/oss-parents/tree/master/oss-parent) project

History
-------
- 1.0.0 (2013/Jan/25)
    - first release
- 1.0.1 (2013/Jan/25)
    - added license information
- 1.0.2 (2013/Apr/11)
    - upgrade dependencies
- 1.0.3 (2014/Feb/17)
    - upgrade dependencies and libraries
    - correct typo in `<name>`
    - update `<url>`
- 1.1.0 (2014/Feb/17)
    - switch from mockito-all to mockito-core
    - change jsr305 to optional dependency
- 1.1.1 (2014/Feb/21)
    - [fix wrong groupId](https://github.com/WorksApplications/worksap-parent/pull/2)
- 1.1.2 (2014/Jun/19)
    - [use thread-safe version of maven-enforcer-plugin](https://github.com/WorksApplications/worksap-parent/issues/3)
    - upgrade dependencies
    - set `3.2.1` to the value of `prerequisites.maven` to help versions-maven-plugin

License
-------
Copyright 2013 Works Applications. Co.,Ltd.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
