# User-Service-E-commerce-Microservice
User Service Implementation
These are Common Endpoints for User Service
Method	    Endpoint	                    Description	                          Auth Required
POST	      /api/users/register	          Register a new user	                   No
POST	      /api/users/login	            Authenticate user & return JWT token	 No
POST	      /api/users/logout            	Invalidate token (optional)	           Yes
PUT        	/api/users/{id}	              Update user profile	for future change                   Yes
DELETE    	/api/users/{id}	              Delete a user (admin or self)	          Yes

🔐 Optional Authentication/Token Endpoints
Method	Endpoint	Description
POST	/api/users/refresh-token	Get a new access token using refresh

