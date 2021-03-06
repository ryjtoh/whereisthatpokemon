### Website URL
https://ryjtoh.github.io/whereisthatpokemon/

### API of Choice
I leveraged the PokeAPI in order to make GET requests to gather the locations within
Pokemon games where the searched Pokemon can be found. As a previous player of the games, finding where I can find each Pokemon in the game is easier with this solution
that can search across games. I am familiar with the data in the PokeAPI, which is why
I chose it.

### Other Uses
The PokeAPI can also be used to gather stats of Pokemon that may not be referenced in the game, such as "Natures" and "Growth Rates" of Pokemon. The PokeAPI also includes a library of all the Pokemon, items, and moves that can be leveraged to create a real life "Pokedex," which acts as Pokemon dictionary in the games. 

### Further Considerations
One of the biggest considerations when creating this app was thinking about the breakpoint system. Keeping in mind the dimensions of a typical phone screen size a user would have these days (6.06 inches diagonal), I had to keep the buttons and search bar easily viewable and accessible to mobile-users. Although the placement of the buttons is different on the mobile view of the web app, they are still logically grouped together and accessible. The font size was adjusted based on the size of a mobile screen as well, being clear and viewable in both desktop and mobile view.

### User Accessibility
Because of the color scheme of the app may be non-optimal for color blind users, I would add a color blind toggle for different types of colorblindness to account for these users. I also made the buttons and font relatively big in order to increase visibility for user with visual diablities. I could also implement a toggle feature to change the font to be more readable, as the chosen font was selected to match the video game theme.

### Improvement/Expansion
One of the main features that I would implement given more time is the option showing of the actual location in game along with the results. I would do this by accessing another API with the location images and make calls to that API based on the user input and filtering. This would enhance the vision and goal of the web app, and give more visual flair. Speaking of visual flair, I would also want to add more animated components to the page as well through CSS. 
