### [Try it out today for free on Apify!](https://apify.com/radeance/ahrefs-scraper)

# 💎 Ahrefs SEO Scraper

![Ahrefs Scraper Cover Image](https://i.imgur.com/yjWggd1.png)
| Try our other scrapers ► | [Semrush SEO Scraper](https://apify.com/radeance/semrush-scraper) | [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper)| [Social Blade Scraper](https://apify.com/radeance/socialblade-api)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|


Welcome to this **Ahrefs Scraper** on **Apify**!<br><br>
This versatile & powerful scraper is designed to **effortlessly** extract comprehensive **SEO data** from **Ahrefs**. Whether you're an SEO professional, digital marketer, or competitive analyst, this scraper helps you uncover **detailed SEO insights** including, **keyword ideas**, **organic traffic data**, **keyword rankings**, **backlink profiles**, **SERP analysis**, **keyword difficulty scores**, website authority metrics, and **competitor intelligence**. Perfect for analyzing any domain or keyword across Ahrefs' entire suite, it provides **web traffic analytics**, top-performing pages, geographic traffic distribution, broken link opportunities, and much more across **180+ countries**.

One of its best features is its **accuracy** & **efficiency** while scraping thousands of SEO data points in minutes, giving you enterprise-level competitive intelligence from all major Ahrefs SEO tools in one go 💎

### [Try it out today for free on Apify!](https://apify.com/radeance/ahrefs-scraper)

## 🛫 Getting Started

1. Create a free Apify account if you don't have one already.
2. Go to our [Ahrefs Scraper](https://apify.com/radeance/ahrefs-scraper) page on Apify.
3. Click the "Try for free" button and start using the scraper.



## Key Features

-   **🔍 SEO Data Extraction:**
    <br>
    ✅ Scrapes comprehensive SEO data from Ahrefs with advanced filtering options
    <br>
    ✅ Extracts detailed information from keyword research, traffic analysis, and competitor insights **automatically**
    <br>
    ✅ Provides key metrics such as keyword difficulty, search volume, ranking positions, backlink profiles, and many many more.
    <br><br>
-   **🌐 Multi-Country Support:**
    <br>
    ✅ Scrapes data for multiple countries and regions
    <br><br>
-   **🔧 Advanced Customization:**
    <br>
    ✅ Allows setting specific URLs, domains, or keywords for targeted analysis
    <br>
    ✅ Easy to configure search modes for exact URLs or subdomain analysis
    <br>
    ✅ Flexible boolean options to include/exclude specific data types
    <br><br>
-   **📊 Flexible Data Output:**
    <br>
    ✅ Outputs data in various formats including CSV, XLSX, JSON, JSONL, XML, and RSS

## 🗂️ Use Cases

-   **SEO Specialists & Digital Marketers**: To gather detailed keyword data, traffic estimates, ranking positions, and competitor analysis for optimization strategies.
-   **Business Owners**: To find comprehensive SEO insights about their website performance, keyword opportunities, and competitor benchmarking.
-   **SEO Analysts**: To analyze **market trends** in search rankings, keyword difficulty, and industry competition patterns.
-   **Developers**: To integrate SEO data into applications for better website optimization and competitive analysis tools.

It essentially streamlines the process of collecting and analysing SEO analytics data, making it a valuable tool for a variety of professionals.

## 📌 Output

### Top Websites Ranking Search

##### `Requires Top Website Category and Top Website Country`

```json
{
  "data_captured_at": "2025-08-06T18:59:28.353316",
  "type": "top_websites",
  "country": "us",
  "top_websites_category": "all",
  "websites_rankings": [
    {
      "rank": 1,
      "categories": [
        "Reference"
      ],
      "rankLastMonth": null,
      "domain": "wikipedia.org",
      "traffic": 5092778148,
      "trafficLastMonth": 5049115293,
      "trafficChange": 43662855,
      "rankChange": null
    },
    {
      "rank": 2,
      "categories": [
        "Arts_and_Entertainment"
      ],
      "rankLastMonth": null,
      "domain": "youtube.com",
      "traffic": 4118279279,
      "trafficLastMonth": 3795747485,
      "trafficChange": 322531794,
      "rankChange": null
    },
    {
      "rank": 3,
      "categories": [
        "Online_Communities"
      ],
      "rankLastMonth": 4,
      "domain": "instagram.com",
      "traffic": 1545765744,
      "trafficLastMonth": 1504738264,
      "trafficChange": 41027480,
      "rankChange": -1
    },
    ...
    {
      "rank": 998,
      "categories": [
        "Reference"
      ],
      "rankLastMonth": 917,
      "domain": "wordreference.com",
      "traffic": 8303244,
      "trafficLastMonth": 9082168,
      "trafficChange": -778924,
      "rankChange": 81
    },
    {
      "rank": 999,
      "categories": [
        "Arts_and_Entertainment"
      ],
      "rankLastMonth": 1098,
      "domain": "deezer.com",
      "traffic": 8301348,
      "trafficLastMonth": 7525104,
      "trafficChange": 776244,
      "rankChange": -99
    },
    {
      "rank": 1000,
      "categories": [
        "Shopping"
      ],
      "rankLastMonth": 999,
      "domain": "markt.de",
      "traffic": 8295974,
      "trafficLastMonth": 8265520,
      "trafficChange": 30454,
      "rankChange": 1
    }
  ],
  "website_rankings_trending_up": [
    {
      "rank": 988,
      "categories": [
        "Health"
      ],
      "rankLastMonth": 429,
      "domain": "cancer.gov",
      "traffic": 8379885,
      "trafficLastMonth": 17126987,
      "trafficChange": -8747102,
      "rankChange": 559
    },
    {
      "rank": 888,
      "categories": [
        "Health"
      ],
      "rankLastMonth": 337,
      "domain": "suckhoedoisong.vn",
      "traffic": 9235287,
      "trafficLastMonth": 20684540,
      "trafficChange": -11449253,
      "rankChange": 551
    },
    ...
  ],
  "website_rankings_trending_down": [
    {
      "rank": 192,
      "categories": [
        "Science"
      ],
      "rankLastMonth": 765,
      "domain": "imd.gov.in",
      "traffic": 32283770,
      "trafficLastMonth": 10601482,
      "trafficChange": 21682288,
      "rankChange": -573
    },
    {
      "rank": 317,
      "categories": [
        "Internet_and_Telecom"
      ],
      "rankLastMonth": 844,
      "domain": "linktr.ee",
      "traffic": 21322705,
      "trafficLastMonth": 9776925,
      "trafficChange": 11545780,
      "rankChange": -527
    },
    ...
  ],
  "website_rankings_last_updated": "2025-08-01T00:00:00Z"
}
```

### Competitors

##### `Requires Domain or URL`

```json
{
    "data_captured_at": "2025-08-06T18:59:22.117374",
    "type": "competitors",
    "domain": "make.com",
    "competitors": [
        {
            "domain": "n8n.io",
            "keywords_competitor": 119105,
            "keywords_common": 28434,
            "keywords_common_percent": 11.8,
            "keywords_target": 92810,
            "domain_rating": 80.0,
            "traffic": 876320,
            "cost": 158746,
            "pages": 15562,
            "country": "us",
            "traffic_last_month": 732538,
            "cost_last_month": 141425,
            "rank": null,
            "rank_last_month": null,
            "top_country": null,
            "top_country_rank": null,
            "top_country_rank_last_month": null,
            "top_category": null,
            "top_category_rank": null,
            "top_category_rank_last_month": null,
            "title": "n8n - FairCode Licensed Workflow Automation Tool",
            "description": "n8n.io is an open-source workflow automation tool that empowers users to connect their favorite apps and automate tasks without any coding knowledge. With its intuitive interface, n8n makes it easy to design complex workflows by integrating over 200 different services, enabling seamless data transfer and efficient operations. Perfect for businesses of all sizes, n8n allows users to streamline processes, save time, and enhance productivity by automating repetitive tasks and creating custom workflows tailored to their unique needs. Explore the endless possibilities of automation with n8n and unlock the potential of your workflow.",
            "is_linkeable": true,
            "traffic_change": 143782,
            "cost_change": 17321,
            "top_country_rank_change": null,
            "top_category_rank_change": null
        },
        ...
    ]
}
```

### Website Traffic

##### `Requires Domain or URL`

```json
{
  "data_captured_at": "2025-08-06T19:00:05.137304",
  "type": "traffic",
  "domain": "make.com",
  "mode": "subdomains",
  "website_overall_search_traffic": 223859,
  "website_overall_search_traffic_last_month": 267840,
  "website_overall_search_traffic_history": [
    {
      "date": "2015-06-01",
      "traffic": 19
    },
    {
      "date": "2015-07-01",
      "traffic": 0
    },
    {
      "date": "2015-08-01",
      "traffic": 0
    },
    ...
    {
      "date": "2025-06-01",
      "traffic": 257228
    },
    {
      "date": "2025-07-01",
      "traffic": 267840
    },
    {
      "date": "2025-08-01",
      "traffic": 223859
    }
  ],
  "website_overall_search_traffic_value": 152306,
  "website_overall_search_traffic_value_last_month": 155123,
  "website_overall_search_traffic_value_history": [
    {
      "date": "2015-06-01",
      "value": 1
    },
    {
      "date": "2015-07-01",
      "value": 0
    },
    {
      "date": "2015-08-01",
      "value": 0
    },
    ...
    {
      "date": "2025-06-01",
      "value": 161892
    },
    {
      "date": "2025-07-01",
      "value": 155123
    },
    {
      "date": "2025-08-01",
      "value": 152306
    }
  ],
  "website_traffic": {
    "trafficMonthlyAvg": 222128,
    "costMontlyAvg": 14564104
  },
  "website_traffic_history": [
    {
      "date": "2025-03-01",
      "organic": 740235
    },
    {
      "date": "2025-04-01",
      "organic": 291553
    },
    {
      "date": "2025-05-01",
      "organic": 265063
    },
    ...
  ],
  "website_overall_search_traffic_by_country": [
    {
      "country": "US",
      "traffic": 77988,
      "trafficLastMonth": 80630,
      "trafficShare": 0.348
    },
    {
      "country": "IN",
      "traffic": 48938,
      "trafficLastMonth": 82564,
      "trafficShare": 0.218
    },
    {
      "country": "GB",
      "traffic": 10224,
      "trafficLastMonth": 11205,
      "trafficShare": 0.045
    },
    ...
  ],
  "website_traffic_by_country": [
    {
      "country": "us",
      "share": 33.24721157239933,
      "monthly_traffic": [
        {
          "date": "2025-03-01",
          "organic": 246108
        },
        {
          "date": "2025-04-01",
          "organic": 96934
        },
        {
          "date": "2025-05-01",
          "organic": 88127
        },
        ...
      ]
    },
    ...
  ],
  "website_traffic_top_pages": [
    {
      "url": "https://www.make.com/en",
      "traffic": 21553,
      "share": 29.96802002224694
    },
    {
      "url": "https://apps.make.com/clio-manage",
      "traffic": 2239,
      "share": 3.113181312569522
    },
    {
      "url": "https://www.make.com/en/ai-automation",
      "traffic": 2142,
      "share": 2.978309232480534
    },
    ...
  ],
  "website_traffic_top_countries": [
    {
      "country": "us",
      "share": 33.24721157239933
    },
    {
      "country": "in",
      "share": 22.578196133631774
    },
    {
      "country": "gb",
      "share": 4.560913183005722
    },
    ...
  ],
  "website_overall_search_traffic_keywords": [
    {
      "keyword": "chat gpt 4",
      "position": 7,
      "positionLastMonth": 13,
      "volume": 391000.0,
      "volumeLastMonth": 379000.0,
      "traffic": 18811.637,
      "trafficLastMonth": 5571.0034
    },
    {
      "keyword": "make",
      "position": 2,
      "positionLastMonth": 2,
      "volume": 58000.0,
      "volumeLastMonth": 59000.0,
      "traffic": 6299.521,
      "trafficLastMonth": 6100.912
    },
    {
      "keyword": "tiktok login",
      "position": 12,
      "positionLastMonth": 0,
      "volume": 230000.0,
      "volumeLastMonth": 0.0,
      "traffic": 5244.613,
      "trafficLastMonth": 0.0
    },
    ...
  ],
  "website_traffic_top_keywords": [
    {
      "keyword": "make",
      "position": 1,
      "traffic": 62000
    },
    {
      "keyword": "clio manage login",
      "position": 6,
      "traffic": 20000
    },
    {
      "keyword": "integromat",
      "position": 1,
      "traffic": 2000
    },
    ...
  ]
}
```

### Backlinks Search

##### `Requires Domain or URL`

```json
{
  "data_captured_at": "2025-08-06T18:59:30.172809",
  "type": "backlinks",
  "domain": "make.com",
  "mode": "subdomains",
  "backlink_check": {
    "domainRating": 86.0,
    "urlRating": 41,
    "backlinks": 1362606,
    "refdomains": 20529,
    "dofollowBacklinks": 96,
    "dofollowRefdomains": 87
  },
  "top_backlinks": [
    {
      "anchor": "Make",
      "domainRating": 88,
      "edu": false,
      "gov": false,
      "httpCode": 200,
      "redirectChain": [],
      "text": true,
      "textPost": "?",
      "textPre": "programming interfaces (APIs), or via third-party tools like Zapier or",
      "title": "Best POS System For Small Businesses (2025) | CO- by US Chamber of Commerce",
      "urlFrom": "https://www.uschamber.com/co/run/technology/pos-systems-for-small-businesses",
      "urlTo": "https://www.make.com/en",
      "inRendered": true,
      "inRaw": true,
      "redirectCode": 0,
      "original": true,
      "urlToMustBeGray": false,
      "urlToHttpCodeCross": false,
      "urlToNew": "None",
      "urlToChainDestinationChanged": false,
      "urlToDelReasonTitle": "None",
      "urlToDelReasonKey": "None",
      "urlToHasDelReason": false,
      "lost_redirect_reason": "",
      "del_reason": "",
      "lost_redirect_source": "",
      "lost_redirect_new_target": "",
      "isLost": true
    },
    {
      "anchor": "",
      "domainRating": 43,
      "edu": false,
      "gov": false,
      "httpCode": 200,
      "redirectChain": [
        {
          "url": "https://www.make.com/en/partners-directory",
          "urlNew": "None",
          "redirectCode": 301,
          "mustBeGray": false,
          "httpCodeCross": false,
          "chainDestinationChanged": false,
          "hasDelReason": false,
          "delReasonTitle": "None",
          "delReasonKey": "None",
          "lostRedirectReason": "None",
          "isLost": true
        },
        ...
      ],
      "text": false,
      "textPost": "",
      "textPre": "",
      "title": "DeepL Write - Meine Erfahrung & Alternativen",
      "urlFrom": "https://jens.marketing/tool/deepl-write/",
      "urlTo": "https://www.make.com/en",
      "inRendered": false,
      "inRaw": true,
      "redirectCode": 0,
      "original": true,
      "urlToMustBeGray": false,
      "urlToHttpCodeCross": false,
      "urlToNew": "None",
      "urlToChainDestinationChanged": false,
      "urlToDelReasonTitle": "None",
      "urlToDelReasonKey": "None",
      "urlToHasDelReason": false,
      "lost_redirect_reason": "",
      "del_reason": "",
      "lost_redirect_source": "",
      "lost_redirect_new_target": "",
      "isLost": true
    },
  ],
  "top_backlinks_count": 20,
  "referal_domains_overall": 15415,
  "referal_domains_overall_last_month": 15356,
  "referal_domains_history": [
    {
      "date": "2015-04-01",
      "count": 57
    },
    {
      "date": "2015-05-01",
      "count": 58
    },
    {
      "date": "2015-06-01",
      "count": 59
    },
    ...
    {
      "date": "2025-05-01",
      "count": 14504
    },
    {
      "date": "2025-06-01",
      "count": 15356
    },
    {
      "date": "2025-07-01",
      "count": 15415
    }
  ]
}
```

### Broken Links Search

##### `Requires Domain or URL`

```json
{
  "data_captured_at": "2025-08-06T18:59:30.251179",
  "type": "broken_links",
  "domain": "make.com",
  "mode": "subdomains",
  "broken_links_inbound": [
    {
      "ahrefsRank": 26,
      "alternate": false,
      "content": true,
      "anchor": "Make’s visual scenario builder",
      "canonical": false,
      "domainRating": 91,
      "edu": false,
      "gov": false,
      "httpCode": 404,
      "image": false,
      "language": "en",
      "dofollow": true,
      "nofollow": false,
      "poweredBy": [
        "wordpress"
      ],
      "redirect": false,
      "redirectChain": [],
      "rss": false,
      "text": true,
      "textPost": ".",
      "textPre": "Start with Zapier’s template library or",
      "title": "13 Technical Marketing Skills You Can Learn (Even If You’re Not Technical)",
      "urlFrom": "https://ahrefs.com/blog/technical-marketing-skills/",
      "urlTo": "https://www.make.com/en/features/scenarios",
      "inRendered": true,
      "inRaw": true,
      "refdomains": 37,
      "traffic": 9.705375,
      "redirectCode": 0,
      "original": true,
      "ugc": false,
      "sponsored": false,
      "urlToMustBeGray": false,
      "urlToHttpCodeCross": false,
      "urlToNew": "None",
      "urlToChainDestinationChanged": false,
      "urlToDelReasonTitle": "None",
      "urlToDelReasonKey": "None",
      "urlToHasDelReason": false,
      "lost_redirect_reason": "",
      "del_reason": "",
      "lost_redirect_source": "",
      "lost_redirect_new_target": "",
      "isLost": true,
      "failure": ""
    },
  ],
  "broken_links_total_backlinks": 3822,
  "broken_links_dofollow_backlinks": 89,
  "broken_links_outbound": [
    {
      "ahrefsRank": 17,
      "linksInternal": 57,
      "linksExternal": 24,
      "urlFrom": "https://www.make.com/en/how-to-guides/how-to-make-an-api-call-tutorial",
      "title": "How to Make an API Call With Make [Tutorial] | Make",
      "alternate": false,
      "canonical": false,
      "dofollow": true,
      "nofollow": false,
      "image": false,
      "redirect": false,
      "rss": false,
      "text": true,
      "edu": false,
      "gov": false,
      "ugc": false,
      "all": true,
      "sponsored": false,
      "links": [
        {
          "urlTo": "https://shopify.dev/docs/api/admin/rest/reference/products/product",
          "textPost": "to perform this action:",
          "textPre": "to retrieve a count of products. Naturally, there is an",
          "anchor": "available Shopify API endpoint",
          "httpCode": 404,
          "redirectCode": 0,
          "alternate": false,
          "canonical": false,
          "dofollow": true,
          "nofollow": false,
          "image": false,
          "redirect": false,
          "rss": false,
          "text": true,
          "original": true,
          "edu": false,
          "gov": false,
          "alt": "",
          "ugc": false,
          "all": true,
          "sponsored": false,
          "failure": ""
        },
        ...
      ]
    },
    ...
  ],
  "brokeen_links_outbound_total_links": 45,
  "broken_links_outbound_dofollow_link": 87
}
```

### Keyword Ideas Search

##### `Requires Keyword and Country`

```json
{
  "data_captured_at": "2025-08-06T18:59:31.293839",
  "type": "keywords",
  "keyword": "ai developer",
  "country": "us",
  "keyword_ideas": [
    {
      "id": "9c71299a29a0d176ea32b43f1ea9ef36-us",
      "keyword": "ai developer",
      "country": "us",
      "difficultyLabel": "Medium",
      "volumeLabel": "MoreThanOneThousand",
      "updatedAt": "2025-07-30T13:54:16Z",
      "volume": 1000.0
    },
    ...
  ],
  "keyword_ideas_count": 1207,
  "keyword_ideas_questions": [
    {
      "id": "5b630aae26bcae43c2f6b967a0e91492-us",
      "keyword": "how to become an ai developer",
      "country": "us",
      "difficultyLabel": "Easy",
      "volumeLabel": "MoreThanOneHundred",
      "updatedAt": "2025-06-28T03:21:44Z",
      "volume": 100.0
    },
    ...
  ],
  "keyword_ideas_questions_count": 104
}
```

### Keyword Ranking Search

##### `Requires Keyword, Domain or URL, Country`

```json
{
  "data_captured_at": "2025-08-06T18:59:44.995913",
  "type": "ranking",
  "keyword": "ai developer",
  "domain": "make.com",
  "country": "us",
  "mode": "subdomains",
  "keyword_ranking_results": [
    {
      "content": [
        {
          "content_type": "ai_overview",
          "data": {
            "title": null,
            "description": "An artificial intelligence (AI) developer is a professional who designs, builds, and implements AI models and algorithms to solve complex problems .  They work with various technologies, including machine learning, deep learning, and data science, to create applications like chatbots, recommendation systems, and automation tools.  AI developers require strong programming skills, particularly in languages like Python, as well as expertise in machine learning frameworks such as TensorFlow or PyTorch.  \nKey Responsibilities:\nDesigning and Implementing AI Models:  . Opens in new tab AI developers create the core algorithms and structures that power AI applications.  ",
            "attribute": "Thumbnail",
            "site_links": [
              {
                "title": "6 Steps to Becoming an Artificial Intelligence Developer [ + Salary]",
                "url": {
                  "url": "https://onlinedegrees.sandiego.edu/artificial-intelligence-developer-career/"
                },
                "attribute": "Thumbnail",
                "is_target": null
              },
              {
                "title": "Becoming an AI Developer: Skills, Projects, and Career Paths - Upwork",
                "url": {
                  "url": "https://www.upwork.com/resources/how-to-become-ai-developer"
                },
                "attribute": "Thumbnail",
                "is_target": null
              },
              {
                "title": "How to Become an AI Developer: Career Guide and Roadmaps",
                "url": {
                  "url": "https://www.netcomlearning.com/blog/how-to-become-an-ai-developer"
                },
                "attribute": "Thumbnail",
                "is_target": null
              }
            ]
          }
        }
      ],
      "pos": 1,
      "pos_with_metrics": null
    },
    {
      "content": [
        {
          "content_type": "organic",
          "data": {
            "link": {
              "title": "What is an AI Developer? | IBM",
              "url": {
                "url": "https://www.ibm.com/think/topics/ai-developer"
              },
              "attribute": null,
              "is_target": null,
              "metrics": {
                "rank": 298,
                "domain_rating": null,
                "url_rating": null,
                "refpages": 7,
                "domains": 5,
                "traffic": 1098,
                "cost": 366914,
                "keywords": 40,
                "top_keyword": null,
                "top_volume": null,
                "nr_words": null,
                "http_code": null
              }
            },
            "site_links": [
              {
                "title": "What is an AI developer?",
                "url": {
                  "url": "https://www.ibm.com/think/topics/ai-developer#What+is+an+AI+developer%3F"
                },
                "attribute": null,
                "is_target": null
              },
              {
                "title": "skills needed to be an AI...",
                "url": {
                  "url": "https://www.ibm.com/think/topics/ai-developer#7+skills+needed+to+be+an+AI+developer"
                },
                "attribute": null,
                "is_target": null
              }
            ]
          }
        }
      ],
      "pos": 2,
      "pos_with_metrics": null
    },
    ...
  ]
}
```

### Keyword Difficulty Search

##### `Requires Keyword, Country`

```json
{
  "data_captured_at": "2025-08-06T18:59:28.399375",
  "type": "keyword_difficulty",
  "keyword": "ai developer",
  "country": "us",
  "keyword_difficulty": 20,
  "keyword_difficulty_results": [
    {
      "content_type": "ai_overview",
      "data": {
        "title": null,
        "description": "An artificial intelligence (AI) developer is a professional who designs, builds, and implements AI models and algorithms to solve complex problems .  They work with various technologies, including machine learning, deep learning, and data science, to create applications like chatbots, recommendation systems, and automation tools.  AI developers require strong programming skills, particularly in languages like Python, as well as expertise in machine learning frameworks such as TensorFlow or PyTorch.  \nKey Responsibilities:\nDesigning and Implementing AI Models:  . Opens in new tab AI developers create the core algorithms and structures that power AI applications.  ",
        "attribute": "Thumbnail",
        "site_links": [
          {
            "title": "6 Steps to Becoming an Artificial Intelligence Developer [ + Salary]",
            "url": {
              "url": "https://onlinedegrees.sandiego.edu/artificial-intelligence-developer-career/"
            },
            "attribute": "Thumbnail",
            "is_target": null
          },
          {
            "title": "Becoming an AI Developer: Skills, Projects, and Career Paths - Upwork",
            "url": {
              "url": "https://www.upwork.com/resources/how-to-become-ai-developer"
            },
            "attribute": "Thumbnail",
            "is_target": null
          },
          {
            "title": "How to Become an AI Developer: Career Guide and Roadmaps",
            "url": {
              "url": "https://www.netcomlearning.com/blog/how-to-become-an-ai-developer"
            },
            "attribute": "Thumbnail",
            "is_target": null
          }
        ]
      },
      "pos": 1,
      "pos_with_metrics": null
    },
    {
      "content_type": "organic",
      "data": {
        "link": {
          "title": "What is an AI Developer? | IBM",
          "url": {
            "url": "https://www.ibm.com/think/topics/ai-developer"
          },
          "attribute": null,
          "is_target": null,
          "metrics": {
            "rank": 298,
            "domain_rating": null,
            "url_rating": null,
            "refpages": 7,
            "domains": 5,
            "traffic": 1098,
            "cost": 366914,
            "keywords": 40,
            "top_keyword": null,
            "top_volume": null,
            "nr_words": null,
            "http_code": null
          }
        },
        "site_links": [
          {
            "title": "What is an AI developer?",
            "url": {
              "url": "https://www.ibm.com/think/topics/ai-developer#What+is+an+AI+developer%3F"
            },
            "attribute": null,
            "is_target": null
          },
          {
            "title": "skills needed to be an AI...",
            "url": {
              "url": "https://www.ibm.com/think/topics/ai-developer#7+skills+needed+to+be+an+AI+developer"
            },
            "attribute": null,
            "is_target": null
          }
        ]
      },
      "pos": 2,
      "pos_with_metrics": null
    },
    ...
  ],
  "keyword_difficulty_source": "Serps",
  "keyword_difficulty_shortage": 22
}
```

### Website Overview / Authority Search

##### `Requires Domain or URL`

```json
{
    "data_captured_at": "2025-08-06T18:59:30.803538",
    "type": "authority",
    "domain": "make.com",
    "mode": "subdomains",
    "website_authority": {
        "domainRating": 86.0,
        "urlRating": 41,
        "backlinks": 1362479,
        "refdomains": 20511,
        "dofollowBacklinks": 96,
        "dofollowRefdomains": 87,
        "domainRatingLastMonth": 85.0,
        "isNsfw": false
    }
}
```

### SERP Search

##### `Requires Keyword, Country`

```json
{
    "data_captured_at": "2025-08-06T18:59:36.848068",
    "type": "serp",
    "keyword": "ai developer",
    "country": "us",
    "serp_results": [
        {
            "content_type": "ai_overview",
            "data": {
                "title": null,
                "description": "An artificial intelligence (AI) developer is a professional who designs, builds, and implements AI models and algorithms to solve complex problems .  They work with various technologies, including machine learning, deep learning, and data science, to create applications like chatbots, recommendation systems, and automation tools.  AI developers require strong programming skills, particularly in languages like Python, as well as expertise in machine learning frameworks such as TensorFlow or PyTorch.  \nKey Responsibilities:\nDesigning and Implementing AI Models:  . Opens in new tab AI developers create the core algorithms and structures that power AI applications.  ",
                "attribute": "Thumbnail",
                "site_links": [
                    {
                        "title": "6 Steps to Becoming an Artificial Intelligence Developer [ + Salary]",
                        "url": {
                            "url": "https://onlinedegrees.sandiego.edu/artificial-intelligence-developer-career/",
                            "input": {
                                "mode": "exact",
                                "protocol": "https",
                                "protocolless_url": "onlinedegrees.sandiego.edu/artificial-intelligence-developer-career/",
                                "signature_info": {
                                    "not_after": "2025-08-08T16:59:36Z",
                                    "signature": "R3A+UGWItpwGp0+SxAjE1yHIqJX4OxEqGo+m4jUxemE="
                                }
                            }
                        },
                        "attribute": "Thumbnail",
                        "is_target": null
                    },
                    {
                        "title": "Becoming an AI Developer: Skills, Projects, and Career Paths - Upwork",
                        "url": {
                            "url": "https://www.upwork.com/resources/how-to-become-ai-developer",
                            "input": {
                                "mode": "exact",
                                "protocol": "https",
                                "protocolless_url": "www.upwork.com/resources/how-to-become-ai-developer",
                                "signature_info": {
                                    "not_after": "2025-08-08T16:59:36Z",
                                    "signature": "bmeCHhVqdrJc0A30okOOd/mJDMidgrxOXOEZ8fy38CI="
                                }
                            }
                        },
                        "attribute": "Thumbnail",
                        "is_target": null
                    },
                    {
                        "title": "How to Become an AI Developer: Career Guide and Roadmaps",
                        "url": {
                            "url": "https://www.netcomlearning.com/blog/how-to-become-an-ai-developer",
                            "input": {
                                "mode": "exact",
                                "protocol": "https",
                                "protocolless_url": "www.netcomlearning.com/blog/how-to-become-an-ai-developer",
                                "signature_info": {
                                    "not_after": "2025-08-08T16:59:36Z",
                                    "signature": "jV9Q31XyxRELJhovffvOV/xznMcUw78u9DGSEyf4CHw="
                                }
                            }
                        },
                        "attribute": "Thumbnail",
                        "is_target": null
                    }
                ]
            },
            "pos": 1,
            "pos_with_metrics": null
        }
    ],
    "serp_source": "Serps",
    "serp_last_updated": "2025-07-30T13:54:16Z"
}
```

## 📍 Input

### Ahrefs Search Parameters

![Scraper Sample Input](https://i.imgur.com/KBzbZzb.png)
<br><br> - **`keyword`**: (Optional) (String)
The keyword to search for on Ahrefs. Enter any keyword or phrase you want to analyze for SEO metrics and competitor insights (e.g. ai automation).
<br><br> - **`url`**: (Optional) (String)
The URL or Domain of the web page to search for on Ahrefs. Enter a complete URL or just the domain name to analyze (e.g. make.com).
<br><br> - **`country`**: (Optional) (String)
Select the country for the search on Ahrefs. This determines the geographical location for search results and keyword data.
💡 Default value is `us` (United States).
<br><br> - **`mode`**: (Optional) (String)
Select the mode for the search on Ahrefs. Choose "exact" to analyze only the specific URL provided, or "subdomains" to include all subdomains of the target domain.
Exact would just analyze the exact provided URL where as subdomains would include wildcard subdomains like `*.make.com/*`.
💡 Default value is `subdomains`.
<br><br> - **`include_traffic`**: (Optional) (Boolean)
If set to True, the search will include web-traffic data from Ahrefs showing organic search traffic estimates, top pages, and traffic trends.
💡 Default value is True.
<br><br> - **`include_keywords`**: (Optional) (Boolean)
If set to True, the search will include keywords data from Ahrefs showing which keywords the target domain ranks for.
💡 Default value is False.
<br><br> - **`include_keywords_difficulty`**: (Optional) (Boolean)
If set to True, the search will include keywords difficulty data from Ahrefs showing the competitive difficulty score for ranking keywords.
💡 Default value is False.
<br><br> - **`include_keywords_ranking`**: (Optional) (Boolean)
If set to True, the search will include keywords ranking data from Ahrefs showing current ranking positions for target keywords.
💡 Default value is False.
<br><br> - **`include_serp`**: (Optional) (Boolean)
If set to True, the search will include SERP (Search Engine Results Page) data from Ahrefs showing competitor analysis and ranking positions.
💡 Default value is False.
<br><br> - **`include_backlinks`**: (Optional) (Boolean)
If set to True, the search will include backlinks data from Ahrefs showing referring domains, link quality metrics, and backlink profiles.
💡 Default value is True.
<br><br> - **`include_broken_links`**: (Optional) (Boolean)
If set to True, the search will include broken links data from Ahrefs identifying dead links and 404 errors on the target domain.
💡 Default value is False.
<br><br> - **`include_web_authority`**: (Optional) (Boolean)
If set to True, the search will include website authority data from Ahrefs showing domain rating, URL rating, and other authority metrics.
💡 Default value is True.
<br><br> - **`include_competitors`**: (Optional) (Boolean)
If set to True, the search will include competitors data from Ahrefs showing direct competitors for the target domain, their rankings, and traffic metrics.
💡 Default value is False
<br><br> - **`include_top_websites`**: (Optional) (Boolean)
If set to True, the search will include top websites data from Ahrefs showing the top 1000 websites worldwide or 100 websites (when filtered) for a specific category or country.
💡 Default value is False
<br><br> - **`category_top_websites`**: (Optional) (String)
The category for the top websites search on Ahrefs. Choose from `all`, `business`, `arts-and-entertainment`, `health`, `news` and many more to filter.
💡 Default value is `all`.
<br><br> - **`country_top_websites`**: (Optional) (String)
The country for the top websites search on Ahrefs. Choose from `worldwide`, `us`, `uk`, `de`, `fr`, `jp`, `br`, `ru` and many more to filter.
💡 Default value is `worldwide`.

![Scraper Bulk Input](https://i.imgur.com/lnaCoUZ.png)

<br> - **`urls`**: (Optional) (Array of Strings)
The URLs or Domains of the web pages to search for on Ahrefs. Enter a list of complete URLs or just domain names to analyze multiple targets at once (e.g. ["make.com", "example.com"]).

### Supported URL Formats

| Link                                                                                                         | Supported |
| ------------------------------------------------------------------------------------------------------------ | --------- |
| [https://blog.apify.com/how-to-scrape-google-reviews/](https://blog.apify.com/how-to-scrape-google-reviews/) | ✅        |
| [https://www.n8n.io](https://www.make.com)                                                                   | ✅        |
| [https://make.com](https://make.com)                                                                         | ✅        |
| [pipedream.com](pipedream.com)                                                                               | ✅        |

### JSON Input

Sample JSON input if you use the apify api via CURL, Python, JS etc.

```json
{
    "keyword": "ai automation",
    "mode": "subdomains",
    "urls": ["https://make.com"],
    "include_backlinks": false,
    "include_broken_links": false,
    "include_keywords": true,
    "include_keywords_difficulty": false,
    "include_keywords_ranking": false,
    "include_serp": false,
    "include_traffic": true,
    "include_web_authority": false,
    "include_competitors": false,
    "include_top_websites": false,
    "category_top_websites": "all",
    "country_top_websites": "worldwide"
}
```

## Available Search Types

Each run can include up to 10 different search types:

-   `traffic` - Traffic analysis data
-   `keywords` - Keyword research
-   `keyword_difficulty` - Keyword difficulty metrics
-   `ranking` - Keyword ranking positions
-   `serp` - Search engine results pages
-   `backlinks` - Backlink analysis
-   `broken_links` - Broken link detection
-   `authority` - Domain authority metrics
-   `competitors` - Direct competitor websites data
-   `top_websites` - Top 1000 / 100 websites worldwide or in a specific category and country

## Usage Limits

This service has different usage limits depending on your subscription status:

| User Type | Monthly Runs | # Bulk URLs Supported | Data Limitations | Search Types per Run | Reset Period |
| --------- | ------------ | --------------------- | ---------------- | -------------------- | ------------ |
| **Free**  | 10 runs      | 3 per run             | All-Data-Access  | Up to 3 types        | 30 days      |
| **Paid**  | Unlimited    | Unlimited per run     | All-Data-Access  | Up to 10 types       | N/A          |

### How Limits Work

-   **Free users**: Limited to 5 runs per 30-day period from your first usage
-   **Paid users**: No limits on the number of runs and access to all data
-   **All users**: Can select any combination of the 10 search types in a single run
-   Usage resets automatically 30 days after your first run (for free users)

## ⚙️ While the scraper is running

During the run, the actor will output log messages letting you know what is going on at any point. Each message always contains specific information about the process including which url / page the actor is working on.

If you provide invalid inputs to the actor, it will immediately stop with a failure state and output log messages explaining what is wrong. If you are unsure what went wrong feel free to open up an issue in the issue tab.

## 🔗 Legality of web scraping and scraping of job listings

The **Ahrefs Scraper** is designed to ethically extract **only publicly available SEO data and information**, and it **does not** scrape private user data such as personal email addresses or personal identifiers.

Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. However, you should be aware that your results could contain personal data. Personal data is protected by the GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read this [blog post](https://blog.apify.com/is-web-scraping-legal/) on the legality of web scraping.

## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the Ahrefs Scraper, please create an issue in the Actor’s Issues tab on the Apify Console.

You can also contact us directly for custom integrations or project use cases at business@radeance.com.

### [Try it out today for free on Apify!](https://apify.com/radeance/ahrefs-scraper)