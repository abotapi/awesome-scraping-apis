<div align="center">

# Awesome Scraping APIs

<strong>Every way to get web data, in one list: official APIs, open datasets, scraping libraries, hosted platforms and ready-made scrapers.</strong>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Last Update](https://img.shields.io/github/last-commit/abotapi/awesome-scraping-apis?label=Last%20update&style=flat-square)

</div>

Before you write a scraper, check whether the data is already available. The cheapest data is an **official API** or an **open dataset**.
If there isn't one, pick a **library** to build your own, a **hosted platform** to run it, or a **ready-made scraper** that already handles
pagination, blocking and cleanup. This list is organized in that order.

## Table of Contents

- [Official APIs](#official-apis)
- [Open Datasets](#open-datasets)
- [Scraping Libraries](#scraping-libraries)
- [Content Extraction & AI Crawlers](#content-extraction--ai-crawlers)
- [Hosted Scraping Platforms](#hosted-scraping-platforms)
- [Ready-Made Scrapers](#ready-made-scrapers)
- [Working with the Data](#working-with-the-data)
- [Legal & Etiquette](#legal--etiquette)
- [Learning](#learning)
- [Related Lists](#related-lists)

## Official APIs

Use these first: stable, documented, and allowed.

- **[Reddit API](https://www.reddit.com/dev/api/)** - Posts, comments and subreddits (OAuth, rate-limited)
- **[YouTube Data API](https://developers.google.com/youtube/v3)** - Videos, channels, playlists and comments
- **[X API](https://docs.x.com/x-api/introduction)** - Posts, users and search (paid tiers)
- **[GitHub REST API](https://docs.github.com/en/rest)** - Repositories, issues, users and more
- **[Hacker News API](https://github.com/HackerNews/API)** - Stories, comments and users via Firebase, no auth
- **[MediaWiki API](https://www.mediawiki.org/wiki/API:Main_page)** and **[Wikimedia API Portal](https://api.wikimedia.org/wiki/Main_Page)** - Wikipedia pages, revisions and page views
- **[Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)** - Query OpenStreetMap: shops, roads and POIs anywhere
- **[Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview)** - Business listings, details and reviews (paid)
- **[TMDB API](https://www.themoviedb.org/documentation/api)** - Movies, TV shows and people
- **[Open-Meteo](https://open-meteo.com/)** - Free weather forecast and historical weather API, no key
- **[Alpha Vantage](https://www.alphavantage.co/documentation/)** - Stock, forex and crypto prices

## Open Datasets

Already crawled for you.

- **[Common Crawl](https://commoncrawl.org/)** - Petabytes of raw web crawl data, free on AWS
- **[Wikidata dumps](https://www.wikidata.org/wiki/Wikidata:Database_download)** - The full structured knowledge graph
- **[OpenAlex](https://openalex.org/)** - Open catalog of scholarly works, authors and institutions
- **[Kaggle Datasets](https://www.kaggle.com/datasets)** - Community datasets on almost any topic
- **[Hugging Face Datasets](https://huggingface.co/datasets)** - ML-ready text, image and audio datasets
- **[data.gov](https://data.gov/)** - US government open data
- **[data.europa.eu](https://data.europa.eu/en)** - EU open data portal

## Scraping Libraries

Build it yourself.

- **[Scrapy](https://github.com/scrapy/scrapy)** - Fast, battle-tested Python crawling framework
- **[Crawlee](https://github.com/apify/crawlee)** / **[Crawlee for Python](https://github.com/apify/crawlee-python)** - HTTP and headless-browser crawling with queues, retries and proxy rotation
- **[Playwright](https://github.com/microsoft/playwright)** - Browser automation for Chromium, Firefox and WebKit
- **[Puppeteer](https://github.com/puppeteer/puppeteer)** - Headless Chrome from Node.js
- **[Selenium](https://github.com/SeleniumHQ/selenium)** - The original browser automation framework
- **[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)** - The classic Python HTML parser
- **[lxml](https://github.com/lxml/lxml)** - Very fast XML/HTML parsing with XPath
- **[Requests](https://github.com/psf/requests)** and **[HTTPX](https://github.com/encode/httpx)** - Python HTTP clients (HTTPX adds async and HTTP/2)
- **[extruct](https://github.com/scrapinghub/extruct)** - Extract JSON-LD, microdata and OpenGraph metadata from HTML

## Content Extraction & AI Crawlers

Turn pages into clean text or Markdown for LLMs.

- **[Trafilatura](https://github.com/adbar/trafilatura)** - Main-text, metadata and comments extraction
- **[Firecrawl](https://github.com/mendableai/firecrawl)** - Crawl a site into LLM-ready Markdown
- **[Crawl4AI](https://github.com/unclecode/crawl4ai)** - Open-source LLM-friendly crawler

## Hosted Scraping Platforms

Run scrapers without managing servers and proxies.

- **[Apify](https://apify.com/store?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Cloud platform and marketplace of thousands of ready-made scrapers ("Actors"), with an API, scheduling and integrations
- **[Zyte](https://www.zyte.com/)** - Scrapy Cloud and an automatic-extraction API
- **[ScrapingBee](https://www.scrapingbee.com/)** - Scraping API with headless browsers and proxies
- **[Bright Data](https://brightdata.com/)** - Proxy networks, scraping browsers and datasets
- **[SerpApi](https://serpapi.com/)** - Google and other search engine results as JSON

## Ready-Made Scrapers

No code: pick a site, run it, download JSON/CSV. Each one is also callable through an API.

### Real estate

- **[Real Estate AU Scraper](https://apify.com/abotapi/realestate-au-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Extract detailed Australian real estate property listings with 30+ structured fields, including price, description, indoor and outdoor…
- **[SeLoger Scraper](https://apify.com/abotapi/seloger-france-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape SeLoger.com properties for sale and rent. Search by location with price, room and property type filters. Extract prices, areas…
- **[PropertyGuru SG Scraper](https://apify.com/abotapi/propertyguru-sg-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape PropertyGuru.com.sg sale and rental listings with 30+ structured fields, including price, PSF, floor area, tenure, nearby MRT…
- **[Avito.ru Scraper](https://apify.com/abotapi/avito-ru-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** ([code](https://github.com/abotapi/avito-scraper)) - Scrape structured listings from Avito.ru by region, category, filters, or direct URL. Automatically paginate through results and extract…

### E-commerce

- **[Coupang Scraper](https://apify.com/abotapi/coupang-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** ([code](https://github.com/abotapi/coupang-scraper)) - Scrape Coupang.com products by keyword, category or URL. Extract 20+ fields including title, brand, price, discount, ratings, reviews…
- **[Ozon.ru Scraper](https://apify.com/abotapi/ozon-ru-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Extract structured product data from Ozon.ru, Russia’s largest marketplace. Search by keyword or use product, category, and seller URLs.…
- **[bol.com Scraper](https://apify.com/abotapi/bol-com-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape bol.com products: title, price, list price and discount, EAN, brand, images, condition, delivery, full specifications, ratings…
- **[Mercado Livre Brazil Scraper](https://apify.com/abotapi/mercadolivre-com-br-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape Mercado Livre Brazil by keyword or URL. Filter by category, brand, price, condition, shipping, official store, and seller rating.…

### Jobs

- **[SEEK Jobs Scraper](https://apify.com/abotapi/seek-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape SEEK.com.au and SEEK.co.nz jobs by keyword, location, or filters. Extract full descriptions, companies, salaries, locations…
- **[HH.ru Jobs Scraper](https://apify.com/abotapi/hh-ru-jobs-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape HH.ru job listings with 50+ structured fields. Search by filters or URLs and extract salary, experience, schedule, employment…

### Social, video & sports

- **[TikTok Profile Scraper](https://apify.com/abotapi/tiktok-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape TikTok without login. Extract profiles, bios, follower stats and videos; search by hashtag or keyword; scrape individual videos…
- **[YouTube Transcript & Subtitle Scraper](https://apify.com/abotapi/youtube-transcript-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Extract transcripts and subtitles from YouTube videos in bulk using video, playlist, channel URLs, or keyword search. Returns timed…
- **[SofaScore Scraper](https://apify.com/abotapi/sofascore-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** ([code](https://github.com/abotapi/sofascore-scraper)) - Pull structured sports data from SofaScore across football, basketball, tennis, and 20+ sports. Search by keyword, paste URLs, fetch…

### Travel & local business

- **[Expedia Hotels Scraper](https://apify.com/abotapi/expedia-universal-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape Expedia.com hotel listings and reviews for any destination. Extract prices, ratings, review text, photos, location details, hotel…
- **[Yellow Pages AU Scraper](https://apify.com/abotapi/yellow-pages-au-scraper?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content)** - Scrape business listings from Yellow Pages Australia by type and location. Get names, contacts, websites, ratings, social links, and…

Browse [360+ more in the Awesome Web Scrapers list](https://github.com/abotapi/abotapi).

## Working with the Data

- **[jq](https://jqlang.org/)** - Slice and transform JSON output on the command line
- **[Datasette](https://datasette.io/)** - Explore and publish scraped data as an instant web app and API

## Legal & Etiquette

- **[RFC 9309: Robots Exclusion Protocol](https://www.rfc-editor.org/rfc/rfc9309.html)** - The robots.txt standard
- **[hiQ Labs v. LinkedIn](https://en.wikipedia.org/wiki/HiQ_Labs_v._LinkedIn)** - The landmark US case on scraping public data
- Collect only public data, respect rate limits, and be careful with personal data (GDPR, CCPA, PIPA).

## Learning

- **[Scrapy documentation](https://docs.scrapy.org/en/latest/)** - Includes an excellent tutorial for beginners

## Related Lists

- **[awesome-web-scraping](https://github.com/lorien/awesome-web-scraping)** - Libraries and tools for web scraping, by language

## Contributing

Know a good API, dataset or tool that's missing? [Open an issue or PR](https://github.com/abotapi/awesome-scraping-apis/issues). Entries should be useful, maintained, and described in one line.

---

<sub>The scrapers in the Ready-Made Scrapers section are maintained by [abotapi](https://abotapi.com/?utm_source=github&utm_medium=awesome-scraping-apis&utm_campaign=content). Everything else is independent.</sub>
