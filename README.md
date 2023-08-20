# Update
The TocWidget is now an official part of Tilium Notes, so no more updates will be made here. 

# Trilium-TocWidget

Table of contents [Trilium](https://github.com/zadam/trilium/) widget for
editable and readonly text notes originally created by [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget).

## Tweaks
- Appears on right panel at 100 height instead of on bottom left at 30 height
- Does not appear on non-text notes
- Only appears in text notes if the label #tocWidget is added
- Child notes that inherit the attribute #tocWidget can remove the widget with #noTocWidget and vice versa

## Screenshot
![TextNotesOnly](https://user-images.githubusercontent.com/89228316/177449255-9d51e030-817e-4742-a961-f822206c1a68.png)
Theme: [Stellar Dark](https://github.com/Lolabird/stellar-dark-theme-trilium)


## Features

- The ToC is live and automatically updated as new headers are added to the note
- Works on editable and readonly text notes
- Clicking on the ToC navigates the note
- Tested on Trilium Desktop 0.50.3

## Installation
- Create a code note of type JS Frontend with the contents of [TocWidget.js](TocWidget.js)
- Set the owned attributes (alt-a) to #widget

## Configuration Attributes
### In the Text Note
- noTocWidget: Set on the text notes you don't want to show the ToC for
### In the Script Note
- tocWidgetHeightPct: Percentage of pane height to use, 0 for dynamic, default
  is 100
- debugLevel: Enable output to the javascript console, default is "info"
  (without quotes): 
    - "error" no javascript console output
    - "warn" enable warn statements to the javascript console
    - "info" enable info and previous levels statements to the javascript console
    - "log" enable log and previous levels statements to the javascript console
    - "debug" enable debug and previous levels statements to the javascript console

## Bugs
- None

## Todo
- Nothing

## Discussions

https://github.com/zadam/trilium/discussions/2799
