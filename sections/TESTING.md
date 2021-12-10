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

FT - This is where we verify a package can be deployed. We dpeloy here continiously without hesitation.<br/>
ST - This is where we verify a configuration or a process is working as techncally expected. We deploy here when all developers agree upon it.<br/>
AT - This is where we veriy logic and features are all working as spcificed in specs. We deploy here when all stakeholders agree upon it.<br/>
PR - This is our production enviroments. We request a deploy from INFRA trough offical channels by writing a change request.<br/>