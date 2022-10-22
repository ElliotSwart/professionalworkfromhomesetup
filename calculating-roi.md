---
layout: default
title: Calculating ROI
nav_order: 12
has_children: false
has_toc: false
---

# {{page.title}}

## Introduction

Now it's time to calculate ROI. This is done by figuring out investment cost and investment gain. 

The cost is determined by the cost of the products on the site, incorporating shipping and tax. What is missing from the cost is facilities management overhead. You could easily increase the cost of this program by 2x-5x in an attempt to track and keep company ownership of the equipment. These calculations assume you trust your employees, do a simple expense reimbursement, and don't attempt to recover this equipment upon exit (though obviously items not listed here, like company laptops, need to be returned).

The gain is more complicated to determine, but lower bounds can be estimated using the [research](research). If you are skeptical, read that first and come back to this page. A 10-20% productivity gain is possible given the evidence. Additionally, though not modeled here, is the reduction in musculoskeletal health conditions and increased in morale. Finally, improved conferencing can be expected to improve memory recall of meetings and reduce video-conference fatigue, leading to higher engagement. In my personal experience, the productivity gains are on the lower side of that bound: approx 20%. However, as a tech executive, much of my time is spent in meetings, planning, etc and not coding.

Employers should be the ones paying for this program, both on principle (see [Joel Test #9](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)) and because they realize the majority of the gains. However, there are many sociological and structural reasons why this may be difficult. My advice for developers reading this is to use the justification contained below to sell this program internally. 

However, for individual programmers doing this for themselves, the ROI is still worth it. The additional productivity gains along with better video presence could lead to more promotion opportunities. Additionally, those productivity gains can buy more time for continuing education which can either help you get promoted or get a better job. Finally, it will have positive health impacts. For anyone who is motivated: the best investment you can make is in yourself. However, this should not be seen as a justification for companies to push this responsibility on their programmers: only a small fraction of your programmers will do this with their funds and you will only see a small fraction of the ROI. The best ROI will come from supplying funds to employees and then expecting them to take advantage of the opportunity.

> The details behind these calculations can be found in this [excel document](assets/ProfessionalWFH_ROI.xlsx). Feel free to download it and play with the numbers. Note that ROI is calculated as ```ROI = Investment gain / Investment base```. An ROI of 0% is breakeven.

## Professional Setup Cost (Recommended)

All products found in the _Recommendation_ sections

The additional decisions are:
- Get a lightly used Leap V2 / allow employees to personally pay the difference for a new one: $425
- Marginally increase monthly internet budget by $100 (e.g. If someone is spending $50, go up to the $150 plan)
- Buy 2 monitors and mount a laptop

This should yield all the benefits described in the article.

_Note: for the 3rd row, we assume 3 years of employment on average per employee. Very little of the equipment should have failed by this point. In practice, many of the most expensive items, such as the chair and the desk, should last long enough to cover most terms of employment. However for modeling, assume that after 3 years, you will need to replace all the equipment._

| First Year Outlay | $5849 |
| Next Years Outlay | $1359 |
| Amortized over 3 years of employment | $2856 |

## Budget Setup Cost

The budget recommendations should theoretically yield much of the improvement listed in the article. However, I cannot vouch for that as I have not integrated all the pieces. Additionally, the lifetime of most of the products is lower, as they are of lower quality. Finally, without a high-end chair, the ergonomic benefits are at risk.

| First Year Outlay | $2420 |
| Next Years Outlay | $700 |
| Amortized over 3 years of employment | $1273 |

## Modeling ROI

We will run the numbers for 3 different employees with the following salaries: $60,000, $100,000, and $200,000. 

We add the cost of 10 hours of salary to the first year to account for the setup time.

The goal of this modeling is to provide an incredibly conservative lower bound of the benefits, just to show how safe and effective providing appropriate setups can be. To this end we make four conservative assumptions:
- The productivity gains are between 10% and 20%. This is on the low end of what is supported by research for the _Professional Setup_.
- The employee's value is break-even with their salary. E.g. the employee making $100,000 is generating $100,000 in value. In practice, an employee making $100,000 would ideally be generating some multiple of that in value.
- The gains from productivity are additive. In real life, because of the [cost of additional programmers on a project](https://en.wikipedia.org/wiki/The_Mythical_Man-Month), providing each programmer in a team of 5 with a 20% productivity increase would increase the team's effective productivity by > 20%.
- There are no gains provided by morale and team cohesion or lower healthcare costs. In reality, these are difficult to quantify but are likely substantial, likely matching the more easily quantified benefits. However, they are not needed to justify a wide application of these recommendations.



### Full Work From Home

|Salary|$60,000|$100,000|$200,000|
|:------|:------|:-----|:-----|
| Adjusted First Year Cost | $6,137 | $6,329 | $6,810 |
| Adjusted Amortized Cost | $2,952 | $3,016 | $3,176 |
| 1st year gain (10%) | -$137 (-2%) | $3,670 (58%) | $13,189 (193%) |
| 1st year gain (20%) | $5,862 (95%) | $13,670 (215%) | $33,189 (487%) |
| Amortized gain (10%) | $3,048 (103%) | $6,983 (231%) | $16,823 (585%) |
| Amortized gain (20%) | $9,047 (306%) | $16,983 (563%)  | $36,823 (1159%) |

Assuming 10% productivity, the first-year breakeven salary is approximately $62,000, the amortized breakeven salary is $30,000.
Assuming 20% productivity the first-year breakeven salary is approximately $30,000, the amortized breakeven salary is $15,000.

### Hybrid Setup
Many companies are transitioning to hybrid setups. This does not mean it is a good idea to ignore home office setups. To show this, let's imagine we must provision 2 setups, one in the office and one at home. Now because both spaces have the setup, the specifics of how at-home/at-office time is broken up are irrelevant. Note that this assumes at least $100 per employee per month is spent on internet access for the office.

|Salary|$60,000|$100,000|$200,000|
|:------|:------|:-----|:-----|
| Adjusted First Year Cost | $12,235 | $12,659 | $13,620 |
| Adjusted Amortized Cost | $5,891 | $6,032 | $6,353 |
| 1st year gain (10%) | -$6,274 (-51%) | -$2,658 (-21%) | $6,379 (47%) |
| 1st year gain (20%) | -$274 (-2%) | $7,341 (58%) | $26,379 (193%) |
| Amortized gain (10%) | $95 (1.5%) | $3,967 (66%) | $13,647 (214%) |
| Amortized gain (20%) | $6,095 (103%) | $13,967 (231%)  | $33,647 (529%) |

Assuming 10% productivity, the first-year breakeven salary is approximately $130,000, the amortized breakeven salary is $60,000.
Assuming 20% productivity the first-year breakeven salary is approximately $62,000, the amortized breakeven salary is $30,000.

## How to interpret and "sell" results

The numbers that are important for you may differ depending on your company structure. Make sure to pick the numbers that your company would find representative.

### Amortized vs 1st Year Gain

Different companies operate on different time horizons due to culture or business conditions. 

You will want to use the 1st year gain estimate if:
- Your company is a startup with less than 2 years of runway (This is most startups)
- Your company experiences very high employee turnover
- Management is rewarded mostly for short-term "wins"

You will want to use to amortized gain if:
- Your company has low to normal employee turnover: 3 years or more
- Your company is well-established and aims for long-term profitability
- Management is rewarded for mid-long term strategic action

I urge you to be very realistic about where your company is, and when in doubt present a plan that is profitable in both cases.


### 10% - 20% productivity gain

There is research evidence for a 40% gain if all suggestions are implemented. However, a healthy dose of skepticism is required as to how the research will translate into your company. My advice is to sell this internally based on a 10% gain, and measure productivity. The higher it rises, the more employees it can be justified to apply to. However, the 20% gain, along with the improved collaboration, morale, etc. should be sold as potential benefits to get people excited.

There can be significant resistance to investment in employee work setups, largely for sociological reasons. You should therefore choose the most defensible option. The one exception is if your company is willing to take risks and spend money on a good bet, not a sure thing. Most companies do not qualify.


### Breakeven

The breakeven points should be used at companies that genuinely want to improve the lives of their workers, without being fiscally irresponsible. Additionally, all the unaccounted-for benefits still apply. Truthfully it is exciting, because it justifies ergonomic and performant setups for almost every white-collar worker, and certainly every programmer. It is a low-risk, high-reward, employee-friendly program. There aren't many of those to be had.


### The Most Conservative Estimate / Sanity Check

For the most conservative estimation, look at *1st year gain (10%)*. This models the fact that you get the smallest possible gain supported by research, and all your employees quit after 1 year. If you expect worse than this, you have larger problems than WFH setups. For example, if your company has less than a year of runway, it is probably not the time to invest. For everyone else, at $62,000 for a work-from-home or $130,000 for a hybrid setup, there is no reason not to implement this program.


<br><br>

| Next: [Supporting Research](research)|