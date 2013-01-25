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
    <version>1.0.0</version>
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