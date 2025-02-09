# Visualizing Technical Indicators Using Python and Plotly.

###### Currently facing issues hosting the application on heroku. As soon as I am able to I'll like the live application here. Any updates will be here
#### DEMO


![gif](assets/TECH-ANALYSIS-DEMO.gif)

*This is version 1 of the web application*
## Table of contents
1. [About the Web app.](#About-the-Web-app.)
2. [Tutorial on how to use the application](#Tutorial-on-how-to-use-the-application)
3. [Inputs required from the user](#Inputs-required-from-the-user)
4. [Returns to user](#Returns)
5. [Indicators Available](#Indicators-as-of-Version-1-of-the-web-application.)
6. [Requirements](#Requirements)
7. [Updates](#Updates)
8. [Updates you can expect](#Updatates-you-can-expect)


## About the Web app. 

With this web application I aim to provide a free open source method for people to visualize and understand various technical indicators. 
People can use this application to select various technical indicators and then visualize and interact with them. This can help new financial engineers get a better understanding of how various parameters of a technical indicator will affect the way we execute trades. It uses the technical analysis library available for python and Plotly's interactive visualization tools to provide the user with a dynamically changing and interactive tool. 

Since this is just version 1 of the application I am yet to fix a lot of bugs and improve on it. So do bear with some of the little nuances. In case you would like to send any suggestions please email me at [sashanksurya9wj@gmail.com](sashanksurya9wj@gmail.com).



## Tutorial on how to use the application.
To use this one must follow the steps below
1. Open the web application in your browser
2. Open Yahoo finance and search for the stock for which you wish to plot the indicator for
3. Copy the ticker value for the stock from Yahoo FInance
4. Paste it in the input box of the application
5. Select the indicator.
6. Select the date range and other input parameters based on the indicator
7. In case you would like to learn more about the indicator click on the link that says "TO learn more about current indicator please click here"

## Inputs required from the user
1. Ticker of Stock
2. Start Date
3. End Date
4. Short Window (or Window 1)
5. Long Window (or Window 2)
6. Signal Window (or Window 3/Window Atr)
7. Indicator to be Visualized

## Returns
1. Link to the current indicator for people to refer to
2. Interactive visualization of the current inidcator for set parameters
3. Dynamically Changing Environment


For any suggestions please email me. 

![](https://www.investopedia.com/thmb/d6VF2gfx_W0UZC77q8RTZKFDsRc=/3711x2087/smart/filters:no_upscale()/dotdash_Final_Technical_Analysis_Strategies_for_Beginners_Sep_2020-01-2fd259fdcac044dd824d1b565e53b4e6.jpg)

## Indicators as of Version 1 of the web application. 
```
1. Accumulation/Distribution Index
2. Aroon Indicator
3. Average Directional index
4. Average True Range (ATR)
5. Awesome Oscillator
6. Bollinger Bands (std - 2)
7. Chaikin Money Flow (CMF)
8. Cummilative Return
9. Daily Return
10. Donchian Channel Bands
11. Ease of Movement
12. Exponential Moving Average
13. Ichimoku Kinkō Hyō (Ichimoku)
14. Kaufman’s Adaptive Moving Average
15. Kelter Channel Index
16. Money Flow index
17. MACD
18. Negative Volume Index Indicator
19. Percentage Price Oscillator
20. Percentage Volume Oscillator
21. Rate of Change
22. Relative Strength Index (RSI)
23. Simple Moving Average
24. Ulcer Index
25. Volume Weighted Average Price
26. Weighted Moving Average
```

## Requirements
```
1. Brotli==1.0.9
2. certifi==2021.10.8
3. charset-normalizer==2.0.7
4. click==8.0.3
5. colorama==0.4.4
6. cycler==0.10.0
7. dash==2.0.0
8. dash-bootstrap-components==1.0.0
9. dash-core-components==2.0.0
10. dash-html-components==2.0.0
11. dash-table==5.0.0
12. DateTime==4.3
13. Flask==2.0.2
14. Flask-Compress==1.10.1
15. gunzcorn==20.1.0
16. idna==3.3
17. itsdangerous==2.0.1
18. Jinja2==3.0.2
19. kiwisolver==1.3.2
20. lxml==4.6.3
21. MarkupSafe==2.0.1
22. matplotlib==3.4.3
23. multitasking==0.0.9
24. numpy==1.21.3
25. pandas==1.3.4
26. Pillow==8.4.0
27. plotly==5.3.1
28. pyparsing==3.0.1
29. python-dateutil==2.8.2
30. pytz==2021.3
31. requests==2.26.0
32. six==1.16.0
33. ta==0.7.0
34. tenacity==8.0.1
35. urllib3==1.26.7
36. Werkzeug==2.0.2
37. wincertstore==0.2
38. yfinance==0.1.64
39. zope.interface==5.4.0
```

To install these please use: 

`pip install -r requirements.txt`


### Updates
1. **Updates on 26th October 2021**
    1. Added functionality to change the type of plot along with the indicator
        1. Added Candlestick plots
        2. Added Closing price plot
        3. Added open price plot
    2. Changed the initial starting and ending date to be 2 years long so that it isn't resource heavy at the beginning


# Updates you can expect 
If an update that I wanted to include is completed it will be striked through. 
1. ~~Include functionality for candlestick, close and open graphs~~
2. Moving averages will include small and long average graphs for better analysis. 
3. Return the cummilative return, if people executed trades purely based on the indicators.

**PLEASE EMAIL ME FOR SUGGESTIONS OR TO COLLABORATE WITH ME**
**This web application is made for academic purposes only**


