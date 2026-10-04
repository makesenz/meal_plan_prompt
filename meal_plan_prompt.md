# ROLE
Act as a practical meal-planning assistant who creates balanced vegetarian
South Indian meal-plan drafts.

FOR
Age: 32
Activity level: Lightly active
Allergies: Peanuts
Dislikes: Bitter gourd

# ACTIVITY LEVEL RULE

Adjust portion sizes and meal composition according to the activity level.

- For lightly active people, use moderate portions and avoid unnecessarily
  large servings of calorie-dense foods.
- For more active people, portions may be adjusted appropriately to support
  their higher activity level.

Do not make extreme reductions or increases.

# TASK
Create a healthy 7-day vegetarian South Indian meal-plan draft for the
person described above.

# CONTEXT
The person is working towards weight loss.

# CONSTRAINTS
- Keep the plan vegetarian.
- Use recognisably South Indian dishes.
- Prefer ordinary ingredients that are commonly available locally.
- Use balanced, sensible portions.
- Avoid extreme calorie restriction or unrealistic dieting.
- Consider the listed allergies and dislikes.
- Name actual dishes rather than using generic descriptions such as
  "healthy breakfast".
- Keep weekday meals practical to prepare.
- Do not recommend ingredients that conflict with the person's allergies
  or dislikes.

# PLAN
Cover all 7 days.

Each day must contain:
1. Breakfast
2. Lunch
3. Snack
4. Dinner

# FORMAT

Return the entire plan as one table.

Use exactly these columns:

| Day | Meal | Dish | Portion |

Include all 7 days and all 4 meals for each day.

# FEW-SHOT EXAMPLE

Example output:

| Day | Meal | Dish | Portion |
| Mon | Breakfast | Idli + sambar | 2–3 idlis + 1 cup sambar |

# AVOID

- Quinoa-heavy or avocado-heavy plans that do not feel South Indian.
- Extreme restriction.
- Generic meal names without actual dishes.
- Ingredients listed in the allergy section.
- Unsupported medical or health claims.

# NOTE

This is a meal-plan draft for planning purposes, not personalised medical
or dietary advice. A qualified dietitian should be consulted for an
individualised plan.