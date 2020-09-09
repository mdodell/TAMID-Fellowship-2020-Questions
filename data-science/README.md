1. Suppose we have the following schema with two tables: Ads and Events

```
Ads(ad_id, campaign_id, status)
Events(event_id, ad_id, source, event_type, date, hour)
```

Each ad can be active or inactive, and this is reflected in the status field.

There are different event types:

```
impression (ad is shown to the user)
click (the user clicked on the ad)
conversion (the user installed the app from the advertisement)
```

We want to write a couple of queries to extract data from these tables. Write SQL queries to extract the following information:

1) The number of active ads.
2) All active campaigns. A campaign is active if there’s at least one active ad.
3) The number of active campaigns.
4) The number of events per each ad — broken down by event type.

1. Calculate a factorial of a number using Python or R.

   ```
   print factorial(5)

   "120"
   ```
1. Calculate the Jaccard similarity between two sets: the size of the intersection divided by the size of the union.

   ```
   print jaccard({'a', 'b', 'c'}, {'a', 'd'})

   "1/4"
   ```
