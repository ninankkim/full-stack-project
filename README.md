### Sugar Oppa (Full-Stack Web Project)

Website Link: https://sugar-oppa.herokuapp.com/main

Team Members:
1. Bargavi Kanneganti
2. Dasom Huber
3. Heeyoung Song
4. Nina Kim

Languages/Technology:
- Bootstrap
- Express
- Postgre SQL
- Beekeeper
- Chart JS

Site Walk-Through:
- The website, Sugar Oppa, is a fully functional budgeting tool that helps keep your finances in check. The main page comes after two seperate pages: the register page and the login page. The user is first greeted by the login page, where they can enter their login details. However, if the user does not have an account, they may click the register button. From there, they can visit the main page and start improving the future of their finances by taking care of their budgets in the present. 

![](imagesforreadme/login.png)

- The main page has two containers: the first one will input a budget value of the users choosing. For an example, the user's budget can be anything from $500 to $10,000 - and that will be set at the users primary budget. The budget can always be changed or altered - in case you come into more money or win the lottery!

- The second input will take in the user's chosen category (food, gas, beer, dog treats) and you can enter how much you intend to spent on these categories. The second container will also take in a date/time to remind them when the transaction was made. From there, the category amount will be deducted from your primary budget, and the user can always go back and delete these categories in case the user wants to make changes. 

![](imagesforreadme/home.png)

- After the user has entered all the necessary components: budget, category, catgegory amount, and date/time - a list of expenses and a colorful donut chart will appear below to show a visual representation of their transactions. The user can also collapse any specific spection of their donut chart by clicking the colorful labels located above.

![](imagesforreadme/expenses.png)
![](imagesforreadme/chart.png)

- The website also takes into account a user's saving. The user can create a name for a particular financial goal they have in mind, and add an amount they would like to save for that goal. For an example, the user may be saving for a vehicle and intend on saving a specific amount. The remaining budget is atuomatically added to the users savings. 

![](imagesforreadme/saving.png)

-------------------------------------------

1. The website utilized Express for our HTTP framework by using mostly get, post, and delete when we needed to retrieve, send data back to the server, or delete. The get method is used to grab data from the server, the post method sends that data to the server and then creates it, while assigning that to the user that has logged in. The delete method was used to delete any input the user had added - in this case, the expenses and how much they were.

2. The website also used lots of bootstrap, we created inputs, buttons, cards, navbars, all through using the link. The majority of the CSS was just sizing and moving the containers/images around to make it look congruent with the style we wanted. By creating ids/classes and adding them onto our html, we were able to access the specific styling details. So, much of CSS was trial and error - seeing what worked and what didn't. 

3. The database was created using four tables, and three of those tables (budget, expenses, and goal setting) were then connected with a user table. From there, we used sequelize, to create our own API, in order to integrate the data from our database in our website.
