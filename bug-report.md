Title: Product list filter, product images, product cart, and product checkout are incorrect
Environment: 
- Desktop | Chrome version 151.0
- URL: https://www.saucedemo.com/
- User: problem_user / secret_sauce
- User information: Nga, Nguyen, 70000
Preconditions: 
- Login successfully by the valid link and account above
Steps to Reproduce: 
1. Observe the product images after login successfully
2. Select each option in the dropdown list and observe the result
3. Click on all the 'Add to cart' buttons and observe the result
4. Click on 'Cart' button and try to change the quantity of the product
5. Click on 'Checkout' button and fulfill the form by the valid values and observe the result
Expected Result: 
- Product images should be different and related to the products at step 1
- Product list must be sorted by the selected filter option at step 2
- All the buttons must be changed to 'Remove' button at step 3
- There is able to change the quantity of the product at step 4
- The form must be fulfilled successfully at step 5
Actual Result: 
- All the product images are the same at step 1
- The default dropdown list option is still selected and Product list is not changed at step 2
- The button name of the products (Sauce Labs Bolt T-Shirt, Sauce Labs Fleece Jacket, Test.allTheThings() T-Shirt (Red)) is not changed to 'Remove' button at step 3 
- There is not able to change the quantity of the product at step 4
- 'First Name' value is changed when trying to input the value at 'Last Name' field at step 5
Severity: Critical
Priority: 1
Attachments: https://drive.google.com/file/d/1yvfTZ159YJB-triJFHQGAimFA64Z7r2v/view?usp=sharing



Title: The selected products of the previous user appear when login by another user
Environment: 
- Desktop | Chrome version 151.0
- URL: https://www.saucedemo.com/
- User: performance_glitch_user / secret_sauce
- User information: Nga, Nguyen, 70000
Preconditions: 
- Login successfully by the valid link and account above
Steps to Reproduce: 
1. Observe the product images after login successfully
2. Click on 'Cart' button and observe the result
Expected Result: At step 1 and 2, the product list must be empty after login by another user
Actual Result:  At step 1 and 2, the product list of other user appears in the new login user
Severity: High
Priority: 2
Attachments: https://drive.google.com/file/d/1cyUEvg8Yzdg2lvrsq6lD_u28tz4jGmqd/view?usp=sharing
