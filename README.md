# Odin Recipes

This project is part of The Odin Project: [Recipes](https://www.theodinproject.com/lessons/foundations-recipes) and aims to create a basic HTML webpage featuring links to several recipes.

Live Demo: https://jambalong.com/odin-recipes/

## Objectives

Completing this project will demonstrate my ability to:

- Create a basic webpage from scratch
- Use the proper HTML boilerplate
- Utilize appropriate HTML elements and attributes
- Apply basic HTML formatting and add links

## Assignments

### Iteration 1: Initial Structure
- Create an `index.html` file within the `odin-recipes` directory.
- Include the usual boilerplate HTML and add an `<h1>` heading “Odin Recipes” to the body.

### Iteration 2: Recipe Page
- Create a new directory named `recipes` within the `odin-recipes` directory.
- Create a new HTML file within the `recipes` directory named after your chosen recipe (e.g., `lasagna.html`), including the usual boilerplate HTML.
- Add an `<h1>` heading with the recipe’s name and link it from the `index.html` file. Example:
  ```html
  <a href="recipes/recipename.html">Recipe Title</a>
  ```

### Iteration 3: Recipe Page Content
Your recipe page should include:

- An image of the finished dish under the `<h1>` heading.
- A “Description” heading followed by a paragraph or two describing the recipe.
- An “Ingredients” heading followed by an unordered list of the ingredients needed.
- A “Steps” heading followed by an ordered list of the steps for making the dish.

### Iteration 4: Add More Recipes
- Add two more recipes with the same page structure.
- Link to the new recipes on the index page, using an unordered list for the links:
  ```html
  <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
  ```
Focus on building out the links rather than their appearance for now.

## Installation Instructions

### Prerequisites
- A web browser (Chrome, Firefox, etc.)

### Installation Steps

1. **Clone the Repository**
   
   Open your terminal and run the following command to clone the repository:
   ```bash
   git clone https://github.com/jambalong/odin-recipes.git
   ```
   
3. **Navigate to the Project Directory**
   
   Change to the project directory:
   ```bash
   cd odin-recipes
   ```
   
4. **Open the `index.html` File**
   
   Open the `index.html` file in your preferred web browser. You can do this by either:
   - Dragging the file into your browser window.
   - Right-clicking the file and selecting "Open with" and choosing your browser.
