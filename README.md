# LinkedIn Sales Navigator Scraper / Extractor

## Description
A scraper tool that automate the extracting of leads and accounts from LinkedIn Sales Navigator.

The scraper is based on the Scrapy framework [http://scrapy.org](http://scrapy.org), right now it's only running on CLI(terminal).

#### Requirements
* LinkedIn Account credentials
* Subscription to LinkedIn Sales Navigator

#### Parameters
The scraper only accept one required parameter which is the absolute URL of the search query result in the LinkedIn Sales Navigator.

#### Data
Leads extractor, extract these fields:
- First name
- Last name 
- Full name
- Public profile URL
- Location
- Current position
- Company name
- Company profile URL

Accounts extractor, extract these fields:
- companyId
- name
- companyType
- emails => ONLY IF COMPANY DESCRIPTION CONTAINS EMAILS!!
- size
- industry
- location
- country
- geographicArea
- city
- postalCode
- line2
- line1
- founded
- followerCount
- website
- staffCount
- description
- profileLink

## Purchase
If you’re interesting to purchase this tool, please follow this link [https://goo.gl/uTGYgD](https://goo.gl/uTGYgD) and click on the buy button, money is in escrow until you’re satisfied and then accept the invoice.

You can customize this tool, by extracting more data or integrating some APIs to look for emails or push extracted leads to a CRM, you can drop me a message via the contact button on this page [https://goo.gl/uTGYgD](https://goo.gl/uTGYgD), just be more specific in you message, in order to understand your requirements, thank you.

## Support
The scraper come with a documentation.

I will assist you in installing and configuring the scraper in your machine/server and run it together until you see data in the output file.
