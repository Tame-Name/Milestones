#CSCI 3308 Software Development Methods and Tools
##Group Project – Milestone One


**Team Name:** Tame_Name

**Members:** David Gerstle, Josh Asmussen, Kamen Shah, Tim Euken, Yiou Gao, Shane Murphy

**Description:** We want to create an Android app that will improve personal success when dieting. The user will input their nutritional goals, such as total calories and macro breakdowns of fats, proteins, and carbs. In addition, the user can specify their diets, such as paleo, vegan, vegetarian, or gluten-free, and their specific food preferences and dislikes. 
The app will in turn give the user a weeks worth of recipes that minimizes ingredients, and a shopping list for the entire week. This will increase diet success by making it easy to shop for and cook recipes, as well as providing a diverse set of recipes each week so the dieter does not have to eat the same thing every day.  
We will be using 3 Edamam APIs: Nutritional Analysis API, Food Data API, and Recipe Search API. These will allow us to pull known nutritional data into the app and use it to optimize the recipes for each day. 

**Vision Statement:** Using technology to enhance people’s personal diet plan and improve overall general health and wellness.

**Motivation:** Several members of the team have had difficulty in the past trying to create a meal plan when dieting. One issue is that having to eat the same foods and recipes day after day gets old extremely quickly. We envision a solution to this problem in which a user can input their nutritional goals and food preferences, and the app will give them a meal plan for the week, including a shopping list and recipes for each meal. This will make it much easier to follow a diet and meet nutritional goals.  

**Risks:** The major risks we are undertaking are lack of experience, API Restrictions, and time constraints. Most of our team has not worked very much with APIs, so it will definitely be a learning experience. In addition, we do not have full details on the data the proposed API will give us, so we hope not to run into an underdeveloped nutritional database that will not provide us with the needed info. Lastly, each member on our team has a very busy schedule this semester, so time constraints will be very limiting. 

**Risk Mitigation Plan:** We plan to prioritize the key features of the app in order to battle our time constraints. We will rely on teammates who are familiar with certain aspects of the project to assist those who are struggling. Lastly, consistent communication will be key in order to make sure daily progress is made and any issues that arise are promptly dealt with. 

**Version Control:** We will we working in design sprints individually and as a team, and will save each version to GitHub after we verify the code is functional. Any bugs will be documented for future versions to address. 

**Development Method:**
Agile/Scrum
We will use asana as a task management tool to organize all current and future tasks.

**Collaboration Tool:** Slack, Cellular devices, GitHub, asana

**Proposed Architecture:**

We are using Android Studio (IDE), XML/Photoshop(Front End), java(Back end), ASP.net(web service), SQL (Backend database), GCE (Hosting platform)

Android app will communicate to the web service which will query the SQL server on GCE. The webservice will then return xml to the android app. 
