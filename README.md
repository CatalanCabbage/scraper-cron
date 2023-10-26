# scraper-cron
## What are we doing?
Building a scraper to get info from a website like BookMyShow and notifying on changes - SMS, telegram etc.  

## What do we need to do?
1. Get data from BookMyShow or PayTM
2. Cron job
3. Sending alerts

### Get data from BookMyShow or PayTM
- Find the API that gives us that info. We can then use that endpoint to detect any changes.
(this is the simplest way)  
- If API isn't possible, we'll have to scrape the website.
(a bit more complex, but we can figure it out)

### Cron job
Find a way to execute our code periodically to check for changes

### Sending alerts
What ways are possible?  
SMS, Telegram, Whatsapp, Cliq, Mail
