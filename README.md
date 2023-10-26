# scraper-cron
## What are we doing?
Building a scraper to get info from a website like BookMyShow and notifying on changes - SMS, telegram etc.  

## What do we need to do? (Draft)
1. Get data from BookMyShow or PayTM
2. Cron job
3. Sending alerts

### Get data from BookMyShow or PayTM
- Find the API that gives us that info. We can then use that endpoint to detect any changes.
(this is the simplest way)  
- If API isn't possible, we'll have to scrape the website.
(a bit more complex, but we can figure it out)

### Cron job
Find a way to execute our code periodically to check for changes.  
We need a server that can host our code, needs to be on always.  

Possible ways:  
- Put it on your machine and keep the laptop on (simplest)
- Use an online hosting service - Replit, Catalyst etc.

Catalyst:  
![image](https://github.com/CatalanCabbage/scraper-cron/assets/45961072/502efa97-aed1-4a75-89ab-5d30098fce39)

✔️**Decision:** We can use Catalyst since it's free and provides the CRON out of the box.

### Sending alerts
What ways are possible?  
SMS, Telegram, Whatsapp, Cliq, Mail

## Todo:
- Find API to get data
- If no API, write code to scrape it
- Set up cron job
- Set up notification
