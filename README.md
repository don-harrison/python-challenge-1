### Crazy Cravings Catering Order System

Welcome to **Crazy Cravings Catering**! This is a Python-based script for managing customer orders from a diverse menu, complete with snacks, meals, drinks, and desserts.

---

#### **Features**
- Interactive menu selection by category.
- Dynamic pricing and multi-level menu handling.
- Quantity input with default fallback.
- Comprehensive order summary and receipt generation.

---

#### **Menu Categories**
1. **Snacks**
   - Cookie: $0.99
   - Banana: $0.69
   - Apple: $0.49
   - Granola bar: $1.99

2. **Meals**
   - Burrito: $4.49
   - Teriyaki Chicken: $9.99
   - Sushi: $7.49
   - Pad Thai: $6.99
   - **Pizza**
     - Cheese: $8.99
     - Pepperoni: $10.99
     - Vegetarian: $9.99
   - **Burger**
     - Chicken: $7.49
     - Beef: $8.49

3. **Drinks**
   - **Soda**
     - Small: $1.99
     - Medium: $2.49
     - Large: $2.99
   - **Tea**
     - Green: $2.49
     - Thai Iced: $3.99
     - Irish Breakfast: $2.49
   - **Coffee**
     - Espresso: $2.99
     - Flat White: $2.99
     - Iced: $3.49

4. **Desserts**
   - Chocolate Lava Cake: $10.99
   - **Cheesecake**
     - New York: $4.99
     - Strawberry: $6.49
   - Australian Pavlova: $9.99
   - Rice Pudding: $4.99
   - Fried Banana: $4.49

---

#### **Usage Instructions**
1. **Launch the script**
   - Run the script in a Python environment (Python 3.10+ is required).

2. **Select a Menu Category**
   - Choose a category (e.g., Snacks, Meals, Drinks, or Desserts).

3. **Pick an Item**
   - Select an item from the displayed menu.

4. **Set Quantity**
   - Input the quantity of the selected item (default is 1 if invalid).

5. **Review Your Order**
   - Continue adding items or finalize your order.

6. **View Receipt**
   - A detailed receipt will be displayed, showing all items, their prices, quantities, and the total amount.

---

#### **Code Highlights**
- **Order Validation**: Ensures correct input types and handles errors gracefully.
- **Dynamic Pricing**: Supports nested menu structures with different price tiers.
- **Readable Formatting**: Neatly formatted receipt for user clarity.
- **Scalable**: Designed to easily accommodate additional menu items or categories.

---

#### **Prerequisites**
- Python 3.10+

---

#### **Example Output**
```
Welcome to Crazy Cravings Catering.
From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Desserts
...
Item name                 | Price  | Quantity
--------------------------|--------|----------
Pizza - Pepperoni         | $10.99 | 2
Soda - Large              | $2.99  | 1
...
Total                     | $24.97
```

---