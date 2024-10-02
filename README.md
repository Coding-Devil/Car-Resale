# Car Resale value predictor  🚗💰
> Assess Your Car's Resale Value!
---

Hey, car enthusiasts and data aficionados! 😎🔍 Ever found yourself scratching your head trying to figure out the right price for your used car? 🤔 Or maybe you’re on the hunt for a sweet deal but are unsure if it’s a steal or a bust? Well, worry no more! I’ve been working on something that’s about to make your life a whole lot easier.

Drumroll, please… 🥁 Introducing the **Car Resale Value Predictor**! 🌟🎉

---
 
### 🚗 **The Problem : A Wild Ride**

Navigating the used car market in India is like trying to drive on an uncharted road. Prices bounce around like a rollercoaster, influenced by a myriad of factors - from the make and model to the mileage and even the seller’s mood. 😅 Imagine trying to price your car without a GPS! That’s where our model comes to the rescue.

### 🧠 **Our Approach: Data Meets Car Deals** 💡

We’ve brewed up a robust machine learning model to predict used car prices based on the features of the car. We trained this bad boy on a treasure trove of data scraped from [Cardekho.com](http://Cardekho.com). 🚀 With this model, you can now predict the price of any used car just by feeding in its features. Cool, right?

---

### 🎯 **Objective: Predict Like a Pro**

Our goal is crystal clear - to build a machine learning model that predicts the selling price of a used car as accurately as possible. Why? Because accurate pricing means:

* **Sellers** can price their cars right and sell faster. 🏁
    
* **Buyers** can find deals that won’t break the bank. 💸
    
* The used car market becomes slicker and more efficient. 🔧
    

### **Data Breakdown: What We’re Working With** 📊

Here’s a peek under the hood at our dataset:

* **car\_name**: The full name of the car, including brand and model.
    
* **brand**: The car’s brand name.
    
* **model**: Specific model name.
    
* **seller\_type**: Type of seller (dealer or individual).
    
* **fuel\_type**: Type of fuel the car uses.
    
* **transmission\_type**: Transmission type (manual or automatic).
    
* **vehicle\_age**: Number of years since the car was bought.
    
* **mileage**: Kilometers the car runs per litre.
    
* **engine**: Engine capacity in cc (cubic centimeters).
    
* **max\_power**: Max power produced in BHP.
    
* **seats**: Number of seats in the car.
    
* **selling\_price**: Price at which the car is listed.
    
    ---
    

### **Model Magic: Who’s the Champ?** 🏅

We’ve tested several models to find the best one for our car price prediction. Here’s how they stacked up:

1. **Random Forest Regressor** 🌲 - Our top performer, offering the best accuracy and versatility. Think of it as the superhero of our model lineup.
    
2. **Decision Tree Regressor** 🌳 - A close second, providing solid accuracy with the added bonus of interpretability.
    
3. **Linear Regression Models** 🧮 - Ridge and Lasso models, although simpler, still have their place in the lineup for their straightforward approach.
    
    ---
    

## 🛠️ **Fine-Tuning: Making It Even Better**

We’ve dialed in our models with hyperparameter tuning to squeeze out every bit of performance. It’s like giving our model a turbo boost to ensure it performs at its peak!

### **The End Game: Pickle It!** 🥒

Finally, we save our model into a pickle file, making it easy to deploy and use for real-time predictions. It’s like having your personal car price guru always at your fingertips!

![image](https://github.com/user-attachments/assets/3c056d68-4de1-4a69-8e36-811501271898)

