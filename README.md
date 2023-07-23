### open-svg-for-teaching-vocabulary
This is a collection of images suitable for teaching vocabulary.

* Scalable Vector Graphics
* Free and Open-sourced
* Drawn (not rendered)
* Full Color 
* As simple as will illustrate the subject effectively 
* Suitable for all ages [more specs to come]

Filenames are the vocabulary word only.
Spaces are replaced with underscores. 
  Dynamically replace them for display.
If there are multiple meanings for a word, a descriptor is added in parentheses.
  Split on '(' and use the first index for the filename.
  
let word = yourFileName.split('(')[0].replace('_', " ");