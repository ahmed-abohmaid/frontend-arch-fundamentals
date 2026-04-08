# Domain Model

## Entities

- Customer
- Restaurant
- Restaurant category
- Menu
- Order
- Driver
- Reviews

---

## Attributes

### Customer

- id - name - email - orders
- Create orders
- Track orders status
- Rate restaurant and food items

### Restaurant

- id - name - ratings (reviews) - restaurant categories - food item - owner - employs
- Update menu (food categories & food items)
- Update order status

### Restaurant category

- id - name - type

### Food item

- id - name - restaurant category - price - rating (review)

### Menu

- id - restaurant categories
- create and update menu by restaurant owner or employees

### Order

- id - restaurant - food items - costumer - price
- update status
- create order
- cancel order

### Driver

- id - name - etc.
- Collect orders from restaurants
- Deliver to customers

### Reviews

- id - customer - ratings
- create reviews by customer
- delete reviews by customer
- approve reviews by restaurant

---

![domain-modelling-01.png](images\domain-modelling-01.png)
