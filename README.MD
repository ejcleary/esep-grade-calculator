# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

This repository contains four main files:
README: defines the library and runtime requirements as well as outlining how to run the unit tests
Go.mod: sets the module path and version of go for the repo
Grade_calculator.go: contains gradecalculator and grade struct as well as the functions necessary to calculate, add, and convert the numerical grades as well as the function to return the calculated grade 
Grade_calculator_test.go: contains three tests to test for expected grades A, B, and F by calling functions in grade_calculator and checking for expected values

Runtime requirements:
Golang 1.24+

There are three tests to test individually for expected grades A, B, and F.

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```