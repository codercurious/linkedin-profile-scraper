# Linkedin profile scraper
Interested in using this scraper? Get it here: [Linkedin profile scraper](https://apify.com/curious_coder/linkedin-profile-scraper)
## How it works

This actor works on a logged in linkedin account, but doesn't require login details or 2FA as it does't login but uses already generated linkedin session information.

You need to pass linkedin cookies to this actor to use the existing session to access search results page and perform scraping.

You can customise and randomise the delay between scraping pages.

## Getting Started

Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 

Login to your linkedin account

Click on the extension and export the linkedin cookies

Paste the cookies into this actor's `Linkedin cookie` input field

Go to [linkedin people search page](https://www.linkedin.com/search/results/people), search with required filters and once you are done, copy the full URL from address bar and pass it to this actor

Copy the link from address bar and paste it to actor `Search URL` input field

Enter start page and end page based on your requirements. You can access up to max 1000 results per search. 

Here is the sample output of this actor:

```json
{
	"firstName": "Asha",
	"lastName": "Shenoy",
	"occupation": "Software Engineer at Sony India Software Centre",
	"id": "705147666",
	"publicId": "asha-shenoy-69619b178",
	"trackingId": "aKjL/4EvRrSuangTvnxFMA==",
	"profileId": "ACoAACoHsxIBxR4EULHUDX6qSW8PPahnBI-MsTc",
	"picture": "https://media.licdn.com/dms/image/D5603AQE9x9x5JKQQCQ/profile-displayphoto-shrink_100_100/0/1672939179577?e=1698883200&v=beta&t=XIJ_-k9w53XtHXqLW9C7Ua07tYz5qrt7CYCpnZfroVw",
	"country": "India",
	"location": "Karnataka",
	"industry": "Computer Software",
	"headline": "Software Engineer at Sony India Software Centre",
	"summary": "Graduate in Computer science and engineering. Keen to develop my technical skills by working on some of the cutting-edge technologies. My fields of interest include  Web development and Cloud computing. Enthusiastic, hard-working and a quick learner.",
	"student": false,
	"jobtitle": "Software Engineer",
	"companyIndustries": [
		"Information Technology and Services"
	],
	"companyName": "Sony India Software Centre",
	"companyId": "13359478",
	"companyShortName": "sonyindiasoftwarecentre",
	"distance": ""
}
```
