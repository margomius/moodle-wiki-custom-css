# Custom CSS for Moodle Wiki Activity

Here is some custom CSS for the wiki activity in [Moodle](https://moodle.org/).

## Description

This custom CSS code tries to style the wiki activity in moodle similar to the German [Wikipedia](https://de.wikipedia.org/wiki/Wikipedia)

## Features
* Three easily distinguishable headlines (h3, h4, h5)
* Bottom border for h3 and h4 to seperate sections
* reduced font-weight
* margin between paragraphs

## How To

### Use Custom CSS in Moodle
* Copy the content of the css-file
* Paste to Dashboard > Site administration > Appearance > Themes > Boost > Advanced Setting > Raw SCSS

### Use Custom CSS only for one Wiki Activity

Right-click page > inspect > search for cmid-X (X is a n id, for example 100)
Replace all selectors in the CSS code.

Instead of
```
#page-mod-wiki-view #region-main h3, #page-mod-wiki-edit #region-main h3 {
```
Use this:
```
.cmid-x h3 {
```
Example for .cmid-100:
```
.cmid-100 h3 {
```

## Version History

* 1.0
    * Initial Release

## Acknowledgments

Inspiration, code snippets, etc.
* [Wikipedia.de](https://de.wikipedia.org/)

## Screenshots

### Custom CSS (Moodle 4.1+)
![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/05_List_View.PNG?raw=true)

### Default CSS (Moodle 4.1+)
![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/06_Single_View.PNG?raw=true)
