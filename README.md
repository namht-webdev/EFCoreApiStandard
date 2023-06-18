## Config for .Net Core App
 
1. EntityFrameworkCore

```
    dotnet add package Microsoft.EntityFrameworkCore
```

2. SqlServer

```
    dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```

3. Identity

```
    dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
```

4. Migrations

```
    dotnet add package Microsoft.EntityFrameworkCore.Design
```

5. Load data references tự động => Lazy loading

```
    dotnet add package Microsoft.EntityFrameworkCore.Proxies

    OnConfiguring
        => optionsBuilder.UseLazyLoadingProxies();
```

6. Authentication with JwtBearer

```
    dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
```
