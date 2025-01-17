# AI-Powered Calorie Tracker & Nutrition Assistant

## Overview
The **AI-Powered Calorie Tracker & Nutrition Assistant** is an innovative application designed to help users monitor their food intake, calculate calories, and receive meal suggestions based on remaining daily calorie limits. By integrating with the USDA database and the Nutritionix API, the system ensures accurate nutritional analysis and personalized recommendations. Additionally, it leverages GPT to analyze inputs and provide suggestions for balanced nutrition.

## Key Features
- **Food Intake Tracking:** Users can log their meals, and the system captures calorie and nutrient information.
- **Calorie Calculation:** Automatically calculates total daily calorie consumption using Nutritionix API data.
- **Meal Suggestions:** Provides personalized meal recommendations to meet daily calorie goals.
- **USDA Integration:** Ensures accurate nutrient data by querying the USDA database.
- **GPT Integration:** Enhances the user experience by processing inputs and generating intelligent suggestions.

## Technologies Used
- **Programming Language:** Python
- **APIs:**
  - Nutritionix API: For nutrient and calorie information.
  - USDA Database: For comprehensive nutrient data.
- **Libraries and Frameworks:**
  - `pandas`, `numpy`: For data manipulation and analysis.
  - `requests`: For API integration.
  - `openai`: For GPT-based interactions.
  - `matplotlib`: For visualizing calorie distribution.
- **Environment:** Jupyter Notebook

## How It Works
1. **Data Input:**
   - Users input the details of the food consumed.
   - The application fetches corresponding calorie and nutrient information using APIs.

2. **Calorie Tracking:**
   - Each meal's calorie content is aggregated.
   - A summary of total daily calorie consumption is provided.

3. **Meal Suggestions:**
   - Based on remaining calorie goals for the day, the GPT model generates meal recommendations to help users meet their targets.

## Installation
### Prerequisites
- Python 3.7 or later
- Jupyter Notebook
- API keys for Nutritionix and OpenAI
