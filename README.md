![logo](https://akhikhl.github.io/gretty/media/gretty_logo_1.x.png "gretty logo")

[![Build Status](https://travis-ci.org/gretty-gradle-plugin/gretty.svg?branch=master)](https://travis-ci.org/gretty-gradle-plugin/gretty)
![Maintenance Status](https://img.shields.io/maintenance/yes/2019.svg)
[![Latest release](https://img.shields.io/badge/release-3.0.1-47b31f.svg)](https://github.com/gretty-gradle-plugin/gretty/tree/v3.0.1)
[![Snapshot](https://img.shields.io/badge/current-3.0.2--SNAPSHOT-47b31f.svg)](https://github.com/gretty-gradle-plugin/gretty/tree/master)
[![License](https://img.shields.io/badge/license-MIT-47b31f.svg)](#copyright-and-license)

Gretty is a feature-rich gradle plugin for running web-apps on embedded servlet containers.
It supports Jetty versions 7, 8 and 9, Tomcat versions 7, 8 and 9, multiple web-apps and many more.
It wraps servlet container functions as convenient Gradle tasks and configuration DSL.

A complete list of Gretty features is available in [feature overview](https://gretty-gradle-plugin.github.io/gretty-doc/Feature-overview.html).

#### Where to start

[![Join the chat at https://gitter.im/saladinkzn/gretty](https://badges.gitter.im/saladinkzn/gretty.svg)](https://gitter.im/saladinkzn/gretty?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

If you are new with Gretty, try [getting started](https://gretty-gradle-plugin.github.io/gretty-doc/Getting-started.html) page.

#### :star: What's new

December 2, 2019, Gretty 3.0.1 is out and available at [Gradle Plugins](https://plugins.gradle.org/plugin/org.gretty) and [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).

This release contains further fixes for Gradle 6.0 support.

December 1, 2019, Gretty 3.0.0 is out and available at [Gradle Plugins](https://plugins.gradle.org/plugin/org.gretty) and [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).

This release introduces Gradle 6.0 support and retires support for JDK7, Gradle versions <5.0 and Tomcat 7.x and 8.0.x.

See [complete list of changes](changes.md) for more information.

December 5, 2018, Gretty 2.3.1 is out and available at [Gradle Plugins](https://plugins.gradle.org/plugin/org.gretty) and [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).

This maintenance release addresses some issues found in Gretty 2.3.0.  See [complete list of changes](changes.md) for more information.

November 28, 2018, Gretty 2.3.0 is out and available at [Gradle Plugins](https://plugins.gradle.org/plugin/org.gretty) and [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).

This release adds support for Gradle 5.0, which was released this week!  Please raise an issue if you find any issues running Gretty 2.3+ with Gradle 5.0.

See also: [complete list of changes](changes.md) for more information.

May 21, 2018, Gretty(.org) 2.2.0 is out and immediately available at [Gradle Plugins](https://plugins.gradle.org/plugin/org.gretty) and [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).

* Changes in this version:

* Bumped default Tomcat 9 version to 9.0.6 (was 9.0.5).

* Support added for Tomcat 8.5 and Tomcat support refactoring (thanks Boris Petrov). Tomcat 8.5 replaces deprecated Tomcat 8.0.

* Bumped Spring Boot version to 1.5.9 (was 1.5.4).

* Bumped versions of asm (6.1.1, was 6.0), Groovy (2.4.15, was 2.4.13) and Spring (4.3.16, was 4.3.9) (thanks Henrik Brautaset Aronsen).

* Fixed incompatibility with java-library plugin (thanks Ollie Freeman).
 
* Dev: various build and test improvements.

See also: [complete list of changes](changes.md) for more information.

#### Documentation

You can learn about all Gretty features in [online documentation](https://gretty-gradle-plugin.github.io/gretty-doc/).

#### System requirements

Gretty requires JDK8 or JDK11 and Gradle 5.0 or newer.

- Since version 2.0.0 Gretty no longer supports JDK6.
- Since version 3.0.0 Gretty no longer supports JDK7, Gradle <5.0, Tomcat 7.x or Tomcat 8.0.x.

#### Availability

Gretty is an open-source project and is freely available in sources as well as in compiled form.

Releases of Gretty (gretty.org fork) from 2.1.0 onwards are available at [Bintray](https://bintray.com/javabrett/maven/org.gretty/view).
Old releases of Gretty up to and including version 2.0.0 are available at [Bintray](https://bintray.com/akhikhl/maven/gretty/view).

#### Copyright and License

Copyright 2013-2018 (c) Andrey Hihlovskiy, Timur Shakurov and [contributors](CONTRIBUTORS).

All versions, present and past, of Gretty are licensed under [MIT license](LICENSE).
