

# DARCY DAVIS - MONASH FINTECH BOOTCAMP ASSIGNMENT #01

# CASE STUDY: POCKETSMITH
 
##

![Alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXuDBVQHkOQrGbHVaeHFnvpGsCLtoWKONJirGBzcPp38QbHurQgas1Sw2COu70SuCb3g&usqp=CAU "Pocketsmith logo")

## Overview and Origin
Pocketsmith is a fintech company based in Dunedin in the South Island of New Zealand that provides personal finance tools for its customeers.
The company was [cofounded in 2008](https://www.pocketsmith.com/blog/yes-were-open-for-business/) by two friends Jason Leong and James Wigglesworth, who still remain CEO and CTO respectively.

So, why have I chosen Pocketsmith as my case study?
* I use the service. I found PocketSmith after one of its competitors, Pocketbook was shut down by Zip Co in 2022.  The reason I have stuck with Pocketsmith as my personal finance tracker is the GUI, it's ability to forecast decades into the future, it's ability to learn your spending patterns, and suggest budgets based on its learning of your spending patterns.
* My experience is that it has been written to gently nudge behavoir change in the user rather than make large changes based on a pre-determined algorithm
* I have also chosen this company as it is based in the South Island of New Zealand.  As Dunedin isn't necessarily regarded as a Tech Industry hub, it is a good reminder that successful ideas can come from anywhere


Pocketsmith was [created](https://www.pocketsmith.com/about/) to "build a handy calendar to plan upcoming income and expenses". This led direcly to an alpha version  being created within about a month.  In a [2014 Interview](https://www.odt.co.nz/business/pocketsmith-picks-xero-customers) to the *Otago Daily Times* Leong remarked that he "...just wanted to have a cool company" although in an earlier [interview in 2013](https://www.odt.co.nz/business/judge-was-once-cocky-contestant) Leong detailed how we had submitted his business plan to the University of Otago's Audacious Business Challenge competition where the winners get access to a Start-Up Incubator. He did not win or place in that competition, but still went on to build his company.

## Funding
Pocketsmith does not appear to have entered many funding rounds.  From the below structure you can see that the co-founders still have a very large interest totally 90% of the shareholdings as at July 2023.  The remaining shareholder Graeme Lance Turner Wiggs (referred to as Lance Wiggs on almost all media releases) is an angel investor, and shares a seat on the [board with the co-founders](https://pitchbook.com/profiles/company/87479-47#signals).  

Lance Wiggs is the Principle of Punakaiki Fund.  Punakaiki Fund invests in startups and provides venture capaital in New Zealand, but it is clear from their annual reports in 2021 and 2022, Pocketsmith is referred to as an interest of Lance Wiggs and has not procured funding through this vehicle.

It is claimed on the [Modest Money blog](https://www.modestmoney.com/is-pocketsmith-legit/) that PocketSmith has received funding from New Zealand-based venture capital firms Flying Kiwi Angels, K1W1 and NZVIF (New Zealand Venture Investment Fund).  I cannot find any evidence of this claim.  Interestingly any involvement of NZVIF is explicity rebutted in [Lance Wiggs' personal blog from 2016](https://lancewiggs.com/2016/02/25/is-nzvif-directionally-correct/), where he uses his investment in Pocketsmith (and the NZVIF's absence of investment) as an example that the NZVIF is not as aggressive as they claim.  On reddit this type of snark would be called Hobby Drama!

![Alt text](https://github.com/darcy5d/Fintech_Assignment_01/blob/main/Orbis_ownership_chart.png?raw=true "Current Pocketsmith ownership structure. Source: Orbis financial database")


## Business Activities and Target Markets:

Pocketsmith's current business model is to provide a personal financial service that allows individuals to track their expenses, create budgets, manage and forecast cash flow and determine an individual's net worth.  Using the budgets and inbuilt assumptions Pocketsmith can forecast forward months, years and decades depending on the level of subscription.

Pocketsmith's target market are individuals who are wanting to understand their personal finances on a category level.  
There is likely to be a cross-over between the 'Barefoot Investor' financial freedom movement, as well as the 'FIRE' (Financial Independence/Retire Early) movement.  
There was 83000 users in 2014 according to the Otago Daily Times.  Assuming a conservative rate of growth of 20% per annum for the subscriber that would equate to about 0.5 Million subsribers during 2024.

There was 83000 users in 2014 according to the Otago Daily Times.  Assuming a conservative rate of growth of 20% per annum for the subscriber that would equate to about 0.5 million subsribers during 2024, or 5 million with a 50% per annum growth rate.  The figure is likely closer to 0.5 million subscribes as [GrowJo](https://growjo.com/company/PocketSmith) estimates Pocketsmith's current revenue at about US$4 Million.

The advantages of Pocketsmith solution comes from three areas:
1. Pocketsmith's algorithms forecast deep in to the future, and can be used for retirement planning.  It does this through simple assumptions and algorithms.
2. The utilisation of open bank feeds.  Pocketsmith has been at the forefront of utilising and read-only banking API's.  In Australia this culminated with the industry standard provided by [Basiq](https://status.basiq.io/).  With worldwide standardisation of read-only banking API's, this will now become a weakness for Pocketsmith unless they can continue to grow
3. Cloud based from the beginning.  Pocketsmith was the major cloud-based personal finance tool until 2020 when competitors such as Mint went cloud-only and others such as Pocketbook and Xero left the space


According to Stackshare, Pocketsmith is written in JavaScript, with jQuery, AngularJS and jQuery UI serving appearing to be the main technologies used and languages.  The UI is the most important part of the app. 

## Landscape:

Pocketsmith finds itself in the personal financial services area of the Financial landscape.
The major innovations that this area has moved through is the machine learning aspect of identifying expenses and suggesting a categorisation for each expense.  The segment has moved from individual coding of expenses manually, which occurred in a previous competior Pocketbook, to now learning what service each merchant provideds.
The Opening up of bank feeds and standardisation of bank's API's to access transaction data has also levelled the playing field in the industry, allowing anyone to access this information and provide a similar service.


### Competition
Previous competion as discussed earlier came mainly from Xero Personal's app, which was also built in New Zealand.  This was also followed by Pocketbook, which was made defunct by Zip Co in 2022. In the current landscape, there are two areas of competition for Pocketsmith:
1. Standalone applications that provide a similar service
    - [Mint.com](https://www.doughroller.net/personal-finance/budgeting/7-alternatives-to-mint-com/) (free)
    - You Need A Budget (YNAB)
    - Every Dollar
    - Google Sheets (for example [CompiledSanity](https://cspersonalfinance.io/), which has a large and dedicated following on Reddit)

2. In-app tools provided by Banks
    - Just in Australia, Commonwealth Bank of Australia, Westpac and NAB are now providing transaction-level data and aggregating this in to categories (see below)
    ![Alt text](https://tillymoney.com.au/wp-content/uploads/2021/08/CBA-cashflow-1024x879.png "Pocketsmith logo")

 https://www.enniscorthyecho.ie/2023/07/03/cash-flow-forecasting-software-market-2023-future-scope-rising-demands-and-industry-growth-by-2029/

## Results

Understanding Pocketbook's success and impact is rather hard to determine.
Objective measures that could be considered include:
- Daily active users
- Subscriber % of total and daily users
- Subscriber growth
- Conversion rate of free (basic) user base to subscriber
- Revenue per employee

Considering that Pocketsmith has seen off two of its major local competition including Xero in New Zealand and Pocketbook in Australia, this should at least been seen as an indication that the current business model is robust enough to take on competition.

## Recommendations

The founders' vision for the company is supposedly virtuous.  They claim to only make money by [selling their software, not the user's data](https://www.pocketsmith.com/blog/shifting-from-money-brilliant-to-pocketsmith/).
To continue on this virtuous path I would advise the following.
1. Sign a deal with The Barefoot Investor Scot Pape and his publishing house HarperCollins to bring his brand and reach to the Pocketsmith App
2. Each book would come with a 1 year trial of the Pocketsmith Basic Plan with a purchase of Pape's book
3. Implement an option in Pocketsmith to follow Pape's instructions

The beauty of The Barefoot Investor is that there is an established brand that is grounded in the physcial world.  Bridging the gap to the digital space and into the world of Fintech leverages the original static content into a cloud-based, live manifestation of his concepts.
Pape's Barefoot Investor theory calls for a regular, calendar-based checkin once per month; as well as the bucketing of expenses in to four groups.  The original intention of Pocketsmith was to manage cash flows through a calendar, so their original missions both allign nicely.

In summary Pocketsmith is a moderately successful personal finance tool.  Its subscription model that targets individuals wanting to obtain a handle on their finances provides a solid revenue model that has ample room for growth.  The biggest threat will come from a standardisation of this type of service being provided by Banks who already have access to consumer's information and online banking platforms.

## References
- https://www.pocketsmith.com/blog/yes-were-open-for-business/
- https://www.pocketsmith.com/about/
- https://www.odt.co.nz/business/pocketsmith-picks-xero-customers
- https://www.odt.co.nz/business/judge-was-once-cocky-contestant
- https://pitchbook.com/profiles/company/87479-47#signals
- https://www.modestmoney.com/is-pocketsmith-legit/
- https://lancewiggs.com/2016/02/25/is-nzvif-directionally-correct/
- https://growjo.com/company/PocketSmith
- https://status.basiq.io/
- https://www.pocketsmith.com/blog/shifting-from-money-brilliant-to-pocketsmith/






