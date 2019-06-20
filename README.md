# Scripts for android projects
## Icons
Create library module `widgets`
Place all your *.svg, *.png, *.jpg icons to ../_icons folder.
Launch `update_drawables.sh`.
All svg icons are formatted to xml and placed at widgets/src/res/drawable.
All other images are just copied there.
Now all project icons at one place and ready to be viewed with any file browser.

## Gradle
Launch `format_gradle.sh`
Now all gradle.kts files are formatted in one fashion. Do it after any gradle files update.

## Strings
Launch `format_strings.sh` to sort all your strings.xml files in alphabetical order