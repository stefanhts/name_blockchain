# name_blockchain
A small self verifying Name based blockchain written in Go. The application takes displays the blockchain as JSON on GET requests and takes POST request to add new
blocks

## To view the chain in action:
1. git clone this repository
2. install all dependencies
3. cd into go_blockchain
4. go run main.go
5. open localhost:8080 in your browser
6. send POSTs using postman or cURL with the format {"msg": "<name>"}

