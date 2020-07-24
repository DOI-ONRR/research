# Background
We have updated a data query tool to be able to query data by production, revenue, and disbursements and then by landowner, location, revenue type, commodity, source, disbursement source and fiscal year. 
## Goals
* Determine whether the new explore data page is usable 
* Identify areas that need fixing 
* Prioritize charts that haven't been built yet  

## Method and desired participants
Over the course of a few weeks, we would like to interview at least 9 participants from the following user groups for 30 minute 1:1 interviews. We will focus on users that have oil and gas experience and understand natural resources data.
* Question Answerers: These are people like congressional aides and internal liaisons who use the site to answer specific questions.
* Agenda Supporters: These are people like those from NGOs or industry who use the site to see how the data supports an agenda they already have in mind.
* Storytellers: These are people like journalists and academics who want the data to tell them a story that they want to share with other people.
* Domain Learners: These are people like state and county government reps and tribal leaders who want to monitor what’s going on within their domain and understand the whole system.

## Recruitment Strategy
* In order to recruit research participants from our target user groups, we will contact people who are familiar with the site or oil and gas revenue data. We will recruit internally from ONRR and externally.
* We are hoping to speak with users who are familiar with our data and can help evaluate if the data organization makes sense.  

We are hoping to speak with users who are familiar with our data and can help evaluate if the data organization makes sense.

## Test Assets:

We will be testing the following:

* Homepage https://dev-nrrd.app.cloud.gov/
* Explore Data page https://dev-nrrd.app.cloud.gov/explore/
* Revenue Prototype https://935313.axshare.com/#g=1&p=revenue_colors_-_final
* Disbursement Prototype https://935313.axshare.com/#g=1&p=compare_states

# Interview guide
## Intro (5 min)
* Introductions 
* Welcome, thank you for taking the time to meet with us.  I’m here today along with a few people from my team who are taking notes.   
* What we do on this team is talk with people about their tasks and observe them completing tasks, to learn about improvements we can make to the site.  Have you ever participated in research like this before? 
* External users: Did {Maroya or Lindsay} send you the consent form to sign? It just states your rights as a participant and that we won't be capturing any personally identifiable information 
* What the consent for is about (if the participant has any questions): It outlines your rights as a participant and says we won’t misuse your personal information. 

## User Task Background (15 min)
* What is your role and how do you use natural resources data in that role?
* Have you used the Natural Resources Revenue portal before?
  * Tell me a little bit about what you use the Portal for.
* What is your overall process when you are using natural resource data?
  * What are your goals?
  * What do you want people to know?
  * How do you know what data or numbers you need for your work?
  * How do you know where to look?
  * How do you verify the data you are going to use?
  * What does your output look like?
* What are the most important pieces of information to you?

## About Testing Prototypes
* We’re going to be looking at some prototypes of designs we’re thinking about. 
* Not everything will be clickable.   
* We’re testing the design we’re not testing you.
* I’d like you to think out loud  
* I want to know what you really think and how you would actually use it.  You can’t hurt my feelings. We want honest feedback so we can make the designs better.  


## Tasks & Questions:
### Start at the Home Page 
https://dev-nrrd.app.cloud.gov/
* Take a look at this page and tell me your general thoughts? 
* What do you think of the information that’s presented? 
* Is this information useful? 
* What do you expect to happen when you click on a different tab? 
Revenue Tab 
* Task: Can you tell me how much revenue was generated in CY 2013 on Native American lands? 
  * Do you prefer the data to be displayed in FY or CY? 
  * Do you expect the total revenue for each year to be displayed on the table? 
  * What does “Not tied to a lease” mean to you? 
  * Are the trends helpful? 
* Task: Can you tell me how much royalties were generated from oil production in Colorado in 2016? ( The purpose of this task is to see how the user will find the query tool since this task can’t be performed on the homepage) 
Disbursement Tab 
* Task: Can you tell me how much was disbursed in FY 2017 to Native Americans? 
  * Do you expect the total disbursement for each year to be displayed in the table? 
  * Are the trends helpful? 
* Task: Where would you go if you want to explore more data and get the whole picture?  (The  purpose of this task is to see how the user will find explore data without directing them there) 

### Explore Data (revenue) 
https://dev-nrrd.app.cloud.gov/explore/
* Poke around a bit and see what you can do on this page and what it's telling you. 
* What do you think of the information presented? 
* Is the information useful? 
* What do you think of the information presented on the national card? 
* Task: How would you compare what's going on with Texas to what's going on in the whole country? 
  * Is the information on the Texas card helpful? 
  * Are there any pieces of information that you would want to compare that you don't see here? 
  * Is it intuitive to click out of a card? 
  * How many locations would you want to compare at once? Are 4 cards a good amount? 
* Are you interested in offshore data?  
  * If answer yes. Task: How would you make the map display offshore data? 
  * Did the offshore data button make sense right away? 
* Is it clear that the cards are only displaying Federal data and not Native American data? 
  * Are you interested in Native American data?  
  * How would you add Native American card to be displayed? 
  * Was that easy or hard to find? 
* Task: How would you view the map by counties? 
  * Did Map level make sense? If not, what’s another name to make it clear? 
  * How would you use county data? Would you want to compare it against other counties? Only counties within a single state? Against the whole state? 

### Revenue Prototype 
https://935313.axshare.com/#g=1&p=revenue_colors_-_final 
* These are proto types of other ways we are thinking of displaying the revenue data. 
* Take a look and let me know your general thoughts? 
* Is this information useful? 
* Is it useful to know the federal land ownership percentage on top of the card? 
* What do you think of how the commodities are displayed? 
  * Is the scale of revenue clear using the circles? 
  * What do you think of the colors? 
* What do you think of how the revenue type is being displayed? 
  * Is the scaled of revenues clear using the circles? 
  * What do you think of the colors used? 
* Is the revenue over time chart useful? 
* Is the nationwide revenue summary by revenue type useful? 
  * What do you think of the colors ? 
* What do you think of the top revenue by location displayed? 
  * Is that information useful? 
  * Would you want to see the top locations displayed in another way? 
* What do you think of the top producing commodities displayed? 
  * Is that information useful? 
  * Would you want to see the top locations displayed in another way? 
* What do you think of the ten highest revenue companies table? 
  * Is that information useful? 
  * Would you want to see the top locations displayed in another way? 
* Do you like the order of the top charts (top location, top commodities, top companies)? If not, how would order them?  
  * Is there any other “top” charts you would like to see? 

### Disbursement Prototype 
https://935313.axshare.com/#g=1&p=compare_states 
* These are proto types of ways we are thinking of displaying the disbursements data. 
* What do you think of the information that’s presented? 
* Is this information useful? 
* What do you expect the data type drop down to do?  
  * Is there another way you would want to switch exploring a different data type? 
* What do you think of the time frame selection? 
* Do you like having the option to select a state using a dropdown as well as clicking on the map? 
* What do you think of the pie chart and table displaying disbursements by recipient? 
* What do you think of the pie chart and table displaying the source of disbursements? 
* Is it helpful to see the disbursement recipients and the source on the same card? 
* Is the disbursement over time chart helpful? 
* Is the bar chart on the bottom displaying the disbursements by source helpful? 
  * Is there another way you prefer that data to be displayed? 

## Close
* Are you interested in participating in future studies? Do you have any other specific areas of the site (or data elements) that you’re interested in providing your feedback on?
* Is there anyone else you recommend we speak with?
* Thank you for your time. Your insights have been helpful to us in understanding how we might improve our site. If there is additional information that comes to mind that you think might be helpful please feel free to reach out to myself via email.
