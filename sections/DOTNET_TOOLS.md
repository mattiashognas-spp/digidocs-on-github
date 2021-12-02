# Dotnet Tools

`/.config/dotnet-tools.json`

## Example:
```json
{
  "version": 1,
  "isRoot": true,
  "tools": {
    "dotnet-outdated-tool": {
      "version": "3.2.0",
      "commands": [
        "dotnet-outdated"
      ]
    },
    "dotnet-reportgenerator-globaltool": {
      "version": "4.8.12",
      "commands": [
        "reportgenerator"
      ]
    },
    "dotnet-ef": {
      "version": "5.0.9",
      "commands": [
        "dotnet-ef"
      ]
    }
  }
}
```

## Execute:
`dotnet tools install`