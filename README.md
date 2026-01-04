# tomato-pasta-page
# 🍝 Dynamic Recipe Page

Here’s your go-to project for building out a recipe web page that runs on data, not just static HTML. All the recipe info—title, photo, ingredients—lives inside a JavaScript object. Whenever you want to update or swap out the dish, just change the data. No need to dig through the markup.

## ✨ Features

- **Data-Driven UI**  
  Everything, from the name to the ingredients and image, comes straight from a single JavaScript object. Update the object, and the page updates with it.

- **Automated List Generation**  
  Instead of listing ingredients by hand, the code loops through an array and creates list items on the spot.

- **Responsive Design**  
  The page uses Bootstrap 4’s grid, so the layout adapts—ingredients and photos stack on small screens, sit side by side on big ones.

- **Custom Aesthetics**  
  The ingredients section pops with a linear gradient background, and the "Lobster" font gives it a bit of culinary flair.

## 🛠️ Built With

- **HTML5:** Semantic structure, with IDs ready for dynamic updates.
- **CSS3:** Custom styles, gradients, and a modern card look with rounded corners.
- **Bootstrap 4:** Handles responsiveness and basic layout with utility classes like `w-100` and `d-flex`.
- **JavaScript (Vanilla):** Handles DOM manipulation, object destructuring, and builds list items as the page loads.

## 🚀 How It Works

Here’s the rundown:

1. **Data Storage:**  
   All the recipe details live inside a `recipeObj`—title, image URL, and ingredients.

2. **Element Selection:**  
   The script grabs the relevant HTML elements using `getElementById`.

3. **Content Injection:**  
   It updates the title and image with `textContent` and `src`.  
   For the ingredients, it loops through the array, creates an `<li>` for each one, and drops them into the `<ul>`.

## 📂 Project Structure

- `Recipe page.html`: The main layout, with IDs the script uses to know where to put things.
- `Recipe page.css`: Handles theme colors, typography, and those gradients on the ingredient box.
- `Recipe page.js`: The engine—takes data from the object and builds out the content.
