# Mint: The FinTech Watershed

## Overview and Origin
Mint was founded in 2006 by Aaron Patzer(1). He was originally working for IBM at the time as an electrical engineer. Throughout his teens and into his college career, he had been running small web development companies, and tracking his expenses (both business and personal) on multiple apps such as Quicken and Microsoft Money (4). 

After a couple of months of neglecting his financial entries, he found that he had hundreds of uncategorized transactions. The applications at the time would require him to go through each and every transaction and categorize them manually. This is where the idea for Mint came about(4).

The company was originally funded by Aaron himself, to make sure that it was viable and strong. He used money from his savings to pay engineers, and made sure that the product would perform well before seeking outside investment (2), (17). 

Investment began slowly at first, but after winning a TechCrunch challenge in early 2009, interest began growing. By September of 2009, Aaron had sold the company to Intuit for $170 Million. (2), (3). 

* How did the idea for the company (or project) come about?
	Aaron was using multiple services for personal financial management. He hadn't logged into Quickbooks in a few months, and when he did, his transactions weren't automatically categorized. That was an issue for him. 

* How is the company funded? How much funding have they received? 
	Series C Funding (1). $31M from DAG Vent. Shasta Vent. And First Round Cap, angel invest Ram Shriram. Latest round of $14M. (2) Full sell to Intuit for $170M (4). Mint is fully owned by a publicly traded company, Intuit now.

## Business Activities:
* What specific financial problem is the company or project trying to solve? 
	Personal budgeting and tracking your wealth at a snapshot. (1) Mint also guides users on things like what debt to pay first, how they could be making more money, etc. (4) (5).
	
	Automatically pulls in your financial activity, categorizes it, and shows you how to make money. Historically, banks did a terrible job at this. It pulls financial data from multiple sources and accounts. 

* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
	Primary customer is any online user that is interested in getting a hold of their personal finances. (Inferred.) Customer size is over 20 million (7). They have found young professionals to be most common cust. 

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
	Quick check on credit score (acquisition of Check) (8)
	Can pay bills directly on the app (acquisition of Check) (9). YNAB cannot do this.
	Massive network of intuit. This gives them an edge on advertisement, referrals, and sale of user data (6).
	If one of their competitors is banks (as (7) argues), then: Mint shows all accts in one place, is a digital financial advisor, simplifies bill payments, Markets competitive CCs, Markets 3rd party loans

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
	Security
	(10) - Account aggregation - proprietary tech
		Transaction Classification - standard industry classification codes (yellow page search engine)
	(11) - use this source for all this shit bruh.
	
	Application Data
	PHP
		What: Programming language for web development. Server side scripting, command line scripting, writing desktop app
		How: works with web server to deliver web pages to specific computers that are requesting information. Web pages use some scripting language (html, others) to communicate the web page data. Server interprets that language and turns it into something useful. (15)
		Mint uses this to make their website look.
	Nginx
		What: NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more.
		How: Basically it's a web server that allows for performance optimization under scale. Uses asynchronous, event-driven approach where requests are handled in a single thread as opposed to new processes for each web request. This multiple processes can be controled by a single process. 
	Bootstrap
		What: Framework for developing responsive and mobile-first websites. 
		How: 
		Mint uses this to allow users to run the app on any mobile device
	Utilities
	Amazon Cloudfront
		What: web service that speeds up distribution of your static and dynamic web content, such as . html, . css, . js, and image files, to your users.
		How: 
	Mixpanel
		What: Mixpanel is a business analytics service company. It tracks user interactions with web and mobile applications and provides tools for targeted communication with them.
		How: 
	Clicktale
		What: tells the story of your customer's behavior. We transform digital interactions into meaningful insights and visualizations,
		How:
	
	DevOps
	NewRelic
		What: Analytics. View and analyze date, 
		How: Application performance monitoring (APM) as SaaS (wasdat?)
	Varnish
		What: increases speed of a website while simultaneously reducing load on the web server. "Caching HTTP reverse proxy"
		How:
	Salt
		What: Infrastructure Management. Orchestration?, Remote execution, configuration mgmt, etc.
		How: Google Analytics, PHP, nginx
	AlertBot
		What: fully integrated monitoring platform. Monitors whatever you tell it to.
		How: 
	Business Tools
	Jira 
		What: Agile product development tool
		How
	Drupal 
		What: Free and open-source content mgmt framework
		How:
	Get Satisfaction
		What: Customer satisfaction software that seems to integrate the software into social media, establish online chat tools, etc.
		How:
		
	What are the specific Fintech technologies that Mint uses?
	In order to get user's financial data: Intuit's API (Application Programming Interface)
	To get CC Score and other things: Through Acquisition of Check: Uses equifax?
	
	Other: 
	Our technology was all open source, and essentially all free: MySQL at the bottom, Hibernate to avoid the need to hire a DBA, Tomcat on Apache, Yahoo’s YUI served as the base for our AJAXy goodness.
	
