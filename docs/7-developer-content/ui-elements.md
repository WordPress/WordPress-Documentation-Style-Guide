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

To express a key or a combination of keys on a keyboard to be pressed by the user, use the `<kbd>` element.

**Example**  

[tip] **Recommended:** `Press <kbd>Control+K</kbd>`. [/tip]  



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