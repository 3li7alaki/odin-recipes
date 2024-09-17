# Odin Recipes

This project is a simple website that showcases a collection of recipes. The purpose is to practice basic HTML structure, linking between pages, and formatting content using headers, lists, and images.

## Project Structure

- `index.html`: The homepage of the website, containing links to all the recipes.
- `recipes/`: A folder containing individual recipe pages.

## Features

1. **Homepage (`index.html`)**:
    - Contains an `h1` heading titled "Odin Recipes".
    - Links to individual recipe pages.

2. **Recipe Pages**:
    - Each recipe page will include:
        - An `h1` heading with the recipe's name.
        - An image of the finished dish.
        - A description of the recipe.
        - An ingredients list.
        - Step-by-step instructions.

## Instructions

1. Clone or download this repository.
2. Open `index.html` in a web browser to view the homepage.
3. Navigate to individual recipe pages via the links provided.

## Iterations

### Iteration 1: Initial Structure
- Create an `index.html` file and add the HTML boilerplate.
- Add an `h1` heading with the text "Odin Recipes".

### Iteration 2: Recipe Page
- Create a `recipes` directory.
- Add an HTML file for each recipe inside the `recipes` directory, starting with one recipe (e.g., `lasagna.html`).
- Add an `h1` heading with the name of the dish.
- Link this page in the `index.html` file.

### Iteration 3: Recipe Page Content
- Add an image, description, ingredients list, and step-by-step instructions to each recipe page.

### Iteration 4: Add More Recipes
- Add two more recipes to the website, each with the same structure as the first recipe.
- Update `index.html` to include links to the new recipes, using an unordered list.

## Example Structure

```plaintext
odin-recipes/
│
├── index.html
├── recipes/
│   ├── lasagna.html
│   ├── pizza.html
│   └── salad.html
