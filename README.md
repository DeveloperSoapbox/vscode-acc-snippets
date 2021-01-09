# Adobe Campaign Snippets

This extension for Visual Studio Code adds useful snippets for Adobe Campaign. These are especially useful for working with ACC web application and workflow Javascript activities.

This is an unofficial extension and I am not affiliated with the Adobe corporation.

## Usage

Type part of a snippet, press enter, and the snippet unfolds. Requires that the file type be set to HTML or Javascript, depending on which snippet set is needed.

Alternatively, press Ctrl+Space (Windows, Linux) or Cmd+Space (macOS) to activate snippets from within the editor.

### ACC Web App Snippets (**Active with files of type HTML**)

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-if`                     | ACC if statement delimited for HTML (i.e. <%if...%>)                               |
| `acc-if-else`                | ACC if-else statement delimited for HTML                                           |
| `acc-for-loop`               | ACC for loop delimited for HTML (i.e. <%for...%>)                                  |
| `acc-setvalue`               | ACC javascript for adding variable to ctx, using document.controller.setValue      |
| `acc-submit`                 | ACC javascript for triggering a page transition, using document.controller.submit  |
| `acc-output-var`             | ACC output string value, delimited for HTML (i.e. <%=ctx.vars.varName%>)           |

### ACC Javascript Snippets (**Active with files of type Javascript**)

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-iter-querydef`          | Declare a queryDef and iterate through records using for loop                      |
| `acc-iter-sqlselect`         | Declare a SQL string, execute it, and iterate records using a for loop             |
| `acc-formatdate`             | ACC formatDate function template                                                   |
| `acc-sqlescape`              | ACC javascript for adding variable to ctx, using document.controller.setValue      |
| `acc-log-info`               | logInfo(value);                                                                    |
| `acc-log-verbose`            | logVerbose(value);                                                                 |
| `acc-log-warning`            | logWarning(value);                                                                 |
| `acc-log-error`              | logError(value);                                                                   |
| `acc-uuid`                   | var uuid = getUUID();                                                              |

### ACC XML Snippets (**Active with files of type XML**)

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



## Installation

1. Install Visual Studio Code 1.44.0 or higher
1. Launch Code
1. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
1. Select `Install Extension`
1. Choose the extension
1. Reload Visual Studio Code

