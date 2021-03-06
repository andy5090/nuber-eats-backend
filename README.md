# Nuber Eats

The Backend of Nuber Eats Clone

## User Model:

- id
- createdAt
- updatedAt

- email
- password
- role(client|owner|delivery)

## User CRUD:

- Create Account
- Log In
- See Profile
- Edit Profile
- Verify Email

## Restaurant CRUD:

- See Categories
- See Restaurants by Category (pagination)
- See Restaurants (pagination)
- See Restaurant
- Search Restaurant

## Dish CRUD:

- Create Dish
- Edit Dish
- Delete Dish

## Order CRUD:

- Orders CRUD
- Orders Subscription:

  - Pending Orders (Owner) (s: newOrder) (t: createOrder)
  - Pending Pickup Order (Delivery) (s: orderUpdate) (t: editOrder(orderUpdate))
  - Order Status (Customer, Delivery, Owner) (s: orderUpdate) (t: editOrder(orderUpdate))

- Add Driver to Order

- Payments (CRON)
