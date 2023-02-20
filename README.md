# STARTER-jpa01

Starter code for https://canvas.vt.edu/courses/165554/assignments/1746171


# Testing with Junit

To run test cases with JUnit, use:

```
mvn test
```

# Code Coverage

To calculate code coverage with Jacoco, use:

```
mvn test jacoco:report
```

Then open: `target/site/jacoco/index.html` in a web browser.

# Mutation testing

To run mutation testing with pitest, use:

```
mvn test org.pitest:pitest-maven:mutationCoverage
```

Then open `target/pit-reports/DATE-TIME-STAMP/index.html`

Note that the `DATE-TIME-STAMP` will vary; it will be something like `202112311716`

