# Curation Tagging Engine API 
## Endpoint
    POST http://52.19.189.170:3001/concepts
    
### Req Body
    articleUrl: [myUrl]
    
## Res Body
    {
        "title": "Islamophobic attacks in Manchester surge by 500% after arena attack",
        "content": "",
        "tags": [
            {
                "id": 2085,
                "name": "Black Swans",
                "type": "briefing",
                "score": 95
            },
            {
                "id": 4119,
                "name": "Manchester",
                "type": "regular",
                "score": 0.9999999977185325
            },
            {
                "id": 9225,
                "name": "Islamophobia",
                "type": "regular",
                "score": 1
            },
            {
                "id": 2583,
                "name": "London",
                "type": "regular",
                "score": 0.9999999911751729
            }
        ],
        "classification": {
            "classifier_id": "2d7aefx102-nlc-2947",
            "url": "https://gateway.watsonplatform.net/natural-language-classifier/api/v1/classifiers/2d7aefx102-nlc-2947",
            "text": "Islamophobic attacks in Manchester surge by 500% after arena attack",
            "top_class": "Black Swans",
            "classes": [
                {
                    "class_name": "Black Swans",
                    "confidence": 0.9544377704399475
                },
                {
                    "class_name": "Disruption in Property Markets",
                    "confidence": 0.011137817604168813
                },
                {
                    "class_name": "Disruptive Trends in China",
                    "confidence": 0.0054951157077630765
                },
                {
                    "class_name": "Digital Currency and Mobile Payments",
                    "confidence": 0.004694456805911281
                },
                {
                    "class_name": "Cyber Threats and Terror",
                    "confidence": 0.004447917031189841
                },
                {
                    "class_name": "AI, Robots & Drones",
                    "confidence": 0.0021810606658187476
                },
                {
                    "class_name": "Education Technology",
                    "confidence": 0.002139158771978472
                },
                {
                    "class_name": "Disruption in Financial Services",
                    "confidence": 0.0020030827969716477
                },
                {
                    "class_name": "The Sharing & On Demand Economies",
                    "confidence": 0.0018040807446795645
                },
                {
                    "class_name": "ESG",
                    "confidence": 0.0017141790121122267
                }
            ]
        },
        "source": {
            "options": {},
            "id": "4b2e7740-4f63-41c9-a183-0fc2ad22276a",
            "name": "the Guardian",
            "legalName": "theguardian.com",
            "domain": "theguardian.com",
            "domainAliases": [
                "theguardian.co.uk",
                "guardianunlimited.co.uk",
                "altiplano.be",
                "theguardian.info",
                "guardian.co.uk",
                "observer.co.uk",
                "altiplano.nl",
                "gmgplc.co.uk",
                "myguardianweekly.co.uk",
                "guardiangardencentre.co.uk",
                "guardianoffers.co.uk",
                "fotocopiagratis.com",
                "fotocopiagratis.it"
            ],
            "url": "https://www.theguardian.com/",
            "site": {
                "url": "http://theguardian.com",
                "title": "News, sport and opinion from the Guardian's US edition | The Guardian",
                "h1": "Trump threatens to prosecute over Manchester attack leaks",
                "metaDescription": "Latest US news, world news, sports, business, opinion, analysis and reviews from the Guardian, the world's leading liberal voice",
                "metaAuthor": null,
                "phoneNumbers": [],
                "emailAddresses": []
            },
            "category": {
                "sector": "Consumer Discretionary",
                "industryGroup": "Media",
                "industry": "Media",
                "subIndustry": "Publishing"
            },
            "tags": [
                "Publishing",
                "B2B",
                "Recruiting"
            ],
            "description": "Latest US news, world news, sports, business, opinion, analysis and reviews from the Guardian, the world's leading liberal voice",
            "foundedYear": 1821,
            "location": "Kings Place, 90 York Way, Kings Cross, London N1 9AG, UK",
            "timeZone": "Europe/London",
            "utcOffset": 1,
            "geo": {
                "streetNumber": "90",
                "streetName": "York Way",
                "subPremise": null,
                "city": "London",
                "postalCode": "N1 9AG",
                "state": "England",
                "stateCode": "England",
                "country": "United Kingdom",
                "countryCode": "GB",
                "lat": 51.5349511,
                "lng": -0.1221585
            },
            "logo": "https://logo.clearbit.com/theguardian.com",
            "facebook": {
                "handle": "guardianus",
                "likes": 684086
            },
            "linkedin": {
                "handle": "company/guardian-jobs"
            },
            "twitter": {
                "handle": "guardian",
                "id": "87818409",
                "bio": "The need for independent journalism has never been greater. Become a Guardian supporter: https://t.co/EWg9aqA7PQ",
                "followers": 6488593,
                "following": 1112,
                "location": "London",
                "site": "https://t.co/c53pnmnuIT",
                "avatar": "https://pbs.twimg.com/profile_images/822336375341125632/-PWnVYAF_normal.jpg"
            },
            "crunchbase": {
                "handle": "organization/the-guardian"
            },
            "emailProvider": false,
            "type": "private",
            "ticker": null,
            "phone": null,
            "metrics": {
                "alexaUsRank": 100,
                "alexaGlobalRank": 143,
                "googleRank": null,
                "employees": 5,
                "employeesRange": "1-10",
                "marketCap": null,
                "raised": 3000000,
                "annualRevenue": null
            },
            "indexedAt": "2017-05-29T19:51:08.010Z",
            "tech": [
                "youtube",
                "amazon_ses",
                "android",
                "google_apps",
                "double_click",
                "google_analytics",
                "ios",
                "dyn_dns"
            ]
        }
    }

## Tags API
    GET https://ptapi-test.curationcorp.com/api/tag
