# Exploratory Data Analysis (EDA) of a Mobile App
Analyze the 'ping' data of a mobile app, key findings, and the impact

## Data
The JSON format data represents the "ping" data for an app for the month of February 2016. It has about 4.8 million rows. When the app is opened by a user, the app pings the analytics system. A user may ping multiple times in a day.

The data has 5 columns:
1. date: date of the ping
2. timestamp: ping timestamp
3. uid: unique id assigned to users
4. isFirst: true if this is the user's first ping ever (some users have been using the app before February)
5. utmSource: traffic source from which the user came

The dates are based on Pacific time.

## Key findings include
1. Weekly cyclical usage pattern which top on Wednesday and bottom on Saturday
2. 60% of the users who download the app the first time abandons the app after 1 week
3. Analyze the usage based on the traffic source

These key findings help improve the product and marketing strategy.
