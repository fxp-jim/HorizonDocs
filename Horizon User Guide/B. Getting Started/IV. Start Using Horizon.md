## Start Using Horizon
______
Welcome to _Horizon_. *Horizon* is designed for tracking demand for all our products and items, enabling us to forecast resource availability accurately. It's important to configure each item correctly before adding it to a sales order to ensure precise demand tracking and effective resource planning.

[insert main menu screenshot]
### Navigate the Main Menu
___
The first thing you see when you're logged into Horizon is the _main menu_. Use the menus on the left side to choose commands and perform tasks in the application. 

![](6_main_menu.png)
 
 **All Parties:** Select this menu to navigate through customer, vendor, and employee records, and more.

**Customers**: Select this menu to manage payment transaction records. 

**Products**: Select this menu to manage all items in the system, including products, services, configurators, and equipment.

   A. **Products** are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling. 
   
   B. Services refer to the intangible items the company offers its customers and clients. It involves providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion. 
   
   C. **Configurators** offer customers a set of predetermined choices for a specific **sales order.** These choices are defined in the configurator and allow users to select a specific number of items, totaling a specific quantity from a specific category. Each choice results in a specific sales order item being entered, and the configurator also determines the Bill of Materials (BOM) needed to produce the chosen product.
   
   D. **Equipment** refers to essential items used in various aspects of product creation and order fulfillment. This can range from basic kitchen utensils like plates and knives to larger items necessary for catering social events, such as tables, chairs, and cloths. Equipment is also included in the Bill of Materials, which outlines all necessary items for creating products.

**Sales Orders** record the sale of products or services to a customer. They specify the transaction time, specific details of the ordered goods or services, and a comprehensive list of items sold, including any configurations.

**Invoices** are accounting documents issued to customers and clients to record sales transactions and request payment. It specifies the agreed-upon prices, quantities, and terms of the sale as detailed in the sales order, and includes any discounts applied.

A **Bill of Materials** (BOM) is akin to a detailed recipe for creating a product. It outlines the necessary parts or materials, their quantities, and how they are created. BOMs can also accommodate different versions or configurations of the product, and while multiple BOMs may exist for an item, typically only one is used at any given time for production.

A **lead** is a recorded instance of a potential customer expressing interest in a product, service, or opportunity. It includes the individual's name details of their inquiry (e.g., inquiring for a wedding party), and the source of the lead (e.g., phone call). Additional information such as contact details and specifics about the opportunity they are interested in (e.g., planning a wedding) are also typically included. Leads are pivotal in sales and marketing, representing prospects that may convert into customers with further engagement.

**Demand** represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

An **item** is a fundamental unit that can be included in various types of orders. It encompasses everything that can be added to an order, such as products, configurators, equipment, and discounts. Each type of item has distinct attributes and leads to the creation of different demand records when ordered. All types of items are categorized as "Items" and are stored in the main item database table.
