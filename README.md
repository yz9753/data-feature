# PPDS - Activity 01 - Data Features: Recipe and Calories Generator

This notebook demonstrates the creation of a simple data feature prototype that helps users to get the meal recipe that they need and its associated calories. Particularly, it helps people who are currently on a diet/workout plan, enjoys to cook but are running out of ideas. 

## Features
- convert a meal name into its associated meal ID 
- searches for related meal recipes and returns the top one result and generates the URL, ingredients, calories and calculates the total calories and the serving size (remember to divide the total calories by the serving size!)

## Chosen APIs 
For the purpose of this activity, we chose two APIs, Spoonacular and NutritionIX API for its user friendly features, comprehensive documentation, and its large database. We believe that these APIs would provide us the oppertunity to experiment, iterate, and grow as programmers.   

## Prerequisites 

To run this notebook, you need to set up API keys for:

- Spoonacular API (for retrieving recipe information, ingredients, and serving size )
- NutritionIX API (for retrieving calorie information of ingredients )
  
Make sure to add these API keys to the SECRETS tab in Google Colab.

**Note: Make sure to insert the API Key for Spoonacular API and the API ID and Key for nutritionIX API (in'x-app-id' and 'x-app-key' under the 'get_calories' Function). This information can be found in the lytspace assignment submission description :)** 


## Usage

1. Run the notebook cells in order.
2. When prompted, enter a meal name (e.g., pasta, sushi, salad, pho).
3. The notebook will display the recipe's website, ingredient list, calories for each ingredient, the total calories of the meal, and the serving size. 


## Note

This is a prototype for educational purposes. In a real-world application, additional features like a User Interface(UI), the ability to generate multiple meal recipes, nutrition breakdown (i.e. total fat, sodium, carbohydrate, cholesterol, protein, etc), robust error handling would be implemented.
