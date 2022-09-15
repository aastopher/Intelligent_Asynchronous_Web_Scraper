# Intelligent Asynchronous Web-Scraper - UFC Completed Events

Intelligent Asynchronous Web-Scraper which will collect completed UFC events and related match data from [ufcstats.com](http://www.ufcstats.com/statistics/events/completed?page=all). Clearing both or just one file will re-scrape the whole file otherwise if new event entries are found compared to the stored events only the new events will be scraped and each file with be updated with the new entries. NOTE: currently removing events from the `completed_events.csv` file manualy then re-running will result in double entries for `completed_event_matches.csv`; otherwise re-running the notebook will either update or refresh the files depending the existence of each file. 

**TO-DO:**
* The notebook should be set to run on a schedule with github actions