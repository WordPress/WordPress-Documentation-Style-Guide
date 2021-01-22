# Command-line syntax

This page explains how to format commands and their arguments in documentation. For more information about other code-related documentation, see [WP-CLI Handbook](https://make.wordpress.org/cli/handbook/), [Code in text](), [Placeholders](), and [Code examples]().

## Command prompt

When you have to show multiple lines of command-line input, initiate each line with the dollar (`$`) prompt symbol.

Don't show the current directory path before the prompt, even if part of the instruction includes creating or changing directories. This is because the directory structure might be different for the user. However, if the general context of the command-line interface changes—such as from the local machine to a remote machine—then add an additional prompt indicator for the new context.

**Examples**  

[tip] **Recommended:**  
```shell
$ wp theme activate twentytwentyone
```  
The output is the following:

```
Success: Switched to 'Twenty Twenty-One' theme.
```  
[/tip]  

[tip] **Recommended:**  
```shell
$ pwd
/srv/www/wordpress-develop.dev
$ cat wp-cli.yml
path: src/
```  
[/tip]  

For single-line commands, the command prompt, that is the dollar symbol (`$`) is optional. However, if you have to show both multi-line and single-line commands, use the command prompt symbol for overall consistency.

Use separate code blocks for command-line instructions that include both input and output lines.

**Example**  

[tip] **Recommended:**  
```shell
$ wp cap list 'editor' | xargs wp cap add 'author'
```  
The output is the following:

```
Success: Added 24 capabilities to 'author' role.
```  
[/tip]  

## Required commands and arguments

When writing commands and arguments that are required, use code font without brackets, braces, or parentheses.

**Examples**  

[tip] **Recommended:**  
```shell
$ wp post list --post_type='page' --format=ids
```  
[/tip]  

[tip] **Recommended:**  
```shell
$ wp core check-update
```  
[/tip]  
In these examples, all words and arguments are required.

For additional information, see [Anatomy of a command](https://make.wordpress.org/cli/handbook/guides/commands-cookbook/#anatomy-of-a-command).

## Optional arguments

When writing arguments that are optional, enclose the arguments in square brackets. If there is more than one optional argument, enclose each item in its individual set of square brackets.

**Example**  

[tip] **Recommended:**  
```shell
$ wp plugin install https://wordpress.org/plugins/gutenberg/ [--force] [--activate]
```  
[/tip]  
In this example, `install` is required, but `[--force]` and `[--activate]` are optional arguments.

## Mutually exclusive arguments

When writing commands where the use has to choose one item, enclose the items in angle brackets (`<>`; also known as *inequality signs*). Sometimes the mutually exclusive choices are also enclosed in braces (also known as *curly braces*). Use vertical bars (also knows as *pipes*) to separate the items. You can have more than two mutually exclusive items that are separated from each other by pipes.

**Example**  

[tip] **Recommended:**  
```shell
$ wp plugin install <plugin|zip|url>
```  
[/tip]  
In this example, `install` is required, and `<plugin|zip|url>` is the accepted positional argument. In fact, `wp plugin install` accepts the same positional argument (the slug, ZIP, or URL of a plugin to install). The `plugin`, `zip`, and `url` choices are mutually exclusive, but one of the argument must be specified.

## Multiple value arguments

Use an ellipsis (`...`) to indicate that the user can specify multiple values for the argument.

**Examples**  

[tip] **Recommended:**  
```shell
$ wp media import [--post_id=<post_id>...]
```  
[/tip]  
In this example, the ellipsis indicates that the user can specify multiple instances of the optional argument `[--post_id=<post_id>]`.

[tip] **Recommended:**  
```shell
$ wp plugin install <plugin|zip|url>...
```  
[/tip]  
In this example, the ellipsis indicates that the user can specify multiple plugins, zip files or URLs.

## Command output

You don't have to show an output for every command. Only add the output if it is useful; for example, if the user needs to copy a value or needs to verify a value from the output.

If you do show have to show an output, use an introductory phrase to separate the command from the output.

**Examples**  

[tip] **Recommended:**  
```shell
$ wp theme status twentytwentyone
```  
The output is the following:

```
Theme twentytwentyone details:
     Name: Twenty Twenty-One
     Status: Active
     Version: 1.1
     Author: WordPress.org
```  
[/tip]  

[tip] **Recommended:**  
```shell
$ wp server --host=localhost.localdomain --port=80
```  
The output is similar to the following:

```
PHP 5.6.9 Development Server started at Fri Jan 22 11:32:56 2021
Listening on http://localhost1.localdomain1:80
Document root is /
Press Ctrl-C to quit.
```  
[/tip]  
