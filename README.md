# Wall Street Jarvis

Bot to provide enriched CX for your stock investment journey


## Demo

Watch it  ([here](https://drive.google.com/file/d/1nLbQPL0C3-DSdJ36ALgd97sVrmte0NwF/view))







## Overview

Wall Street Jarvis (WSJ) is a revolutionary chatbot solution that enables you to perform trading activities, check the price of assets, and view your Profit/Loss statement effortlessly on your favorite messaging app, WhatsApp. With WSJ, you no longer need to log in to a complicated trading platform or constantly monitor the stock market on multiple devices.

## Compoenets Used
!<img width="971" alt="components" src="https://github.com/aku019/Wall-Street-Jarvis/assets/39730533/91b81163-e8c4-4cd2-b1aa-9dfd95dac628">


- Broker Apis: Used Alpaca Java API's([LINK](https://github.com/Petersoj/alpaca-java))

- Journey Builder, Auto Bot Builder, Whatsapp Self serve, Agent Dashboard : these are services provided by Gupshup for their CX product

## Current Functionalities

- Place buy and sell orders
- Check current price of shares
- Check Profit /Loss 
- Get daily digest of stock news using CX-Marketing and - ChatGPT
- Resolve your market related queries with help of AutoBot
- Customer support via Agent Dashboard

## Sequence Diagram
<img width="850" alt="sequence" src="https://github.com/aku019/Wall-Street-Jarvis/assets/39730533/8c4e5e64-5d45-435e-b0c7-4b626f6c333c">


## Business Impact

### Reduction of effort for users

- WSJ's user-friendly interface ensures that even novice traders can easily buy or sell assets with just a few clicks on your favorite messaging app.
-  Bot provides you with daily market digests, keeping you up-to-date with the latest market trends.

### Competitive advantage                                                         
- Improved customer satisfaction by providing an easy and convenient way for traders to manage their portfolio and stay informed.
- Increased adoption of trading by providing user friendly interface on an already familiar application.
- Improved efficiency by leveraging the power of artificial intelligence, WSJ enables you to make well-informed trading decisions, even on-the-go.

## Operational Overheads

### Feasibility of productization

- We will need to integrate with the actual broker APIs(currently sandbox API’s are being used). These actual - API are chargeable
- User Onboarding to get started with trading via WhatsApp

### Maintenance

- Keeping up to date with latest stable updates of Gupshup’s solutions and Brokers APIs. 
- Analyze user feedback to provide better experience to users.

### Compliance

- Currently it’s completely legal to use a bot for stock market trading, but we always need to comply with any relevant regulations and guidelines, like data security.

## Technology Stack

- JAVA(Spring Boot)
- Python(Flask)
- Ngrok
- Mongo DB
- Broker APIs
- ChatGPT APIs



## What’s next?

- Integrate Portfolio details and analytics features as well, generally available with paid versions of Broker APIs.
- Provide options to place different types of orders like stop loss,market order etc.
- Designing a CSAT flow 
- Adding feature to invest in Mutual Funds and other feasible invest instruments
