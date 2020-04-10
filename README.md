# Airbnb

## Table of Contents
- [Background](#Background)
- [Project Goal](#project-goal)
- [Data](#the-data)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(EDA))

---

## Background 

Airbnb is an online marketplace for rentors to rent out lodging such as homes, apartment, lofts, and all kinds of living space. According to [Airbnb](https://declara.com/content/A5YPWkg8), as of October 2018, it has over 1,000,000 listings in 34,000 cities and 190 countries. It has revolutionized the lodging market providing opportunities for individuals to make an extra income, keep hotel rates in check, and offer travelers more lodging options.

---

## Project Goal

Being raised in San Francisco, I am aware that house prices between districts can vary dramatically. 

As of April 2020:
- Noe Valley median price: **$2,210,000**
- Mission District median price: **$1,530,000**
- Distance between the centers of the two neighboring districts is 1.8 miles.

Let's look at another group:
- Inner Sunet median home price: **$1,750,000** 
- Outer Sunset median home price of **$1,429,000**
- Distance between the heart of two neighboring districts is also 1.8 miles.

House prices play a role between districts, but how do Airbnb prices vary between them? In other words, if investors are looking to buy a property in San Francisco just for an extra stream of income through Airbnb, should they be saving over a million dollars on purchasing properties in a less expensive neighborhood?

---

## The Data

Airbnb has public downloadable datasets between cities across the world. There are details of each listing, reviews and neighborhoods. I was mainly working off of the detailed listing dataset which contains all listings of San Francisco in 2019. Data was scraped June of 2019 and it has 7575 rows, 106 columns. 

---

## Exploratory Data Analysis (EDA)

**How are listing price distributed across San Francisco?**

Listing price mostly concentrate in the lower end, with a handful of really expensive listing with over $500 per night.

![all_listings](images/list_all.png)

**How do price vary between neighborhoods?**
Graph below shows average listing price for the top 20 most expensive neighborhoods along with count of listings in the neighborhood.

![top_20](images/top_20.png)


I am curious to see what affects pricing other than location of the listings. 

**One would think that listing price would increase as number of guests allowed increase. Is that the case for listings in San Francisco?**

It turns out not so much.

![accomomdates](images/accomoates.png)



analysis 
conclusion
references

 












