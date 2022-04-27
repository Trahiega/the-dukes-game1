# Note formatting
## Line Spacing
Markdown renders a single linebreaks if they are preceded by two spaces. That's how you do a linebreak instead of new paragraph.

This line here has two spaces at the end  
and it makes a linebreak.

This text here uses double line break

creating a new paragraph.

Mkdocs or the material theme does not show bullet list without full line between start of list and normal line of text.

Text
- list that will not show in mkdocs/material

Text

- List that will render correctly

## Links
Obsidian will automatically update both wikilinks and markdown links when changing the file names.

### Wikilinks

Standard Wikilink
[[The-Kingdom-of-Krahan]]

Using a wikilink for a heading
[[The-Kingdom-of-Krahan#Settlements]]

Wikilink with a custom link name
```[[filename|Display text]]```
[[The-Kingdom-of-Krahan|The Kingdom of Krahan]]

### Using unlinked mentions
If any text in a note matches the name or alias of another note, it will show up in the unlinked mentions.

##### Setting an alias
Specify the the aliases using the YAML front matter (this **must** be at the very top of the note to work).
```
---
aliases: [AI, Artifical Intelligence]
---
```

##### Linking with aliases
Once you've set an alias you can use it to create links.

## Footnotes
See [[Lady-Aliyah|Lady Aliyah]] page for example

## Linking to Blocks
Linking to Blocks is Obsidian flavour markdown and does not work outside of Obsidian.

```
[[Lady-Aliyah#^cf5283]]
```
Add the link, and after the file name enter ^, then if you search for the "block" you are after, Obsidian will automatically generate a block ID for that block.
See [[Lady-Aliyah#^cf5283]]

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

Material theme for MKDOCs
https://squidfunk.github.io/mkdocs-material/

MKDOCs reference
