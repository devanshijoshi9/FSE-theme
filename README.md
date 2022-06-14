# FSE-theme
WordPress Full Site Editing theme

## FSE Block-Theme setup

- Block-theme must include templates/index.html file. ( Along with index.php & style.css file )
- Template parts must include inside Parts folder.
- theme.json file is option but strongly recommended
## What is included in this Repo: 

- Block Templates.
- Block Template Parts.
- Reuse of Block Template Parts.
- Add Custom Global styles.

## Process:

**Block Template parts** - For eg. Footer, and Header which we can use separately in any block template.

**Steps to create Header Block template Part using Editor.**
- Go to the editor, click on the template part block, and name it a header. ( Modify Advanced HTML part and add custom CSS class )
- Hit on the + button and add a group block.
- Again hit the + button to add a column block. Select any 2-column layout.
- Add site logo/title/tagline in left column.
- Add a navigation block in the right column.

**Steps to create Footer Block template Part using Editor.**
- First 3 steps are common.
- Add any info inside your footer Block Template Part.

**Steps to create Footer Block template Part for Single Post page**
- Use header and Footer Template Parts.
- In between these two Template Parts, Add a 2-column layout to show Post data on the left side and the Sidebar ( Contain search, calender, and gallery ) Template part.

**Note:** All Block Template Parts are `Custom Post Types` and the post_type is `wp_template_part`.
**Note:** All Block Templates are `Custom Post Types` and the post_type is `wp_temaples` 