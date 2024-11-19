# product-prices-and-ratings
# How It Works
Input Form for Product Data:

Users input product name, price, and rating.
Data validation ensures price and rating are numbers, with ratings limited to 1-5.
Dynamic Graphs:

Two graphs (price-graph and rating-graph) are created.
Bars are dynamically generated with widths proportional to price or rating values.
Sorting:

Sorting by price or rating reorders the products array and regenerates the graphs.
Real-Time Updates:

Adding a product immediately updates both graphs without a page reload.


# Example Workflow
Enter "Product A", 30, and 4. Click Add Product.
Enter "Product B", 50, and 5. Click Add Product.
Click Sort by Price to reorder the price graph.
Click Sort by Rating to reorder the rating graph.
Add new data, and the graphs automatically reflect the updated dataset.
This implementation provides a clean, interactive way to visualize and manage product data dynamically.
