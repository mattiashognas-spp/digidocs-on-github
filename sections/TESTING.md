# Testing

## Unit tests

We prefer to use Specification By Example trough Gherkin language and we generate tests from these specs using Specflow in dotnet.

We prefer to use utilize TDD over post-implementation tests.

Packages of tools and frameworks and tools we commonly use are:
- XUnit at test framework
- FluentAssertions to create readability
- Moq for mocking
- coverlet for test coverage
- Specflow for autogenerating tests from specs

## Code quality

To maintain code quality we require each pull requests to be verified by one or more developer(s) and we require Sonarscanner control to be run with zero quality annotations.

## Enviroments

We deploy frequently to FT.<br/>
When all devs agree, we deploy to ST.<br/>
When all stakeholders agree we deploy to AT.<br/>
And lastly we let INFRA Team deploy to PR.<br/>
