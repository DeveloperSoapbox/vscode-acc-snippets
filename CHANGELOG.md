# Change Log

All notable changes to the "vscode-springboot-snippets" extension will be documented in this file.

## 0.0.3

#### Initial release

## 1.0.0

#### Added support for XML files, with the following snippets for schema creation:

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-schema-compute-str`     | compute-string element with basic attributes                                       |
| `acc-schema-enum`            | enumeration element with basic child elements / attributes                         |
| `acc-schema-key`             | key element with basic child elements / attributes                                 |
| `acc-schema-id`              | Alias for acc-schema-key                                                           |
| `acc-schema-index`           | dbindex element with basic child elements / attributes                             |
| `acc-schema-attr-string`     | Schema attribute of type string with some basic attributes                         |
| `acc-schema-attr-integer`    | Schema attribute of type long with some basic attributes                           |
| `acc-schema-attr-byte`       | Schema attribute of type byte with some basic attributes                           |
| `acc-schema-attr-date`       | Schema attribute of type date with some basic attributes                           |
| `acc-schema-attr-datetime`   | Schema attribute of type datetime with some basic attributes                       |
| `acc-schema-attr-boolean`    | Schema attribute of type boolean with some basic attributes                        |
| `acc-schema-attr-memo`       | Schema attribute of type memo and some basic attributes                            |

<br/>

#### Added the following snippets to Javascript file support:

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-log-info`               | logInfo(value);                                                                    |
| `acc-log-verbose`            | logVerbose(value);                                                                 |
| `acc-log-warning`            | logWarning(value);                                                                 |
| `acc-log-error`              | logError(value);                                                                   |
| `acc-uuid`                   | var uuid = getUUID();                                                              |