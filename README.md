# Recipe Organizer
## Team Information
### Team Members
- Nick Vatev
- Ali Ismail 
- Vedant Kansara
---
## Project Description
### Domain
[Project description]
---
## User Stories
### User Story 1 - Save Recipes
As a user, I want to create and save my own recipes so that I can easily access them in the future.
### User Story 2 — Search Recipes
As a user, I want to search for recipes by name or ingredient so that I can quickly find something I want to cook.
### User Story 3 — Organize Recipes
As a user, I want to categorize my recipes so that I can keep my collection organized.
### User Story 4 — Discover Recipes
As a user, I want to find new recipes using an external recipe database so that I can discover meals I haven't tried before.
### User Story 5 — Edit Recipes
As a user, I want to edit or delete saved recipes so that I can keep my collection up to date.
### User Story 6 — View Recipe Details
As a user, I want to view a recipe's ingredients, instructions, and preparation time so that I can follow it while cooking.

---
## Use Cases
### Use Case 1 — Add Recipe
Actor: User
Description: Allows the user to create and save a recipe.
Main Flow:
The user selects the option to add a recipe.
The application displays a form for recipe information.
The user enters the recipe name, ingredients, instructions, and preparation time.
The user submits the form.
The application validates and saves the recipe.
The application confirms that the recipe was saved.
Alternative Flow: If required fields are missing, the application displays an error message.
### Use Case 2 — Search Recipes
Actor: User
Description: Allows the user to search their saved recipes.
Main Flow:
The user enters a recipe name or ingredient.
The application searches the saved recipe collection.
The application displays matching recipes.
The user selects a recipe to view its details.
Alternative Flow: If no matching recipes are found, the application displays an appropriate message.
### Use Case 3 — Categorize Recipes
Actor: User
Description: Allows the user to assign categories to saved recipes.
Main Flow:
The user selects a saved recipe.
The user chooses a category.
The application updates the recipe's category.
The user can filter recipes by category.
### Use Case 4 — Discover Recipes
Actor: User
Description: Allows the user to discover recipes using an external API.
Main Flow:
The user enters a keyword or ingredient.
The application sends a request to the external recipe API.
The API returns matching recipes.
The application displays the results.
The user selects a recipe to view additional information.
Alternative Flow: If the API is unavailable, the application displays an error message.
### Use Case 5 — Edit or Delete Recipe
Actor: User
Description: Allows the user to modify or remove recipes from their collection.
Main Flow:
The user selects a saved recipe.
The user chooses to edit or delete it.
For editing, the application displays the existing information and allows changes.
For deletion, the application requests confirmation.
The application saves the changes or removes the recipe.

---
## Minimal Viable Product (MVP)
| Team Member | MVP Use Case |
|-------------|--------------|
| Nick Vatev | Add Recipe |
| Ali Ismail | Search Recipe |
| Vedant Kansara | Categorize Recipes |

### Note: These assignments may be adjusted
The MVP will focus on allowing users to save recipes, search their saved collection, categorize recipes, and discover recipes through an external API.
### Note: Discovering recipes work distribution is to be determined

---
# Entities
### Note: To be adjusted if necessary
### Entity 1 — Recipe
Represents an individual recipe stored in the application.
Attributes:
recipeId
name
ingredients
instructions
preparationTime
category
Responsibilities:
Store recipe information.
Provide access to recipe details.
Represent a recipe independently of the user interface.
### Entity 2 — Ingredient
Represents an ingredient used in a recipe.
Attributes:
name
quantity
unit
Responsibilities:
Store ingredient information.
Allow recipes to contain multiple ingredients.
### Entity 3 — RecipeCollection
Represents a collection of saved recipes.
Attributes:
recipes
Responsibilities:
Maintain a collection of recipes.
Support adding, removing, and retrieving recipes.

---
## API Usage
**API Name: -**
**Documentation:** [-]
**How it is used in the program: A recipe API will be used to retrieve recipes from an external database**
---
## Design Diagrams 
-
### UML Class Diagram 
-
### Sequence Diagrams 
-
---
## How to Run
[-]
---
## Notes
[To be worked on soon.]
