### Procedure

Consider a use case of the car rental application as follows:
* Use Case Name: Release a Vehicle (to a customer)
* Description: A customer arrives to acquire the vehicle and depart for desired destination. The vehicle reservation contract is signed and the vehicle is released to the customer.
* Actors: Front-Desk Clerk, Customer
* Basic Flow ("Sunny Day Scenario"): 
    1.   A customer comes to the office to acquire a vehicle.
    2.    The clerk locates the vehicle reservation contract by means of the reservation number and/or customer name. [Exception: Required vehicle type is not available due to late arrivals.]
    3.    The customer signs the contract and the clerk gives the keys to the vehicle.
    4.    The clerk then marks the contract active by entering the vehicle release date (today's date) onto the vehicle reservation contract. The use case terminates at this point.
* Exceptions ("Rainy Day Scenario"):
 
    1. Required vehicle type is not available due to late arrivals:
    2. Raised when the reserved vehicle is not available due to late returns. The customer is informed of the situation and told about the other vehicle types that are available. The customer is offered an incentive to accept another vehicle type. If the customer is not satisfied, the reservation is cancelled without penalty charges. The customer either accepts another vehicle type or cancels the reservation.
* Postconditions: The customer departs with the vehicle and the reservation contract is marked active, or the reservation is cancelled.
* Stakeholder: Reservation department

Experiment 1 recap: Use case was completed. Noun phrases and conceptual classes were identified, and the domain object model was constructed.

Now, the steps to complete the time sequence model is as follows:

Step 1: Identify the verb phrases from each sentence in basic flow.

Step 2: Fine tune the verb phrases to convert them to operations performed by the objects.

Step 3: Complete the method invocation/message passing between the objects to implement the basic flow of the use case. 

Output: Time sequence model is constructed for the given use case.


Students examine requirements from the perspective of the classes and objects found in the vocabulary of the problem domain. 

Case study :  Consider a use case of the car rental application as follows,

* **Use Case Name** : Release a Vehicle (to a customer) 
* **Description** : A customer arrives to acquire the vehicle and depart for desired destination. The  vehicle     reservation contract is signed and the vehicle is released to the customer.
* **Actors** : Front-Desk Clerk, Customer.

Student could draw a sequence diagram based on the architecture to show the interaction between the objects.  