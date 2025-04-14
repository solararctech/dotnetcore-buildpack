# Heroku .NET Core Buildpack (Build All)

Forked from `jincod/dotnetcore-buildpack`

Use as `https://github.com/solararchtech/dotnetcore-buildpack`

Key difference is that modification builds all projects with `Program.cs` which allows to have 2 or more projects projects for both `web` and `worker`. e.g. `App.API` and `App.ServiceWorker`.

**Important:** fork is compatible with internal projects and not aimed to replace or give more features than sourced reposity. Please use [source repository](https://github.com/jincod/dotnetcore-buildpack) instead.