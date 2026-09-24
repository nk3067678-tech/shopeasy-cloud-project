# ShopEasy — User Flow

## 1. Objective

Define the basic journey a customer follows while using ShopEasy.

The goal is to make the shopping experience simple and easy to understand.

---

## 2. Main User Journey

```text
Customer
   ↓
Open ShopEasy
   ↓
View Products
   ↓
Select Product
   ↓
Add to Cart
   ↓
View Cart
   ↓
Checkout
   ↓
Order Confirmation
```

---

## 3. Step-by-Step Flow

### Step 1 — Open Website

The customer opens the ShopEasy website.

**User Goal:**
Access the shopping experience.

---

### Step 2 — Browse Products

The customer views the available products and their prices.

**User Goal:**
Find a product they are interested in.

---

### Step 3 — Select Product

The customer selects a product to learn more about it.

**User Goal:**
Understand the product before adding it to the cart.

---

### Step 4 — Add to Cart

The customer clicks **Add to Cart**.

The selected product is added to the shopping cart.

**User Goal:**
Save the product for purchase.

---

### Step 5 — View Cart

The customer opens the cart and reviews selected products.

**User Goal:**
Check selected products and quantities.

---

### Step 6 — Checkout

The customer proceeds to checkout.

Future versions can include:

* Delivery information
* Payment method
* Order summary

**User Goal:**
Complete the purchase.

---

### Step 7 — Order Confirmation

After a successful purchase, the customer receives an order confirmation.

**User Goal:**
Know that the order was successfully placed.

---

## 4. Current MVP Flow

The current working version supports:

```text
Open Website
     ↓
View Products
     ↓
Add to Cart
     ↓
View Cart
```

Checkout and order confirmation are planned for future versions.

---

## 5. Error Scenarios

### Products Cannot Load

If the product data cannot be loaded, the website should show an appropriate error message.

### Add to Cart Failure

If a product cannot be added to the cart, the user should receive clear feedback.

### Checkout Failure

In future versions, if checkout fails, the user should be informed and given an option to retry.

---

## 6. PM Considerations

The Product Manager should review the user flow to ensure:

* Each step has a clear user goal
* Users understand what to do next
* Unnecessary steps are minimized
* Errors provide useful feedback
* The flow supports the product goal
* Future features can be added without making the experience confusing

---

## 7. Future Improvements

The user flow can later be expanded with:

* User Login
* Product Search
* Product Categories
* Product Details
* Cart Quantity Management
* Checkout
* Pay
