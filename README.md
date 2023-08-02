### open-svg-for-teaching-vocabulary
This is a collection of images suitable for teaching vocabulary.

* Scalable Vector Graphics
* Free and Open-sourced
* Drawn (not rendered)
* Full Color 
* As simple as will illustrate the subject effectively 
* Suitable for all ages [more specs to come]

Filenames are the vocabulary word only.

Spaces are replaced with underscores - polar_bear.svg
  Dynamically replace these underscores for display.

Parentheses are used for disambiguation - chicken(meat).svg
  Split on '(' and use the first index to display the word or use it as an id.
  let myId = yourFileName.split('(')[0];
  let myDisplay = myId.replace(/_/g, ' ');