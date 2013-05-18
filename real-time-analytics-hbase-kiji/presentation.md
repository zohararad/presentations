= data-x="0" data-y="0"

## Real-Time Analytics
## with **HBase** & **Kiji**
Case Study of **Quicklizard.com**

---
= data-x="1500" data-y="0"

## Quicklizard

eCommerce Business-Intelligence Platform

---
= data-x="1500" data-y="0"

We help eCommerce store owners make the **right decisions**

and **react** to changes in their store & market-place

based on **real-time** and historical information

---
= data-x="3000" data-y="0"

Measure anything that happens in an eCommerce store
<br /><br />
Provide real-time and historical BI on events and trends

in the context of the client's store and market-place

---
= data-x="3000" data-y="0"

Answer questions like:

* How many times was a product viewed or purchased?
* Were viewes and purchases part of a campaign?
* How well is a landing page performing?
* How should you order a list of products to maximize revenue?
* What is the optimal price for a product in comparison to competition?

---
= data-x="4500" data-y="0"

To do that, we process 100s of thousands of events per-day

both in **real-time** and in batch using **Storm**, **HBase** & **Hadoop**

---
= data-x="0" data-y="1500"

## The Challenge:

* Handle 100s of thousands of daily events
* Generate real-time BI for incoming data
* Analyze historical data and generate useful insights over time
* Use historical trends to make real-time decisions

---
= data-x="1500" data-y="1500"

## Our Solution

* **Storm** - Real-time event aggregation and decision making
* **HBase** - Real-time & historical aggregated data store
* **Kiji** - Data collection & analysis framework for HBase
* **Hadoop M/R** - Offline data processing and analysis

---
= data-x="3000" data-y="1500"

# HBase
## The Hadoop Database

---
= data-x="3000" data-y="1500"

## We chose HBase because:

* It's exteremly robust & scalable
* It can handle huge amounts of data
* Perfect for data aggregation (counters, TTL, row scans)
* Supports Map/Reduce (thanks to Hadoop)

---
= data-x="3000" data-y="1500"

# BUT....
We're using HBase with a bit of help from

---
= data-x="4500" data-y="1500"

# Kiji
Real-time data collection, aggregation and analysis for HBase

---
= data-x="4500" data-y="1500"

## Kiji simplifies

* HBase schema management
* Data collection (keys, TTLs, counters, history)
* Data retrieval
* Data aggregation and analysis (M/R)

---
= data-x="6000" data-y="1500"

In other words, Kiji makes it easier to use HBase as a real-time BI platform

---
= data-x="0" data-y="3000"

# The End Result

---
= data-x="1500" data-y="3000"

Short and long-term data is aggregated

in a scalable, robust data store (HBase)

---
= data-x="1500" data-y="3000"

This data is used for real-time BI and decision-making

Since it's readily available (no Hadoop M/R).

---
= data-x="3000" data-y="3000"

Historical data (logs) is analysed offline (Hadoop M/R)

And is fed back into real-time data store (HBase).

---
= data-x="4500" data-y="3000"

Historical data can be analyze and queried in near real-time

(coming soon thanks to Kiji...)

---
= data-x="6000" data-y="3000"

We can answer questions like:
<blockquote>
"How well is my campaign performing now in comparison to last week?"
</blockquote>

---
= data-x="6000" data-y="3000"

Or let you say things like:
<blockquote>
"Email me if the conversion rate of white washing machines falls below 2%"
</blockquote>

---
= data-x="7500" data-y="3000"

## In Real-Time
and over large amounts of data

---
= data-x="0" data-y="0"

# Thank You
## Questions?

---
= data-x="1500" data-y="0"

Presentation: http://goo.gl/YAuOv

E: zohar@quicklizard.com

W: www.quicklizard.com
