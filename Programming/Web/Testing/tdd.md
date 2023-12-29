---
title: Test Driven Development
date: 2021-12-24
---

# Test Driven Development

Main Principle: Write the test case before the implementation of the function (only for unit tests)

Convention:

1. You should only have one assertion per test case
   - Why? Because we immediately want to know the cause of the failed test case
   - Note: Sometimes there is no way around having multiple assertions.

Steps:

1. Write the function signature
2. Write the test cases for that function
3. Write the function logic so the the tests pass

What makes a good test?

1. Scope: How much of our code is covered by our single test case
2. Speed: How fast our test case runs. The faster our test cases are the more we will run our tests.
3. Fidelity: How close our test cases are to a real scenario
4. Tests should not be flaky tests that sometimes pass and sometimes fail
5. Avoid writing tests that depend on the outcome of another test

How many test cases should you write?
We should write the lest amount of test cases that will cover all of our code path

What is the difference between the test source set and the androidTest source set?

1. Tests that only run on the Android Emulator (Instrumented Unit Tests) should be put in the androidTest source set (directory)
2. Unit Tests that run on the JVM and not on the Emulator go in the tests source set.
