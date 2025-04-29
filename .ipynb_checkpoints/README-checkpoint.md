# LearnML_PracticalApp2
AI/ML Course Practical Application 2 Exercise - Kaggle Used Cars

## Price of Used Cars 

Jupiter Notebook: [Used Cars Analysis](https://github.com/shruti0209/LearnML_PracticalApp2/blob/main/Used_Cars_Analysis.ipynb) 

### Problem Statement 
As part of this exercise, I were provided with historic data on sell of used cars. In addition to the actual selling price of the cars, the data included other information of the car like the manufacturer, odometer reading, age, type, model etc of the cars. My goal was to understand what factors make a car more or less expensive and provide clear recommendations to the client -- a used car dealership -- as to what consumers value in a used car.

### Approach 
Using the available data here's what I did:
1. Explored the target and independent variables
2. Built a regression model to predict the target variable i.e. price of used car
3. Used the model built to identify independent variables that influenced the price prediction the most i.e enlisted the variables that had high absolute regression coefficients

### Findings 
Using the data available to me, I could estimate the selling price of cars with almost 80% accuracy. With my model, I could potentially estimate the total value of client's inventory. I have identified key factors that would influence prices of cars. Client could maximize their income by marketing these features. Client should also consider these factors to obtain new inventory to maximize the value of their inventory. 

The factors that are most valued by customers include:
1. **Odometer readings** - lower reading is highly desired; lower odometer value could seek high price even when the car is old  
2. **Condition of cars** - cars in good condition are desired even in difficult markets
3. **Transmission** - transmission type 'other' is very popular. We'll require additional information on this tranmission type to further understand customer behavior
4. **State/region** - cars from regions that experience harsher winters are less likely to seek high price (unless the cars are in good condition)
5. **Manufacturer** - cars by certain manufacturer (Tesla, Alfa-Romeo, Ram, Porsche, Jaguar etc.) seek higher value and certain others (Saturn, Mercury, Pontiac, Morgan, Chrysler etc.) are valued lower
6. **Age of car** - higher the age, lower the value 

