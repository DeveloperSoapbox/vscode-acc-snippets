# Adobe Campaign Snippets

This extension for Visual Studio Code adds useful snippets for Adobe Campaign. These are especially useful for working with ACC web application and workflow Javascript activities.

This is an unofficial extension and I am not affiliated with the Adobe corporation.

## Usage

Usage Details Here

### ACC Web App Snippets

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-if`                     | ACC if statement delimited for HTML (i.e. <%if...%>)                               |
| `acc-if-else`                | ACC if-else statement delimited for HTML                                           |
| `acc-for-loop`               | ACC for loop delimited for HTML (i.e. <%for...%>)                                  |
| `acc-setvalue`               | ACC javascript for adding variable to ctx, using document.controller.setValue      |
| `acc-submit`                 | ACC javascript for triggering a page transition, using document.controller.submit  |
| `acc-output-var`             | ACC output string value, delimited for HTML (i.e. <%=ctx.vars.varName%>)           |

### ACC Javascript Snippets

| Snippet                      | Purpose                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `acc-iter-querydef`          | Declare a queryDef and iterate through records using for loop                      |
| `acc-iter-sqlselect`         | Declare a SQL string, execute it, and iterate records using a for loop             |
| `acc-formatdate`             | ACC formatDate function template                                                   |
| `acc-sqlescape`              | ACC javascript for adding variable to ctx, using document.controller.setValue      |


## Installation

1. Install Visual Studio Code 1.44.0 or higher
1. Launch Code
1. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
1. Select `Install Extension`
1. Choose the extension
1. Reload Visual Studio Code

