# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/optional-skills/health/fitness-nutrition/scripts/body_calc.py

Prompts

```
['calculate BMI from weight in kg and height in cm with weight category classification', 'calculate total daily energy expenditure using Mifflin-St Jeor BMR formula and activity level', 'estimate one-rep max from weight and reps using Epley, Brzycki, and Lombardi formulas', 'calculate daily macro split for protein, fat, and carbs based on calorie target and goal', 'estimate body fat percentage using US Navy circumference method with neck, waist, and hip measurements', 'search USDA FoodData Central for nutrition information given a food query string', 'search USDA FoodData Central for nutrition info with a custom maximum number of results', 'display formatted nutrition details including calories, protein, fat, carbs, fiber, and sugar for a food item', 'search nutrition info for multiple foods provided via stdin pipe', 'run the nutrition search CLI with one or more food query arguments']
```

Usage

```
{'calculate_bmi': 'calculate BMI from weight in kg and height in cm with weight category classification', 'calculate_tdee': 'calculate total daily energy expenditure using Mifflin-St Jeor BMR formula and activity level', 'estimate_one_rep_max': 'estimate one-rep max from weight and reps using Epley, Brzycki, and Lombardi formulas', 'calculate_macros': 'calculate daily macro split for protein, fat, and carbs based on calorie target and goal', 'estimate_body_fat': 'estimate body fat percentage using US Navy circumference method with neck, waist, and hip measurements'}
```

## File: NousResearch_hermes-agent/optional-skills/health/fitness-nutrition/scripts/nutrition_search.py

Prompts

```
['calculate BMI from weight in kg and height in cm with weight category classification', 'calculate total daily energy expenditure using Mifflin-St Jeor BMR formula and activity level', 'estimate one-rep max from weight and reps using Epley, Brzycki, and Lombardi formulas', 'calculate daily macro split for protein, fat, and carbs based on calorie target and goal', 'estimate body fat percentage using US Navy circumference method with neck, waist, and hip measurements', 'search USDA FoodData Central for nutrition information given a food query string', 'search USDA FoodData Central for nutrition info with a custom maximum number of results', 'display formatted nutrition details including calories, protein, fat, carbs, fiber, and sugar for a food item', 'search nutrition info for multiple foods provided via stdin pipe', 'run the nutrition search CLI with one or more food query arguments']
```

Usage

```
{'search_nutrition_info': 'search USDA FoodData Central for nutrition information given a food query string', 'search_nutrition_max_results': 'search USDA FoodData Central for nutrition info with a custom maximum number of results', 'display_food_nutrition': 'display formatted nutrition details including calories, protein, fat, carbs, fiber, and sugar for a food item', 'search_nutrition_stdin': 'search nutrition info for multiple foods provided via stdin pipe', 'run_nutrition_cli': 'run the nutrition search CLI with one or more food query arguments'}
```

