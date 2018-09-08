# fathom [![Build Status](https://travis-ci.org/thomasmchen/fathom.svg?branch=master)](https://travis-ci.org/thomasmchen/fathom) [![codecov](https://codecov.io/gh/thomasmchen/fathom/branch/master/graph/badge.svg)](https://codecov.io/gh/thomasmchen/fathom)

Real-Time Customer/Product Review Analysis Platform

# Testing
Run linter via:
```
mvn checkstyle:checkstyle -Dcheckstyle.consoleOutput=true
```
Run tests:
```
mvn test
```
Sample start flow:
```
mvn clean validate
mvn clean compile
mvn checkstyle:checkstyle -Dcheckstyle.consoleOutput=true
mvn clean test
```

## Contributing
Please refer to the [Git Flow](https://github.com/thomasmchen/fathom/wiki/Git-Flow) document in the Wiki for guidance on contributing.

## Versioning
Meter adheres to Semantic Versioning 2.0.0. Learn more [here](https://semver.org/). <br>
The current version of fathom is `0.0.1`.