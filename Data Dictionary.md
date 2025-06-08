The datasets provided contain the following information:

1. **ProductCategory**:

   * **CategoryID**: Unique identifier for product categories.
   * **CategoryName**: Name of the product category (e.g., Blueprints, Drone Kits, Drones, eBooks, Robot Kits).
   * **CategoryAbbreviation**: Abbreviation for the category (e.g., BP for Blueprints, DK for Drone Kits).

2. **Orders**:

   * **OrderID**: Unique identifier for each order.
   * **Date**: Date when the order was placed.
   * **CustomerID**: References the customer placing the order.
   * **ProdNumber**: References the product ordered.
   * **Quantity**: Number of units of the product ordered.

3. **Customers**:

   * **CustomerID**: Unique identifier for each customer.
   * **FirstName** and **LastName**: Customer's name.
   * **CustomerEmail**: Email address of the customer.
   * **CustomerPhone**: Phone number of the customer.
   * **CustomerAddress**, **CustomerCity**, **CustomerState**, **CustomerZip**: Customer's address details.

4. **Products**:

   * **ProdNumber**: Unique identifier for each product.
   * **ProdName**: Name of the product.
   * **Category**: References the product category ID.
   * **Price**: Price of the product.

To create a dashboard that visualizes total sales and other key metrics, we can use **Google BigQuery** to process the data and **Looker Studio** to visualize the results, linking product sales by category, customer data, and order history.

