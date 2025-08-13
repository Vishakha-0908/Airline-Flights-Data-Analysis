# Airline-Flights-Data-Analysis

The dataset contain following columns:

1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

10) Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

11) Price: Target variable stores information of the ticket price.

# Case study questions
Q1. What are the airlines in the dataset, accompanied by their frequencies.

Interpretation:
Vistara has the highest number of flights, followed by Air India. Airlines like GO FIRST, AirAsia, and SpiceJet have comparatively fewer flights. This indicates a dominance of certain carriers in the dataset.

Q2. Show Bar Graphs representing the Departure Time & Arrival Time.

Interpretation:
Most flights depart in the Morning, Early Morning, and Evening time slots.
For arrivals, the most common time slots are Night and Evening, suggesting many flights arrive late in the day.

Q3. Show Bar Graphs representing the Source City & Destination City

Interpretation:
Delhi is the top source city, followed by Mumbai and Bangalore.
As a destination, Mumbai is slightly ahead, with Delhi, Bangalore, and Hyderabad also being major arrival points.

Q4. Does price vary with airlines?

Interpretation:
Vistara and Air India have the highest average ticket prices. GO FIRST, Indigo, and AirAsia offer comparatively lower fares. This may reflect differences in service levels, routes, or demand.

Q5. Does ticket price change based on the departure time and arrival time?

Interpretation:
Prices tend to be higher for flights departing in the Morning and arriving in the Morning or Afternoon. Lower prices are common for late-night departures and arrivals, which may be less convenient for travellers.


Q6. How does the price change with change in Source and Destination?

Interpretation:
While the dashboard shows the frequency of flights per city, the pricing effect isn’t fully visualized here. However, given the patterns, major metro-to-metro routes (e.g., Delhi–Mumbai) likely command higher prices compared to smaller city pairs.

Q7. How is the price affected when tickets are bought in just 1 or 2 days before departure?

Interpretation:
Prices are highest when only 1–2 days are left before departure, then drop sharply as the booking window increases. This aligns with typical airline pricing strategies favouring early booking.

Q8. How does the ticket price vary between Economy and Business class?

Interpretation:
Business class fares are significantly higher than economy, with economy making up the majority (88.88%) of tickets in the dataset.

Q9. What will be the Average Price of Vistara airline for a flight from Delhi to Hyderabad in Business Class?

Interpretation:
The average price for this specific combination is ₹47.94K, indicating a premium fare for this route and class.
