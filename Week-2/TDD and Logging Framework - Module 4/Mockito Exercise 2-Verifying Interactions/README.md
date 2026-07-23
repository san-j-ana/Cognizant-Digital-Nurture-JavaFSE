# Exercise 2: Verifying Interactions using Mockito

## Objective
To verify that a specific method is called on a mock object using Mockito.

## Files
- ExternalApi.java
- MyService.java
- MyServiceTest.java

## Concepts Used
- Mockito
- Mock Object
- verify()
- JUnit 5

## Description
- A mock object of `ExternalApi` is created.
- The mock object is passed to `MyService`.
- The `fetchData()` method is called.
- The `verify()` method checks whether `getData()` was invoked.

## Expected Result

Tests run: 1

Failures: 0

BUILD SUCCESSFUL

## Technologies Used
- Java
- JUnit 5
- Mockito
