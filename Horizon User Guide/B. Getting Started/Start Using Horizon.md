## Start Using Horizon
______
Welcome to _Horizon_. This file is designed for tracking demand for all our products and items, enabling us to forecast resource availability accurately. It's important to configure each item correctly before adding it to a sales order to ensure precise demand tracking and effective resource planning. 

Access the main features of the app by tapping the buttons in the left-hand tab bar. 

* [Launch Horizon File](#https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/Horizon%20User%20Guide/B.%20Getting%20Started/Start%20Using%20Horizon.md#launch-horizon-fileLaunch%20Horizon%20File)
* Create a Horizon Account
	* Create Your Own Horizon Account
	* Create an Account for Another User in Horizon
* **Log In and Out of Horizon**
* **Navigate the Main Menu**
* **Reset Your Password**
* **Delete Your Horizon Account**

### Launch Horizon File
_____________________
1. **Open FileMaker Pro**: Start the FileMaker Pro application.
2. **Access Hosts Menu**:
    - **Mac**: Go to the top menu bar, select **File**, then **Hosts**.
3. **Select Your Server**: Choose the server hosting your database from the list.
4. **Open the Horizon File**: Find and click on the Horizon file, then confirm by clicking OK.

These steps will launch the Horizon file in FileMaker Pro.

### Create a Horizon Account
____
With your Horizon account, you can access all Horizon files, including Parties, Products, Sales Orders, Invoices, Bill of Materials, and Leads. You can create sales orders, generate demand, generate invoices, create Bills of Materials, and more.
#### Create Your Own Horizon Account

1. **Open Horizon**: [Follow the steps to launch the Horizon file](I.%20Launching%20Horizon%20File.md).
2. **Add Account**: Click **Add Account** on the login page.
3. **Enter Email**:
    - Type your email username and select your domain.
    - Click **Send Request** to validate.
4. **Confirm Email Sent**: Click **OK**.
5. **Validate Email**:
    - Open the **Request for Horizon Access** email.
    - Copy and paste the link into your browser.
    ⚠️ Link expires in 15 minutes.
    
![](https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/1_create_your_own_horizon_account.png)

6. **Select Privilege**: Choose your privilege (e.g., manager, chef), or your role in the system.
7. **Set Password**: Enter your password and click **Continue**.
8. **Enter Details**: Fill in your name and contact info. Select a preferred contact method.
9. **Save Contact Method**: Tick the **Primary** box and click **Save**.
10. **Account Created**: Click **OK**.

#### Create an Account for Another User in Horizon

###### To create an account for another user if you're logged in to Horizon:

1. **Navigate to Employees:**
    
    - Go to **All Parties** > **Employees** > **New Record**.
2. **Enter Employee Details:**
    
    - Fill in the required fields, including the first name and primary contact method. Click **Save**.
3. **Edit Employee Record:**
    
    - Click on the new record and enter a valid email under **FileMaker user name**.
4. **Assign Privilege:**
    
    - Select a **FileMaker privilege** based on the user's role (e.g., manager, chef). Click **Add Account**.
    
![](https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/2_create%20_account_another_user.png)

5. **Email Confirmation:**
    
    - Click **OK** when the **Email Sent** notification appears.
6. **Activate Account:**
    
    - Open the **Request for Horizon Access** email, use the provided link to open FileMaker Pro within 15 minutes, set a new password, and click **Continue**.
7. **Finalize:**
    
    - Click **OK** on the **Account Created** notification.

This process efficiently sets up a new user account in Horizon.

### Log into Your Horizon Account
__________________________________
##### Log in using your Horizon login information

1. **[Launch Horizon file](I.%20Launching%20Horizon%20File.md).**
2. **Open Login Page:**
    - Go to the Horizon login page.
3. **Enter Credentials:**
    - **Account Name:** Enter the email associated with your Horizon account (e.g., xxx@gmail.com).
    - **Password:** Enter your password.

![](https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/7_log_in_screen.png)

4. **Log In:**
    - Click **Log In** or press **Enter** (Windows) / **Return** (Mac).
##### Troubleshooting Login Issues
- If you have trouble with your password, [reset your password](IV.%20Resetting%20Your%20Password.md).

### Log Out of Horizon
___________________
#### From the Main Menu:
- Click **Log Out** at the bottom of the main menu.
#### From Other Pages:
- Click **Main Menu** at the top left.
- Then, click **Log Out** at the bottom of the main menu.

### Navigate the Main Menu
___
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


Demand represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

* An **[item](#item)** is a fundamental unit that can be included in various types of orders. It encompasses everything that can be added to an order, such as products, configurators, equipment, and discounts. Each type of item has distinct attributes and leads to the creation of different demand records when ordered. All types of items are categorized as "Items" and are stored in the main item database table.







### Reset Your Horizon Password
______________________________
**To reset your password if you're not logged in to Horizon:** 

1. [Launch Horizon file.](I.%20Launching%20Horizon%20File.md)

2. Enter your **account name** (email) on the Horizon login page.

3. Click **Reset Password**.

4. Click **OK** after receiving the **Email Sent** notification.

5. Open the Horizon email titled **Request for Password Reset**, copy the link, paste it into your browser's address bar, and press Return (Mac) to **Open FileMaker Pro**.

   ⚠️ Note: The link expires in 15 minutes.

6. Enter your new password, deleting any system-generated one if necessary.

   💡 Tip: Use the tab key to move to the next field easily.

7. Click **Change Password**.

8. Click **OK** upon seeing the successful **Password Reset** notification.

**To reset your password if you're logged in to Horizon**:

1. Go to the main menu, and click on **All Parties.**

2.  Click **Employees** tab. 

3. Find your employee record by using **Find Mode** or **Browse Mode** option — scrolling through the list of employees in the left pane. Click on the record to open it. 

4. Click on **Reset Password** down the **Delete Account** button.

![](https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/4_reset_password.png)

5. Click **OK** after receiving the **Email Sent** notification.

6. Open the Horizon email titled **Request for Password Reset**, copy the link, paste it into your browser's address bar, and press Return (Mac) to **Open FileMaker Pro**.

	⚠️ Note: The link expires in 15 minutes.

7. Enter your **new password**, if needed, delete any system-generated one.

8. Click **Change Password**.

9. Click **OK** upon receiving the successful **Password Reset** notification.
