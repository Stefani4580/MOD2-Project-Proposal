# MOD2 Project Proposal - Hair of the Dog
## by Stefani Baker

# Description
Imagine this.  You've enjoyed a evening out with friends.  The next morning, in the midst of your hangover, you've decided you'd like a little of the hair of the dog that bit you.  But alas, the evening was so epic that you may have destroyed the brain cell that held the information.  What do you do??

Go to **Hair of the Dog**!

Hair of the Dog is your one stop shop for all things alcoholic.  Do you remember the name of the drink?  We've got you!  Can only remember the spirit?  We've got you!  Have a shelf full of alcohol and don't know what to make?  We've got you!

At Hair of the Dog, you can find recipes for your favorite alcoholic beverages, find recipes for the alcohol you have on hand and discover new drinks.

# Technical Specifications
## API
The CocktailDB - [API Documentation](https://www.thecocktaildb.com/api.php)

The API is free for non-commercial use with no limits on number of calls.  There is a limit of 100 items available in the database.

Search cocktail by name
https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita

List all cocktails by first letter
https://www.thecocktaildb.com/api/json/v1/1/search.php?f=a

Search ingredient by name
https://www.thecocktaildb.com/api/json/v1/1/search.php?i=vodka

Lookup full cocktail details by id
https://www.thecocktaildb.com/api/json/v1/1/lookup.php?i=11007

Lookup ingredient by ID
https://www.thecocktaildb.com/api/json/v1/1/lookup.php?iid=552

Lookup a random cocktail
https://www.thecocktaildb.com/api/json/v1/1/random.php

Lookup a selection of 10 random cocktails (only available to $2+ Patreon supporters)
https://www.thecocktaildb.com/api/json/v1/1/randomselection.php

List Popular cocktails (only available to $2+ Patreon supporters)
https://www.thecocktaildb.com/api/json/v1/1/popular.php

List most latest cocktails (only available to $2+ Patreon supporters)
https://www.thecocktaildb.com/api/json/v1/1/latest.php

Search by ingredient
https://www.thecocktaildb.com/api/json/v1/1/filter.php?i=Gin
https://www.thecocktaildb.com/api/json/v1/1/filter.php?i=Vodka

Filter by multi-ingredient (only available to $2+ Patreon supporters)
https://www.thecocktaildb.com/api/json/v1/1/filter.php?i=Dry_Vermouth,Gin,Anis

Filter by alcoholic
https://www.thecocktaildb.com/api/json/v1/1/filter.php?a=Alcoholic
https://www.thecocktaildb.com/api/json/v1/1/filter.php?a=Non_Alcoholic

Filter by Category
https://www.thecocktaildb.com/api/json/v1/1/filter.php?c=Ordinary_Drink
https://www.thecocktaildb.com/api/json/v1/1/filter.php?c=Cocktail

Filter by Glass
https://www.thecocktaildb.com/api/json/v1/1/filter.php?g=Cocktail_glass
https://www.thecocktaildb.com/api/json/v1/1/filter.php?g=Champagne_flute

List the categories, glasses, ingredients or alcoholic filters
https://www.thecocktaildb.com/api/json/v1/1/list.php?c=list
https://www.thecocktaildb.com/api/json/v1/1/list.php?g=list
https://www.thecocktaildb.com/api/json/v1/1/list.php?i=list
https://www.thecocktaildb.com/api/json/v1/1/list.php?a=list


 Images
Drink thumbnails
Add /preview to the end of the cocktail image URL
https://www.thecocktaildb.com/images/media/drink/vrwquq1478252802.jpg/preview (100x100 pixels)


Ingredient Thumbnails
https://www.thecocktaildb.com/images/ingredients/gin-Small.png (100x100 pixels)
https://www.thecocktaildb.com/images/ingredients/gin-Medium.png (350x350 pixels)
https://www.thecocktaildb.com/images/ingredients/gin.png (700x700 pixels)

## Technical Approach

### DB - Firebase
I will attempt to learn Firebase for this project.  I will store my API data in Firebase to reduce on the number of API calls over the network thus reducing overall response time.

### UI
- React Bootstrap
- React Router

### Data Structures
- Classes
    - Alcohol
    - Recipe

## Wireframe

https://balsamiq.cloud/shambyf/pm6ekv2



