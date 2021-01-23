# FullApp (Dotnet Core + React)

# Notes

**Run application**

```bash
# run DotNet API
$ cd API
$ dotnet watch run

# run React UI
$ cd client-app
$ npm start
```

**Add migrations**

```
$ dotnet ef migrations add "ActivityEntityAdded" -p .\Persistent\ -s .\API\
```

**MediatR**

Package: MediatR.Extensions.Microsoft.DependencyInjection

**Command to create react project**

```bash
# Create the project
$ npx create-react-app client-app --use-npm --typescript

# If you clone this repo
$ cd client-app
$ npm install

# Starts the development server.
$ npm start

# Bundles the app into static files for production.
$ npm run build

# Starts the test runner.
$ npm test

# Removes this tool and copies build dependencies, configuration files
# and scripts into the app directory. If you do this, you can’t go back!
$ npm run eject
```


**Links**

- Create VS Code snippets [https://snippet-generator.app/](https://snippet-generator.app/)
