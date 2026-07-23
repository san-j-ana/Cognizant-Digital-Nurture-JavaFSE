
# Exercise 1: Mocking and Stubbing using Mockito

## Objective
To test a service that depends on an external API using Mockito.

## Files
- ExternalApi.java
- MyService.java
- MyServiceTest.java

## Concepts Used
- Mockito
- Mock Object
- Stubbing
- JUnit 5

## Description

- A mock object is created for the external API.
- The `getData()` method is stubbed to return `"Mock Data"`.
- The mock object is passed to `MyService`.
- The test verifies that the returned value matches the expected result.

## Expected Result

Tests run: 1

Failures: 0

BUILD SUCCESSFUL

## Technologies Used
- Java
- JUnit 5
- Mockito
