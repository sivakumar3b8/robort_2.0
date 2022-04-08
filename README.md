# README
ruby -v 2.6.5
mongoid -v 7.0
	
Rspec Test cases
Order
  is expected to validate that :x_pos looks like an integer greater than or equal to 0 and less than or equal to 5
  is expected to validate that :y_pos looks like an integer greater than or equal to 0 and less than or equal to 5
  is expected to validate that :facing cannot be empty/false

Orders
  POST /api/robot/0/orders
    Should return success rsponse
