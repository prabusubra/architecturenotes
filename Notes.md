

 client -> API Gateway -> Authorization server(Keycloak) -> Eureka discovery service -> hyptrix config server -> zipkin traces
 
 
1. Product
	id - alphanumeric
	name - string
	image - 
	price - double
	status [available/outofstack]
	ratingids - list
	
2. Rating
	id - 
    rating - [1-5]
	comment - string
	user -
	ratedProduct - product id
	 
3. User
    id - 
	name - 
	image - 
	rating - id 
	
4. Purchase
    id - 
	paymenttype - [Card/Cash/UPI]
	amount - 
	status - [failed/Success/returned/replacement]
	paymentdate - date
	product - 
	
