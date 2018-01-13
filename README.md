# recipe-to-list
App Project for LearnTeachCode workshop


## Features
* Camera
* Saves image
* Uses OCR to translate characters from images to machine-encoded text
* Editable text
* Translates ingredients into a list of groceries with the appropriate amount to buy (for example, if the recipe calls for 1/4 c onion, Recipe to Text will list the item as 1 onion)
* Checkable boxes to keep track of which items need to be bought. 
* Library of saved images


## Implementation Details

* Inputs of the app
  * image (object)
  * user's edits of text (string) 
  * data about conversions from ingredient amount to grocery list item (string)
  * checking off boxes of grocery list items (boolean)
* Outputs
  * ingredient list (string)
  * grocery list items (string)
  * grocery list items change appearance when checked off by user
* Variables
  * image
  * ingredient list
  * grocery list items
  * name of recipe (string)
* Data that needs to be stored permanently
  * ingredient list
  * grocery list items
  * name of recipe
* Events
  * button click for turning on the camera
  * button click for taking a picture
  * typing ingredient list
  * clicks for checkable boxes
  * button click for choosing to make an edit
  * button click for choosing to "make my list"
  * button click to save recipe
  
  


