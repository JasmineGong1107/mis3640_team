# Project Proposal 

## The Big Idea:
### The Main Idea:
The premise of the project is to create an investment monitor for crypto assets. 
User inputs will be: crypto coin, quantity owned, and monetary investment made. 
Multiple types of crypto coins may be entered. 
The user has the option to track both an individual asset's value and the weighted portfolio's value.
The entry object will be stored on the server and tracked 24 hours a day.
The user will be able to specify an acceptable-loss percentage that the program will push an email notification
if the asset / portfolio depreciates past (Example: 10% loss-tolerance. 10.01% depreciation => email nofication).

### Exploration and Generation:
This project requires research on the topic of cryptocurrency and the crypto markets. As crypto coins remain
largely unregulated, investors run the risk of high volatility and scams. Thus, the research must be focused
on crypto coin origination, valuation, and payoff characteristics. The findings will be used to identify the
program requirements in tracking asset value. 

### Minimum Viable Product:
The minimum viable product is a website that allows users select a single crypto coin from a specified list of cryptocurrencies
(this reduces the complexity of tracking high-yield, smaller cap crypto coins). The user will also input the quantity owned 
and the monetary investment made. The quantity will be restricted to whole assets. The monetary investment is limited to USD. 
The loss-tolerance will be set at a fixed 10%. The program will notify if the singular coin's valuation depreciates past the 
loss-tolerance. 

### Stretch Goal:
The stretch goal is a website that allows users to input the name of a crypto coin into a field, and the program runs a query on 
the input. It will return a list of matches. The user can input quantity owned and monetary investment made. Because crypto coins may 
be fractionally owned, it will be a challenge to create a standard to measure against. The options for baseline currency are yet
to be decided. The user can create a portfolio object that contains multiple crypto objects. The user may input a loss-tolerance for
individual crypto objects as well as the portfolio object. The program will display % total return for the individual crypto coins
and the portfolio. The user may specify notification preferences (Example: Notify when portfolio depreciates 10%, but not when the 
crypto coin depreciates 10%). 

## Learning Goals: