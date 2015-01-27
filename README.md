# products

Task:

Write a simple python webservice that returns the objects & manipuates the data found 
here http://www.unisport.dk/api/sample/.

/products/

should return the first 10 objects ordered with the cheapest first.

/products/kids/

should return the products where kids=1 ordered with the cheapest first

/products/?page=2

The products should be paginated where page in the url above should return the next 10 objects

/products/id/

should return the individual product.
