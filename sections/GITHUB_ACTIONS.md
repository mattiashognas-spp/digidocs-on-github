# Github Actions

## Continous integration

We use github antions for our CI workflow.
Common usage is:<br/>
On pull request: Run Sonarcloud and unit tests.<br/>
On push to master/main: Run build and package as nuget and send to our gtihub nuget repository for internal usage OR send to Octopus Deploy for deploy.<br/>

## Continous delivery

We use Octopus Deploy to deploy our packages to each enviroment.

## Read more
[Official documentation](https://docs.github.com/en/actions)