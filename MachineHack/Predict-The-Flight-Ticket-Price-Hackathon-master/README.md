# Predict-The-Flight-Ticket-Price-Hackathon

# Problem Statement

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. Huh! Here we take on the challenge! As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.Size of training set: 10683 records Size of test set: 2671 records 

# Features: 
Airline: The name of the airline.

Date_of_Journey: The date of the journey.

Source: The source from which the service begins. 

Destination: The destination where the service ends. 

Route: The route taken by the flight to reach the destination. 

Dep_Time: The time when the journey starts from the source. 

Arrival_Time: Time of arrival at the destination. 

Duration: Total duration of the flight. 

Total_Stops: Total stops between the source and destination. 

Additional_Info: Additional information about the flight.

Price: The price of the ticket


# Link to the Competition: https://www.machinehack.com/hackathons/predict_the_flight_ticket_price_hackathon


# Leaderboard Score  

PUBLIC LB Score: 0.94410 (Rank 81)

# Evaluation Metric  

1 - np.sqrt(np.square(np.log10(y_pred +1) - np.log10(y_true +1)).mean())
