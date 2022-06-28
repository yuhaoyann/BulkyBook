# BulkyBook Project

Simple page built with asp.net on visual studio which allows user to add/edit/delete categories.

## Getting Started

1. Go to [BulkyBook](https://github.com/yuhaoyann/BulkyBook), fork and clone the repo to local.
2. Set up a local SQL server, set server name, user Id, password etc
3. Add following to appsettings.json

```json
"ConnectionStrings": {
        "DefaultConnection": "Server={server name};Database=Bulky;User Id=SA;Password={your password}"
    }
```

4. Update database by typing `dotnet ef database update` in terminal
5. Run the app

## Final Product

!["main page"](https://github.com/yuhaoyann/BulkyBook/blob/master/BulkyBookWeb/Content/Images/MainPage.png)
!["create category"](https://github.com/yuhaoyann/BulkyBook/blob/master/BulkyBookWeb/Content/Images/CreateCategory.png)
