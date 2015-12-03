---
layout:     post
title:      Business Model Case Study - Uber Part 2
date:       2015-12-03 14:00:00
summary:    This part of the analysis on Uber’s business model focus on the characteristics of it’s operating model and will also provide a reading list for further discussion about Uber.
categories:
---

This part of the analysis on Uber’s business model focus on the characteristics of it’s operating model and will also provide a reading list for further discussion about Uber.

##Uber as a Platform and Network Effects

Uber is a platform (in economics jargon they are known as [multi-sided platform or two-sided market](https://en.wikipedia.org/wiki/Two-sided_market){:target="_blank"}, with riders on one side and drivers on the other. What this means is that the value that riders get from this platform increases with the number of drivers on the Uber network due to increased availability and reduced wait times and vice versa where the benefit of more riders to drivers is shorter times between pickup increasing utilisation and therefore incomes. In economics jargon this is known as [indirect network effects](https://en.wikipedia.org/wiki/Network_effect#Types_of_network_effects){:target="_blank"}. Note that the network effects for ride-sharing in general are local, that is, as a rider in Melbourne the value of large number of drivers in Sydney to me is zero. All I care about is the availability and wait time local to me i.e. Melbourne, which is determined by the number of local drivers.

An excellent article on platform dynamics in the Uber context is provided by [Ben Thompson at Stratechery](https://stratechery.com/2014/uber-fights/){:target="_blank"}.

The key point of platforms is that network effects they create pose significant barriers to entry for new competitors. Once a platform gains critical mass (the point at which users choose that platform purely because everyone else is on it irrespective of the merits of the product or UX itself) is established there is little to gain and much to lose from moving to a less mature platform for participants on the existing platform, the effects of which deters new entrants from establishing a new platform in the first place.

This is the driving motivation behind Uber’s rapid expansion to new cities across the world. There is a first-mover advantage in establishing platforms (the so-called ‘winner take all’ scenarios that Silicon Valley types love to glorify).

##Owning the Customer Relationship

While Uber doesn’t own the physical means of production which in this case is the drivers and their passenger carrying vehicles but they do control something more valuable in the form of the intellectual property means of production, namely the data on where all the riders and drivers are located ([example of a club good](https://en.wikipedia.org/wiki/Club_good){:target="_blank"}).

Because Uber has a monopoly on driver and rider location data and the ability to match rider with driver (drivers going outside Uber and establishing relationships with riders isn’t practical in this market and vice versa) Uber controls the relationship with the customer (i.e. ability for driver and rider to interact and transact) and also fare pricing.

One of the importance things to understand about platforms where indirect network effects are in play is that you need to keep the ratio of all the sides in sync. In the context of Uber, you don’t want excess supply of drivers fighting for to few riders because this reduces driver utilisation and therefore driver income, and vice versa, you don’t wan’t to few drivers for to many riders because this creates excessive wait time and poor user experience.

They manage the balance between demand and supply through the use of surge pricing in the short-run.

In the long-run, Uber’s strategy in expanding the for-hire vehicle (FHV) market is to cut fare pricing. They need to reduce fares in a controlled manner because the relationship between fare pricing, drive utilisation, rider demand and driver supply is sensitive to slight changes and can become unstable. Massive drops in fares (default fares not surge pricing fares) may reduce the supply of drivers because the increase in driver utilisation may not compensate sufficiently for the fare drop.

The key metric to measure the opportunity cost of drivers is the ratio of fare price to driver utilisation which I suspect this is something that Uber keeps a close eye on in each local market.


##Revenue Model

Uber generates revenue by taking a transaction fee per ride that occurs through their platform. They can charge this transaction fee from drivers because they own the relationship with riders and drivers cannot transact with these riders unless they go through Uber. The more rides there are the more revenue that Uber generates. This is the driving motivation for expanding into more markets geographically and conceptually.


##Cost Structure of Production: OPEX v CAPEX

There are two means of production:
*drivers and vehicles; and
*real-time location data of both riders and drivers.

For simplicity sake I’ll ignore non-operational costs for the moment but in any case are fixed relative to output i.e. fare rides. Uber also has operations teams in each city and country they operate in which again can be treated as a fixed cost relative to fare rides.

The production of location data (i.e. displaying data through Uber app) is a fixed cost relative to rides that occur and namely server costs and maintaining the back-end service underlying the Uber app. The fixed cost is insignificant relative to the scale they’re working at, a couple hundred cities and counting, hundreds of thousands (if not millions) of rides per city per annum. 

As for the data itself, as discussed in the [analysis of the Uber UX](http://davidni.com/2015/12/03/ux-case-study-uber){:target="_blank"} the marginal cost of the actual location data was infinite (i.e. could not get this data before at any price) but now is effectively zero due to the proliferation of smartphones.

As discussed in [Part 1](http://davidni.com/2015/12/04/business-model-case-study-uber-part-1){:target="_blank"}, unlike the incumbent taxi services who own and operate the vehicles and therefore have capital tied up in order to provision a fleet of vehicles, the marginal cost of adding an additional Uber driver is almost zero i.e. cost of recruitment and on boarding are minimal, the limit to supply is driven by the opportunity cost of the drivers themselves. Effectively Uber is shifting the capital costs of owning and operating a fleet of vehicles to drivers themselves thus allowing Uber to provide a taxi service equivalent at a fraction of the capital required that a taxi owner-operator can (even after discounting the substantial per taxi licence fee that they incur).

The benefits are two-fold:

* The velocity at which Uber can scale it’s operation is an order of magnitude greater than under a [capex-heavy](https://en.wikipedia.org/wiki/Capital_expenditure){:target="_blank"} model (demonstrated by the speed in which Uber has expanded into more and more cities and countries) because capital raised can be used to accelerate growth of rider and driver base instead of tied up in expensive assets that depreciate rapidly;

* An [opex-driven](https://en.wikipedia.org/wiki/Operating_expense){:target="_blank"} model is less risky than an capex-driven one because your expenses correlate with demand with the former while your costs are still the same even if sales tank under the latter.


##Velocity of Scaling, Acquisition Costs, and VC Funding

As discussed above the nature of the Uber cost structure means they can scale an order of magnitude more rapidly than under a capex-model. This high velocity to scale is critical in markets driven by network effects, as the dynamics are akin to land grabs with competing platforms in a race to acquire critical mass in riders and drivers for a local market because there are no second place in winner-take-all markets. This makes Uber somewhat different to incumbent taxi services in that their asset-lite model allows them to establish monopolies globally rather than limited to a single local market.

This high velocity to scale characteristic is the reason why venture capital has pored funding into Uber as the VC model is based around investing in startups (whose financing opportunites are limited due to non-existent balance sheets) that are high risk, high return (10-100x returns) in relatively short investment horizons (10-12 years).

The VC funding that Uber has raised are effectively being used as acquisition costs. My understanding is that Uber has been heavily subsidising drivers whereby payout to drivers > fares per ride in markets where competition is fierce from other tech plays (e.g. Lyft in US and Didi Kuadi in China). Obviously that isn’t a sustainable model but the rationale is to acquire riders/drivers to get to critical mass as quickly as possible through subsidies and to outlast your opponent by leveraging deeper pockets Uber has from their funding efforts. I’m not a big fan of this sort of competition because they have [Bertrand-like dynamics](https://en.wikipedia.org/wiki/Bertrand_competition){:target="_blank"} where the two players battle each other without any significant change in marketshare but exhausting a whole lot of capital they could’ve deployed in less competitive markets.

In markets where there it isn’t strong competition Uber can afford to acquire the initial batch of users at [CAC](https://en.wikipedia.org/wiki/Customer_acquisition_cost){:target="_blank"} > [LTV](https://en.wikipedia.org/wiki/Customer_lifetime_value){:target="_blank"} because if they can get to critical mass the acquisition costs for subsequent riders will be zero without the risk of having capital tied up in a battle of attrition.

The dynamics here reminds me a lot of the strategy board game [Risk](https://en.wikipedia.org/wiki/Risk_(game)){:target="_blank"}. There are benefits to capturing as much territory as quickly as possible but you’ve got to be careful you don’t overstretch yourself because a well-funded opponent can beat you locally or engage you in a battle of attrition which weakens you in other markets.

By the way, Risk is a really good game to learn about the interaction between strategy and ego. Great game.


##Putting it all together

*Technology change means that can provide greater safety and availability without regulation that previously wasn’t possible.

*The underlying product is a step-change superior to the existing product (incumbent taxi services) in the market.

*Discovered that demand is elastic and can increase driver income by cutting fares and expanding rider demand while simultaneously expanding driver supply. Riders want availability which requires driver supply. Drivers want income which comes through better utilisation which is driven by more rider demand (as allocation problem is now solved increasing driver utilisation due to GPS and smartphone adoption).

*Under status quo need to get licence and other regulatory requirements, controlled driver supply implication is cannot expand market and drop fare prices, slow velocity to scale etc.

*If Uber play by rules and only focus on using tech to more efficiently match rider to driver, the impact is limited. Impact only comes from expanding market (from existing taxi service to car replacement, public transport replacement, and goods delivery) which cannot happen without unlimited entry of drivers. Go to platform model. Implications are under platform unlimited driver supply, asset-lite means velocity of scaling faster, land-grab and winner-take-all dynamics.

*For better or worse Uber has followed the ask forgiveness, not permission (or more accurately don’t ask forgiveness or permission) mantra.

*Land-grab/Winner-take-all dynamics means need to focus on acquisition which require capital which Uber doesn’t have sufficient of as they are a startup with insufficient organic cashflow to fund this.

*VC provide funding in assets that:
Have massive market opportunity;
Can grow quickly to seize this opportunity; and
Acquired market share is defendable.

VCs don’t care about the balance sheet (as startups don’t have balance sheet anyway). Uber ticks these boxes hence VC and businesses like Uber are made for each other.

*Uber is expanding the market far greater than what that the taxi service ever was while at the same time taking all the share of the market from the incumbent taxi services as well.

*As or if they expand market into car ownership, public transport, and goods delivery market they will want to have more control over the user experience at the driver level which would require them to move away from a platform-centric/asset-lite model to a direct owner-seller/capex-heavy model. You would expect they would have IPOed and have a strong balance sheet that will allow them to fund this by the time they make this transition.


##Reading list

###Bull Case for Uber

[How to Miss By a Mile: An Alternative Look at Uber’s Potential Market Size](http://abovethecrowd.com/2014/07/11/how-to-miss-by-a-mile-an-alternative-look-at-ubers-potential-market-size/){:target="_blank"} - A response by Bill Gurley to analysis by Aswath Damodaran which I link to below.

[Why Uber Fights](https://stratechery.com/2014/uber-fights/){:target="_blank"} - Great summary of platform strategy and network effects in Uber context by Ben Thompson.

[Uber 2.0: Human Self-Driving Cars](https://stratechery.com/2015/uber-2-0-human-self-driving-cars/){:target="_blank"} - Uber and Self-Driving Cars.


###Bear Case for Uber

[A Disruptive Cab Ride to Riches: The Uber Payoff](http://aswathdamodaran.blogspot.com.au/2014/06/a-disruptive-cab-ride-to-riches-uber.html){:target="_blank"} - Aswath Damodaran touched a nerve with this bearish assessment of Uber’s private valuation in 2014.

[How Big of a Deal is Uber?](http://justin-singer.org/blog/2013/10/how-big-of-a-deal-is-uber/){:target="_blank"} - Bearish assessment of Uber. Good summary of Uber’s business model.

[Beautiful Illusions: The Economics of UberX](http://justin-singer.org/blog/2014/06/beautiful-illusions/){:target="_blank"} - Bearish analysis of Uber’s driver utilisation numbers.

[The Economics of UberX (Part II)](http://justin-singer.org/blog/2014/11/the-economics-of-uberx-part-ii/){:target="_blank"} - More bearish analysis of Uber’s driver utilisation numbers.


###More analysis by Aswath Damodaran

[On Uber Rollercoaster Narrative Tweaks](http://aswathdamodaran.blogspot.com.au/2015/10/on-uber-rollercoaster-narrative-tweaks.html){:target="_blank"} - Redux of first analysis of Uber valuation. You get the impression that Aswatch has changed perspective and is more bullish on Uber’s prospects.

[Dream Big or Stay Focused? Light’s Counter to Uber!](http://aswathdamodaran.blogspot.com.au/2015/10/dream-big-or-stay-focused-lyfts-counter.html){:target="_blank"} - Analysis of Uber’s nemesis in the US, Lyft.

[The Ride Sharing Business: Playing Pundit](http://aswathdamodaran.blogspot.com.au/2015/10/the-ride-sharing-business-playing-pundit.html){:target="_blank"} - Punditry on how market will play out.



###Surge Pricing

[A Deeper Look at Uber’s Dynamic Pricing Model](http://abovethecrowd.com/2014/03/11/a-deeper-look-at-ubers-dynamic-pricing-model/){:target="_blank"} - Bill Gurley on 'surge' pricing.

[Uber and the delicate business of creating a platform](http://www.digitopoly.org/2012/08/25/uber-and-the-delicate-business-of-creating-a-platform/){:target="_blank"} - Analysis of issues of 'surge' pricing by Joshua Gans.

[Uber’s tough market design challenge](http://www.digitopoly.org/2014/02/28/ubers-tough-market-design-challenge/){:target="_blank"} - More analysis of issues around 'surge' pricing by Joshua Gans.


###Is Uber Christensen Disruptive?

[Is Uber disruptive?](http://www.digitopoly.org/2015/11/17/is-uber-disruptive/){:target="_blank"} - Joshua Gans discuss whether Uber is 'disruptive' in the Christensen sense. Answer: No.

[Beyond Disruption](https://stratechery.com/2015/beyond-disruption/){:target="_blank"} - Ben Thompson discuss whether Uber is 'disruptive' in the Christensen sense. Answer: No.


###Miscallaneous

[Uber, sharing and the compensation mechanism](http://www.digitopoly.org/2015/06/28/uber-sharing-and-the-compensation-mechanism/){:target="_blank"} - Perspective of on changing regulatory landscape from economist point of view.

[Uber’s New BHAG: UberPool](http://abovethecrowd.com/2015/01/30/ubers-new-bhag-uberpool/){:target="_blank"} - Bill Gurley explains the why/what/how of UberPool.

[Is Uber really in a fight to the death](http://www.digitopoly.org/2014/11/25/is-uber-really-in-a-fight-to-the-death/){:target="_blank"} - Good analysis on the motives for drivers to 'multi-home’.

[Couldn’t find a cab last night? Here’s why](http://www.theage.com.au/victoria/couldnt-find-a-cab-last-night-heres-why-20110325-1ca66.html){:target="_blank"} - News article on Melbourne taxi market in 2011. Highlights a lot of issues with taxi services that have riders flocking to Uber. Also great summary of numbers of operating taxis in Melbourne. Interestingly they have estimate of driver utilisation at 'all-time low of 27 per cent' which seems incredibly low.