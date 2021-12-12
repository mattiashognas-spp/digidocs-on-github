# Github Actions

## Continous integration

We use Github Actions for our CI workflow.
Our common usage is:<br/>

On pull request: Run Sonarcloud and unit tests.<br/>

On push to master/main: Run build and package as nuget and send to our Github nuget repository for internal usage as a packade OR send to Octopus Deploy for deploy.<br/>

## Continous delivery

We use Octopus Deploy to deploy our packages to each enviroment.

## Read more
[Official documentation](https://docs.github.com/en/actions)
