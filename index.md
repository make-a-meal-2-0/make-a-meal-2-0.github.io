# Overview
[Organization Page Repo](https://github.com/make-a-meal-2-0) <br/>
[Deployment](http://makeameal2.meteorapp.com/#/) <br/>
[M2 Project Board](https://github.com/make-a-meal-2-0/mam2/projects/1) <br/>
[M3 Project Board](https://github.com/make-a-meal-2-0/mam2/projects/4) <br/>

Make-A-Meal is an application that students can use to create an account for their personal preferences which will save information about the user such as dietary restrictions, local food availability, and taste preferences. The application ask the user upon making an account what types of cooking tools are available (George Foreman Grill, Microwave, Toaster Oven, etc.) and then will suggest different different recipes to the user based on their preferences, restrictions, and tools available. Extra information will be made available to the user in the form of cost per serving, number of servings per recipe, and time to prepare the recipe. The goal of the application is to help students feed themself through the gentle guidance toward the direction of edible and easily attainable food. Through the widespread use of this application we believe our foundation can solve collegiate hunger and spread awareness of the ability to cook and feed yourself. 

### There is an ancient proverb that says: 
<blockquote>
"give a man a fish and he'll eat for a day, but give a man a George Foreman Grill and he'll survive his computer science degree"
  </blockquote>
  
# User Guide

[Landing Page](https://makeameal2.meteorapp.com/#/) <br/>
Our home page.
<img src="/images/Landingpagev2.png"> 
<br/>
<br/>
<br/>
[Add Recipe Page](http://makeameal2.meteorapp.com/#/add) <br/>
Our page which allows users to input their own recipes to the collection.
<img src="/images/addRecipev2.png"> 
<br/>
<br/>
<br/>
[My Recipe Page](http://makeameal2.meteorapp.com/#/list) <br/>
Our page that shows a list of recipes the user has inputted, or their favorites/saved.
<img src="/images/myRecipesv2.png"> 
<br/>
<br/>
<br/>
[Recipes Page](http://makeameal2.meteorapp.com/#/searchR) <br/>
This shows all the recipes in the collection.
<img src="/images/recipesv2.png"> <br/>
<br/>
<br/>
<br/>
[Vendors Page](http://makeameal2.meteorapp.com/#/searchV) <br/>
Showcases all nearby vendors in a 1-mile radius.
<img src="/images/vendorsv2.png"> 
<br/>
<br/>
<br/>
# Community Feeback
On average, our user testers were supportive of the main goals of our application and our general layout. However, there were criticisms of our functionality, namely in the lack of recipes and vendors. There was also some concern for the UI: empty space on the bottom of the landing page, reuse of names, confusion as to the meaning of fields, unclear alerts, and more. Better naming conventions, further increase in items in our database, and more interactive features in the future should address these issues.
<br/>
<br/>
<br/>
# Installation Guide
First, install Meteor.  
Create a working Github Repository.  
Download a zip file of Make-A-Meal-2.0.  
Copy the app, config repositories, and .gitignore file (optional) into your repo.  
cd into the local app directory and run the following command to install required libraries: meteor npm install.  
Now run the app with: meteor npm run start.  
Sign up/Log in to access all features.
<br/>
<br/>
<br/>
# Developer Guide
Follow the installation guide, as shown above.  
To modify the fields & features of recipes and vendors, modify the app/imports/api subdirectories.  
To change the permissions accessing recipes and vendors for each account, modify the app/imports/startup/server subdirectories.  
To enhance Recipes themselves, modify the app/imports/ui/components/Recipe.jsx file. Check out https://react.semantic-ui.com for additional features. <br/>
To test default accounts and others items in Collections, modify the app/config/settings.development.json file. 


### Our Team
<table>
  <tr>
    <td width="123">
<img src="https://avatars1.githubusercontent.com/u/33167577?s=460&v=4"/>
      </td>
    <td>
      <strong>[Marty Apilado](https://martyjapilado.github.io/)</strong> is our workhorse behind our creative design process. He is an apspiring software developer who hopes to make an impact.
    </td>
    </tr>
  <tr>
    <td width="123">
<img src="https://avatars0.githubusercontent.com/u/19947797?s=460&v=4"/> 
      </td>
    <td>
      <strong>[Anthony Gasbarro](https://agasbarro36.github.io/)</strong>, a graduate EE student in the computer track and a former Nuclear Reactor Operator for the Navy.
    </td>
    </tr>
    <tr>
    <td width="123">
<img src="https://avatars2.githubusercontent.com/u/21329545?s=460&v=4"/> 
      </td>
    <td>
      <strong>[Davin Takahashi](https://dvntaka.github.io/)</strong> is a  developer for this project. He is trying to pursue one of his diverse niches as an undergraduate CS major. 
    </td>
    </tr>
</table>

