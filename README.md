![banner](https://i.postimg.cc/PrswhLdn/bible-gateway.png)

# 📖 Bible Gateway Scraper

## 🎯 Introduction

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.1` |
| **Last Update** | Nov 30, 2025 |

---



The Bible Gateway Apify Scraper is a powerful web scraping tool specifically designed to extract Bible passages and search results from the popular Bible study website, BibleGateway.com. This scraper enables users to collect various Bible-related information, including specific passages, search results, and verse content from multiple Bible versions.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-uvu9NrOGJdnPmVqai-NnoT2513UC-logo_bg-sharing.png" alt="BibleGateway.com Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/bible-gate-way-com-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


BibleGateway.com is one of the leading online Bible study platforms, offering access to hundreds of Bible translations and versions. The Bible Gateway Apify Scraper helps users to gather valuable data from this platform, which can be used for various purposes like Bible study, research, content creation, and theological analysis. This scraper is built using Apify, a popular web scraping and automation platform, which ensures a seamless and efficient data extraction process.

## 🚀 Use Cases

The Bible Gateway Apify Scraper can be used in multiple scenarios, including but not limited to:

1. **📚 Bible Study and Research:** Extract specific Bible passages and verses for personal study, academic research, or theological analysis across different Bible versions.
2. **✍️ Content Creation:** Gather Bible content for creating devotionals, sermons, educational materials, or religious content for websites and applications.
3. **🔍 Comparative Analysis:** Compare passages across different Bible versions to understand translation differences and theological nuances.
4. **🔎 Keyword Research:** Search for specific words or themes across the Bible to find relevant verses and passages.
5. **📱 Bible App Development:** Collect Bible content for developing Bible applications, websites, or digital study tools.

Happy scraping! 🎉

## 📥 Input

To use this actor, you need to provide the following input:

- Field: **🔍 search**
  - Type: string
  - Required: Yes
  - Description: The keyword(s) or passage reference you're looking for (e.g., 'John 3:16', 'love', 'faith')
- Field: **📖 version**
  - Type: string
  - Required: Yes
  - Description: Select the English Bible version you want to search

### 📚 Available Bible Versions

The scraper supports a wide range of Bible versions including:

- KJV (King James Version)
- NKJV (New King James Version)
- NIV (New International Version)
- ESV (English Standard Version)
- NLT (New Living Translation)
- NASB (New American Standard Bible)
- AMPC (Amplified Bible)
- And many more...

## 🔍 How to use the search parameter?

1. **📖 Specific Passage Reference**

   - Format: "Book Chapter:Verse" (e.g., "John 3:16", "Genesis 1:1", "Psalm 23:1-6")
   - The scraper will return the exact passage from the specified Bible version

2. **🔎 Keyword Search**
   - Format: Any word or phrase (e.g., "love", "faith", "grace", "salvation")
   - The scraper will search for all verses containing the keyword and return multiple results

### 💡 Examples

Specific passage:

```
search: "John 3:16"
version: "NIV"
```

Keyword search:

```
search: "love"
version: "KJV"
```

## 📤 Output

The scraper provides different output formats depending on the search type:

### 📖 For Passage Searches (e.g., "John 3:16")

```json
{
  "url": "https://www.biblegateway.com/passage/?search=John%203:16&version=AMPC",
  "search": "John 3:16",
  "version": "AMPC",
  "passage": "16 For God so greatly loved and dearly prized the world that He [even] gave up His only begotten (unique) Son, so that whoever believes in (trusts in, clings to, relies on) Him shall not perish (come to destruction, be lost) but have eternal (everlasting) life."
}
```

### 🔎 For Keyword Searches (e.g., "love")

```json
{
  "url": "https://www.biblegateway.com/quicksearch/?quicksearch=love&version=KJV",
  "search": "love",
  "version": "KJV",
  "totalResults": 310,
  "suggestedResult": "Did you mean: love",
  "allSearchResults": [
    {
      "title": "John 3:16",
      "content": "For God so loved the world, that he gave his only begotten Son..."
    },
    {
      "title": "1 John 4:8",
      "content": "He that loveth not knoweth not God; for God is love."
    }
  ]
}
```

## ✨ Features

- **📚 Multiple Bible Versions:** Support for hundreds of Bible translations and versions
- **🔍 Flexible Search:** Search by specific passage references or keywords
- **📋 Comprehensive Results:** Get full passage text or multiple search results
- **📊 Structured Data:** Clean, structured JSON output for easy integration
- **⚡ Reliable Scraping:** Built with Apify's robust scraping infrastructure

## ❓ FAQ

**Q: 🤔 How do I set up the Bible Gateway Apify Scraper?**

A: To set up the scraper, you'll need an Apify account. Once you have an account, you can access the scraper through the Apify Console, input the required search parameters and Bible version, and start the scraping process.

**Q: ⚖️ Is this scraper legal to use?**

A: Web scraping is subject to legal and ethical considerations. Before using the Bible Gateway Apify Scraper, ensure that you comply with the website's terms of service, robots.txt file, and any applicable laws and regulations. Bible Gateway's content is generally available for educational and research purposes.

**Q: ⚡ How fast is the data extraction process?**

A: The speed of data extraction depends on various factors such as the complexity of the search, server response time, and the amount of data being extracted. The scraper is designed to be efficient and respectful of the website's resources.

**Q: 🔄 Can I search across multiple Bible versions at once?**

A: Currently, the scraper processes one Bible version at a time. You can run multiple instances with different versions to compare passages across translations.

**Q: 📥 How can I export the extracted data?**

A: The Bible Gateway Apify Scraper allows you to export the extracted data in various formats like JSON, CSV, or Excel. You can download the data directly from the Apify Console or use the Apify API to integrate it into your applications.

**Q: 🤷‍♂️ What's the difference between passage search and keyword search?**

A: Passage search (e.g., "John 3:16") returns the specific verse or passage you requested. Keyword search (e.g., "love") returns all verses containing that word, which can be hundreds of results depending on the keyword.

## 🔗 Need to scrape more data

Here are some other scrapers you might find useful:

- [Dice.fm Scraper](https://apify.com/lexis-solutions/dice-com-jobs-scraper)
- [Luma Events Scraper](https://apify.com/lexis-solutions/lu-ma-scraper)
- [Holidaycheck Scraper](https://apify.com/lexis-solutions/holidaycheck-scraper)

---

👀 **Got feedback or need an extension?**

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us via [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

---
