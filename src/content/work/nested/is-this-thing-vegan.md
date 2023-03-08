---
title: Is This Thing Vegan?
publishDate: 2023-02-10 00:00:00
img: /assets/isthisthingvegan.gif
img_alt: App displaying ingredients of beyond meat after entering UPC code.
description: |
   Developed a project to help check if ingredients withing food products are actually vegan.
tags:
  - Design
  - Dev
  - Branding
---

Link to project https://is-this-vegan.netlify.com

### **How It's Made?**

Tech used: HTML, CSS, JavaScript, product ingredients are pulled from calls to [Open Food Facts API] (https://us.openfoodfacts.org), background image is from Freepik.

### **How Does It Function?**

Enter a UPC code within the input field then click the Get Info button.

"is this thing vegan?" cycles through the ingredients from the API and populates ingredients from the product within a table returning a value of yes, no, idk and maybe next to each ingredient.

yes will be displayed in green for the ingredient is vegan.

idk or maybe will be displayed in yellow if there is any uncertainty that the ingredient is vegan

no will be displayed in red if there is absolute knowledge that the ingredient is not vegan.

### **Where Is The ingredient list populating from?**

"is-this-thing-vegan" receives information from API calls to Open Food Facts.

### **Optimizations:**
 Background image and styling were updated with the help of @xoladybugs so the project appeared more fun and playful. Removed border from being displayed on page load before product image rendered. By using JavaScript, I was able to display the border on click after a request was fetched to the API.

### **Lessons Learned:**

 Some of the ingredients that the API aren't sure if it's vegan displays as idk and maybe. Some of those ingredients also appear to be vegan ingredients. More research needs to be done to determine if those ingredients are in fact vegan.

Thank You! I got the idea to build this project from watching @Mayanwolfe's Twitch stream. @xoladybugs thanks for your help with improving the look and feel for this project.