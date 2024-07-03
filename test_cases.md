# Test Cases

![Test Cases Page Image](images/testcases/testcase.webp)


All test cases below are written based on my own experience according to the exploratory testing methodology

Test environment: https://rpstore.pl/

TC_001. Adding a product to the cart

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_001          | Adding a product to the cart | User is on the homepage of the online store: https://rpstore.pl/ | 1 | Scroll to the tab section and click on the first tab | - | Page loads correctly. It opens a page with a list of products | Pass | - |
|              |                        |              | 2 | Click on the first product from the list | - | Product detail page loads | Pass | - |
|              |                        |              | 3 | Select product properties: color, size and quantity | - | The product properties are correctly marked | Pass | - |
|              |                        |              | 4 | Click the "Add to Cart" button | - | Product is added to the cart and confirmation cart pop-up is displayed | Pass | - |
|              |                        |              | 5 | Verify cart icon updates | - | Cart icon reflects the addition of the product | Pass | - |
|              |                        |              | 6 | Verify product details in the cart | - | Product appears in the cart with correct details (e.g., name, price, quantity) | Pass | - |

TC_002. Changing the quantity of products in the cart

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_002          | Changing the quantity of products in the cart | Open a webpage: https://rpstore.pl/ You have at least one product in the cart | 1 | Go to the cart page | - | Cart page loads correctly Product is visible in the cart | Pass | - |
|              |                        |              | 2 | Change the quantity of the product (e.g., increase from 1 to 2) | - | Quantity input updates correctly | Pass | - |
|              |                        |              | 3 | Verify the total price in the cart  | - | Total price reflects the correct amount based on the updated quantity | Pass | - |
|              |                        |              | 

TC_003. Removing products from the cart


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_003          | Removing products from the cart | Open a webpage: https://rpstore.pl/ You have at least one product in the cart | 1 | Go to the cart page | - | Cart page loads correctly Product is visible in the cart | Pass | - |
|              |                        |              | 2 | Click on the 'usuń' button | - | The product is removed from the cart There is a displayed message: 'twój koszyk jest pusty | Pass | - |

TC_004. Checking links to product categories


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_004          | Checking links to product categories | Open a webpage: https://rpstore.pl/  | 1 | Select the first  product category from the left and go to it (click on it) | - | The subpage with the correct category is shown | Pass | - |
|              |                        |              | 2 | Please repeat this action for each product category | - | All subpages are displayed with correct category of product | Pass | - |
         
TC_005 Verify correct product search functionality   

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_005          | Verify correct product search functionality | Open a webpage: https://rpstore.pl/  | 1 | Click on the magnifying glass icon on the left side of the webpage| - | The search window is shown | Pass | - |
|              |                        |              | 2 | Enter the input value 'szorty Lana' and click ENTER | 'szorty Lana' | The subpage with selected product is displayed | Pass | - |

TC_006. Verify incorrect product search functionality

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_006          | Verify incorrect product search functionality | Open a webpage: https://rpstore.pl/  | 1 | Click on the magnifying glass icon on the left side of the webpage| - | The search window is shown | Pass | - |
|              |                        |              | 2 | Enter the input value and click ENTER | 'gazeta' | The subpage with selected product is not displayed   There is a displayed message 'Nie znaleziono wyników' | Pass | - |

TC_007. Checking functionality of "sprawdź" button under 'NOWOŚCI' banner

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_007          | Checking functionality of "sprawdź" button under 'NOWOŚCI' banner | Open a webpage: https://rpstore.pl/  | 1 | Locate the 'NOWOŚCI' banner| - | Banner is visible on the homepage | Pass | - |
|              |                        |              | 2 | Verify the "sprawdź" button under the banner | - | There is   "sprawdź" button on the homepage The button is clickable | Pass | - |
|              |                        |              | 3 | Click on the "sprawdź" button | - |User is redirected to the page with section 'Nowości' | Pass | - |

TC_008. Verify a function that calculates total price after applying a discount 


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_008          | Verify a function that calculates total price after applying a discount |The webpage is open: https://rpstore.pl/  User has products in the cart and valid discount| 1 | Go to the cart page | - | Cart page loads correctly.  | Pass | - |
|              |                        |              | 2 | Verify the initail total price of products in the cart  | - | The initial total price of products is displayed correctly | Pass | - |
|              |                        |              | 3 | Apply a discount code  | discount code: 'DISCOUNT10' | Discount code is acepted and a message confirming the discount is displyed | Pass | - |
|              |                        |              | 4 | Verify the total price of products after aplaying the discount | - | PTotal price is recalculated correctly considering the discount | Pass | - |
|              |                        |              | 5 | Verify the discount amount is displayed separetly | - | Discount amount is shown as a separate line item  | Pass | - |
|              |                        |              | 6 | Verify the final total price including the discount and any applicable taxes/shipping | - | Final total price is accurate, reflecting the discount and any additional charges | Pass | - |

