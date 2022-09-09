Shopping card calculator

You're making a shopping card for a website. You have the following items in your cart:

```js
const cart = [
  { name: "Widget", price: 9.95 },
  { name: "Gadget", price: 22.95 },
  { name: "Doodad", price: 5.95 },
  { name: "Thingamabob", price: 7.95 },
  { name: "Gizmo", price: 12.95 },
  { name: "Doohickey", price: 3.95 },
];
```

Calculate the total price of all items in your cart, but include 22.2% tax and add ability to set discount by promocodes.

One of the promocodes is `FRIDAY_13` which gives 10% discount, the other one is `SALE_2022` that gives 2$ discount if the price of the product is bigger than 10. 

It will look like this:

```js
const totalPrice = calculateTotalPrice(cart, "FRIDAY_13");
```
