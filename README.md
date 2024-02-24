# pokemon-tracker

<a href="https://github.com/nilpatel-cs/pokemon-tracker/releases">See Releases</a>

A pokemon tracker built using PyQt6 and SQLite that allows for easy tracking of pokemon caught

This is a program which is built using PokeAPI, you can think of it as a over engineered checklist that allows you to keep track and measure your progress in collecting all pokemon and variations of pokemon.

The program is built with pokemon that can be stored in pokemon home in mind, some pokemon forms have been excluded for that reason, also gen 9 isn't included and will be added once home sprite are available.

The interface allows you to filter by generation / region (for regional variant like Alolan Raichu), catch status, shininess, gender forms and alternate forms.

You can also generate a box view which shows you what your home boxes should look like based on the current pokemon that are caught, ones that aren't caught are transparent.

There is also a text summary which breaks down all the percentage completions for specific categories as well as a whole split between shiny and basic.

A lot of QOL features are added, you will automatically prompted to pick a gender / form for pokemon that have differences of those type whenever you attempt to update one you also don't have to worry about keeping track of seperate categories with shared pokemon (example updating a male rattata will also update the regular rattata catch status approriately)

I've found and removed several bugs before shipping this out but if there are any other bugs you find let me know  

