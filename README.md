# Gushe
Web app for exploring the Persian Dastgahs using a hybrid tuning system that combines limit-3 Pythagorean ratios with limit-11 microtones (sori and koron). 



keyboard shortcuts

SPACE bar starts and stops the preview of the selected mode.
Number keys 1-0 play are mapped to the first 10 notes of the selected mode. Up to 4 notes can be played at once.



Interface

The circle represents the pitch space. The colour coded nodes represent the underlying gamut (tuning system). Clicking on each node will sound the associated frequency.

The step display at the top shows the first degree of the selected mode. Click on the arrows to rotate the scale within the pitch space to see different transpositional possibilities of each mode.

The text field show the content of the mode chosen in the dropdown menu. The text is interpreted as follows: 

name =  note(annotation), note(annotation), etc. Where name can be any string to denote a given mode, the note name must match the notes already existing on the underlying pitch grid. Accidentals are expressed as "flat", "sharp', "koron" & "sori". A dash ("!") can be used instead of a comma to denote a changeable scale degree called "moteghayer" in the Persian musical system. In this case holding the shift key while pressing the number key corresponding to that scale degree will play the alternate (second) pitch. Here is an example of a valid text:         

Šur = C(a), D(f), E koron, F, G, A(m) ! A koron, B flat

Notes that are not already on the pitch grid can also be defined by using rations (e.g. 3/2) as well as cent numbers (e.g. 90) measure relative from the first degree of the scale.

More documentation to come.
  
