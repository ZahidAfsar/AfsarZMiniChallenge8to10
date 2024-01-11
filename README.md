// Zahid Afsar
// 1 - 11 - 24
// Mini Challenge 8 - 10
// Design an API based on mini challenges from the Combine:
Also, each one must have their own service file, inside a Service folder
Data Validation is required.
Endpoints:
1. Magic 8 Ball: create a endpoint generates 8 unique responses. One controller
2. Guess It: create 3 endpoints (one controller) that takes an input, then outputs if the number is higher or lower than the number guessed.
Easy Mode 1-10
Medium Mode 1-50
Hard Mode 1-100
3. Restaurant Picker: create 1 endpoint that takes an input and generates a Randomly Generated Restaurant based on the category chosen. 10 Restaurants per category.

// Peer Review by : Kyle Ma 
// Peer Comment : Assignment is complete and code is organized nicely. All the validation is done correctly. I like that there is an error code for GuessIt if the input is out of bounds. The .toLower is is nice touch for the resturant picker as well. 
One thing that i noticed that could be changed is the input for resturant picker, "fast food". The space inbetween makes it strange to input into postman since URL's don't have them. 
