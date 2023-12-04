# Poetry For Neanderthals

Poetry for Neanderthals is a Party game made by the Exploding Kittens company. The game invloves a selection of "word cards" which have to be described to other players using only single-syllable words.

This is an application version created for Android 12 using Java in Android Studio. This is indended as a personal project and to allow us to both play the game easier and to allow us to have a larger repository of words to pick from without repetition.

Feel free to use this application yourself or expand upon the word repository, but please support the official release by purchasing the game directly from the creators. https://www.explodingkittens.com/products/poetry-for-neanderthals



## Base Gameplay

Base gamplay is quite simple. We just need a selection of cards with both 1-point words and 3-point word phrases. For example the 1-point word "salt" and the respective 3-point phrase being "Salt Shaker".

The gameplay from the pespective of this application is very simple. Step 1, pick a random card. Step 2, wait for user input for "1 point guessed", "3 point guessed", "card skipped" (for 0 points), or "bonk" (meaning the rules were violated resulting in -1 points). Step 3, select a new card and repeat until the time runs out.



## Construction of the Application

Construction of the application should be very simple. We will need a total of 3 screens.

The first screen will be a "main menu" of sorts which will allow the user to signal when they are ready.

The second screen will be the main gameplay, showing the card and giving the 4 options to progress through the game as described above

The third screen will be the "end of game" screen, showing the score from the last game and allowing the users to either return to the main menu or play again.



## Word List(s)

Word lists for the base game have already been compiled, as described here https://www.reddit.com/r/boardgames/comments/pv51ap/is_there_a_complete_list_of_all_cards_in_poetry/

We will not be using the base word sets as to avoid any copywrite, so instead will compile a new list of as many words as possible and a respective 3-point word phrase for them.

Gathering a list of nouns is easy enough, but the hard part here will be creating a list of phrases for the 3-point cards.
