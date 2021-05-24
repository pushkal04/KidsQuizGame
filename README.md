# Description
A basic 2D game for children of standard 1st which allows them to select letters (placed as options) in order to form a word of the picture that would be shown.
(If a picture is of Bird -> Then the letters of the word will be randomized -> RDIB -> The Students will have to arrange them as BIRD -> Pop-up will be shown as Correct/ Incorrect.)

# Features
- Randomizing the questions(pictures) each time the game starts again.
- Randomizing the letters
- A Place to arrange the letters.
- Score (On the basis of arrangement).
- Showing correct word for 2 seconds if the formed word is incorrect.
- Hint
- Animation

# Gameplay
1) The user clicks on a letter, that letter gets placed in the first empty slot. Similarly, the user would click consecutive letters to form a word.
2) When the entire word of the picture is formed:
       a) if the formed word is correct and matched with picture, his score would increase.
       b) if the formed word is incorrect, the correct word is shown at the bottom.
3) The next button gets highlighted. (if formed word is incorrect highlight it after 2 seconds)
a) On clicking it, new set of picture and letters appears.
- For each question, the set of corresponding letters must be randomized each time it appears.
- For each letter selected, it goes to the empty slot. If the undo button is pressed, the letter comes back to its previous position.

# Data Points
- Records the word that the child is selecting whether right or wrong for each question.
- Records the number of times the child clicked on hint button.
- Stores the data in JSON format.

# Setting up
When loaded into untiy, a scriptable object is stored in the scriptable objects folder.
Number of questions to be uploaded and information about questions including pictures 
and answers can be uploaded through the scriptable object. 

