Title: Reset App State does not reset the product button from Remove to Add to cart  
Environment: Microsoft Edge, Windows 11, saucedemo.com  
Preconditions: User is logged in as standard\_user.  
Steps to reproduce:  
1\. Open the inventory page.  
2\. Click Add to cart for Sauce Labs Backpack.  
3\. Open the menu.  
4\. Click Reset App State.  
Expected Result: The cart is cleared, and the product button changes from Remove to Add to cart.  
Actual Result: The button remains Remove. Clicking it does not remove the item or restore the expected state.  
Severity: Low (assuming the issue is limited to this state-reset behavior).  
