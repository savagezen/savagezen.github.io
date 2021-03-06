---
title: "Carnivore Diet: 45 Day Follow Up"
author: Austin
date: 2020-03-30
categories: [Research, Nutrition]
tags: [day 45, carnivore, carnivore diet, caffeine, electrolytes, cardiovascular load, omega 3, omega 6, fatty acid]
toc: false
---

**Caffeine:**

In this sub-test of 15 samples, I looked at how caffeine dosage (total mg / day) and last time of ingestion effected sleep quality (simple 1-5 scale).  One note on the raw data (link below) is that the caffeine / sleep samples were taken on consecutive days.  They do not correspond to the dates and other values on the spreadsheet.  I.E.  the caffeine / sleep samples were taken on 15 consecutive days, but the other values were only being monitored and documented three times per week.

At any rate, dosage did not have a significant relationship (p < 0.01) with either sleep quality or time of ingestion.  However, last time of ingestion had a notably significant relationship with sleep quality (p = 0.0068).  The strength of the relationship was also notable (r = -0.67).  This means that the later in the day caffeine was ingested, the more poor sleep quality was.

While the relationship between time of ingestion and dosage was not statistically significant, it was close (p = 0.0123) and the correlation was strong (r = 0.63) suggestion that the later in the day you consume caffeine, the higher your total dosage for the day is (which makes sense).  Follow up analysis could include comparing different dosages at different times (e.g. 600mg all within a one hour window versus over a 6 hour window; and again 6 hours in the am versus, etc...).

> I erroneously confused the two figures in the previous commit.  My apologies.


**Cardiovascular Load (and electrolytes):**

Notable Correlations:

| Var 1 | Var 2 | *r* | p |
|-------|-------|-----|---|
| CVL   | CA    | 0.0367 | -0.90 |
| Weight | Cal | 0.0572 | 0.80 |
| Na     | K | 0.0002 | 0.99 |
| Na     | Ca | 0.0313 | 0.85 |

\* *Note:* Only the sodium / potassium relationship was statistically significant, though with a larger data set this may have changes (see below).

Most obviously, weight and calories have a positive correlation -- the more you eat, the more you weigh.  Interestingly though there was *not* a significant relationship between traingin volume (time) and calories *or* weight.

From this data set, the variable with the most significant effect on cardivascular load (CVL = MAP * RHR) was calcium.  The relationship was very strong (-0.90) meaning that increased calcium *decreased* CVL.  Annecdotally, it looks like overall electrolyte consumption (sum of sodium, calcium, magnesium, and potassium) would continue to decrease CVL given the absence of other variable changes.

Next, sodium had a positive and significant relationship with potassium as well as calcium (not quite statistically significant).  I had not extended the testing to include [real salt](https://redmond.life/realsalt/), though the pink sea salt I was consuming likely had trace minerals as well.  However, this is probably mostly likely due to [the electrolyte supplement I was consuming](https://www.flyby.co/products/flyby-fuel-electrolyte-powder-lemon-lime) -- i.e. ingested ratios were consistent since they were coming from a supplement rather than raw / varied sources.

> Initially I planned on obtaining about 30 samples.  The actual sample was much smaller.  I intended on using samples from my previous studies on sodium ([1](https://github.com/savagezen/savagezen.github.io/blob/master/_posts/2019-03-08-blood-pressure-01.md), [2](https://docs.google.com/spreadsheets/d/1IU5-A1XtKTGN1AyGS6J562pRoQ8XduEmuM1_xzhbaz8/edit?usp=sharing)).  However, I wanted to look at all electrolytes rather than just sodium.

> Additionally I don't have a home blood pressure cuff, work is delayed with coronavirus outbreak, and pharmacy kiosks are closed for the same reason.  In the future (90 days?) I may resume data tracking and do follow up blood work again since my planned 60 day blood pannel will likely be delayed due to the aforementioned aoutbreak.

**Cardiovascular Load (and fatty acids):**

Much later in this trial I started to look at Omega-6 to Omega-3 ratios (n = 5).  The sample is quite small, but nevertheless here's the results.

| Var 1 | Var 2 | *r* | p |
|-------|-------|-----|---|
| O3    | Ratio | 0.0285 | -0.92 |
| O6    | CVL   | 0.0833 | -0.83 |
| RHR   | CVL   | 0.0242 | 0.93 |

> Again, we don't have a large enough sample for many samples to be statistically significant (r < 0.01, or preferrably r < 0.001).

Here we see that there is a negative relationship between O6 consumption and CVL (as one goes up, the other goes down) which was surprising.  It was also suprising that O6:O3 ratio did not have a significant effect on any of the cardiac variables.  O3 consomupion had a strong impact on the overall CVL.

Additionally, RHR had a stronger impact on CVL than did MAP in this sample.  Note that this wasn't true in the larger sample above (looking at electrolytes).  The abobve data set subsumes this smaller data set.
