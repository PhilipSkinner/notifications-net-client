## [1.2.0] - 2017-05-11
## Changed

* Added new methods for managing templates:
    * `GetTemplateById` - retrieve a single template
    * `GetTemplateByIdAndVersion` - retrieve a specific version for a desired template
    * `GetAllTemplates` - retrieve all templates (can filter by type)
    * `GenerateTemplatePreview` - preview a template with personalisation applied

* Refactored MSTest tests to NUnit tests.
    * This allows for wider compatibility with a variety of IDEs.

## [1.1.0] - 2016-12-16
### Changed

* Update to `Client.GetNotifications()`
    * Notifications can now be filtered by `reference` and `olderThanId`, see the README for details.
    * Updated method signature:

 ```csharp
client.GetNotifications(String templateType = "", String status = "", String reference = "", String olderThanId = "")
```
     * Each one of these parameters can be `null`

# Prior versions

Changelog not recorded - please see pull requests on github.