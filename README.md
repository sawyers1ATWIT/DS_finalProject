# DS_finalProject


# Introduction
The objective of this project is to use a dataset to explore creating a machine learning method in python. As someone who is very interested in machine learning, I'm excited to learn more about how to implement a model in python. For this project, I used a dataset from Kaggle describing a spaceship based on the Titanic, on which passengers are being randomly transported to an alternate universe. My goal is to answer the following research questions:
1. Are any of the features correlated?
2. Which of the features are most indicative of whether a passenger will be transported or not?
3. Can we predict if a passenger will be transported based on the feature variables using logistic regression?
4. How well did the model perform?

# Selection of Data
The dataset has 14 columns summarized in the table below:
| **Column**        | **Meaning**                                      |
|---------------|------------------------------------------------------|
| PassengerID   | Unique ID for each passenger on the ship             |
| HomePlanet    | Planet each passenger departed from                  |
| CryoSleep     | Binary indicator if passengers were in cryosleep     |
| Cabin         | Cabin number of each passenger (deck/num/side: P/S)  |
| Destination   | Passenger’s destination                              |
| Age           | Age of each passenger                                |
| VIP           | Indicator if passenger paid for VIP service          |
| RoomService   | Amount the passenger was billed for room service     |
| FoodCourt     | Amount the passenger was billed at the food court    |
| ShoppingMall  | Amount the passenger was billed at the shopping mall |
| Spa           | Amount the passenger was billed at the spa           |
| VRDeck        | Amount the passenger was billed on the VR Deck        |
| Name          | First and last name of passenger                     |
| Transported   | Indicator of whether a passenger was transported     |
