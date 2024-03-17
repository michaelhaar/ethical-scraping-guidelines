# Ethical Scraping Policy

These concepts are embedded in every web scraper that I write.

It’s basically a summary of the following articles:

- https://blog.apify.com/is-web-scraping-legal/
- https://www.empiricaldata.org/dataladyblog/a-guide-to-ethical-web-scraping
- https://scrapingrobot.com/blog/ethical-web-scraping/
- https://towardsdatascience.com/ethics-in-web-scraping-b96b18136f01
- https://monashdatafluency.github.io/python-web-scraping/section-5-legal-and-ethical-considerations/
- https://research.aimultiple.com/web-scraping-ethics/
- https://www.meritdata-tech.com/resources/blog/data/web-scraping-best-practices-ethical-data-collection/
- https://www.digital-recht.at/ist-screen-scraping-rechtlich-zulaessig/
- https://discoverdigitallaw.com/is-web-scraping-legal-short-guide-on-scraping-under-the-eu-jurisdiction/
- https://www.frag-einen-anwalt.de/Kleinanzeigen-Web-Scraping-legal--f349307.html

## SCRAPE ONLY PUBLIC DATA

Scraping publicly available information on the web in an automated way is legal as long as the scraped data is not used for any harmful purpose or directly attacking the scraped website’s business or operations.

## THE API WAY IS OFTEN THE BEST WAY

Some websites have their own APIs built specifically for you to gather data without having to scrape it. This means that you’d be doing it according to their rules; you have been authorized to get the information. So, if there’s an API, use it instead of scraping.

## RESPECT COPYRIGHTS

Copyright infringement is the use or production of copyright-protected material without the permission of the copyright holder. Be careful with potentially copyrighted material like images and texts.

## RESPECT PERSONAL DATA

There are data protection regulations around personally identifiable information (PII) in many countries, the major ones being GDPR in the EU and CCPA in California. Therefore, it is important not to scrape personally identifiable information!

## BE GENTLE TO THEIR SERVERS

The process of scraping can be pretty harsh on the server, and aggressive scraping can sometimes lead to functionality issues, generating a bad user experience for human users. You should request data at a reasonable rate and during off-peak hours and strive to never be confused for a DDoS attack.
E.g. less than 1 request every 10-15 seconds.

## IDENTIFY YOURSELF

Provide a User Agent string that makes your intentions clear and provides a way for them to contact us with questions or concerns.
E.g.: User-Agent: ‘Heimdall Extractor (contact@heimdall.com)

## VALUE THE CONTENT WE KEEP

We should only take the kind of content that we need. And always have a good reason for getting the content in the first place. The purpose of using the data is to create more value, not duplicate it.

## TREAT THE DATA WITH RESPECT

You were given permission to take the content, but that doesn’t mean you can now grant that permission to others. Don’t pass it off as if it were your own.

## GIVE BACK WHEN YOU CAN

We will look for ways to return value to the scraped websites. Maybe we can drive some (real) traffic to your site or credit them in an article or post.

## RESPECT THE ROBOTS.TXT

Also known as Robots Exclusion Standard, the robots.txt file is what indicates the web-crawling software where it is allowed (or not allowed) within the website. This is part of the Robots Exclusion Protocol (REP) which are a group of web standards created as a way to regulate how robots crawl the web.

## RESPECT THE TERMS AND CONDITIONS

This is the main way the website owner tells you the rules. Yes, it’s easier to just click “I agree” or “I accept” and hope for the best. Remember they wrote those for a reason. They are talking to you, listen to what they have to say.

## ASK FOR PERMISSION

Some basic human courtesy is always appreciated. They have something that you want, be courteous and ask before assuming the information is free for you to take. Remember: the data doesn’t belong to you.

## BE COOPERATIVE

We will respond in a timely fashion to the scraped website owner’s outreach and work with them towards a resolution.
