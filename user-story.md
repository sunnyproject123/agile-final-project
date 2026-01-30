Product Catalog – User Stories

1. Create Product
As a catalog administrator, 
I need the ability to create a product in the catalog, 
so that new products can be made available for sale.

Acceptance Criteria
Given the catalog administrator is authenticated and authorized
When the administrator submits a request with all required product fields
Then a new product is created in the catalog
And the system returns a success response with the product ID

2. Retrieve Product
As a customer or system user, 
I need the ability to retrieve a product from the catalog, 
so that I can view product details.
Acceptance Criteria
Given a product exists in the catalog
When a customer or system user requests the product by its unique identifier
Then the system returns the product details
And the response contains accurate and complete product information

3. Update Product
As a catalog administrator, 
I need the ability to update a product in the catalog, 
so that product information stays accurate and up to date.
And the catalog administrator is authenticated and authorized
Acceptance Criteria
When the administrator submits valid updated product information
Then the product details are updated successfully
And the system returns a confirmation of the update

4. Delete Product
As a catalog administrator, 
I need the ability to delete a product from the catalog, 
so that obsolete or discontinued products are removed.
Acceptance Criteria
Given a product exists in the catalog
And the catalog administrator is authenticated and authorized

Acceptance Criteria
When the administrator submits a delete request for the product
Then the product is deleted successfully
And the system returns a confirmation of deletion

5.Like Product
As a customer, 
I need the ability to like a product in the catalog, 
so that I can express interest and influence product popularity.

6. Dislike Product
As a customer, 
I need the ability to dislike a product in the catalog, 
so that I can provide negative feedback on products.

7. List All Products
As a customer or system user, 
I need the ability to list all products in the catalog, 
so that I can browse the available products.

8. Query Subset of Products
As a customer or system user, 
I need the ability to query a subset of products in the catalog, 
so that I can filter products based on specific criteria (e.g., category, price, popularity).

9.Cloud Hosting
As a system owner, 
I need the product catalog to be hosted in the cloud, 
so that it is scalable, reliable, and accessible.
Acceptance Criteria
Given a cloud environment is provisioned for the product catalog service
When the product catalog application is deployed
Then the service is running in the cloud
And it is accessible via a public or internal endpoint as required

10. Automated Deployment
As a DevOps engineer, 
I need automated deployment of new changes to the cloud, 
so that updates can be released quickly, consistently, and with minimal manual effort.
