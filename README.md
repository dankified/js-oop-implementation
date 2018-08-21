# Class Implementation

##Instructions
Create a **Drink** class. Each **instance** of this **class** should have the following properties: name, brand, flavor. flavor is an optional parameter with a default value of **null**. Define a **method** named **describe** in the **Drink class** that returns a string that has the following format if the drink has a **flavor** **property** `${brand}: ${name} with flavor ${flavor}` else if the **flavor** is null return `${brand}: ${name}`.
Create a **Spirit** class that inherits from **Drink**. This **class** has the same properties as **Drink** but it will add another property named **alcoholContent** (which is a numeric value between 0 and 100) if the **alcoholContent** value falls out of those values assign 0 to it.
Define a function in **Spirit** named **haveASip**. This function will take a parameter named **weight** and it will substract the **alcoholContent** from the **weight** argument and return the resulting value divided by 10. 