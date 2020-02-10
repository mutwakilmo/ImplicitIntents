# ImplicitIntents

# Android fundamentals 02.3: Implicit intents

## What you should already know

You should be able to:

-   Use the layout editor to modify a layout.
-   Edit the XML code of a layout.
-   Add a  `Button`  and a click handler.
-   Create and use an  `Activity`.
-   Create and send an  `Intent`  between one  `Activity`  and another.

## What you'll learn

-   How to create an implicit  `Intent`, and use its actions and categories.
-   How to use the  `ShareCompat.IntentBuilder`  helper class to create an implicit  `Intent`  for sharing data.
-   How to advertise that your app can accept an implicit  `Intent`  by declaring  `Intent`  filters in the  `AndroidManifest.xml`  file.

## What you'll do

-   Create a new app to experiment with implicit  `Intent`.
-   Implement an implicit  `Intent`  that opens a web page, and another that opens a location on a map.
-   Implement an action to share a snippet of text.
-   Create a new app that can accept an implicit  `Intent`  for opening a web page.

## App overview

In this repo you create a new app with one  `Activity`  and three options for actions: open a web site, open a location on a map, and share a snippet of text. All of the text fields are editable (`EditText`), but contain default values.
