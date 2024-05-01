### Business Context

Used automobiles are in high demand in the Indian market right now. The pre-owned car market has grown over the past few years and is currently bigger than the new car market, notwithstanding the recent slowdown in new car sales. A young software start-up called Cars4U wants to get into this market by finding openings.

While 3.6 million new automobiles were sold in 2018, there were about 4 million used cars purchased and sold. Sales of new cars are slowing down, which may indicate that consumers' preferences are changing to the pre-owned market. In fact, rather than purchasing brand-new vehicles, several auto dealers opt to swap out their outdated vehicles for pre-owned ones. Used cars are very different animals with enormous uncertainty in both pricing and supply compared to new cars, where price and supply are fairly deterministic and managed by OEMs (Original Equipment Manufacturer), with the exception of dealership level discounts that only apply in the final stages of the customer journey. In light of this, these used automobiles' price strategy becomes crucial to their ability to expand in the market.

As a senior data scientist at Cars4U, you have to come up with a pricing model that can properly estimate the price of used automobiles and may help the business in creating profitable strategies employing differential pricing. For instance, if the company is aware of the going rate, it will never sell anything for less.

 
### Objective

To explore and visualize the dataset, build a linear regression model to predict the prices of used cars, and generate a set of insights and recommendations that will help the business.

 
### Data Description

The data contains the different attributes of used cars sold in different locations. The detailed data dictionary is given below. 


- S.No.: Serial number
- Name: Name of the car which includes brand name and model name
- Location: Location in which the car is being sold or is available for purchase (cities)
- Year: Manufacturing year of the car
- Kilometers_driven: The total kilometers driven in the car by the previous owner(s) in km
- Fuel_Type: The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)
- Transmission: The type of transmission used by the car (Automatic/Manual)
- Owner_Type: Type of ownership
- Mileage: The standard mileage offered by the car company in kmpl or km/kg
- Engine: The displacement volume of the engine in CC
- Power: The maximum power of the engine in bhp
- Seats: The number of seats in the car
- New_Price: The price of a new car of the same model in INR Lakhs (1 Lakh = 100,000 INR)
- Price: The price of the used car in INR Lakhs
