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

When referring to a UI element by name, format the name in bold using the `<b>` element in HTML or `**` in Markdown. UI element names include those of buttons, windows, menus, dialogs, or any other element in the page or console that has a visible name. Don't use code font for UI element names, unless it is an element that [requires code font](https://make.wordpress.org/docs/style-guide/developer-content/code-in-text/); in which case use both code font and bold text formatting. Capitalize UI element names as per document context, but if the element names are inconsistent, use sentence-case capitalization.

Don't apply bold formatting to an official feature name or product name, except when it directly refers to an element in the page that uses the name (such as a window title or button name).

**Examples**  

[warning] **Not recommended:** In the Appearance section, select "Themes" and then click the "Add New" button. [/warning]  
[tip] **Recommended:** In the **Appearance** section, select the **Themes** option and then click **Add New**. [/tip]  

[warning] **Not recommended:** Click **DOWNLOAD**. [/warning]  
[tip] **Recommended:** Click <span class="dashicons dashicons-download"></span> **Download**. [/tip]  

## Pressing and typing keyboard keys

To express a key or a combination of keys on a keyboard to be pressed by the user, use the `<kbd>` element. To refer to a keyboard shortcut, use either *keyboard shortcut* or *key combination.* To refer to the action of pressing a key or combination, use the verb *press*. To refer to the action of inputting a key or combination, use the verbs *type, enter*, or *input*.

**Examples**  

[tip] **Recommended:** `Press <kbd>Control+K</kbd>`. [/tip]  

The text renders as follows:  
[tip] **Recommended:** Press <kbd>Control+K</kbd>. [/tip]  

If you're using non-HTML markup, use monospace text formatting, which is how `<kbd>` renders. In Markdown, enclose the key name in backticks (``` ` ```).

To express a key that the user has to type to enter that key's value as text input, use the `<code>` element instead of the `<kbd>` element. For more information, see [Code font](https://make.wordpress.org/docs/style-guide/formatting/text/#text-highlighting).

To refer to a keyboard key, use the key's name. If the key's name is ambiguous, use the form *the <code><var>KEY_NAME</code></var> key.*

**Examples**  

[tip] **Recommended:** Press <kbd>Esc</kbd>. [/tip]  
[tip] **Recommended:** Press the <kbd>Esc</kbd> key. [/tip]  

Don't abbreviate the names of modifier keys such as Control, Shift, Command, and Option. Spell out the complete key names and don't use their symbols. To refer to a key combination that uses a modifier key, use the form *<code><var>MODIFIER_KEY</code></var>+<code><var>KEY_NAME</code></var>.*

**Examples**  

[warning] **Not recommended:** Press <kbd>Ctrl+T</kbd>. [/warning]  
[tip] **Recommended:** Press <kbd>Control+T</kbd>. [/tip]  

[warning] **Not recommended:** Press <kbd>⌘+T</kbd>. [/warning]  
[tip] **Recommended:** Press <kbd>Command+T</kbd>. [/tip]  

In most cases, to accommodate both Windows and Mac users, insert the Mac shortcut in parentheses after the Windows shortcut.

**Examples**  

[warning] **Not recommended:** To redo, press <kbd>Ctrl+Y</kbd> (<kbd>⌘+Y</kbd>). [/warning]  
[tip] **Recommended:** To redo, press <kbd>Control+Y</kbd> (or <kbd>Command+Y</kbd> on Mac). [/tip]  

To refer to a key or combination that uses the Shift key, use the form *<code><var>MODIFIER_KEY</code></var>+<kbd>Shift</kbd>+<code><var>KEY_NAME</code></var>.*

**Examples**  

[tip] **Recommended:** Press <kbd>Control+Shift+T</kbd>. [/tip]  
[tip] **Recommended:** Press <kbd>Alt+Shift+R</kbd>. [/tip]  

In general, use uppercase capitalization for character keys.

Spell out the names of characters that could be ambiguous or confusing in a keyboard shortcut, such as comma, hyphen, period, and plus.

