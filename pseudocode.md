# Mind Reader Pseudocode

## Functionality

**Main Goal**: Create a single page web app that plays a game with the user to read their mind. Each page shows different content. The last two pages show symbols and need to change every time the mind reader is reset.

### Things to keep in mind
- Make sure the symbols change between uses so the user doesn't know.

## Objects
- Pages
  - Contains instructions and buttons
- Buttons
  - Next
  - Reset
  - Reveal
- Symbols
 - Should change and randomize every reset.

 ## Define Objects and Functions

 - Pages
   - Text
     - Text changes at top of page.
  - Subtext
    - Text changes at bottom of page.
  
- Buttons
 - nextButton -> Takes user to next page from current page.
 - resetButton -> Takes user to the first page.
 - revealButton -> Takes user to the last page.

- Symbols
  - Symbols -> Array of different symbols.

## Pages

Page 1:
- Text - "I can read your mind".
- goButton displayed.

Page 2:
- Text - "Pick a number from 01-99"
- nextButton displayed.
subText - "When you have your number click next".
- resetButton displayed.

Page 3:
- Text - "Add both digits together to get a new number".
- nextButton displayed.
- Subtext - "Ex: 14 is 1+4=5/n" click next to proceed".
- resetButton displayed.

Page 4:
- Text - "Subtract your new number from the original number".
- nextButton displayed.
- SubText - "Ex: 14-5=9 click next to proceed".
- resetButton displayed.

Page 5:
- Symbols Shows list of numbers with a symbol assigned to each (zero should be the correct symbol)
- revealButton displayed.
- subText - "Find your new number and note the symbol beside the number".
- resetButton displayed.

Page 6:
- Symbol shows correct symbol.
- subText should say "Your symbol is: " + Symbol.
