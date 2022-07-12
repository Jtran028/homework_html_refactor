# CODE REFACTOR ASSIGNMENT

## This Assignment's Task

This weeks assignment was to REFACTOR a source code given to us.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes Made in HTML 
* Changed most DIV classes to proper HTML Semantics
* Changed CSS to match proper SEMANTIC changes
* Added ALT and TITLE to all image's to create better accessibility for different loading criteria
* Changed LINE 37 from a CLASS to ID to properly fix the link feature when clicking "Search-Engine-Optimization"

## Changes Made in CSS
* Changed the selector ".header div" to ".header nav" so that the CSS applied to the navigation bar properly after HTML Semantics added
* Removed the IMG URL in the CSS, replaced the div class to an img class and added its relavtive source.

## FINAL
All Semantic HTML changes made still kept the original format of the website while adding better accessibility to certain aspects.

The websites navigation bar links now work properly

All images now display text when hovered over

All changes made have included comment lines.

## LIVE LINK
https://jtran028.github.io/homework_html_refactor/

## Screen Shot
<img src="https://user-images.githubusercontent.com/108315442/178410043-8590edc5-cfee-4c7e-b4e8-8f392b43d21f.png">
