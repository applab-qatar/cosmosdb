# cosmosdb

I forked this package from [Cosmosdb](https://github.com/jupitern/cosmosdb), So please use that to get latest version. 
This package modified to make compatible for our project. Modifications mentioned in change log below.

## Installation

Include applab/cosmosdb in your project, by adding it to your composer.json file.

```php
{
    "require": {
        "applab/cosmosdb": "1.*"
    }
}
```

## Changelog
### v1.0

This package changed some functionalities to the [Cosmosdb](https://github.com/jupitern/cosmosdb) package. All other functionality exists in this package as well #v2.5.2.

- Changed ms-version to 2018-12-31 
- Auth Header request method($verb) changed to GET in query function
- [List (ReadFeed) Documents](https://learn.microsoft.com/en-us/rest/api/cosmos-db/list-documents) api request method changed to GET in query function.

## Note

This package adds additional functionalities to the [AzureDocumentDB-PHP](https://github.com/cocteau666/AzureDocumentDB-PHP) package. All other functionality exists in this package as well.

## Limitations

Use of `limit()` or `order()` in cross-partition queries is currently not supported.

