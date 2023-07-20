# ChefBot - Recipe Generator Chatbot

ChefBot is an AI-powered recipe generator chatbot that assists users in generating recipes based on their provided ingredients or prompt. The bot utilizes OpenAI's GPT-3.5 Turbo model to generate creative and engaging recipe ideas. With ChefBot, users can discover new dishes, find alternatives for specific ingredients, and even obtain nutritional information for their recipes.


## Features

- **Recipe Generation**: ChefBot can generate recipes based on user-provided ingredients or prompts. It uses the power of GPT-3.5 Turbo to create diverse and inventive recipes.

- **Content Moderation**: The bot incorporates content moderation to ensure that responses adhere to community guidelines. If a user input violates any predefined categories, ChefBot will provide a warning and explanation.

- **Ingredient Alternatives**: When a user indicates they lack a particular ingredient, ChefBot can suggest alternatives or modify the recipe to exclude the missing item.

- **Nutritional Information**: ChefBot can provide nutritional values for recipes upon user request, making it helpful for individuals with dietary preferences or restrictions.

- **Keyword Recognition**: ChefBot recognizes keywords like "veg," "non-veg," or "vegan" to tailor recipes to users' dietary preferences.

- **User-Friendly Interface**: The bot employs a simple conversational interface, providing users with a seamless recipe generation experience.



## Prerequisites

Before running ChefBot, you need to have the following installed:

- Jupyter Notebook
- Python 3
- OpenAI Python Library (`openai`)
- Dotenv Python Library (`dotenv`)

You can install the required dependencies using the following command:

```bash
pip install openai
pip install dotenv
```

## Getting Started

1. Clone the repository to your local machine.

```bash
git clone https://github.com/krutika-ladani/chefbot.git
```

2. Navigate to the project directory.

```bash
cd ChefBot
```

3. Get your OpenAI API key and create a `.env` file in the project's root directory.

```
OPENAI_API_KEY=your_openai_api_key_here
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the `main.ipynb` notebook in Jupyter Notebook.

6. Execute the cells to run the ChefBot recipe generator chatbot.

## Usage

1. ChefBot will greet you with a prompt message, explaining its capabilities.

2. You can start the conversation by providing a question or mentioning your available ingredients. The bot will then generate a recipe based on your input.

3. ChefBot may ask clarifying questions to ensure the recipe meets your preferences. Answer them accordingly.

4. If you lack a specific ingredient, let the bot know, and it will suggest an alternative or adjust the recipe accordingly.

5. To obtain nutritional information for the generated recipe, ask ChefBot, and it will provide the details.

6. If ChefBot encounters any inappropriate content in your input, it will warn you about the specific categories that were violated.

7. To stop the conversation with ChefBot, you can interrupt the kernel or restart the kernel and clear the outputs.

## Future Enhancements

ChefBot is a flexible and expandable project. Here are some potential enhancements to consider:

- **User Profiles**: Implement user profiles to store preferences and dietary restrictions for personalized recipe recommendations.

- **Web Interface**: Create a web-based version of ChefBot for a more user-friendly and visually appealing experience.


## Acknowledgments

- This project is made possible by OpenAI's GPT-3.5 Turbo model.

- Special thanks to the creators and maintainers of the dependencies used in this project.

---

Happy cooking with ChefBot! 🍳🧁🍲


