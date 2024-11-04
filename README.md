# NutrifyMe
## Design Document
**Authors**: Supriya Polepalli, Anjana Kola, Mayank Dalal, Ravi Patidar, Saurabh Rathi.


## Introduction
In today's health-conscious world, a recipe recommendation system can be an invaluable tool for individuals looking to eat well and maintain a balanced diet. Our Recipe Recommendation website aims to be a comprehensive platform where users can discover, explore, and share recipes that cater to their nutritional needs. The website will feature:
- A Diverse Selection of Recipes: Users can browse a wide variety of recipes across different cuisines and dietary preferences, including vegan, gluten-free, low-carb, and more.
- Nutritional Insights: Each recipe will include detailed nutritional information, helping users make informed choices about their meals and understand their dietary impact.
- Personalized Recommendations: Leveraging user preferences and dietary goals, the system will provide tailored recipe suggestions that align with individual health objectives.
- User Reviews and Ratings: Community engagement will be encouraged through user-generated reviews and ratings, allowing others to gauge the popularity and effectiveness of each recipe.


## Logo
![NutrifyMe](https://github.com/supriyapolepalli/XML_Project/blob/main/WhatsApp%20Image%202024-11-03%20at%2018.14.42.jpeg)


## Data Feeds
- **Youtube API** : [To incorporate engaging video content related to recipes, cooking techniques, and nutritional insights providing visual guidance for meal preparation.](https://developers.google.com/youtube/v3)
- **Spoonacular API**:[To access recipes and nutritional information for enhanced meal planning.](https://wger.de/en/software/api)


## Functional Requirements
### **Requirement 100.0: Search for Recepies**
Scenario: As a user interested in cooking, I want to search for recipes by title, ingredients, or cuisine, so that I can easily find dishes that match my preferences.
Dependencies
- Recipe data is available and accessible via the Spoonacular API.
- The search functionality must be user-friendly.
Assumptions
- Recipe titles and ingredients are accurately listed in the database.
Examples 1.1
Given a feed of recipe data is available
When I search for "chocolate cake"
Then I should receive results that include:

Title: "Rich Chocolate Cake"; "Moist Chocolate Cake"
Ingredients: Chocolate, Flour, Sugar, Eggs
Cuisine: Dessert
Nutritional Info: 350 calories per serving
Reviews Count: 150

### **Requirement 101.0: Viewing Recipe Details**
Scenario: As a user, I want to view detailed information about a recipe, including ingredients, cooking instructions, and nutritional insights, so that I can make informed cooking choices.
Dependencies
- Recipe data is accessible via the Spoonacular API.
Assumptions
- Users will be interested in comprehensive details before trying a recipe.
Examples 1.1
Given I select a recipe titled "Vegetable Stir-Fry"
When I view the recipe details page
Then I should see:

Title: Vegetable Stir-Fry
Ingredients: Bell peppers, Broccoli, Carrots, Soy sauce
Cooking Instructions: Step-by-step cooking directions
Nutritional Info: 200 calories, 10g protein, 5g fat
Preparation Time: 30 minutes

### **Requirement 102.0: YouTube Integrations**
Scenario: As a user, I want to access video content related to recipes and cooking techniques, so that I can enhance my understanding through multimedia resources.
Dependencies
- Access to the YouTube API for video content.
Assumptions
- Users enjoy consuming content in various formats.
Examples 1.1
Given I am on the details page for "Pasta Primavera"
When I scroll to the YouTube section
Then I should see embedded videos, including:
Video Title: "How to Make Pasta Primavera"
Duration: 10 minutes

### **Requirement 103.0: User Account Management**
Scenario: As a user, I want to manage my account settings, including my profile information, saved recipes, and dietary preferences, so that I can personalize my experience.
Dependencies
- A secure user database for managing account information.
Assumptions
- Users value the ability to customize their experience.
Examples 1.1
Given I am logged into my account
When I navigate to the Account Settings page
Then I should see options to:
Edit Profile: Update my name, email, and password.
Dietary Preferences: Select dietary restrictions (e.g., vegetarian, gluten-free).
Saved Recipes: View and manage my favorite recipes.


## Scrum Roles
- DevOps/Product Owner/Scrum Master : Supriya Polepalli
- Frontend Developer: Mayank Dalal, Ravi Patidar
- Integration Developer: Saurabh Rathi, Anjana Kola


## Weekly Meetings
Tuesday 12PM on Teams 
