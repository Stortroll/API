# Börsdata API
## This repository contains information about Börsdata API. 
 
## Getting started
1. If you dont have an API KEY you need to Apply for it on [Börsdata MyPage.](https://borsdata.se/en/mypage/api)
2. Then you can download our sample projects from GitHub and start coding.

## Documentation
1. We use this Github as the main info page for programmers. 
2. Most info is in the [Wiki](https://github.com/Borsdata-Sweden/API/wiki).
3. The API calls is documented [here with swagger](https://apidoc.borsdata.se/swagger/index.html)
4. You can read about the API on our [info page](https://borsdata.se/info/api/api_info)
5. Try our [c# sample client](https://github.com/Borsdata-Sweden/API-CSharp-Client).


## Rate Limits
The API is rate limited to 2 calls pr.second.  
You will recieve a 429 when exceding the rate limit.  

There is no set max limit of api calls, but you should try not to exceed 10K api calls per 24h.  
It's ok to do more api calls occasionally, but not every day.  
Please try to stay below 10K per day.

## Issues Tracking
We use GitHub's Issues tracker for our project. Feel free to create bug reports and features requests. Make sure to read the documentation before asking questions - this will avoid repeated questions, leaving us more time for developing the library.

## Sample Code
- [C# API Lib with sample code](https://github.com/Borsdata-Sweden/API-CSharp-Client).  
- [Python Lib with sample code](https://github.com/JoelRoxell/borsdata-sdk).   
(Special thanks to Joel Roxell for Python API lib!)

## Stay Tuned
Follow us on [Twitter](https://twitter.com/search?f=tweets&vertical=default&q=BORSDATA%20OR%2040procent20ar&src=savs) and [Facebook](https://www.facebook.com/borsdata.se/) to receive updates.


## Disclaimer
Börsdata and the information contained herein is not intended to be a source of advice or credit analysis with respect to the material presented, and the information and/or documents contained in this website do not constitute investment advice.  
The user is responsible for the risk and should therefore acquire information about the terms that apply to trade with such instruments, and about the qualities of the instruments. Placements or other positions in financial instruments such as stock is done at your own risk. <br> Börsdata cannot in any way be held responsible for any investment decisions that result from the financial information on the website.  
Always do your own Research. 


# Updates
## 2019-04-04  
-Add new API call to get list of Last Stockprice for all Instruments.  
(No need to call all Instruments to get last stockprices on daily basis. One call instead of +1600)
  
-Add new API call to get all reports for one Instrument.  
(To get Year, R12, Quarter Reports you only need one call)

## 2020-04-21
- Add maxCount to get up to 20 year stockprice, 20 year reports and 40 R12&Quarter reports.
- Add report/kpi meta data for translations.
- Add stockprices/date to get all stockprice for a specific date.


