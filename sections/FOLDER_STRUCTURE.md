# Folder Structure

```
.gitignore
.env
global.json
README.md
src
    app_name.sln
    a_library/**/*.*
    another_library/**/*.*
    main_app/**/*.*
    main_app.tests/**/*.*
```

## File Content Examples:
.env
```
DOTNET_ENVIRONMENT="Development"
```

.gitignore<br>
```
bin
obj
*.log
.vs
```

global.json
```
{
  "sdk": {
    "version": "3.1.403"
  }
}
```

[Official documentatiton of README.md](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
