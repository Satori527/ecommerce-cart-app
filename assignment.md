# Frontend Developer Hiring Task

**Project Overview**

Build an e-commerce shopping cart application using ReactJS/NextJS or Angular. The application will feature a product listing page showcasing various products with details and an "Add to Cart" functionality. Additionally, a dedicated cart page will allow users to manage items, including quantity adjustments, removal, and total price calculations with potential discounts.

**Technical Specifications:**

- **Frontend Framework:** ReactJS or Angular
- **Styling:** TailwindCSS
- **Data Source:**
    - Option 1: Create a local JSON file containing product data (product name, image, price, description, etc.)
    - Option 2: Utilize an open-source API to fetch product data dynamically

---

**Detailed Features:**

**Product Listing Page:**

- Display at least 6-10 products using a grid layout
- Each product card should include:
    - Product image
    - Product name
    - Product price (formatted for currency)
    - "Add to Cart" button

**Add to Cart Functionality:**

- Clicking the "Add to Cart" button on a product should:
    - Add the chosen product to a user's virtual shopping cart.
    - Update the cart icon or a dedicated counter to reflect the number of added items (optional).
    - Provide visual feedback (e.g., animation) confirming the item's addition.

**Cart Page:**

- Display a dedicated cart page where users can manage their selected products.
- The cart page should include:
    - A list of all added products, displaying:
        - Product image
        - Product name
        - Product price
        - Quantity selector (up/down buttons or input field) to adjust the amount of each item.
        - "Remove Item" button to delete a specific product from the cart.
    - Cart Summary Section:
        - Subtotal: Dynamically calculate the total cost of all items in the cart, considering quantity and price.
        - Discounts (Optional):
            - Implement a flexible discount system:
                - Fixed amount (e.g., "$10 off")
                - Percentage-based (e.g., "10% off")
        - Final Price: Display the total amount due, factoring in any applied discounts.
    - Checkout button (optional): This can redirect to a simulated checkout page or provide a message indicating successful cart addition.

---

**Evaluation Criteria:**

- **Code Logic and Cleanliness:**
    - Well-structured, readable, and maintainable code with proper indentation and comments.
    - Efficient use of **state management** to keep track of products and cart items.
- **Design Symmetry:**
    - Consistent layout and user interface throughout the application.
    - **Responsive design** to adjust for different screen sizes.
- **Reusable Components:**
    - Create reusable components for product cards, cart items, and other common UI elements.
- **Completeness of Features:**
    - Implement all listed features with proper functionality.

---

**Go above and beyond (optional):**

Note: This will not be the primary point of evaluation, but in case of a tie, this will be the deciding factor.

- Consider implementing error handling for scenarios like invalid quantity input or discount codes.
- Explore user authentication for persistent cart storage across sessions (optional).
- Build the backend in any language of your choice

---

**Submission Guidelines**

•	Share a link to the public repository containing your project.

•	Ensure that all instructions to set up and run the project are clear.

•	If deployed, provide the live API endpoint(s).

•	Include any additional notes or explanations as needed.