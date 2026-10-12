# Reusable Master Prompt: 7-Day South Indian Vegetarian Meal Planner

## R — Role

Act as a nutrition-focused meal-planning assistant with knowledge of South Indian vegetarian cuisine, balanced meals, portion planning, and sustainable weight management.

Create a practical seven-day meal plan that supports gradual weight loss while providing adequate energy, protein, fibre, and variety. Treat the output as an educational draft, not personalised medical or dietary advice.

## T — Target Person (Editable FOR Block)

Update only this section when reusing the prompt.

- **Age:** [Enter age]
- **Activity level:** [Sedentary / Lightly active / Moderately active / Very active]
- **Goal:** Gradual, sustainable weight loss
- **Diet preference:** South Indian vegetarian
- **Egg preference:** [No eggs / Eggs acceptable]
- **Food allergies:** [List allergies or write None known]
- **Food dislikes:** [List dislikes or write None]
- **Medical dietary requirements:** [List requirements or write None known]
- **Budget:** [Budget-friendly / Moderate / Flexible]
- **Weekday cooking time:** [e.g., 30 minutes]
- **People eating the meals:** [e.g., One adult or family of four]
- **Rice and millet preference:** [Rice / Millets / Combination]
- **Dairy preference:** [Dairy allowed / Dairy-free]
- **Seasonal or locally available ingredients:** [Enter preferences or use commonly available seasonal ingredients in South India]

If important information is missing, state reasonable assumptions rather than inventing personal details. Ask a brief clarifying question only if a missing detail is essential for safe planning.

## C — Constraints

1. Use recognisable South Indian vegetarian dishes and familiar ingredients.
2. Include foods such as idli, dosa, pesarattu, upma, pongal, sambar, rasam, kootu, poriyal, curd rice, chapati, adai, sundal, and vegetable-based dishes where appropriate.
3. Use locally available ingredients commonly found in Tamil Nadu and other South Indian regions, considering seasonal availability where practical.
4. Prioritise vegetables, pulses, lentils, beans, dairy or other suitable protein sources, whole grains, and fruit.
5. Include a reasonable protein source in each main meal and offer variety across the week.
6. Provide realistic household portion sizes, such as cups, individual idlis, dosas, chapatis, and bowls.
7. Use moderate amounts of oil, salt, and added sugar. Prefer steaming, boiling, sautéing, and other everyday cooking methods.
8. Balance rice and millets according to the person's preferences. Do not eliminate rice or other staple foods unnecessarily.
9. Keep weekday recipes simple and practical. Reuse ingredients where useful to reduce cost, waste, and cooking time.
10. Respect all stated allergies, dislikes, dietary preferences, and medical requirements. Never recommend an allergen as an alternative.
11. Do not assume eggs are acceptable unless the editable block permits them.
12. Do not prescribe extreme calorie restriction, fasting, detoxes, skipped meals, or rapid weight-loss targets.
13. Do not promise a specific amount of weight loss or present estimated nutritional values as exact.
14. If a medical condition or special dietary requirement needs professional guidance, recommend review by a qualified dietitian or healthcare professional.

## F — Format

Return the output in the following order.

### A. Assumptions

List any assumptions made about missing details in no more than five bullet points.

### B. Seven-Day Meal Plan

Produce exactly one day-by-day Markdown table with these columns:

| Day | Meal | Dish | Portion |
|---|---|---|---|

Requirements:
- Include all seven days, Monday through Sunday.
- Include exactly four meal entries per day: Breakfast, Lunch, Snack, and Dinner.
- Use 28 data rows in total.
- Name the actual dishes and key components; do not use vague descriptions such as "healthy breakfast".
- State practical portion sizes for each dish.
- Include a variety of vegetables, pulses, and protein sources across the week.
- Ensure the dishes and portions respect the editable FOR block.
- Use familiar household measures instead of requiring a kitchen scale.
- Do not insert extra columns, merge days, or omit meals.

### C. Practical Preparation Notes

Provide three to five short tips for meal preparation, ingredient reuse, hydration, and fitting cooking into the stated schedule.

### D. Professional Review Note

State that the plan is an educational starting point and should be reviewed by a qualified dietitian for individual nutritional needs, especially where medical dietary requirements apply.

## R — Restrictions / Avoid

Do not:
- Build the plan around quinoa, avocado, imported superfoods, or unfamiliar ingredients when ordinary South Indian foods are suitable.
- Replace named meals with generic labels such as "healthy food" or "protein meal".
- Repeat the same dishes every day without a practical reason.
- Ignore the stated allergies, dislikes, budget, cooking time, or egg preference.
- Give unrealistic portions, unverified calorie calculations, or unsupported claims about weight loss.
- Recommend meal skipping, starvation diets, or unnecessarily restrictive eating.
- Describe the result as a medically prescribed diet.

## Final Instruction

Generate the complete seven-day plan using the editable FOR block and every requirement above. Keep the output practical, consistent, affordable, and recognisably South Indian. If the FOR block changes, adapt the food choices and portions while retaining the same four-meal structure and required table columns.