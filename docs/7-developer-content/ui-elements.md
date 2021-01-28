# UI elements and interaction

## Emphasize the task

When writing about interactions involving the user interface (UI), emphasize on the task to be accomplished, rather than how the user should interact with the UI element. By avoiding reference to UI elements, you help the reader understand the purpose of an instruction and avoid confusion due to additional external elements.

However, be watchful of the context and the reader demographic and how that influences your documentation; sometimes the objective of a procedure is to guide readers through elements on a page.

**Examples**  

[warning] **Not recommended:** Click the PUBLISH button. [/warning]  
[warning] **Not recommended:** Click the *Publish* button. [/warning]  
[warning] **Not recommended:** Click the "Publish" button. [/warning]  
[tip] **Recommended:**  Click **Publish**. [/tip]  
[tip] **Recommended** (consider context): Publish the post. [/tip]  

[warning] **Not recommended:** Click the arrow indicator to open the **Time zone** options section. [/warning]  
[tip] **Recommended:** To open the **Time zone** options section, click the dropdown arrow. [/tip]  
[tip] **Recommended** (consider context): Open the **Time zone** options section. [/tip]  

## Formatting UI element names

When referring to a UI element by name, format the name in bold using the `<b>` element in HTML or `**` in Markdown. UI element names include those of buttons, windows, menus, dialogs, or any other element in the page or console that has a visible name. Don't use code font for UI element names, unless it is an element that [requires code font](//code-in-text.md); in which case use both code font and bold text formatting. Capitalize UI element names as per document context, but if the element names are inconsistent, use sentence-case capitalization.

Don't apply bold formatting to an official feature name or product name, except when it directly refers to an element in the page that uses the name (such as a window title or button name).

**Examples**  

[warning] **Not recommended:** In the Appearance section, select "Themes" and then click the "Add New" button. [/warning]  
[tip] **Recommended:** In the **Appearance** section, select the **Themes** option and then click **Add New**. [/tip]  

[warning] **Not recommended:** Click **DOWNLOAD** [/warning]  
[tip] **Recommended:** Click <span class="dashicons dashicons-download"></span> **Download**. [/tip]  

## Pressing and typing keyboard keys

To express a key or a combination of keys on a keyboard to be pressed by the user, use the `<kbd>` element. To refer to a keyboard shortcut, use either *keyboard shortcut* or *key combination.* To refer to the action of pressing a key or combination, use the verb *press*. To refer to the action of inputting a key or combination, use the verbs *type, enter*, or *input*.

**Examples**  

[tip] **Recommended:** `Press <kbd>Control+K</kbd>`. [/tip]  

The text renders as follows:  
[tip] **Recommended:** Press <kbd>Control+K</kbd>. [/tip]  

If you're using non-HTML markup, use monospace text formatting, which is how `<kbd>` renders. In Markdown, enclose the key name in backticks (``` ` ```).

To express a key that the user has to type to enter that key's value as text input, use the `<code>` element instead of the `<kbd>` element. For more information, see [Code font](//text.md).

To refer to a keyboard key, use the key's name. If the key's name is ambiguous, use the form *the <code><var>KEY_NAME</code></var> key.*

**Examples**  

[tip] **Recommended:** Press <kbd>Esc</kbd>. [/tip]  
[tip] **Recommended:** Press the <kbd>Esc</kbd> key. [/tip]  

Don't abbreviate the names of modifier keys such as Control, Shift, Command, and Option. Spell out the complete key names and don't use their symbols. To refer to a key combination, use the form *<code><var>MODIFIER_KEY</code></var>+<code><var>KEY_NAME</code></var>.*

**Examples**  

[warning] **Not recommended:** Press <kbd>Ctrl+T</kbd>. [/warning]  
[tip] **Recommended:** Press <kbd>Control+T</kbd>. [/tip]  

[warning] **Not recommended:** Press <kbd>⌘+T</kbd>. [/warning]  
[tip] **Recommended:** Press <kbd>Command+T</kbd>. [/tip]  

In most cases, to accommodate both Windows and Mac users, insert the Mac shortcut in parentheses after the Windows shortcut.

**Examples**  

[warning] **Not recommended:** To redo, press <kbd>Ctrl+Y</kbd> (<kbd>⌘+Y</kbd>). [/warning]  
[tip] **Recommended:** To redo, press <kbd>Control+Y</kbd> (or <kbd>Command+Y</kbd> on Mac). [/tip]  

To refer to a key or combination that uses the Shift key, use the form *<code><var>MODIFIER</code></var>+<kbd>Shift</kbd>+<code><var>KEY_NAME</code></var>.*

**Examples**  

[tip] **Recommended:** Press <kbd>Control+Shift+T</kbd>. [/tip]  
[tip] **Recommended:** Press <kbd>Alt+Shift+R</kbd>. [/tip]  

In general, use uppercase capitalization for character keys.

Spell out the names of characters that could be confusing in a keyboard shortcut, such as comma, hyphen, period, and plus.


## Terminology and usage

There can be multiple elements in a user interface. [Emphasize the task](#emphasize-the-task) and focus on the feature and functionality of the UI element, rather than focusing on the UI element itself.

**Examples**  

[tip] **Recommended:** Go to **Plugins > Installed Plugins**. [/tip]  
[tip] **Recommended:** In the **Plugins** section, click **Installed Plugins**. [/tip]  

Following are the terminology and word usage when referring to UI elements:

###
### Buttons
###

## Interaction verbs