**Examples**  

[warning] **Not recommended:** Press <kbd>Control++</kbd>. [/warning]  
[tip] **Recommended:** Press <kbd>Control+Plus</kbd>. [/tip]  

## Terminology and usage

There can be multiple elements in a user interface. [Emphasize the task](#emphasize-the-task) and focus on the feature and functionality of the UI element, rather than focusing on the UI element itself.

**Examples**  

[tip] **Recommended:** Go to **Plugins > Installed Plugins**. [/tip]  
[tip] **Recommended:** In the **Plugins** section, select **Installed Plugins**. [/tip]  

Following are the terminology and word usage when referring to UI elements:

### Window, page, dialog, and view

A *window* is the complete application window in a desktop environment. A window can also refer to adaptive application elements that can be opened and closed. To refer to a window, use the form *the <code><var>LABEL_NAME</code></var> window.*

**Examples**  

[warning] **Not recommended:** On the **Publish** page, click **Save**.  [/warning]  
[tip] **Recommended:** In the **Publish** window, click **Save**. [/tip]  

Generally, a *page* is the shortened version of the word *webpage*. To refer to a page, use the form *the <code><var>LABEL_NAME</code></var> page.*

**Examples**  

[warning] **Not recommended:** On the Dashboard, go to the **Updates** window. [/warning]  
[tip] **Recommended:** On the Dashboard, go to the **Updates** page. [/tip]  

A *dialog* is a small window that appears in front of the window, but is separate from the main application window. To refer to a dialog, use the form *the <code><var>LABEL_NAME</code></var> dialog.*

**Examples**  

[warning] **Not recommended:** In the **Choose Image** pop-up window, click **Upload**. [/warning]  
[tip] **Recommended:** In the **Choose Image** dialog, click **Upload**. [/tip]  

A *view* or a *pane* is a smaller section that is part of the application window. Generally, a view is adjacent to other UI elements and regions, and cannot be hidden, whereas a window is separate and can be hidden. To refer to a view, use the form *the <code><var>LABEL_NAME</code></var> view.*

**Example**  

[tip] **Recommended:** In the **Appearance** view, click **Typography**. [/tip]  

When referring to windows, dialogs, and views, use the preposition *in*. Use *on* when referring to a page.

**Examples**  

[tip] **Recommended:** In the **Customize** window, click **Edit**. [/tip]  
[tip] **Recommended:** On the **Users** page, click **Add New**. [/tip]  
[tip] **Recommended:** In the **Delete Widget** dialog, click **Delete**. [/tip]  
[tip] **Recommended:** In the **Custom Menus** view, click **Primary Menu**. [/tip]  

### Button and icon

A *button* is a UI element that performs or initiates a specified action when clicked or tapped. To refer to a button, use the form *the <code><var>LABEL_NAME</code></var> button.*

**Examples**  

[warning] **Not recommended:** Click the "Publish" button. [/warning]  
[tip] **Recommended:** Click **Publish**. [/tip]  

An *icon* is a image, sign, or symbol that depicts a function. An icon can also be a component of a button. To refer to a button with an icon, use the form *the <code><var>BUTTON_ICON</code></var> <code><var>LABEL_NAME</code></var> button.* If you are unsure of the name of the icon, inspect the element to use the `aria-label` attribute. For more information, see [Using an aria-label](https://www.w3.org/TR/WCAG20-TECHS/ARIA14.html).

**Examples**  

[warning] **Not recommended:** Click the <span class="dashicons dashicons-search"></span> icon. [/warning]  
[tip] **Recommended:** Click <span class="dashicons dashicons-search"></span> **Search**. [/tip]  

If a UI element name ends with an [ellipsis](https://make.wordpress.org/docs/style-guide/punctuation/ellipses/) (...), exclude the ellipsis.

**Examples**  

[warning] **Not recommended:** Click **Read more...**. [/warning]  
[tip] **Recommended:** Click **Read more**. [/tip]  

In general, avoid using directional language such as *above, top, below, left-hand side, lower-right side* in instructions to locate UI elements or other content. Directional language proves to be difficult for accessibility or for localization. If a particular UI element or other content is difficult to convey, include a screenshot or illustration.  

**Examples**  

[warning] **Not recommended:** On the upper-right part of the page, click the button with the checkmark. [/warning]  
[tip] **Recommended:** Click **✓ Publish**. [/tip]  

### Menu bar

A *menu bar* is a set of menus that is at the top of a desktop application window, such as **File**, **Edit**, or **View**. Each menu has a set of submenus or commands. To refer to a menu, use the form *the <code><var>LABEL_NAME</code></var> menu.* To refer to an item in the menu, use the form *the <code><var>LABEL_NAME</code></var> command.*

When combining multiple small actions into a single sequential step use angle brackets (>) to make simple sentences. If you use angle brackets, use the following guidelines:
- Insert spaces around each angle bracket, with the space before the bracket being a nonbreaking space (`&nbsp;`).
- Don't use bold text formatting for each individual menu name. Instead, enclose the entire sequential step in a single bold element; for example, in HTML use `<b>Settings > Media</b>` and in Markdown, use `**Settings > Media**`.
- Enclose the angle bracket with a `<span>` tag and add an `aria-label` attribute with *and then* text (`<span aria-label="and then">></span>`). Otherwise, some screen readers may skip over brackets or read `>` as *greater than*.

For more information, see [Instructions with multiple actions](https://make.wordpress.org/docs/style-guide/formatting/procedures/#instructions-with-multiple-actions).

**Examples**  

[tip] **Recommended (HTML):** Select `<b>Edit&nbsp;<span aria-label="and then">></span> Text&nbsp;<span aria-label="and then">></span> Encoding</b>`. [/tip]  
[tip] **Recommended (Markdown):** Select `**Edit&nbsp;<span aria-label="and then">></span> Text <span aria-label="and then">></span> Encoding**`. [/tip]  

This renders as: Select **Edit > Text > Encoding**.
A screen reader interprets this as *Select Edit and then Text and then Encoding*.

Use this format only for combining multiple small actions into a single sequential step; for example, *In the __Settings__ menu click __Media__*. Use this format only for menu items; don't use it to express a combination of different UI elements.

**Examples**  

[warning] **Not recommended:** Select **Edit** > **Appearance** > **Themes** > **+** > **Activate**. [/warning]  
[tip] **Recommended:** Select **Edit > Appearance**, and select **Themes**. Click on **Add New** and click **Activate**. [/tip]  

### Toolbar

A *toolbar* is a set of buttons for the most frequently used user features. To refer to a toolbar, use the form *the <code><var>LABEL_NAME</code></var> toolbar.*

**Example**  

[tip] **Recommended:** In the **Admin** toolbar, click **Profile**. [/tip]  

### Tab

A *tab* is a navigation element that looks like a file tab. To refer to a tab, use the form *the <code><var>LABEL_NAME</code></var> tab.*

**Example**  

[tip] **Recommended:** Select **Settings > Preferences**, and then click the **Edit** tab. [/tip]  

### Text box

A *text box* or a *text field* is a box that the user can input or type in. To refer to a text box, use the form *the <code><var>LABEL_NAME</code></var> box*. Use code formatting for the text that the user inputs using the `<code>` element in HTML, backticks (``` ` ```) in Markdown, or a monospace font in other markup.

**Examples**  

[tip] **Recommended:** In the **Link** box, enter your sitemap link. [/tip]  
[tip] **Recommended:** In the **Mail server** box, enter the port as `110`. [/tip]  
[tip] **Recommended:** In the **Alt text** box, enter a brief image description without exceeding 100 characters. [/tip]  

### Dropdown list, combo box, and spin box

A *dropdown list* or a *list box* is a UI element that provides a list of items for the user to choose from. To refer to a dropdown list, use the form *the <code><var>LABEL_NAME</code></var> dropdown list* or *the <code><var>LABEL_NAME</code></var> box* depending upon the context.

**Example**  

[tip] **Recommended:** In the **Default page** dropdown list, select **Homepage**. [/tip]  

A *combo box* is a combination of a text box and a dropdown list. To refer to a list box, use the form *the <code><var>LABEL_NAME</code></var> box*. To refer to the action of inputting a value into a combo box, use the verbs *enter, type*, or *select*.

**Example**  

[tip] **Recommended:** In the **Post** box, type or select the post type you want to use. [/tip]  

A *spin box* is a UI element that lets the user choose a value — a numerical value in most cases — by clicking arrows or by typing. To refer to a spin box, use the form *the <code><var>LABEL_NAME</code></var> box*. To refer to the action of entering a value into a spin box, use the verb *enter*.

**Example**  

[tip] **Recommended:** In the **Font Size** box, enter a font size. [/tip]  

### Expander

An *expander arrow* is a UI element that is used to expand or collapse a section of navigation or content. Avoid referring to expander arrows in documentation. If you have to refer to them, use the terms *expander arrow* and *expandable section*.

**Example**  

[tip] **Recommended:** To expand the **Advanced options** section, click the expander arrow. [/tip]  

### Checkbox

A *checkbox* is a box that indicates whether a particular value is selected or not. To refer to a checkbox, use the form *the <code><var>LABEL_NAME</code></var> checkbox.* Be cautious while using the verb *check*, which can be ambiguous. Use *select* instead.

**Examples**  

[tip] **Recommended:** Select the **Search engine visibility** checkbox. [/tip]  
[tip] **Recommended:** Clear the **Crop thumbnail** checkbox. [/tip]  

### Radio button

A *radio button* is a button used to choose one item from a group of mutually exclusive options. A radio button is used when only one item can be chosen from the list. To refer to a radio button, use the radio button's label, or refer to the group of buttons by its label.

**Examples**  

[tip] **Recommended:** Click **Your latest posts**. [/tip]  
[tip] **Recommended:** Select your preferred **Post visibility**. [/tip]  

### Toggle button

A *toggle button* is a UI element that switches back and forth between on and off options or states. To refer to a toggle button, either use *toggle* as a noun or action verb.

**Examples**  

[tip] **Recommended:** To deactivate, click the **Plugin** toggle. [/tip]  
[tip] **Recommended:** You can toggle **Fixed background** in the **Block Settings** sidebar. [/tip]  

## Interaction verbs

For more information about interactive words to describe UI, see the [Word list and usage dictionary](https://make.wordpress.org/docs/style-guide/word-list/).

To describe interactions with UI elements, use the following verbs:

### Click

When the environment is presumably a desktop with a mouse, use *click* for most targets such as buttons, links, list items, and radio buttons.

**Examples**  

[warning] **Not recommended:** Click on **Save**. [/warning]  
[tip] **Recommended:** Click **Save**. [/tip]  

Hyphenate *left-click*, *right-click*, and *double-click*.

When a click or tap action reveals a collapsed list, use the phrase *click to expand* or *expand*.

It's acceptable to write *click in* when referring to a region that needs focus (for example, *click in the window*), but not when referring to a control or a link.

### Select

Use *select* when referring to the action of the user selecting targets such as menu commands, checkboxes, items, and dropdown lists. Select can be use interchangeably instead of *click* or *check* in describing checkboxes and dropdown lists.

**Examples**  

[tip] **Recommended:** In the **Appearance** section, select the **Themes** option and then click **Add New**. [/tip]  
[tip] **Recommended:** Select **Edit > Text > Encoding**. [/tip]  
[tip] **Recommended:** In the **Plugins** section, select **Installed Plugins**. [/tip]  

### Select and hold

Use *select and hold* when referring to the action of the user selecting and holding a UI element. It's acceptable to use *right-click* with *select and hold* when the instruction isn't specific to touch devices.

**Examples**  

[tip] **Recommended:** To pick multiple images, select and hold an image and choose the required images. [/tip]  
[tip] **Recommended:** On Windows devices, select and hold (or right-click) to open the context menu. [/tip]  

### Enter, type, input  

Use *enter, type*, and *input* when referring to the action of the user entering text, or inserting a value.

**Examples**  

[tip] **Recommended:** In the **Post** box, type or select the post type you want to use. [/tip]  
[tip] **Recommended:** In the **Link** box, enter your sitemap link. [/tip]  

### Go to

Use *go to* when referring to the action of opening a menu, going to a website, webpage, a tab, or another place in the UI.

**Example**  

[tip] **Recommended:** Go to **Plugins > Installed Plugins**. [/tip]  

### Tap  

When the environment is presumably a touch device, use *tap* for most targets such as buttons, links, list items, and radio buttons.

**Example**  

[tip] **Recommended:** Tap **Save**. [/tip]  

### Press

Use *press* when referring to a key or a key combination that performs or initiates a specified action when activated.

**Example**  

[tip] **Recommended:** To redo, press <kbd>Control+Y</kbd> (or <kbd>Command+Y</kbd> on Mac). [/tip]  

### Choose

Use *choose* when referring to the action of the user making a choice from multiple options, a list of items, or numerical values.

**Example**  

[tip] **Recommended:** In the **Font Size** box, choose a font size. [/tip]  

### Clear

Use *clear* when referring to the action of clearing a selection, usually from a checkbox.

**Example**  

[tip] **Recommended:** Clear the **Crop thumbnail** checkbox. [/tip]  

### Hold, hover

When the environment is presumably a touch device, use *hold* and *hover* when referring to the action of the user holding or hovering the pointer over a UI element, but not clicking the element. This action involves waiting for the UI element to react. To refer to the action of pointing the mouse pointer use *point to*. This action doesn't imply a length of time waiting for the UI element to react to user action.

**Example**  

[tip] **Recommended:** On the **Admin** toolbar, hold the pointer over **New**. [/tip]  

### Switch, turn on, turn off, enable

Use *switch, turn on, turn off*, and *enable* when referring to the action of turning a switch or toggle key on or off.

**Examples**  

[tip] **Sometimes okay:** To turn on **Fixed background** follow these steps: [/tip]  
[tip] **Recommended:** You can toggle **Fixed background** in the **Block Settings** sidebar. [/tip]  
[tip] **Recommended:** To enable full width, select the **Site Width** toggle button. [/tip]  
[tip] **Recommended:** To switch between fixed width and full width, use the **Site Width** toggle button. [/tip]  

Don't use *enable* or *allow* to express an ability to do something. Use *lets you* instead.

**Examples**  

[warning] **Not recommended:** The `get` request enables you to retrieve the data. [/warning]  
[warning] **Not recommended:** The `get` request allows you to retrieve the data. [/warning]  
[tip] **Recommended:** The `get` request lets you retrieve the data. [/tip]  

### Move, drag

Use *move* and *drag* when referring to the action of moving or dragging a UI element from one place in the UI to the other. In most cases, *move* and *drag* are used for tiles, files, and folders. It is acceptable to use *move* or *move through* to describe moving around UI such as a window or page.

**Examples**  

[tip] **Recommended:** Drag to upload items in the **Media Uploader**. [/tip]  
[tip] **Recommended:** Move the file to the **Shared** folder. [/tip]  

### Open

Use *open* when referring to the action of opening targets such as apps, programs, files, folders, tabs and websites. Don't use *open* for menus and commands.

**Example**  

[tip] **Recommended:** Open **Settings**. [/tip]  

### Close

Use *close* when referring to the action of closing targets such as apps, programs, files, folders, notifications, dialogs, tabs, and websites.

**Example**  

[tip] **Recommended:** Close the **Options** tab. [/tip]  
[tip] **Recommended:** After uploading the image, close the **Choose Image** dialog. [/tip]  

### Zoom

Use *zoom, zoom in*, and *zoom out* a when referring to the action of changing the magnification of a screen, window, or a page.

**Example**  

[tip] **Recommended:** Zoom in to see more details in the figure. [/tip]  