TC_009. Verify if the order process is correct (without logged in)

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_009          |  |The webpage is open: https://rpstore.pl/  User has at least one product in the cart and does not have to be logged in| 1 | Go to the cart page | - | Cart page loads correctly  | Pass | - |
|              |                        |              | 2 | Verify the products and quantities in the cart   | - | Products and quantities match the user's selection   | Pass | - |
|              |                        |               | 3 | Click the 'Przejdź dalej' button | - | User is redirected to the checkout page | Pass | - |
|              |                        |               | 4 |Fill in the contact fields and shipping information (name, address, etc.)  | email: joanna.kowalska@gmail.com, name: Joanna, surname: Kowalska, address: ul. Brzozowa 40, 00-000 Warszawa, Poland, telefon number: 789654123| Shipping information is entered correctly | Pass | - | 
|              |                        |               | 5 | Click the button 'Przejdź do wysyłki' | - | You are redirected to the shipping method page  | Pass | - |
|              |                        |               | 6 | Select the shipping method and click 'Przejdź do płatności' button   | shipping method: kurier DHL | You are redirected to the payment page   | Pass | - |
|              |                        |                | 7 |Check the option 'Taki sam jak adres wysyłki' as billing address, mark field 'Akceptuję regulamin i politykę prywatności' and click the button 'Zamawiam i płacę'  |- |You are redirected to the payment method page  | Pass | - | 
|              |                        |               | 8 | Select payment method and click button 'Płacę'| payment method: BLIK | You are redirected to the payment page | Pass | - |
|              |                        |               | 9 | Enter BLIK code and confirm payment through the clicking on the 'Dalej button'  | BLIK code: 000 |Payment information is entered correctly, you are redirected to the summary order page| Pass | - |
|              |                        |               | 10 | Review the order summary and verify the order confirmation email  | -  |The order summary is displayed and the confirmation email is sent The order process is successfully completed | Pass | - |

TC_010. Creating a new user account

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_010          | Creating a new user account |The webpage is open: https://rpstore.pl/  | 1 |Click on the 'log in' icon in the upper right corner | - |You are redirected to the login page   | Pass | - |
|              |                        |              | 2 |Click on the hyperlink 'Utwórz konto'   | - | You are redirected to the registration page  | Pass | - |
|              |                        |               | 3 |Complete all required fields (input values) and markt option 'Akceptuję regulamin i politykę prywatności'  | imię: Jan, nazwisko: Kowalski, email: kowalski.jan@gmail.com, hasło: 12#345.89@ |You are redirected to the homepage, you are logged in correctly.   | Pass | - |

TC_011. Logging in ( valid credentials) and logging out


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_011          |Logging in and logging out  |The webpage is open: https://rpstore.pl/  | 1 |Click on the 'login' icon in the upper right corner  | - | Login page is displayed  | Pass | - |
|              |                        |              | 2 |Enter valid username and password   | email:kowalski.jan@gmail.com, hasło:  12#345.89@   | Fields are accepted  | Pass | - |
|              |                        |               | 3 |Click on the 'login' button  | - | User is logged in and redirected to the page with order history. Button 'Wyloguj' is displayed  | Pass | - |
|              |                        |               | 4 |Click on the 'logout' hyperlink| - | Pass | - | User is logged out and redirected to the homepage
|              |                        |               | 5 |Verify "Login" button is visible again  | - |'Login' button is displayed   | Pass | - |

TC_012. Logging in with invalid credentials

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_012          | Logging in with invalid credentials |The webpage is open: https://rpstore.pl/  | 1 |Click on the 'login' icon in the upper right corner  | - | Login page is displayed  | Pass | - |
|              |                        |              | 2 |Enter invalid email or password   | email: invalid@gmail.com, hasło: 12345 |  Fields accept input | Pass | - |
|              |                        |               | 3 |Click on the 'Zaloguj się" button  | - | You are remain on the login page. Login incorrect | Pass | - |
|              |                        |               | 4 |Verify error message is displayed|-|Is showned message: 'Nieprawidłowy email lub hasło'   | Pass | - |
|              |                        |               | 5 |Verify login fields are not cleared  | - | Email and password fields still contain input  | Pass | - |

TC_013. Password reminder functionality

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_013          | Password reminder functionality |The webpage is open: https://rpstore.pl/ User is on the login page, User must have an existing account with a valid email address | 1 |Navigate to the login page|-|Login page is displayed  | Pass | - |
|              |                        |              | 2 |Click on the 'Nie pamiętasz hasła?' link |-|You are redirected to the password reminder page| Pass | - |
|              |                        |               | 3 |Enter a registered email address in the email input field  | email:kowalski.jan@gmail.com | Email input field accepts the email | Pass | - |
|              |                        |               | 4 |Click on the 'Odzyskaj' button|-| You are redirected to recover password page with message:'Na Twój adres został wysłany e-mail z instrukcjami dotyczącymi odzyskania hasła'.   | Pass | - |
|              |                        |               | 5 |Verify the inbox of the entered email address  | - |An email with a password reset link is sent to the provided email address   | Pass | - |
|              |                        |               | 6 |Open the email received and click on the password reset link|-|You are redirected to a password reset page   | Pass | - |
|              |                        |               |7 |Enter a new password in the provided fields and click on the 'Zresetuj' button | - |You are successfully log in with the new password and redirected to the order history page   | Pass | - |

TC_014.  Newsletter subscription functionality

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_014          | Newsletter subscription functionality |The webpage is open: https://rpstore.pl/ User must have an existing account with a valid email address | 1 |Scroll to the newsletter subscription section at the bottom of the homepage and click on 'Newsletter' field|-|Is displayed a popup you can entry needed data  | Pass | - |
|              |                        |              | 2 |Entry needed values in the input fields  | name: Jan, email: kowalski.jan@gmail.com |Fields accept the input data   | Pass | - |
|              |                        |               | 3 |Click on the 'Zapisz się' button  | - | Is displayed a message 'Udało się' | Pass | - |
|              |                        |               | 4 |Check the inbox of the entered email address | - |An email confirming your subscription has been sent| Pass | - | 
|              |                        |               | 5 |Click the confirmation link in the email.  | - |You are successfully subscribed to the newsletter   | Pass | - |
|              |                        |               | 6 |    |- || Pass | - |

TC_015. Verify if the order process is correct (for logged in user)

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| TC_015          |  |The webpage is open: https://rpstore.pl/  User has at least one product in the cart and  is logged in| 1 | Log in with input data and go to the cart page |login data:  email: kowalski.jan@gmail.com, hasło: 12#345.89@, product: 'szorty Lana'  | You are logged in successfully. Cart page loads correctly.| Pass | - |
|              |                        |              | 2 | Verify the products and quantities in the cart   | - | Products and quantities match the user's selection   | Pass | - |
|              |                        |               | 3 | Click the 'Przejdź dalej' button | - | User is redirected to the checkout page | Pass | - |
|              |                        |               | 4 |Fill in the contact field and shipping information (name, address, etc.)  | email: joanna.kowalska@gmail.com, name: Joanna, surname: Kowalska, address: ul. Brzozowa 40, 00-000 Warszawa, Poland, telefon number: 789654123| Shipping information is entered correctly | Pass | - | 
|              |                        |               | 5 | Click the button 'Przejdź do wysyłki' | - | You are redirected to the shipping method page  | Pass | - |
|              |                        |               | 6 | Select the shipping method and click 'Przejdź do płatności' button   | shipping method: kurier DHL | You are redirected to the payment page   | Pass | - |
|              |                        |                | 7 |Check the option 'Taki sam jak adres wysyłki' as billing address, check field 'Akceptuję regulamin i politykę prywatności' and click the button 'Zamawiam i płacę'  |- |You are redirected to the payment method page  | Pass | - | 
|              |                        |               | 8 | Select payment method and click button 'Płacę'| payment method: BLIK | You are redirected to the payment page | Pass | - |
|              |                        |               | 9 | Enter BLIK code and confirm payment through the clicking on the 'Dalej button'  | BLIK code: 0000  |Payment information is entered correctly, you are redirected to the summary order page| Pass | - |
|              |                        |               | 10 | Review the order summary and verify the order confirmation email  | -  |The order summary is displayed and the confirmation email is sent The order process is successfully completed| Pass | - |
