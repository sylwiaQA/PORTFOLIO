# Bug Reports 

![Bug Reports Page Image](images/bugreports/bugreports.jpg)


Test environment: https://academybugs.com/find-bugs/

Below you can find some bug reports which I have encountered during exploratory testing


# BU-1: Functionality to display a specific number of products on the page does not work

| Field                | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **Bug ID**           | BU-1                                                                                             |
| **Title**            | Functionality to display a specific number of products on the page does not work                 |
| **Severity**         | High                                                                                             |
| **Issue type**       | Crash                                                                                            |
| **Description**      | After navigating to the main page and clicking on any filter label to display a certain number of products on the page, the page crashes suddenly. Additionally, the functionality does not work. |
| **Environment**      | - **URL:** [academybugs.com](http://academybugs.com) <br> - **Browser:** [Firefox 127.0.2 (64 bity)] <br> - **Operating System:** [Microsoft Windows 11 Home]|
| **Steps to reproduce** | 1. Open [academybugs.com](http://academybugs.com) <br> 2. Click the "Find Bugs" on the navigation bar <br> 3. Click on the button to show a certain number of results at the top left |
| **Expected result**  | The selected number of results should be displayed according to the clicked buttons.              |
| **Actual result**    | The page freezes when clicking on the number of results. Functionality does not work.             |
| **Attachments**      | [BU-1.mp4](images/bugreports/BU-1.mp4)                                                            |
|                      | ![BU-1.Screenshot](images/bugreports/BU-1.png)                                                    |

# BU-2:  Loader icon is not vertically centered relative to the Label "Add to cart"  

| Field                | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **Bug ID**           | BU-2                                                                                             |
| **Title**            | Loader icon is not vertically centered relative to the Label "Add to cart"                       |
| **Severity**         | Medium                                                                                           |
| **Issue type**       | UI/Visual                                                                                       |
| **Description**      | After clicking the "Add to Cart" button the loader icon briefly appears, it is not vertically centered in relation to the label "Add to cart". |
| **Environment**      | - **URL:** [academybugs.com](http://academybugs.com) <br> - **Browser:** [Firefox 127.0.2 (64 bity)] <br> - **Operating System:** [Microsoft Windows 11 Home] |
| **Steps to reproduce** | 1. Open [academybugs.com](http://academybugs.com). <br> 2. Click the "Find Bugs" link in the navigation bar. <br> 3. Click the "Add to cart" button. |
| **Expected result**  | The loader icon should appear vertically centered in relation to the label "Add to cart".    |
| **Actual result**    | The loader icon is not vertically centered; it appears incorrect with the label.               |
| **Attachments**      |  [BU-2.mp4](images/bugreports/BU-2.mp4)     |

# BU-3: Excessive space before the last letter in "Return to store" button

| Field                | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **Bug ID**           | BU-3                                                                                             |
| **Title**            | Excessive space before the last letter in "Return to store" button                       |
| **Severity**         | Medium                                                                                           |
| **Issue type**       | UI/Visual                                                                                       |
| **Description**      | After removing a product from the cart, the "Return to store" button appears with excessive space before the last letter 'E' |
| **Environment**      | - **URL:** [academybugs.com](http://academybugs.com) <br> - **Browser:** [Firefox 127.0.2 (64 bity)] <br> - **Operating System:** [Microsoft Windows 11 Home] |
| **Precondition**      | User has at last one product in the cart |
| **Steps to reproduce** | 1. Open [academybugs.com](http://academybugs.com). <br> 2. Click the "Find bugs" link on the navigation bar. <br> 3. Click on a product, open it, and click the "Add to cart" button. <br> 4. Remove the product from the cart  |
| **Expected result**  | "Return to Store" button is written corretly.               |
| **Actual result**    | There is excessive space before the last letter 'E' in the "Return to store" button.     |
| **Attachments**      |  [BU-3.mp4](images/bugreports/BU-3.mp4) <br>  ![Screenshot](images/bugreports/BU-3.png)       |

# BU-4: Inability to increase product quantity above 2

| Field                | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **Bug ID**           | BU-4                                                                                             |
| **Title**            | Inability to increase product quantity above 2                                                    |
| **Severity**         | High                                                                                             |
| **Issue type**       | Functionality                                                                                     |
| **Description**      | After adding one or more products to the cart, when navigating to the cart and attempting to set the product quantity to 3 or more, clicking the "update" button results in the quantity resetting to 2. |
| **Environment**      | - **URL:** [academybugs.com](http://academybugs.com) <br> - **Browser:** [Firefox 127.0.2 (64 bity)] <br> - **Operating System:** [Microsoft Windows 11 Home] |
| **Steps to reproduce** | 1. Navigate to [academybugs.com](http://academybugs.com). <br> 2. Click the "Find bugs" link on the navigation bar. <br> 3. Add one or more products to the cart. <br> 4. Click the "View cart" link at the top left of the page. <br> 5. Set the quantity of products to 3 or more. <br> 6. Click the "Update" button below. |
| **Expected result**  | The product quantity should be updated regarding to the entered value after clicking "Update".  |
| **Actual result**    | Upon clicking "Update", the product quantity resets to 2 instead of allowing values above 2.    |
| **Attachments**      | ![Screenshot](images/bugreports/BU-4.png)       |


            
