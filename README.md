# Custom Recipe Tutorial Generator

Welcome to the **Custom Recipe Tutorial Generator**! This project is a Flask-based web application that takes a list of ingredients as input and generates a step-by-step recipe tutorial. It uses OpenAI's GPT model to create recipes with creative names and fun facts about the ingredients.

## Image
![Screenshot (9504)](https://github.com/user-attachments/assets/f69d8c11-9de9-461e-a882-46d4993f50a1)


## Features

- **Ingredient-Based Recipe Generation**: Enter the ingredients you have, and the app generates a complete recipe with a fun name and detailed instructions.
- **Creative Recipe Names**: Each recipe comes with a quirky, humorous alternate name.
- **Fun Facts**: Learn something interesting about the recipe or its ingredients.
- **Clipboard Support**: Easily copy the generated recipe with a single click.
- **User-Friendly Interface**: Designed with Bootstrap for a clean and intuitive UI.

## Technologies Used

- **Python**: Backend programming language.
- **Flask**: Web framework for building the application.
- **OpenAI API**: Generates recipes and fun facts.
- **Bootstrap**: For responsive and visually appealing design.

## Setup Instructions

Follow these steps to set up the project locally:

### Prerequisites

- Python 3.8 or higher
- An OpenAI API key
- Flask library installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/custom-recipe-generator.git
   cd custom-recipe-generator
   ```

2. Install dependencies:
   ```bash
   pip install flask boltiotai
   ```

3. Set the `OPENAI_API_KEY` environment variable:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key"
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://localhost:8080`.

## Usage

1. Enter a list of ingredients/items you have, separated by commas (e.g., "Bread, Jam, Potato").
2. Click the **"Share with me a tutorial"** button to generate a recipe.
3. View the generated recipe and copy it using the **Copy** button.

## Project Structure

```plaintext
.
├── main.py                  # Main Flask application
└──README.md               # Project documentation
```

## Example

- **Input Ingredients**: Bread, Jam, Potato, Haldi, Tomato Ketchup
- **Generated Recipe**:
  ```
  Recipe: "Spicy Tomato Delight"
  Funny Name: "Tomato Tango Surprise"
  
  Steps:
  1. Heat oil in a pan.
  2. Add chopped potatoes, haldi, and chilly powder. Stir until golden.
  3. Mix in tomato ketchup and garam masala.
  4. Spread on bread and enjoy your creation!

  Fun Fact: Did you know ketchup was once sold as medicine in the 1800s?
  ```

---

Happy cooking and coding! 🍳👨‍💻
```

You can customize the placeholders (e.g., repository link, OpenAI API key) as per your project specifics.
