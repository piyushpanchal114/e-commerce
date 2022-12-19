
# e-commerce-backend-django
e-commerce backend using Django, DRF, JWT.

## Features
- User can create their accounts in respect to ordering the item.
-	User authentication is done by using JWT. Every registered user will get the access token and refresh token at the time of login.
-	Different permissions are given to the user to perform different tasks. Ex – Only Admin can update the status of order.
-	Every endpoint has secure access according to the type of user.
-	Each endpoint serves the clean JSON data to the client.
-	Any anonymous user can come and view product and add them into cart but only registered user can proceed the order.

## **User End Points Available**

 - `/auth/` - for viewing all endpoints related to authentication.
	 - `/users/` - for registration of user.
	 - `/users/me/` - for viewing current user details.
	-   `/jwt/create/`  - for logging in.
	-   `/jwt/refresh/`  - for getting access token by refresh token.
	-   `/jwt/verify/`  - for verifying user.

 - `/store/` - for veiwing all major endpoints to the client.

	 -	`/collections/` - for getting collections. 
	 -	 `/products/` - for veiwing all products.
	 - `/products/id/` - for getting individual product.
	 - `/products/id/reviews/` - for getting all reviews of a product.
	 - `/products/id/reviews/id/` - for getting a specific review of a product.
	 - `/carts/` - for viewing a cart.
	 - `/orders/` - for getting all orders of a individual.
	- `/orders/id/`- for getting a specific order of a individual.
	 - `/customers/` -  for getting profile of a individual.



