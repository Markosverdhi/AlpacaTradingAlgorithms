# Constant-Weighing Asset Allocation

In <i>general</i>, constant weighing asset allocation is a self explanatory model; it entails the regular rebalancing of the user's portfolio to match certain parameters set by the user.
<div>

## Front-End
- The front end will have many different elements, and it is dependent on what the fron-end developer decides to use as a medium of presentation to the user. Whether they decide to go the route of app or web development will be discussed and then this section will be updated to reflec that.
## Back-end
- The algorithm itself is not a predictive model in the sense that it does not actively predict future market values, rather it is a reactive statistical analysis tool that will automate the process of day trading through a ticker system.
<div>

## Data Storage
- I have not decided whether the application requires cloud storage at all. Using the cloud would imply that the user's input would be processed remotely through servers, which means that I would have to either outsource the work of computation to another company such as AWS or IBM Watson, or I would have to build my own server computer that is capable of handling multiple computations at once.
<div>

- Another possibility would be designing the program to run off the user's home machine. This would be easier for me to manage, but it would also put my code at risk, should I decide to go the route of proprietary code. If this project goes open-source *(which I think it will)*, I will probably go this route and allow anybody with a github account to clone and run the algorithms at their own discretion. This means that the individual would be able to 
<div>

## Requirements
- numpy version 1.21.5
- pandas version 1.4.2
- alpaca_trade_api version 2.3.0