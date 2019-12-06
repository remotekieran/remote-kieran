---
title: "Defining and launching an API"
date: 2017-07-11
description: "Successful repositioning and price increases had bumped revenue significantly for this SaaS product - but user growth remained stagnant."
showDate: false
draft: false
tags: ["product strategy", "pricing"]
---

Successful [repositioning and price increases](/work/maximising-revenue) had bumped revenue significantly for this [SaaS product](https://sqlizer.io). But new user growth remained stagnant. The low-hanging marketing fruit was gone and I was working on growth with long-term channels.

> Long overdue some love from the product team, we set out to find what the product was missing in the eyes of customers and the market.

## Step 1: customer research

The product has a diverse set of customers: regular free users, irregular one-off users, regular weekly users, heavy daily users. The product team already had a few ideas of what they wanted to build in order to offer more value. We wanted to ask an open ended question to guage customer desires and see if they matched any of our assumptions. We asked a selection of customers from across these segments one question:

> What do you wish this product could do that it doesn't now, and why?

Over 60% of respondents said an API would improve their current workflows with the product. APIs are sometimes a "me too" thing, offering little value to customers. But some products seem incomplete without one. Something that turns files into SQL databases is such a product. As it goes, this was one of the product team's ideas too.

## Step 2: defining the API

Working with product and engineering, I defined the API functionality customers had expressed:

* **Run multiple file conversions at once**. Customers often export from multiple sources, convert using the product, and then add to their SQL database. Using the product interface means this is a tedious and manual process. The API should enable multiple concurrent conversions.

* **Convert big files**. Customers chunk files in the gigabytes into smaller versions so the interface can handle them. The API should remove the need to chunk files.

* **Compatible with all sorts of software**. Source data comes from everywhere and customers have an array of software they use to complete their tasks. The API needed to be versatile.

## Step 3: beta, feedback, messaging

Once the API was built I ran a beta testing period with willing customers. This enabled us to test the tech as well as get feedback to help us improve it. The beta lasted one month.

During this time I also worked on messaging for the API. No other competing products had an API so, leaning heavily on wording from our customer feedback and beta, I focused on the unique nature (for this product category) of being able to create a continuously deliverable data migration pipeline.

Once the beta was over and the product team was happy to release, it was launch time.

## Step 4: launch 🚀

Users of this product are mainly developers or other tech savvy users. More specifically, those working with SQL databases.

The API launch revolved around a featured [Product Hunt](https://www.producthunt.com/posts/sqlizer-api) hunt. Product Hunt has a broad audience of designers, developers, marketers, and people generally interested in tech, so the appeal of the product was wide enough to warrant a Product Hunt launch.

Once the product had been hunted a concerted push across our mailing lists (including free, paid, current, and past users), relevant subreddits, HackerNews, and social media ensured considerable coverage on the day. For the weeks afterward the push continued with coverage in [DBWeekly](https://dbweekly.com), content across blogs, social, and the long tail of search.

Since the launch both new users and API usage has continued to grow at a healthy rate month-on-month.