# 388-Design-Project

This Arduino project is a small representation of a system that would monitor the number of occupants in a store and check customers' health before unlocking the door to a store.

1. Ultrasonic Distance Sensors recognize customers approaching the door
2. A temperature sensor "checks the temperature of the customer"
3. If the customer doesn't have a temperature over 100.4 and the occupancy of the store is less than 25 people the door opens and the customer is allowed in
4. When the "inside" Ultrasonic Distance Sensor recognizes a customer approaching the door to leave the door opens
5. LEDs identify the Occupancy level of the store for the customers attempting to go inside
     Red: Maximum Occupancy (25 Customers) || Yellow: Medium Level Occupancy (13-24 Customers) || Green: Low Occupancy (less than/equal to 12 Customers) 

Ultrasonic Distance Sensors: Recognize customers entering or leaving the store
OLED: Displays the number of occupants in the store, the temperature of incoming customers, and the distance from the doors to the customers leaving or approaching
Motor: Represents the unlocking/opening and closing of the store's doors
LEDs: Displays the Occupancy Level of the store
Temperature Sensor: Represents checking the temperature of the incoming customers
