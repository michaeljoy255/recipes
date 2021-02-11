# Recipes

Store and convert recipes to PDF.

## Ideas

- Use Vue and Vuetify for the project
- Store the following for recipes:
  - Recipe Name
  - Recipe Image
  - Ingredients: Array
  - Categories: Array (Dessert, Soup, Entre, etc.)
  - Tags: Array (Fast, Easy, Attention Required, etc.)
  - Prep Time: DateTime
  - Cook Time: DateTime
  - Instructions: Array
  - Step: Object (details of the prep or cook step, maybe even images)
- Download Recipe PDF
- Search recipes by: 
  - Name
  - Ingredients
  - Category
  - Tags
  - Prep Time
  - Cook Time
  
```javascript
// Example Recipe object
const Recipe = {
  name: String,
  image: String,
  ingredients: [],
  categories: [],
  tags: [],
  prepTime: DateTime,
  cookTime: DateTime,
}
```
