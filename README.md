# mkdocs-asyncapi-plugin
This plugin helps to render AsycnAPI schema in your mkdocs markdown page. It uses AsyncAPI Standalone react component to render your asyncapi schema file.

Supports both .json and .yml files. Simply use the tag:

`<asyncapi-tag src="/path/to/schema.json"/>`

## Accepted values
In addition to the `src` attribute following attributes work with the tag.

| Action | Attribute | Accepted values |
|---|---|---|
| Show or hide | `sidebar` | `true` or `false` |
| Show or hide | `info` | `true` or `false` |
| Show or hide | `servers` | `true` or `false` |
| Show or hide | `operations` | `true` or `false` |
| Show or hide | `messages` | `true` or `false` |
| Show or hide | `schemas` | `true` or `false` |
| Show or hide | `errors` | `true` or `false` |
| expand or collapse | `messageExamples` | `true` or `false` |
| sidebar configuration| `showServers` | `byDefault` or `bySpecTags` or `byServersTags` |
| sidebar configuration| `showOperations` | `byDefault` or `bySpecTags` or `byServersTags` |
| asyncapi parser configuration | `parserOptions` | See available [options here](https://github.com/asyncapi/parser-js/blob/master/API.md#module_@asyncapi/parser..parse) |
| label customization | `publishLabel` | Any string value |
| label customization | `subscribeLabel` | Any string value |