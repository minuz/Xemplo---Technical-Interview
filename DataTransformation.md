# Exercise: Data Transformation

You have been given an array of objects representing products sold on an e-commerce platform. Your task is to perform various data transformations on this array to derive meaningful information.

## Requirements:

1. Calculate the total value of all products in the array and display it.
2. Find the product with the highest price and display its details.
3. Filter the products to only include those with a quantity greater than 5 and display the filtered products.
4. Create a new array that includes the name and price of each product, sorted in descending order based on price.
5. Group the products by category and display them in a hierarchical structure.

```
Total value of all products: $2539.94

Product with the highest price:
- Name: iPhone X
- Price: $999.99
- Category: Electronics
- Quantity: 10

Filtered products (quantity > 5):
- Name: iPhone X
  Price: $999.99
  Category: Electronics
  Quantity: 10
- Name: Samsung Galaxy S21
  Price: $899.99
  Category: Electronics
  Quantity: 7
- Name: Nike Air Max
  Price: $129.99
  Category: Shoes
  Quantity: 15

Products sorted by price (descending):
- Name: iPhone X
  Price: $999.99
- Name: Samsung Galaxy S21
  Price: $899.99
- Name: Sony PlayStation 5
  Price: $499.99
- Name: Nike Air Max
  Price: $129.99

Products grouped by category:
- Electronics:
  - Name: iPhone X
    Price: $999.99
    Quantity: 10
  - Name: Samsung Galaxy S21
    Price: $899.99
    Quantity: 7
- Shoes:
  - Name: Nike Air Max
    Price: $129.99
    Quantity: 15
- Gaming:
  - Name: Sony PlayStation 5
    Price: $499.99
    Quantity: 3
```

Please implement the necessary code in TypeScript/JavaScript to achieve the above requirements. Feel free to ask any questions if you need further clarification. Good luck!
