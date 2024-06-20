### What's in the Main Menu of Horizon?

The first thing you see when you're logged into Horizon is the _main menu_. Use the menus on the left side to choose commands and perform tasks in the application. 

![](6_main_menu.png)
 
 * **All Parties**: Select this menu to navigate through customer, vendor, and employee records, and more.

* **Customers**: Select this menu to manage payment transaction records. 

* **Products**: Select this menu to manage all items in the system, including products, services, configurators, and equipment.

	A. **Products** are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling. 
	
	B. **Services** are 
	
	C. **Configurators** offer customers a set of predetermined choices for a specific **sales order.** These choices are defined in the configurator and allow users to select a specific number of items, totaling a specific quantity from a specific category. for selecting products, such as different types of six-inch cakes (e.g., yellow, chocolate, red velvet, carrot). Each choice results in a specific sales order item being entered, and the configurator also determines the Bill of Materials (BOM) needed to produce the chosen product.
	
	D. **Equipment** refers to essential items used in various aspects of product creation and order fulfillment. This can range from basic kitchen utensils like plates and knives to larger items necessary for catering social events, such as tables, chairs, and cloths. Equipment is also included in the Bill of Materials, which outlines all necessary items for creating products.

* A **Bill of Materials** (BOM) is akin to a detailed recipe for creating a product. It outlines the necessary parts or materials, their quantities, and how they are created. BOMs can also accommodate different versions or configurations of the product, and while multiple BOMs may exist for an item, typically only one is used at any given time for production.

* **Leads** 



* **Demand** represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

* An **item** is a fundamental unit that can be included in various types of orders. It encompasses everything that can be added to an order, such as products, configurators, equipment, and discounts. Each type of item has distinct attributes and leads to the creation of different demand records when ordered. All types of items are categorized as "Items" and are stored in the main item database table.

