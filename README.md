# Parking-system-1st-year-project

If we maintain customer data records physically (using pen and paper in particular), it is always a disaster for the parking system. Therefore, via the use of this project, we have created a program in the C language to store and maintain the records of the clients who are parking their cars.
This is how the code works:
Firstly, it records entry or the exit of the customer, then it takes the category of the vehicle such as two wheeler, four wheeler or commercial transport vehicle. Then, it takes sub-category of vehicle such as scooty, car, bike, etc. Further, it takes details from the user like owner name, contact number, vehicle number, etc. Then after all these steps entry receipt is printed for the user with the entry time and all other details on it. Simultaneously, all this data of the customer is stored in a text file. 
The procedure for exit is quite time efficient as it only takes vehicle number from the user and matches it with the data in the text file. It then prints the exit receipt of the vehicle with exit time, user details and the cost of parking printed on it.
Once the receipt is printed, the vehicle’s record is also deleted from the text file so that if the same vehicle enters next time there is no mismatch of data. At the same time, the same data is also added in another text file so that it can be read later if required.
