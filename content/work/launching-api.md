---
title: "Defining and launching an API"
date: 2018-05-07
showDate: false
draft: false
tags: ["product strategy", "pricing"]
---
After a [repositioning and double price raise](http://remotekieran.com/work/maximising-revenue) growth had become stagnant for this [SaaS product](https://sqlizer.io). The low-hanging marketing fruit was eaten and I was working on growth with long-term channels. Long overdue some love from the product team, we set out to find what the product was missing in the eyes of customers and the market.

## Step 1: customer research 👀

The product has a diverse set of customers: regular free users, irregular one-off users, regular weekly users, heavy daily users. We contacted a selection of customers from across these segments and asked one question:

> What do you wish this product could do that it doesn't now and why?

The product team already had a few ideas of what they wanted to build in order to offer more value. Asking such an open ended question was a good way to guage customer desires and see if they matched any of our assumptions.

Over 60% of respondents said an API would improve their current workflows with the product. Not every product benefits from an API. They're sometimes a "me too" thing, offering little value to customers. But then there are products that seem incomplete without one. Something that turns files into SQL databases is such a product. As it goes, this was one of the product team's ideas too.

## Step 2: defining the API

Working with product and engineering, I defined the API functionality customers had expressed:

* **Run multiple file conversions at once** - customers often export from multiple sources, convert using the product, and then add to their SQL database. Using the product interface means this is a tedious and manual process. The API should enable programmatic access.

* **Convert big files** - customers chunk files that are in the gigabytes into smaller versions so the interface can handle them. The API should remove the need to chunk files.

* **Compatible with all sorts of software** - source data comes from everywhere and customers have an array of software they use to complete their tasks. The API needed to be versatile.

## Step 3: beta, feedback, messaging

Once the API was built I ran a beta testing period with willing customers. This enabled us to test the tech as well as get feedback to help us improve it. The beta lasted one month.

During this time I also worked on messaging for the API. There was no other product with such an API so, leaning heavily on customer wording, I focused on the unique nature of being able to create a continuously deliverable data migration pipeline.

Once the beta was over and the product team was happy to release, it was launch time.

## Step 4: launch 🚀

As a somewhat technical product the audience is tech savvy. More specifically, those working with SQL databases. Luckily, (SQL) databases play a pivotal role in software so the appeal is wide.

The API launch revolved around a featured [Product Hunt](https://www.producthunt.com/posts/sqlizer-api) hunt. While Product Hunt has a broad audience of designers, developers, marketers, and people generally interested in tech, the appeal of the product was wide enough to warrant a Product Hunt launch.

Once the product had been hunted a concerted push across our mailing lists (including free, paid, current, and past users), relevant subreddits, HackerNews, and social media ensured considerable coverage on the day. For the weeks afterward the push continued with coverage in [DBWeekly](https://dbweekly.com), content across blogs, social, and the long tail of search.

Since the launch API usage has continued to grow at a healthy rate month-on-month.