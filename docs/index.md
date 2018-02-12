# Workshop performance testing with Gatling and Perfana

## Goals

This workshop is aiming to get you acquainted with the Perfana performance test framework. You will learn how to create a load test script using Gatling and how to create a continuous performance validation setup that can be integrated in your CI/CD pipelines.

## Prerequisites
* [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) installed
* JDK8 installed
* Maven installed
* An IDE with Scala support, for instance [IntelliJ IDEA](https://www.jetbrains.com/idea/)


## Setting up your environment

For your convenience a complete Perfana test / demo environment is available in this repository: [https://github.com/perfana/perfana-test-env](https://github.com/perfana/perfana-test-env)
Please clone this repository and follow the instructions.


## Exercises

### Gatling

[exercise 1: Maven archetype](exercise-1.md) 

[exercise 2: Recording script with Gatling recorder](exercise-2.md)

[exercise 3: Integrate recorded script in template script](exercise-3.md)

[exercise 4: Inject data into the script](exercise-4.md)

[exercise 5: Checks & conditional execution](exercise-5.md)

[exercise 6: Data correlation](exercise-6.md)

[exercise 7: Add logic to the script](exercise-7.md)

[exercise 8: Configure the workload](exercise-8.md)

### Perfana

[exercise 9: View test results in Perfana](exercise-9.md)

[exercise 10: Adding Key Performance Indicators](exercise-10.md)

## Continuous performance validation

[exercise 11: Integrate test in CI pipeline](exercise-11.md)
