
### Running the mustpass tests
`./gradlew -Dprofile=mustpass runTests`

### Checking the test results of the mustpass tests
`./gradlew -Dprofile=mustpass checkTests`

### Force rerun of a test
-a is to not rebuild project dependencies (renjin etc.)
`./gradlew --rerun-tasks -a test`
e.g.
`./gradlew --rerun-tasks -a cran:date:test`