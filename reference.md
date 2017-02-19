# Code quality metrics tools

## Sonarqube

* https://plugins.gradle.org/plugin/org.sonarqube

## Code coverage (JaCoCo)

* https://docs.gradle.org/current/userguide/jacoco_plugin.html
* https://github.com/springfox/springfox/blob/fb780ee1f14627b239fba95730a69900b9b2313a/gradle/coverage.gradle

test.finalizedBy jacocoTestReport

## PMD

* https://docs.gradle.org/current/userguide/pmd_plugin.html
* Ruleset for pmd - place it at etc/pmd. configure ruleset path
* ignorefailure to allow build to pass

## Checkstyle

* https://docs.gradle.org/current/userguide/checkstyle_plugin.html
* Rules for checkstyle - place it in etc. configure rules path
