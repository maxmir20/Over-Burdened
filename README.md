# Overburdened

*IBM Z Datathon for Social Good Honourable Mention*

This project was used to address homelessness in the Bay Area. Having researched several causes of homelessness, we decided to see if we could develop a preventive tool that would provide early alerts for renters at risk.

Rent burden (how much of ones income is going to rent) is exceptionally high in the Bay area, especially among lower-income individuals. In many cases, renters are spending up to 75% of their income simply to remain in their homes.

Using Zillow datasets on rental prices in the Bay area, we decided to train an ARIMA machine learning model to estimate predicted price increases in the future. Using this tool, coupled with a users income and zip code, we could then determine how much of a renter's paycheck would be spent on average in that area. If the user is not yet spending a significant portion of their paycheck, we estimated how many years it would take before they would enter a level of rent burden that would be unsustainable. In addition, we also would use the model to predict the average rent-burden in surrounding zip codes, giving users options for neighborhoods that might better suit their income. The program itself was built on Python, and served as a command line interface that would let users enter their income and zip code before calculating their current rent burden and displaying the results on a map.

In this way, we hoped to give at-risk renters an opportunity to look ahead and plan out how their future might look given their current situation. Since tech results invariably end up being less accessible to homeless populations, we looked to create something that might prevent this situation before it happens. 
