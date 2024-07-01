# Test Cases

![Test Cases Page Image](images/testcases/testcase.webp)

001. Adding a product to the cart

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 001          | Adding a product to the cart | User is on the homepage of the online store: https://rpstore.pl/ | 1 | Scroll to the tab section and click on the first tab | - | Page loads correctly. It opens a page with a list of products | Pass | - |
|              |                        |              | 2 | Click on the first product from the list | - | Product detail page loads | Pass | - |
|              |                        |              | 3 | Select product properties: color, size and quantity | - | The product properties are correctly marked | Pass | - |
|              |                        |              | 4 | Click the "Add to Cart" button | - | Product is added to the cart and confirmation cart pop-up is displayed | Pass | - |
|              |                        |              | 5 | Verify cart icon updates | - | Cart icon reflects the addition of the product | Pass | - |
|              |                        |              | 6 | Verify product details in the cart | - | Product appears in the cart with correct details (e.g., name, price, quantity) | Pass | - |

002. Changing the quantity of products in the cart

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 002          | Changing the quantity of products in the cart | Open a webpage: https://rpstore.pl/ You have at least one product in the cart | 1 | Go to the cart page | - | Cart page loads correctly Product is visible in the cart | Pass | - |
|              |                        |              | 2 | Change the quantity of the product (e.g., increase from 1 to 2) | - | Quantity input updates correctly | Pass | - |
|              |                        |              | 3 | Verify the total price in the cart  | - | Total price reflects the correct amount based on the updated quantity | Pass | - |
|              |                        |              | 

003. Removing products from the cart


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 003          | Removing products from the cart | Open a webpage: https://rpstore.pl/ You have at least one product in the cart | 1 | Go to the cart page | - | Cart page loads correctly Product is visible in the cart | Pass | - |
|              |                        |              | 2 | Click on the 'usuń' button | - | The product is removed from the cart There is a displayed message: 'twój koszyk jest pusty | Pass | - |

004. Checking links to product categories


| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 004          | Checking links to product categories | Open a webpage: https://rpstore.pl/  | 1 | Select the first  product category from the left and go to it (click on it) | - | The subpage with the correct category is shown | Pass | - |
|              |                        |              | 2 | Please repeat this action for each product category | - | All subpages are displayed with correct category of product | Pass | - |
         
005. Verify correct product search functionality   

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 005          | Verify correct product search functionality | Open a webpage: https://rpstore.pl/  | 1 | Click on the magnifying glass icon on the left side of the webpage| - | The search window is shown | Pass | - |
|              |                        |              | 2 | Enter the input value 'szorty Lana' and click ENTER | 'szorty Lana' | The subpage with selected product is displayed | Pass | - |

006. Checking functionality of "sprawdź" button under 'NOWOŚCI' banner

| Test case ID | Test Case Description | Precondition | Step # | Test Steps Details | Test Data | Expected Results | Status | Comments |
|--------------|------------------------|--------------|--------|--------------------|-----------|------------------|--------|----------|
| 006          | Checking functionality of "sprawdź" button under 'NOWOŚCI' banner | Open a webpage: https://rpstore.pl/  | 1 | Locate the 'NOWOŚCI' banner| - | Banner is visible on the homepage | Pass | - |
|              |                        |              | 2 | Verify the "sprawdź" button under the banner | - | There is   "sprawdź" button on the homepage The button is clickable | Pass | - |
|              |                        |              | 3 | Click on the "sprawdź" button | - |User is redirected to the page with section 'Nowości' | Pass | - |

