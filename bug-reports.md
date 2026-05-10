# Bug Reports

## Bug 001

### Title
Valid Login with "locked_out_user" as username

### Steps to Reproduce
1. Open the website login page https://www.saucedemo.com/
2. Insert valid username (locked_out_user)
3. Insert valid password (secret_sauce)
4. Click Login

### Expected Result
User logs successfully

### Actual Result
Log in error



## Bug 002

### Title
Add all products to cart

### Steps to Reproduce
1. Open the website login page https://www.saucedemo.com/
2. Insert valid username (locked_out_user)
3. Insert valid password (secret_sauce)
4. Click Login
5. Add "Sauce Labs Backpack" , " Sauce Labs Bike Light", "Sauce LAbs Bolt T-Shirt", "Sauce Labs Fleece Jacket" , "Sauce Labs Onesie" , "Test.allTheThings() T-Shirt (Red)" to the cart. 
6. Open the cart

### Expected Result
The cart displays 6 products

### Actual Result
Only 3 products are displayed in the cart : "Sauce Labs Bike Light" , "Sauce Labs Backpack" , " Sauce Labs Onesie"
