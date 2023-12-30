# Reference

A reference article is information-oriented.
It provides a structured description of a product:
its APIs, classes, functions, configuration options, actions, and so on.
Start with a summary of what this reference article is about, and what the items you are describing are used for.

## Command

Syntax:

```shell
cmd [OPTIONS]
```

## Options

Describe what each option is used for:

-o, --open
: Opens a file.

-c, --close
: Closes a file.

-v, --version
: Displays version information.

-h, --help
: Displays help.


<tldr>
    <p>Shortcut: <shortcut>Ctrl+Space</shortcut></p>
    <p>Configure: <ui-path>Settings / Preferences | Editor | Code Completion</ui-path></p>
</tldr>

HELLLLLLLLLLLLLLO

<p>Shortcut: <shortcut>Ctrl+Space</shortcut></p>
<p>Configure: <ui-path>Settings / Preferences | Editor | Code Completion</ui-path></p>

<procedure title="Procedure's title" collapsible="true">
    <step>Step 1.</step>
    <step>Step 2.</step>
</procedure>

```kotlin
    class Person(val name: String) {
        val children: MutableList<Person> = mutableListOf()

        constructor(name: String, parent: Person) : this(name) {
            parent.children.add(this)
        }
    }
```

{collapsible="true" collapsed-title="Person.kt"}

{collapsible="true"}
Expanded by default
{collapsible="true" default-state="expanded"}
: This is the definition of the first term.

Collapsed by default
{collapsible="true" default-state="collapsed"}
: This is the definition of the second term.

<deflist style="narrow" sorted="desc">
    <def title="First Term">
        This is the definition of the first term.
    </def>
    <def title="Second Term">
        This is the definition of the second term.
Send an <tooltip term="HTTP">HTTP</tooltip> request.
    </def>
</deflist>

WOWOWOWOWOWO

<code-block lang="tex">
    \begin{equation}
    x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
    \end{equation}
</code-block>

![Getting started](new_topic_options.png)

<video src="https://youtu.be/BeJu9bMPLGU"/>

To output a line on the screen use
`echo "Hello world!"`.

To output a line on the screen use
<code>echo "Hello world!"</code>.

<seealso>
    <!--Provide links to related how-to guides, overviews, and tutorials.-->
</seealso>