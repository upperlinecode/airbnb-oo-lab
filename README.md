# kwk-airbnb-oo-lab

Airbnb is a web application that allows people to rent their own homes or apartments to travelers. It started in San Francisco as an alternative to costly hotels for people traveling to academic conferences. The original web application was built using Ruby! Today, Airbnb is in 191 countries, and has hosted over 160 million guests. Its projected revenue by 2020 is over $3 billion. 

Today, your job is to build Airbnb’s Listing class. A listing object contains the information about a residence available for rental.

1. Start by defining the Listing class.
2. The class should have attributes of host, beds, dates_available, cancellation, guest, reviews, and price. Give each attribute a reader and a writer. 
3. A listing should initialize with a cancellation of “strict”. Write an initalize method that does this.
4. A listing should initialize with with an empty array for the guests attribute. Modify your initialize method to do this. 
5. A listing should initialize with an empty hash for the reviews attribute. Modify your initialize method to do this. 
host, beds, dates_available, and price will need to be passed in when the listing is created. Modify your initialize method to do this. 
6. Create a few new instances of the Listing class, passing in appropriate data types/data structures as arguments. 
7. Write a class method called reserve_and_pay. reserve_and_pay should take two parameters: the name of the guest making the reservation, and the number of nights they will be staying for. It should add the guest to the guests array and  return the total cost of the stay. 
8. Write a class method called leave_review, which takes in two arguments: the guest leaving the review, and the text of the review. The method should add a key-value pair to the reviews hash, with the guest as the key, and the text of the review as the value. 
9. BONUS: Make your reserve_and_pay method take in an array of the dates the guest will be staying. Use that list to update the dates_available array so that the reserved dates are no longer available. 
10. BONUS: Now change your guests attribute to initialize to an empty hash. Instead of simply adding the name of the guest to an array, your reserve_and_pay method should add the guest to the hash as a key, and the array of dates as the associated value. 
11. BONUS: Add any additional methods or attributes you can think of (or modify the ones we have already written) to make this listing as realistic as possible. 
12. BONUS: Build out the Host class in the host.rb file! Make sure to include a create_listing method, which creates a new instance of the Listing class.  
