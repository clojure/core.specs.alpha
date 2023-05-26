core.specs.alpha
========================================

core.specs.alpha is a Clojure library containining specs to describe Clojure core macros and functions.

Clojure 1.9+ depends on this library and provides it to users of Clojure. Thus, the recommended way to use this library is to add a dependency on the latest version of Clojure 1.9+, rather than including it directly. In some cases, this library may release more frequently than Clojure. In those cases, you can explictly include the latest version of this library with the dependency info below.

NOTE: This library is alpha and subject to breaking changes. At a future point, there will be a non-alpha stable version of these specs.

For more information:

* Spec rationale - https://clojure.org/about/spec
* Spec guide - https://clojure.org/guides/spec
* Spec split notice - https://groups.google.com/forum/#!msg/clojure/10dbF7w2IQo/ec37TzP5AQAJ

Releases and Dependency Information
========================================

Latest stable release: none

* [All Released Versions](https://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.clojure%22%20AND%20a%3A%22core.specs.alpha%22)

* [Development Snapshot Versions](https://oss.sonatype.org/index.html#nexus-search;gav~org.clojure~core.specs.alpha~~~)

[deps.edn](https://clojure.org/guides/deps_and_cli) dependency information:

    org.clojure/core.specs.alpha {:mvn/version "0.2.62"}

[Leiningen](https://github.com/technomancy/leiningen) dependency information:

    [org.clojure/core.specs.alpha "0.2.62"]

[Maven](https://maven.apache.org/) dependency information:

    <dependency>
      <groupId>org.clojure</groupId>
      <artifactId>core.specs.alpha</artifactId>
      <version>0.2.62</version>
    </dependency>

Developer Information
========================================

* [GitHub project](https://github.com/clojure/core.specs.alpha)
* [Changelog](https://github.com/clojure/core.specs.alpha/blob/master/CHANGES.md)
* [Bug Tracker](https://clojure.atlassian.net/browse/CLJ)
* [Continuous Integration](https://github.com/clojure/core.specs.alpha/actions/workflows/test.yml)


Copyright and License
========================================

Copyright (c) Rich Hickey, and contributors, 2023. All rights reserved.  The use and distribution terms for this software are covered by the Eclipse Public License 1.0 (https://opensource.org/licenses/eclipse-1.0.php) which can be found in the file epl-v10.html at the root of this distribution. By using this software in any fashion, you are agreeing to be bound bythe terms of this license.  You must not remove this notice, or any other, from this software.
