# CSE325 BLAZOR - Navigation
Learn how to manage request routing by using the @page directive, Blazor routing, NavLink, and NavMenu components. Increase an app's flexibility by adding routing parameters in your Blazor components

## SET-UP

Base project cloned from and using instructions from: [BLAZOR navigation](https://learn.microsoft.com/en-us/training/modules/use-pages-routing-layouts-control-blazor-navigation/?utm_source=copilot.com)
````
git clone https://github.com/MicrosoftDocs/mslearn-blazor-navigation.git BlazingPizza
````
Change the remote origin
````
git remote set-url origin https://github.com/migarcos/repo.git

git remote -v     (to verify)
````

### Debug notes

- [CTRL] + [SHIFT] + [P]
- .Net Generate Assets for Buil and Debug

Correct BlazingPizza.csproj, to use net10.0 (if neccesary)
````
<PropertyGroup>
    <TargetFramework>net10.0</TargetFramework>
    <ImplicitUsings>enable</ImplicitUsings>
  </PropertyGroup>
````
Go to /Properties/launchSettings.json, and change:
````
"dotnetRunMessages": true,
````

### Execution 

- You can use [F5] or 'dotnet run' CLI command

    Is possible you need to delete the pizza.db file (Some SQLite problem about schema with **Address** table)