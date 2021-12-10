# Workflow

We try to be as agile as possible while maintaining a workflow with rigorious testing.

## Our principles

Any new feature should be built according to the following requirements.

- Should be in the form of a pull request in GitHub
- Should compile
- Should have it's PR isolated to a single task of the feature
- Should contain a name or a description that gives the code reviewer(s) enough information to review the changes
- Should contain a code review that is accepted by all parties
- Should contain 80%+ unit and/or integrations test coverage
- Should contain no new bugs in Sonarscanner gate
- Should contain no new vulnerabilities in Sonarscanner gate
- Should contain no new security hotspots in Sonarscanner gate
- Should contain no new code smells in Sonarscanner gate
- Should contain no new duplications in Sonarscanner gate

Failure of these requirements require code refactoring.
In special cases where requirements cannot be met - A cencus among code reviewer(s) is required to accept the deviation.