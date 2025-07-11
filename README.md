# Maven parent POM for EXPath Packages in Elemental

[![Build Status](https://dl.circleci.com/status-badge/img/gh/evolvedbinary/elemental-expath-package-parent/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/evolvedbinary/elemental-expath-package-parent/tree/main)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/license/apache-2-0)
[![Maven Central](https://img.shields.io/maven-central/v/xyz.elemental.expath/elemental-expath-package-parent?logo=apachemaven&label=maven+central&color=green)](https://central.sonatype.com/search?namespace=xyz.elemental.expath)
[![Slack](https://img.shields.io/badge/elemental-slack-56b6f8.svg?logo=slack)](https://join.slack.com/t/elemental-xyz/shared_invite/zt-34r53san4-fzHCV0vDT9lYSMChUdn3cQ)
[![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-contributor%20covenant-5e0d73.svg?logo=contributorcovenant)](https://www.contributor-covenant.org/version/2/1/code_of_conduct.html)

This repository contains a Maven parent POM that you may use as the basis of your EXPath Packages for Elemental.
It defines a number of sensible defaults and versions that can help you get started quickly in your own projects.

## Using
If you would like to use this as a base for your own EXPath Package, then you can add the following to the top of your package's `pom.xml` file:

```xml
    <parent>
        <groupId>xyz.elemental.expath</groupId>
        <artifactId>elemental-expath-package-parent</artifactId>
        <version>1.1.0</version>
        <relativePath/>
    </parent>
```

If you are looking for a quick way to generate a skeleton for your EXPath Package, you should take a look at the: [elemental-expath-package-archetype](https://github.com/evolvedbinary/elemental-expath-package-archetype).
