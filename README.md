### **BACK-END DEVELOPMENT**

# **Project: Lyft Trip Data**

<br>

Suppose I am a Data Analyst at Lyft, a ride-sharing platform. For a project, I was given three tables:

- trips: trips information
- riders: user data
- cars: autonomous cars

_Have fun!_

<br>

# **Write the following queries:**

<br>

## **1. Let’s examine the three tables**

```
SELECT * FROM trips;

SELECT * FROM riders;

SELECT * FROM cars;
```

What are the column names?

<br>

## **2. What’s the primary key of trips, riders and cars?

<br>

## **3. Try out a simple cross join between riders and cars**

Is the result useful?

<br>

## **4. Suppose we want to create a Trip Log with the trips and its users**

Find the columns to join between trips and riders and combine the two tables using a LEFT JOIN.

Let trips be the left table.

<br>

## **5. Suppose we want to create a link between the trips and the cars used during those trips**

Find the columns to join on and combine the trips and cars table using an INNER JOIN.

<br>

## **6. The new riders data are in! There are three new users this month**

Stack the riders table on top of the new table named riders2.

<br>

# **Bonus: Queries and Aggregates**

<br>

## **7. What is the average cost for a trip?**

<br>

## **8. Lyft is looking to do an email campaign for all the irregular users**

Find all the riders who have used Lyft less than 500 times!

<br>

## **9. Calculate the number of cars that are active**

<br>

## **10. Write a query that finds the two cars that have the highest trips_completed**

<br>

### ***This Project was completed by [Nalini Vo] (https://github.com/Nalini1998)***