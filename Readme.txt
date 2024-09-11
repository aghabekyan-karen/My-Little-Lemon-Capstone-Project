APIs

GET in http://localhost:8000/api/menu/1
GET in http://localhost:8000/api/menu
POST http://localhost:8000/api/menu/
GET in http://localhost:8000/api/booking/tables
POST http://localhost:8000/api/api-token-auth/

Testing

DJOSER endpoint, for instance, to perform a POST request and register a new user. /auth/users/
To log in and obtain an authentication token. /api-token-auth/
To log in using the DJOSER endpoint. /auth/token/login
Menu items /api/menu/ /api/menu/{menuItemId}
Table reservations /api/booking/tables/ /api/booking/tables/{bookingId}