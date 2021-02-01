# Procedures and instructions

A procedure is a sequence of numbered steps or instructions for achieving a particular task. Procedures can be presented in various formats such as illustrations, infographics, videos, single-step instructions, and numbered procedures.

For more information about lists of items that aren't part of a procedure, see [Lists]().
For more information on expressing UI elements, see [UI elements and interaction]().

## Introductory sentences

In most cases, introduce a procedure with an introductory sentence that initiates the procedure that follows. If the heading of the content explains what the procedure is about, and no additional context is required, then don't include an introductory statement. You can introduce a procedure with an imperative statement.

The introductory sentence can end with a colon or a period. Use a period if the introductory content is extended, and a colon if the introductory statement is shorter and immediately precedes the procedure. The text preceding the colon must distinctly stand alone as a complete sentence. That is, don't introduce a procedure with a partial statement.

**Examples**  

[warning] **Not recommended:** To change the settings: [/warning]  
[tip] **Recommended:** To change the settings, follow these steps: [/tip]  
[tip] **Recommended:** Change the settings: [/tip]  

[warning] **Not recommended:** The settings are: [/warning]  
[tip] **Recommended:** The settings that can be changed are as follows: [/tip]  

## Single-step procedures

When a procedure consists of a single step or instruction, consolidate it into the introductory sentence.

**Examples**  

[warning] **Not recommended:** To save the modified file, follow this step:
1. Click **Save Changes**.  
[/warning]  

[warning] **Not recommended:** To save the modified file, follow this step:
- Click **Save Changes**.  
[/warning]  

[tip] **Recommended:** To save the modified file, click **Save Changes**. [/tip]  

## Sub-steps in numbered procedures

In numbered procedures, label sub-steps with lowercase letters, and sub-sub-steps with lowercase Roman numerals.

When a step has sub-steps, write the step as an [introductory statement](#introductory-sentences) to the sub-steps.

**Example**  

[tip] **Recommended:**
1. To set up your development environment, follow these steps:  
   a. Install Node development tools as follows:  
      i. Download and install Node Version Manager (nvm).  
      ```sh
      curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
      ```

      ii. Quit and restart the terminal.  
      ```sh
      nvm install --lts
      ```  
   b. Set up your WordPress environment:    
      i. Download, install, and start Docker Desktop following the instructions for your OS.  
      ii. Install the WordPress environment tool.
      ```sh
      nvm install --lts
      ```  
      iii. Start the environment from an existing plugin or theme directory, or a new working directory:
      ```sh
      wp-env start
      ```
   c. Set up your code editor.  
[/tip]  

## Instructions with multiple actions

In general, use one step per action. However, you can combine multiple small actions into a single sequential step using angle brackets (>) to make simple sentences. Insert spaces around each bracket, and don't make the brackets bold.

**Examples**  

[tip] **Recommended:** 1. Go to **Settings** > **Media**. [/tip]  
[tip] **Recommended:** 1. Go to **Edit** > **Text** > **Encoding**. [/tip]  

[alert] Caution: Screen readers may skip over brackets and may not read them as intended. For example, **Settings** > **Media** may be read as *Settings Media*, which might confuse readers. Analyze with an accessibility expert before implementing this approach. [/alert]  

Avoid making long sequential steps. Consider rewriting them by splitting them into sub-steps if they get complicated.

## Repetitive procedures

Write concise steps without writing repetitive instructions with bold UI elements.  

**Examples**  

[warning] **Not recommended:**  
1. Click **Menu**. You will see **Settings** in the **Menu** dropdown.  
2. Under the **Settings** option, click **Media**.  

[/warning]  
[tip] **Recommended:**  
1. Click **Menu**.  
2. Under the **Settings** option that appears, click **Media**.  

[/tip]  

Avoid repeating procedures. Instead, reference those procedures and link to them.  

**Examples**  

[tip] **Recommended:** Quit and restart the terminal as you did in the previous step. [/tip]  
[tip] **Also recommended:** [Quit and restart the terminal as you did in the previous step.](#) [/tip]  

## General guidelines for writing procedures

- Format procedures consistently so that readers know where to find them easily by scanning content.
- In general, use headings for procedures so that readers find the exact instructions quickly. Write the heading such that it describes what the instructions will help the readers do.  
  **Examples**  

  [tip] **Recommended:** Create a new page [/tip]  
  [tip] **Recommended:** Edit your post [/tip]  

- Capitalize the first word in each step and end the step with a period; except where the step doesn't include end punctuation.
- Write complete sentences with a consistent sentence structure. Use a standard writing style for headings and instructions in procedures.
- Use [imperative verb forms]() in procedures.
- Don't use *please* in instructions.
- Individually [number each step](#sub-steps-in-numbered-procedures) in a procedure. It is acceptable to combine short steps that occur in the same place in the UI.
- State the purpose of the actions before stating the action.  
  **Examples**  

  [warning] **Not recommended:** Click **Save Changes** to save the modified file. [/warning]  
  [tip] **Recommended:** To save the modified file, click **Save Changes**. [/tip]  

- Write the instructions in the order that the reader needs to follow. State the location of the action before stating the action. If there are multiple sets of procedures with steps and sub-steps, restate the location of the action in the first step of the procedure.  
  **Examples**  

  [warning] **Not recommended:** Click **Settings** > **Media** after navigating to the task menu bar. [/warning]  
  [tip] **Recommended:** Navigate to task menu bar, then click **Settings** > **Media**. [/tip]  

- It is acceptable to not provide context such as UI element position multiple times within a step, if the instruction appears in the same UI where the action occurs.
- If a particular step is optional in a procedure, indicate it by mentioning "Optional" at the beginning of the step.  
  **Examples**  

  [tip] **Recommended:** Optional: If docker is not running, try to restart the service using:
  ```sh
  sudo systemctl daemon-reload
  sudo systemctl restart docker.service
  ```
  [/tip]  

- If you think that a specific step might confuse the reader, provide an introductory step. You can also include a brief phrase so that the reader follows the instruction at the right place.  
  **Example**  

  [tip] **Recommended:** Navigate to the menu bar and click on the **Encoding** tab. [/tip]  

- When there is more than one way to achieve a particular task, give the best way to do so. Multiple alternative procedures can confuse readers.
- In general, avoid using directional language such as *above, top, below, left-hand side, lower-right side* in instructions to locate UI elements or other content. Directional language proves to be difficult for accessibility or for localization. If a particular UI element or other content is difficult to convey, include a screenshot or illustration.  
  **Examples**  

  [warning] **Not recommended:** On the upper-right part of the page, click the button with the checkmark. [/warning]  
  [tip] **Recommended:** Click **✓ Publish**. [/tip]  

- Don't include keyboard shortcuts in instructions.
- Most of the time, end procedures with a definite action or result that helps the reader achieve that particular task.
