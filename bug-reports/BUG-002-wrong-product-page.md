BUG-002   
Title: Backpack opens the wrong product details page  
Environment: Google Chrome, Windows 11, [saucedemo.com](http://saucedemo.com)  
Preconditions: Logged on site as problem\_user  
Steps to reproduce:

1. Open saucedemo.com and log in as problem\_user.  
2. Open the Inventory page.  
3. Click the name or image of Sauce Labs Backpack.  
4. Observe the product details page and URL. 

Expected: When the user clicks on the name or image of the product, the page of this particular product opens.  
Actual: When the user clicks on the name or image of the Sauce Labs Backpack, the page of another product Sauce Labs Fleece Jacket [https\://www\.saucedemo.com/inventory-item.html?id=5](https://www.saucedemo.com/inventory-item.html?id=5) opens.  
Severity: Medium  
Priority: Medium