## Landscape:
* What domain of the financial industry is the company in?
	Personal finance, wealth management
* What have been the major trends and innovations of this domain over the last 5-10 years?
	Purchased by Intuit in 2009. Purchased Check in 2014. Integrates with Quicken. Added targeted ads and recommends better solutions and credit cards. They seem to be in a steady state.
* What are the other major companies in this domain?
	Personal capital, credit karma, tiller, ynab

## Results
* What has been the business impact of this company so far?
	Before mint, there were several separate budgeting apps. Quicken, microsoft money to manage personal and business income. No automatic categorization, yellow pages was used to identify the different transactions and their locations. Since then, we've seen automatic linking of multiple accounts into a single location for users to identify, categorize, and budget their transactions. Apps like YNAB allow users to follow a specific budgeting methodolgy to manage money. Mint is arguably the watershed app for personal finance, online wealth management, and possibly POS payment apps. (Source, my balls)

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
	# Users, paid vs free (guess), Traffic to site (quora interview), #EEs

* How is your company performing relative to competitors in the same domain?
	Mint is currently the top, and the largest, based on web traffic data, although they are shrinking. (crunchbase). YNAB is the next closest, followed by Personal Capital, and with Tiller in the rear. 

## Recommendations
* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!) 
Keep the app lightweight (complaint about it being too rigid)
	1. Provide financial and investment advice to users. 
	2. Find a way to control user's spending. Everything at this point is on the reactive end. 
* Why do you think that offering this product or service would benefit the company?
	1. Apps like Robinhood have revolutionized the ability for users to make investments on their own by lowering the barriers to entry for those that aren't educated in stocks. Private capital is already performing the advice portion. Combining the two from the mint user's budget will incentivize new users and keep existing ones. 
	2. I can set budgets all day, but sticking to them is another story.
* What technologies would this additional product or service utilize? 
* Why are these technologies appropriate for your solution?

-----------------

# Appendix/References
Sources:
* (1) - https://www.crunchbase.com/person/aaron-patzer#section-jobs
* (2) - https://en.wikipedia.org/wiki/Mint.com
* (3) - https://www.crunchbase.com/search/funding_rounds/field/organizations/last_funding_type/haveamint (picture)
* (4) - Podcast: Ep072 "The Startup Playbook Podcast"
* (5) - https://www.mint.com/
* (6) - https://www.investopedia.com/articles/personal-finance/082216/how-mintcom-makes-money-intu.asp
* (7) - https://blog.mint.com/credit/mint-by-the-numbers-which-user-are-you-040616/
* (8) - https://thefinancialbrand.com/52417/mint-banking-pfm-competitive-threat/
* (9) - https://www.forbes.com/sites/benkepes/2014/05/28/intuit-moves-deeper-into-personal-finance-acquires-mobile-bill-payment-vendor-check/#23b88d205dad
* (10) - https://yalantis.com/blog/mint-personal-finance-app-underlying-development-technology/
* (11) - https://stackshare.io/mint/mint
* (12) - https://money.stackexchange.com/questions/81253/how-to-recover-from-credit-score-hit-from-paying-off-loan
* (13) - https://www.financialsamurai.com/personal-capital-latest-assets-under-management/
* (14) - https://youngandthrifty.ca/why-i-cancelled-mint-com/
* (15) - https://www.dummies.com/programming/php/how-php-works/
* (16) - https://kinsta.com/knowledgebase/what-is-nginx/
* (17) - https://www.allbusiness.com/interview-with-aaron-patzer-mint-com-11480419-1.html
* (18) - https://techcrunch.com/2010/10/28/mint-data-delivers-a-view-into-the-spending-habits-of-its-4-million-users/
* (19) - https://mashable.com/2011/09/27/mint-aaron-patzer-interview/
* (20) - https://neilpatel.com/blog/how-mint-grew/
* (21) - https://www.quora.com/How-did-Mint-acquire-1-0m+-users-without-a-high-viral-coefficient-scalable-SEO-strategy-or-paid-customer-acquisition-channel