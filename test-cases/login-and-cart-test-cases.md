[ID_ T-001.md](https://github.com/user-attachments/files/33595664/ID_.T-001.md)
ID: T-001  
Title: Successful login with valid credentials  
Preconditions: User is on the login page  
Steps:  
1\. Enter username standard\_user  
2\. Enter password secret\_sauce  
3\. Click Login  
Test data: standard\_user / secret\_sauce  
Expected result: Inventory page opens, products are visible  
Actual result: Successful login
Status: Pass

ID: T-002  
Title: Unsuccessful login with invalid password  
Preconditions: User is on the login page  
Steps:  
1\. Enter username standard\_user  
2\. Enter password notsecret\_sauce  
3\. Click Login  
Test data: standard\_user / notsecret\_sauce  
Expected result: Not to enter on site and fail text  
Actual result: Site says: Epic sadface: Username and password do not match any user in this service  
Status: Pass

ID: T-003  
Title: Login with clear login and password  
Preconditions: User is on the login page  
Steps:

1. Click Login

Test data:   
Expected result: Not to enter on site and fail text  
Actual result: Site says: Epic sadface: Username is required  
Status: Pass

ID: T-004  
Title: Login and add to cart any item  
Preconditions: User is on the login page  
Steps:  
1\. Enter username standard\_user  
2\. Enter password secret\_sauce  
3\. Click Login  
4\. Click to Add to cart button on any item.  
5\. Click to Cart cart button   
6\. Check own item  
Test data: standard\_user / secret\_sauce  
Expected result: Items add to cart   
Actual result: Item add to cart  
Status: Pass

ID: T-005  
Title: Login and add to cart any item and remote this item  
Preconditions: User is on the login page  
Steps:  
1\. Enter username standard\_user  
2\. Enter password secret\_sauce  
3\. Click Login  
4\. Click to Add to cart button on any item.  
5\. Click to Cart cart button   
6\. Check own item  
7\. Click to remote button  
Test data: standard\_user / secret\_sauce  
Expected result: Items add to cart and after click to remote button item remote  
Actual result: Item add to cart and remote after click remote button  
Status: Pass
