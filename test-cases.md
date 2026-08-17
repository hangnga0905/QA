# QA


ID: TC-001      
Title: Login Home page and Checkout successfully                   
Preconditions:
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: standard_user / secret_sauce)
- There is a valid user information (ex: First Name: Nga, Last Name: Nguyen, and Zip/ Postal Code: 70000)
Steps:
1. Open the prepared link above
2. Input the valid username and password
3. Click on 'Login' button
4. Choose any products and click on 'Add to cart' button
5. Click on 'Cart' icon
6. Click on 'Checkout' button
7. Fulfill the form with 'First Name', 'Last Name', and 'Zip/ Postal Code'
8. Click on 'Continue' button
9. Click on 'Finish' button
Expected Result:
- Login successfully by the valid account
- Thank you form appears after submitting the form by the valid data
Priority: High



ID: TC-002     
Title: Login Home page unsuccessfully by the invalid account                
Preconditions: 
- There is a valid link: https://www.saucedemo.com/
- There is an invalid account (ex: standard_user_1 / secret_sauce)
Steps:
1. Open the prepared link above
2. Input the invalid username and password
3. Click on 'Login' button
Expected Result:
- User cannot login by the invalid account and the warning message appears to let the user knows about the non-matching value
Priority: Medium



ID: TC-003    
Title: Login Home page unsuccessfully by the empty              
Preconditions: 
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: standard_user / secret_sauce)
Steps:
1. Open the prepared link above
2. Leave the username and password fields by the empty
3. Click on 'Login' button
4. Leave the username by the empty and fill the password by the valid value
5. Click on 'Login' button
6. Leave the password by the empty and fill the usernme by the valid value
7. Click on 'Login' button
Expected Result:
- At step 3, 5, 7, user cannot login by the empty and the warning message appears to let the user knows about the required field
Priority: Medium


ID: TC-004     
Title: Login Home page unsuccessfully by the valid account which is not able to login                
Preconditions: 
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: locked_out_user / secret_sauce)
Steps:
1. Open the prepared link above
2. Input the valid username and password
3. Click on 'Login' button
Expected Result:
- User cannot login by the valid account and the warning message appears to let the user knows about the locked user
Priority: Medium


ID: TC-005
Title: Re-login Home page successfully
Preconditions: 
- There is a valid link: https://www.saucedemo.com/
- There are some valid accounts (ex: standard_user_1 / secret_sauce and problem_user/ secret_sauce,..)
Steps:
1. Open the prepared link above
2. Input the first valid username and password
3. Click on 'Login' button
4. Click on 'Burger' icon and select 'Logout' option
5. Input the second valid username and password
6. Click on 'Login' button
7. Repeat step 4, 5, 6 with other accounts
Expected Result:
- User can re-login successfully and there is no broken layout
Priority: Medium


ID: TC-006 
Title: Checkout unsucessfully                     
Preconditions:    
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: standard_user / secret_sauce)
- There is a valid user information (ex: First Name: Nga, Last Name: Nguyen, and Zip/ Postal Code: 70000)
Steps:
1. Open the prepared link above
2. Input the valid username and password
3. Click on 'Login' button
4. Choose any products and click on 'Add to cart' button
5. Click on 'Cart' icon
6. Click on 'Checkout' button
7. Click on 'Cancel' button
8. Click on 'Checkout' button and click on 'Continue' button without fulfulling the form
9. Click on 'Checkout' button
10. Fulfill the form with 'First Name', 'Last Name', and 'Zip/ Postal Code'
11. Click on 'Continue' button
12. Click on 'Cancel' button
Expected Result: At step 7, 8, 12, checkout unsuccessfully by going back to Home page and still keep the selected product
Priority: Medium


ID: TC-007
Title: Checkout successfully when user continue shopping                     
Preconditions:    
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: standard_user / secret_sauce)
- There is a valid user information (ex: First Name: Nga, Last Name: Nguyen, and Zip/ Postal Code: 70000)
Steps:
1. Open the prepared link above
2. Input the valid username and password
3. Click on 'Login' button
4. Choose any products and click on 'Add to cart' button
5. Click on 'Cart' icon
6. Click on 'Continue Shopping' button
7. Repeat step 4 with other product(s)
8. Repeat step 5
9. Click on 'Checkout' button
10. Fulfill the form with the valid 'First Name', 'Last Name', and 'Zip/ Postal Code'
11. Click on 'Continue' button
12. Click on 'Finish' button
Expected Result: User checkouts successfully
Priority: Medium



ID: TC-008
Title: Checkout sucessfully when removing some selected products                 
Preconditions:    
- There is a valid link: https://www.saucedemo.com/
- There is a valid account (ex: standard_user / secret_sauce)
- There is a valid user information (ex: First Name: Nga, Last Name: Nguyen, and Zip/ Postal Code: 70000)
Steps:
1. Open the prepared link above
2. Input the valid username and password
3. Click on 'Login' button
4. Choose any products and click on 'Add to cart' button
5. Click on 'Cart' icon
6. Click on 'Checkout' button
7. Click on 'Remove' button to remove some selected product(s)
8. Click on 'Checkout' buton
9. Fulfill the form with 'First Name', 'Last Name', and 'Zip/ Postal Code'
10. Click on 'Continue' button
11. Click on 'Finish' button
Expected Result: User checkouts successfully after removing some products
Priority: Medium


