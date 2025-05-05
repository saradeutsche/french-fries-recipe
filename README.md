# french-fries-recipe
class FrenchFries:
    def __init__(self):
        self.ingredients = {
            "Potatoes": "4 large",
            "Vegetable Oil": "For frying",
            "Salt": "To taste",
            "Paprika": "1/2 tsp (optional)",
            "Garlic Powder": "1/2 tsp (optional)",
        }
        self.steps = [
            "Peel and cut the potatoes into thin strips.",
            "Soak the potato strips in cold water for 30 minutes to remove excess starch.",
            "Drain and pat dry with a paper towel.",
            "Heat oil in a deep fryer or pan to 175°C (350°F).",
            "Fry the potatoes in small batches for about 3-4 minutes until soft but not browned.",
            "Remove from oil and let them drain on a paper towel.",
            "Increase the oil temperature to 190°C (375°F).",
            "Fry the potatoes again until golden brown and crispy, about 2-3 minutes.",
            "Remove from oil, drain, and immediately season with salt and optional spices.",
            "Serve hot and enjoy your homemade French fries!"
        ]
    
    def display_recipe(self):
        print("🍟 French Fries Recipe 🍟\n")
        print("Ingredients:")
        for ingredient, quantity in self.ingredients.items():
            print(f"- {quantity} {ingredient}")
        print("\nSteps:")
        for i, step in enumerate(self.steps, 1):
            print(f"{i}. {step}")

# Example usage
recipe = FrenchFries()
recipe.display_recipe()
