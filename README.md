# Release Diff Checker Cli

The aim of this tool is to have a command line tool to show you a list of differences between staging and production environments with in a chef centralized release flow. Ideally we can see cookbook version differences, any changes in roles, or possibly any changes in general to the application overrides block. Hopefully to also have the ability to narrow down by a passed list of applications to cut down on the noise of the output.

## Useage
- Clone the project
- Build the binary `go get && go build`
- Put the binary in your path
- Call the binary `reldiff` for overall differences
- Pass it a list of apps you care about `reldiff --apps=app-name1,app-name2,app-name3`

For now that is it. More feature may be added by a per request basis
