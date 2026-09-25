# ShopEasy — User Flow

## 1. Objective

Define the main journey a user follows while interacting with ShopEasy.

The flow focuses on the MVP shopping experience: discovering products and adding them to the cart.

---

## 2. Main User Flow

```text
User
  ↓
Open ShopEasy
  ↓
View Homepage
  ↓
Browse Products
  ↓
View Product Name, Image and Price
  ↓
Click "Add to Cart"
  ↓
Cart Count Increases
  ↓
Cart Information Updates
```

---

## 3. Detailed Flow

### Step 1 — Open Website

The user opens the ShopEasy website.

### Step 2 — View Homepage

The user sees:

* ShopEasy branding
* Shopping cart count
* Product introduction
* Product catalog

### Step 3 — Browse Products

The user can view:

* Wireless Headphones
* Smart Watch
* Laptop

Each product includes:

* Product image
* Product name
* Price
* Add to Cart button

### Step 4 — Add Product

The user clicks **Add to Cart**.

The system:

1. Adds the product to the cart.
2. Updates the cart count.
3. Updates the cart message.

### Step 5 — Continue Shopping

The user can continue browsing and add additional products.

---

## 4. User Flow Diagram

```text
┌──────────────┐
│     User     │
└──────┬───────┘
       ↓
┌──────────────┐
│ Open Website │
└──────┬───────┘
       ↓
┌──────────────────┐
│ Browse Products  │
└──────┬───────────┘
       ↓
┌──────────────────┐
│ View Product     │
│ Image + Price    │
└──────┬───────────┘
       ↓
┌──────────────────┐
│  Add to Cart     │
└──────┬───────────┘
       ↓
┌──────────────────┐
│ Update Cart      │
│ Count            │
└──────┬───────────┘
       ↓
┌──────────────────┐
│ Continue Shopping│
└──────────────────┘
```

---

## 5. Alternative Flow

If the user does not want a product:

```text
Browse Product
      ↓
Does not Add to Cart
      ↓
Continue Browsing
```

---

## 6. Future User Flow

Future versions can extend the flow:

```text
Browse Products
      ↓
Product Details
      ↓
Add to Cart
      ↓
View Cart
      ↓
Login / Sign Up
      ↓
Checkout
      ↓
Payment
      ↓
Order Confirmation
      ↓
Order Tracking
```

---

## 7. PM Considerations

The PM should monitor where users may face friction in the journey.

Important areas include:

* Product discovery
* Product information
* Add-to-cart interaction
* Cart visibility
* Checkout experience
* Payment experience

Future improvements should be based on user feedback and product usage data.
