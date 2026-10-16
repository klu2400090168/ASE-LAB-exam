# CalculatorProject

A simple Java calculator with a JUnit 5 unit test and GitHub Actions CI.

## Run tests locally

Requires Java 17 and Maven.

```bash
mvn test
```

## Run the program

```bash
mvn -q -DskipTests package
java -cp target/classes Calculator
```

Expected program output:

```text
Sum: 30
```

The GitHub Actions workflow runs `mvn test` on pushes and pull requests.
