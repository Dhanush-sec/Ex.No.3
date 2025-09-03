# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques

### DATE:                                                                            
### REGISTER NUMBER : 
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting  

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type
Procedure:


---

#  Food Menu Nutritional Chart

## *Introduction*

A *Food Menu Nutritional Chart* is an organized representation of dish-specific nutritional information, which helps consumers make informed choices about their diet. It typically includes the *dish name, ingredients, calories, protein, fat, and allergen information, often displayed in a **tabular format* for easy comparison. With the increasing awareness of *health, diet tracking, and food allergies*, such structured charts have become essential in restaurants, cafeterias, hospitals, and fitness centers.

The integration of *AI-driven prompt techniques* allows the chart to be dynamic, user-friendly, and personalized to customer needs. Below is a detailed theoretical framework of how different prompting strategies enhance the construction and use of nutritional charts.

---

## *Direct Instruction Prompt*

This method provides *clear and explicit instructions* for generating a nutritional chart. For example:
"Generate a Food Menu Nutritional Chart showing dish name, ingredients, calories, protein, fat, and allergen info. Present the data clearly in a tabular column for easy comparison, and attach related food pictures for each dish."

* *Application:* Ensures consistency in the structure of the chart.
* *Benefit:* Users get a quick, straightforward table without ambiguity.

---

## *Contextual Prompting*

This approach adapts the output depending on the user’s *previous request or context*.
"If the user asks for details of specific dishes, present their ingredients, nutritional values, and allergens in a structured table, while also showing images of the dishes for better understanding."

* *Application:* Enables personalized responses. For example, if a customer asks specifically about Cheese Pizza, the chart will highlight only that dish with full breakdown.
* *Benefit:* Provides *user-specific details*, reducing unnecessary information.

---

## *Persona-Based Prompting*

Here, the system adopts the role of a *nutritionist or restaurant assistant*.
"Act like a nutritionist and friendly restaurant assistant. Explain each dish in a helpful, conversational tone. Example: 'Here’s a breakdown of the dish so you can easily compare calories, protein, and allergens!'"

* *Application:* Adds a *human touch* to the data.
* *Benefit:* Customers feel guided rather than overwhelmed by raw numbers.
* *Example:* Instead of just showing "Cheese Pizza – 600 Calories," the assistant says: “This pizza is rich in energy (600 calories) but contains dairy and gluten, so it may not be suitable for lactose-intolerant individuals.”

---

## *Few-Shot Prompting*

This method uses *examples to teach the system* how to generate outputs in a consistent manner.
\*"Here are examples:

* Dish: Grilled Chicken Salad → Calories: 350 → Protein: 30g → Fat: 15g → Allergen: None → Image: Salad picture

* Dish: Cheese Pizza → Calories: 600 → Protein: 20g → Fat: 22g → Allergen: Gluten, Dairy → Image: Pizza picture
  Now, generate a table for multiple dishes with the same format."\*

* *Application:* Helps the model learn the *exact format* required.

* *Benefit:* Reduces inconsistency in charts.

---

## *Chain of Thought Prompting*

This strategy uses a *step-by-step reasoning approach* to build the chart.
\*"To prepare the Food Chart, follow these steps:

1. List dish names.
2. Break down main ingredients.
3. Add calories, protein, and fat per serving.
4. Highlight possible allergens (gluten, nuts, dairy, etc.).
5. Create a comparison table.
6. Insert relevant food pictures."\*

* *Application:* Ensures *accuracy and completeness* of the nutritional chart.
* *Benefit:* Prevents missing details and promotes *systematic construction*.

---

## *Instruction with Constraints Prompt*

Here, the chart must follow specific formatting or content rules.
"Keep the table clean and readable with no more than 8 columns. Use short descriptions for ingredients. Provide 1 clear picture per dish. Keep text concise but informative."

* *Application:* Ensures the chart is *readable and visually appealing*.
* *Benefit:* Prevents clutter, making it easier for end-users to interpret data.

---

## *Reflective Prompting*

This technique improves clarity by *reflecting the user’s query* before answering.
"When a user asks 'What’s the nutritional value of this dish?', first reflect it: 'You’d like to know the nutritional breakdown for this dish, right?' Then, show them the table row for that dish with an image."

* *Application:* Avoids misinterpretation of user queries.
* *Benefit:* Ensures the customer receives *precise information* for the intended dish.

---

## *Conclusion*

A *Food Menu Nutritional Chart* is not only a tool for *dietary awareness* but also an essential feature for people with *allergies, medical restrictions, or fitness goals. By applying different **prompting algorithms*, the chart can be structured, contextualized, user-friendly, and visually engaging.

This structured approach transforms *static nutritional labels* into *interactive, intelligent food guides*, making it easier for customers to make healthy choices.
| Dish Name             | Ingredients                         | Calories | Protein (g) | Fat (g) | Allergens          | Image |
| --------------------- | ----------------------------------- | -------- | ----------- | ------- | ------------------ | ----- |
| Grilled Chicken Salad | Chicken, lettuce, tomato, olive oil | 350      | 30          | 15      | None               | 🥗    |
| Cheese Pizza          | Wheat flour, cheese, tomato sauce   | 600      | 20          | 22      | Gluten, Dairy      | 🍕    |
| Veggie Burger         | Bun, lettuce, tomato, bean patty    | 450      | 18          | 14      | Gluten, Soy        | 🍔    |
| Paneer Butter Masala  | Paneer, cream, tomato gravy, butter | 520      | 22          | 28      | Dairy              | 🍲    |
| Fish Curry with Rice  | Fish, rice, spices, coconut milk    | 480      | 25          | 20      | Fish, Coconut      | 🐟🍛  |
| Chocolate Brownie     | Cocoa, butter, sugar, flour, eggs   | 400      | 6           | 18      | Gluten, Egg, Dairy | 🍫    |


---





# Result: Thus the Prompts were exected succcessfully.

