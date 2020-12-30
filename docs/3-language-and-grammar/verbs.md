# Verbs
<!-- https://docs.microsoft.com/en-us/style-guide/word-choice/dont-use-common-words-in-new-ways -->
Use precise verbs to write clear, succinct sentences. Use active voice while writing documentation. Some exceptions for using passive voice can be made. For additional information, refer [Voice]().  
Also, write in present tense rather than future tense. For additional information, refer [Tense]().

## Verb forms in reference documentation

For writing reference documentation to explain a procedure, phrase the procedure in terms of what the action does, not what the user/developer would do. These forms of verbs are also used in glossaries and word usage dictionaries.
Usually, the only difference between the two verb forms is an *-s* at the end of the verb. An example of the verb without *-s* would be how most developers write git commits: *Add new file.*

**Examples**

[warning] Not Recommended: `do_action( 'activate_header' )` : Fire before the Site Activation page is loaded. [/warning]  
[tip] Recommended: `do_action( 'activate_header' )` : Fires before the Site Activation page is loaded. [/tip]

## Moods of verbs

In general, use an indicative mood of verbs that convey a factual, friendly, and natural tone without being condescending towards the reader.

**Types of verb moods**

| **Mood**          | **Description**                                              | **Example**                                                                              |
|-------------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------|
| **Indicative**    | Expresses factual statements, questions, and assertions.     | The dashboard displays a relevant overview and summary of your website.                  |
| **Conditional**   | Expresses conditional statements; normally uses if/then.     | If you click the **Preview** button, you'll see a preview of your page on the front-end. |
| **Imperative**    | Expresses a request, command, instructions, etc.             | Click **Preview**.                                                                       |
| **Subjunctive**   | Expresses hypothetical, non-factual, or doubtful statements. | You might need to click **Preview**.                                                     |
| **Interrogative** | Expresses uncertainty, asks a question.                      | Do you need to click **Preview**?                                                        |

Avoid using subjunctive and interrogative moods while writing documentation. Any form of uncertainty, hypothesis is confusing for the reader. Don't change moods within a sentence.
