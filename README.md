"# capstone-project-just-nom-saisahasra" 

In my project, I implemented encapsulation extensively. A clear instance of encapsulation within it is exemplified by the 'Shop' class. Within this class, various variables such as 'name', lists of 'toppings', 'garnishes', 'pizzas', and 'burgers' are encapsulated as private variables. Additionally, the class provides getter and setter methods. Through this encapsulation, it is guaranteed that the variables of the 'Shop' class can only be accessed and modified through the defined public interfaces.


I used encapsulation throughout my project, an example of encapsulation would be the class Shop,  the Shop class encapsulates variables such as 'name', lists of 'toppings',' garnishes', 'pizzas' and 'burgers' as private variables. The class contains getters and setters. Another example of encapsulation would be my SError class, this class contains or encapsulates multiple methods.

I also used inheritance in a lot of my classes, I initially tried to follow the UML diagram and tried to include the Burger recipe and Pizza recipe classes so that the Burger class and Pizza class could inherit from them. However, for my code, I thought it was best to have foodItem be the parent class to the Burger and Pizza class.  I also have multiple classes inheriting from MenuItem class.

I have used polymorphism in my recipe class where I’m adding and removing ingredients the method works for both garnishes and toppings this is one function working for bot object and the ingredient won’t be decided until runtime when the user pick the fooditem.
 
Abstraction


Throughout my program I have commented on area I believe are hard to read to try and improve readability and I have written brief explanations of some part of my code. 

I believe my program has a lot of user interaction as parts of my program change based on what the user enter, for example when they choose a menu some menus have error so they will not open, as well as based of the food they select different ingredients are displayed.

I load the files (test data menus) in my takeaway shop, here I have a method that asks the user to select a file, my loadfile method checks for errors and if the selected if does not have errors in it its will split the file and stores the data.




