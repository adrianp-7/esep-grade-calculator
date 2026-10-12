# ESEP Grade Calculator

Overview

Calculates weighted student grades using assignments, exams, and essay categories.

Weights

Assignments: 50%
Exams: 35%
Essays: 15%

Grade Scale

A >= 90
B >= 80
C >= 70
D >= 60
F < 60

Runtime requirements: Golang 1.24+

Running Tests

```
cd grade_calculator/
go test ./...
```

Running Coverage

```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
