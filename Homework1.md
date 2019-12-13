# Mint: The FinTech Watershed

## Overview and Origin
Mint was founded in 2006 by Aaron Patzer(1). He was originally working for IBM at the time as an electrical engineer. Throughout his teens and into his college career, he had been running small web development companies, and tracking his expenses (both business and personal) on multiple apps such as Quicken and Microsoft Money (4). 

After a couple of months of neglecting his financial entries, he found that he had hundreds of uncategorized transactions. The applications at the time would require him to go through each and every transaction and categorize them manually. This is where the idea for Mint came about(4).

The company was originally funded by Aaron himself, to make sure that it was viable and strong. He used money from his savings to pay engineers, and made sure that the product would perform well before seeking outside investment (2), (17). 

Investment began slowly at first, but after winning a TechCrunch challenge in early 2009, interest began growing (2). Mint's most recent Series C Funding was about $31M from DAG Ventures and Shasta Ventures. THe first round cap came from angel investor Ram Shriram (1). By September of 2009, Aaron had sold the company to Intuit for $170 Million(3). 
 

## Business Activities:

Mint came into existence to solve two problems. The first problem was that transactions in traditional personal finance applications were neither categorized, nor usefully labeled. The second problem was that the categorization did not automatically update the transaction into a useful snapshot of a user's budget(2). Mint solved these two problems early on in the process, but because they were so focused on ensuring the software was successful before releasing it, the engineers at Mint were able to tack another useful feature onto to application. Instead of just showing a budget to users, Mint shows users a full snapshot of their net worth. In addition to this, Mint also guides users on what debt to pay down first, and how they could be earning more interest based on different savings account options (4) (5). 

In 2014, Mint purchased an application called Mint Bills for $350M. Mint Bills (formally Check) allowed users to pay bills through the application, and generated revenue by allowing credit card and insurance advertisements in the app(22). In general, Mint is attempting to give users visibility into and control of their finances from a single application. 

Mint has a very large customer target, due to the ubiquitous nature of cellular telephones. Anyone interested in gaining control of their finances by using modern, personal technology is an intended customer for Mint. Mint is estimated to be used by over 20 Million customers. The most common user of Mint is young professionals, although how much of the customer base they make up is unknown (7).

It is this author's opinion that Mint was able to acquire their massive customer base (and competitive advantage) through several key factors, listed below. 

1. First out the gate: Mint was the first, or at least the best at the time, to aggregate all of the user's data, automatically categorize it, and present it in a tidy bow. While Quicken and Microsoft Money did some of what Mint does, we can know - through the continuing success of Mint - that they didn't or don't do it like Mint does.

2. The Behemoth Intuit: Mint has the disproportionate advantage of Intuit's resources. At an estimated $6.9B in revenue (23), Intuit has the capability to absorb (read: acquire) nearly any financial player that it deems profitable or threatening to their current sandbox. Intuit has acquired several companies specifically to increase Mint's capabilities, as we have seen with the acquisition of Check in 2014. 

3. Check acquisition - this allowed Mint to provide bill pay from the app. In addition to this, and mentioned earlier, Mint purchased Check's revenue stream, which is built on credit card and insurance advertisements. Mint has leveraged this stream to recommend specific credit cards to their users, and to provide a quick check on the user's credit score. - a targeted service that competitors cannot offer (8,9).

### Technologies in Use

The following presents an overview of all of the technologies and applications that Mint uses to provide its service. Sleuthing is still underway to find descriptions of the exact Fintech algorithms and technologies that Mint employs. The majority of these technologies were found using Crunchbase.com (24)

#### 	Security
* Account aggregation - proprietary tech
* Transaction Classification - standard industry classification codes (yellow page search engine)

####	Application Data
* PHP
	* What is it: Programming language for web development. Server side scripting, command line scripting, writing desktop applications

	* How it works: works with web server to deliver web pages to specific computers that are requesting information. Web pages use some scripting language (html, others) to communicate the web page data. Server interprets that language and turns it into something useful. (15)
	
	* Author's Understanding: Mint uses PHP to quickly translate packets of information from the user to Mint's servers.

* Nginx
	* What is it: NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more.
	
	* How it works: Basically it's a web server that allows for performance optimization under scale. Uses asynchronous, event-driven approach where requests are handled in a single thread as opposed to new processes for each web request. This multiple processes can be controled by a single process. 
	
	* Author's Understanding: Mint uses this...

* Bootstrap
	* What is it: Framework for developing responsive and mobile-first websites. 
	
	* How it works: 
	
	* Author's Understanding: Mint uses this to allow users to run the app on a multitude of mobile devices, thus allowing different types of hardware (specifically cell phones or tablets) to utilize their application. 
	
#### Utilities
* Amazon Cloudfront
	
	* What is it: web service that speeds up distribution of your static and dynamic web content, such as . html, . css, . js, and image files, to your users.
	
	* How it works: 
	
	* Author's Understanding: 

* Mixpanel
	* What is it: Mixpanel is a business analytics service company. It tracks user interactions with web and mobile applications and provides tools for targeted communication with them.

	* How it works: 
	
	* Author's Understanding: 
	
* Clicktale
	* What is it: tells the story of your customer's behavior. We transform digital interactions into meaningful insights and visualizations,
	
	* How it works:
	
	* Author's Understanding: 
#### DevOps
* NewRelic
	*What is it: Analytics. View and analyze date, 

	* How it works: Application performance monitoring (APM) as SaaS (wasdat?)

	* Author's Understanding: 
	
* Varnish
	* What is it: increases speed of a website while simultaneously reducing load on the web server. "Caching HTTP reverse proxy"
	
	* How it works:

	* Author's Understanding:

* Salt
	* What is it: Infrastructure Management. Orchestration?, Remote execution, configuration mgmt, etc.
		
	* How it works: Google Analytics, PHP, nginx

	* Author's Understanding:

* AlertBot
	* What is it: fully integrated monitoring platform. Monitors whatever you tell it to.
	
	* How it works: 
	
	* Author's Understanding: 

#### Business Tools
* Jira 
	* What is it: Agile product development tool
	
	* How it works:

	* Author's Understanding:
* Drupal 
	* What is it: Free and open-source content mgmt framework
	
	* How it works:

	* Author's Understanding:

* Get Satisfaction
	* What is it: Customer satisfaction software that seems to integrate the software into social media, establish online chat tools, etc.

	* How it works:

	* Author's Understanding: 

#### Specific Fintech Technologies
Still sleuthing about for this information.
	
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
* (22) - https://www.wsj.com/articles/intuit-in-talks-to-buy-mobile-finance-app-1398826760?tesla=y
* (23) - https://www.crunchbase.com/organization/intuit#section-interest-signals-by-bombora
* (24) - https://www.crunchbase.com/organization/haveamint#section-overview